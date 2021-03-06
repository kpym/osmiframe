# osmiframe

The standard `iframe` generated by OSM use 4 coordinates to set the view zone (in a `bbox` parameter).

This repo provide a thin wrapper that allows to use 3 parameters : the center coordinates (`lat`, `lon`) and the zoom factor (`z`).

Here is an example of use

```
<iframe src="https://kpym.github.io/osmiframe/?lat=48.8583&lon=2.2945&z=17"
        width="400" height="210" frameborder="0"></iframe>
```

And you can see the result in [example.html](https://kpym.github.io/osmiframe/example.html).

If you need IE support you can use `https://kpym.github.io/osmiframe/ie/` as replacement. This version loads [url-polyfill](https://github.com/lifaon74/url-polyfill).
