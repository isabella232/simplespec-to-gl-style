## simplespec-to-gl-style

Converts GeoJSON styled with [simplestyle-spec](https://github.com/mapbox/simplestyle-spec/) to a GL Style

## Install

```
npm install @mapbox/simplespec-to-gl-style --save
```

#### Usage:

```js
var convert = require('@mapbox/simplespec-to-gl-style');

var style = convert(myGeoJSON);

var map = new mapboxgl.Map({
    container: 'map',
    style: style, // add style to a map
    center: [-74.50, 40],
    zoom: 9
});
```
