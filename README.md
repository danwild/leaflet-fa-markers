# leaflet-fontawesome-markers

Very simple vector markers with FontAwesome icons, compatible with Leaflet v1.

## Use:

```javascript
var marker = L.marker([lat, lon], {
	icon: L.icon.fontAwesome({
		prefix: 'fa', // you could probably add another icon lib prefix here, not tested.
		icon: 'info-circle',
		markerColor: '#00a9ce',
		iconColor: '#FFF'
	})
});
```
