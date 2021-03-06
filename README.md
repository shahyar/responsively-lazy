# responsivelyLazy

This is the source of the best lazy loading implementation available.

You can find a demo at [http://ivopetkov.github.io/responsivelyLazy/](http://ivopetkov.github.io/responsivelyLazy/) and learn how the magic works at [http://ivopetkov.com/b/lazy-load-responsive-images/](http://ivopetkov.com/b/lazy-load-responsive-images/)

## How to use

* Include the css file in the head tag
```
<link rel="stylesheet" href="responsivelyLazy.min.css">
```

* Include the js file right before the end of the body tag 
```
<script async src="responsivelyLazy.min.js"></script>
```

* Write the image code
```
<div class="responsively-lazy" style="padding-bottom:68.44%;">
    <img alt="" src="images/2500.jpg" data-srcset="images/600.jpg 600w, images/400.jpg 400w, images/800.jpg 800w, images/1500.jpg 1500w, images/1000.jpg 1000w, images/2000.jpg 2000w" srcset="data:image/gif;base64,R0lGODlhAQABAIAAAP///////yH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />
</div>
```
The things to customize are the **padding-bottom** style, and the values of the **src** and **data-srcset** attributes.

## Got questions?
You can find me at [@IvoPetkovCom](https://twitter.com/IvoPetkovCom) or [ivopetkov.com](http://ivopetkov.com)