# [`<lazyload-image>`](http://1000ch.github.io/lazyload-image)

![](assets/lazy-sloth.jpg)

Photo by [Susana Fernandez](https://www.flickr.com/photos/susivinh/6970379146)

## About

HTMLImageElement extension for lazy loading. Images will be loaded when they are shown.

## Usage

Load `lazyload-image.js` in your HTML.

```html
<script src="lazyload-image.js"></script>
```

Modify your `<img>` elements such as following.

```html
<img is="lazyload-image" src="path/to/your/image.jpg" width="100" height="100">
```

You can specify load offset.

```html
<img is="lazyload-image" src="path/to/your/image.jpg" offset="200" width="100" height="100">
```

## Fallback

If browser does not support `document.registerElement()`, Images will be loaded as usual.

## License

MIT: http://1000ch.mit-license.org
