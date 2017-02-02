# leaflet-fontawesome-markers

Very simple vector markers with FontAwesome icons, compatible with Leaflet v1.

## Use:

```javascript

var blueMarker = L.marker([lat, lon], {
	icon: L.icon.fontAwesome({
		prefix: 'fa', // you could probably add another icon lib prefix here, not tested.
		icon: 'info-circle',
		markerColor: '#00a9ce',
		iconColor: '#FFF'
	})
}).addTo(map);

var spinningMarker = L.marker([lat, lon], {
	icon: L.icon.fontAwesome({
		prefix: 'fa',
		icon: 'circle-o-notch fa-spin',
		markerColor: '#ff89b5',
		iconColor: '#FFF',
		// use XY offsets to nudge positioning of icons, negative accepted
		iconXOffset: -2, 
		iconYOffset: 0,
	})
}).addTo(map);

```
