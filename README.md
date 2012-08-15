bl-jquery-image-center
======================

Centers an image by moving, cropping and filling spaces inside it's parent container. This plugin maintains aspect
ratio giving it a very professional looking finish in most situation.

Usage
-----

Include the plugin in your page.

```html
<script type="text/javascript" src="/path/to/jquery.blImageCenter.js"></script>
```

Use a jquery selector on the image(s) you wish to perfectly fit inside their parent container and call imageCropFill()

```javascript
$('img').imageCropFill();
```

To demonstrate what is happening here,

If you want the image to completely fill the area and crop the image whilst maintaining aspect ratio, then
imageCenterResize() is the function you are looking for.

```javascript
$('img').imageCenterResize();
```
