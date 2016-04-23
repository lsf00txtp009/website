# Website Read Me or Not
Lightweight jQuery extension for modifying scrolling speed in modern web browsers. Supports vertical or horizontal scrolling direction, including user-defined easing.

## Installation
Include the latest version of [jQuery](http://jquery.com/download) and `jQuery.scrollSpeed.js` in the `<head>` of your HTML document:
```html
<script src="jQuery.min.js"></script>  
<script src="jQuery.scrollSpeed.js"></script>
```
## How to Use
Reference the `scrollSpeed()` method and modify the `step` and `speed` parameters to create the desired scrolling effect. The `step` parameter defaults to `100` units, while `speed` defaults to `800` milliseconds; custom easing is optional. See the live demo: [code.nath.co/scrollSpeed](http://code.nath.co/scrollSpeed)

```javascript
$(function() {  

    // Default
    jQuery.scrollSpeed(100, 800);
    
    // Custom Easing
    jQuery.scrollSpeed(100, 800, 'easeOutCubic');
    
});
```  

