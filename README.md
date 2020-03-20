# leaflet-fa-markers [![NPM version][npm-image]][npm-url] [![NPM Downloads][npm-downloads-image]][npm-url]

Very simple vector markers with FontAwesome icons, compatible with Leaflet v1.

![Screenshot](/screenshots/markers.png?raw=true)

## Use:

```javascript
var blueMarker = L.marker([lat, lon], {
  icon: L.icon.fontAwesome({
    iconClasses: "fa fa-info-circle", // you _could_ add other icon classes, not tested.
    markerColor: "#00a9ce",
    iconColor: "#FFF"
  })
}).addTo(map);

var spinningMarker = L.marker([lat, lon], {
  icon: L.icon.fontAwesome({
    iconClasses: "fa fa-circle-o-notch fa-spin",
    markerColor: "#ff89b5",
    iconColor: "#FFF",
    // use XY offsets to nudge positioning of icons, negative accepted
    iconXOffset: -2,
    iconYOffset: 0
  })
}).addTo(map);
```

[npm-image]: https://badge.fury.io/js/leaflet-fa-markers.svg
[npm-url]: https://www.npmjs.com/package/leaflet-fa-markers
[npm-downloads-image]: https://img.shields.io/npm/dt/leaflet-fa-markers.svg
