## What
Dictionary of commonly-used data URIs.

## How

`npm install data-uri-snippets --save`

Then, in your JS:

```
import snippets from 'data-uri-snippets'

// white 1x1 pixel
var img = new Image()
img.src = snippets.white1x1png
```

## Values
* `white1x1` - 1x1 opaque white gif (35 bytes)
* `white1x1png` - 1x1 opaque white png (67 bytes)

## Sources
* [1x1 gif and png](http://proger.i-forge.net/%D0%9A%D0%BE%D0%BC%D0%BF%D1%8C%D1%8E%D1%82%D0%B5%D1%80/[20121112]%20The%20smallest%20transparent%20pixel.html)
