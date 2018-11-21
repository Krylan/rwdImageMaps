# RWD Image Maps

### Allows image maps to be used in a responsive design by recalculating the area coordinates to match the actual image size on load and window.resize

Notice: This code is modification of stowball's jQuery-rwdImageMaps repository. I wanted to get rid of dependencies using simple and light solution.
---

#### Usage:

* If possible, add [correct, unitless](http://dev.w3.org/html5/markup/img.html) `width` and `height` attributes to your image map images. You can override these in CSS to make them responsive.
* In a `<script>` block or a separate file, call:

```js
rwdImageMaps(document.querySelectorAll('img[usemap]'));
```

---

Original work Copyright (c) 2016 [Matt Stow](http://mattstow.com)
Modified work Copyright (c) 2018 Krylan

Licensed under the MIT license *(see [LICENSE](https://github.com/Krylan/rwdImageMaps/blob/master/LICENSE) for details)*  
Minified version created with Online YUI Compressor: http://www.refresh-sf.com/
