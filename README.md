# website

 # jQuery.scrollSpeed		 # jQuery.scrollSpeed
 Lightweight jQuery extension for modifying scrolling speed in modern web browsers. Supports vertical or horizontal scrolling direction, including user-defined easing.		 Lightweight jQuery extension for modifying scrolling speed in modern web browsers. Supports vertical or horizontal scrolling direction, including user-defined easing.
 		 
 ## Installation		 ## Installation
 Include the latest version of [jQuery](http://jquery.com/download) and `jQuery.scrollSpeed.js` in the `<head>` of your HTML document:		 Include the latest version of [jQuery](http://jquery.com/download) and `jQuery.scrollSpeed.js` in the `<head>` of your HTML document:
 ```html		 ```html
 <script src="jQuery.min.js"></script>  		 <script src="jQuery.min.js"></script>  
  <script src="jQuery.scrollSpeed.js"></script>		  <script src="jQuery.scrollSpeed.js"></script>
  ```		  ```
  ## How to Use		  ## How to Use
 -Reference the `scrollSpeed()` method and modify the `step` and `speed` parameters to create the desired scrolling effect. The `step` parameter defaults to `100` units, while `speed` defaults to `800` milliseconds; custom easing is optional. See the live demo: [code.bynathan.com/scrollSpeed](http://code.bynathan.com/scrollSpeed)		 +Reference the `scrollSpeed()` method and modify the `step` and `speed` parameters to create the desired scrolling effect. The `step` parameter defaults to `100` units, while `speed` defaults to `800` milliseconds; custom easing is optional. See the live demo: [code.nath.co/scrollSpeed](http://code.nath.co/scrollSpeed)
  		  
  ```javascript		  ```javascript
  $(function() {  		  $(function() {  
 @@ -19,24 +19,24 @@
     // Custom Easing		     // Custom Easing
     jQuery.scrollSpeed(100, 800, 'easeOutCubic');		     jQuery.scrollSpeed(100, 800, 'easeOutCubic');
     		     
 });		 });
 ```  		 ```  
 		 
 ## Browser Support		 ## Browser Support
 – Google Chrome  		 – Google Chrome  
 – Safari ( Desktop )  		 – Safari ( Desktop )  
 – Internet Explorer ( Disabled for performance )  		 – Internet Explorer ( Disabled for performance )  
 – Firefox  		 – Firefox  
 – Opera ( Not Tested )  		 – Opera ( Not Tested )  
 		 
 ## Release Notes		 ## Release Notes
 **jQuery.scrollSpeed 1.0**   		 **jQuery.scrollSpeed 1.0**   
 – Initial Release   		 – Initial Release   
 **jQuery.scrollSpeed 1.0.1**      		 **jQuery.scrollSpeed 1.0.1**      
 – Added support for horizontal scrolling   		 – Added support for horizontal scrolling   
 – Minor code cleanup  		 – Minor code cleanup  
 **jQuery.scrollSpeed 1.0.2**      		 **jQuery.scrollSpeed 1.0.2**      
  – Added paramater for custom easing  		  – Added paramater for custom easing  
  		  
  ## Feedback		  ## Feedback
 -If you discover any issues or have questions regarding usage, please send a message to [mail@bynathan.com](mailto:mail@bynathan.com) or find me on twitter [@ByNathan](http://twitter.com/ByNathan).		 +If you discover any issues or have questions regarding usage, please send a message to [code@nath.co](mailto:code@nath.co) or find me on GitHub [@nathco](https://github.com/nathco).
