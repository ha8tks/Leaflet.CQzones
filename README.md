# Leaflet.CQzones
### What is this?
Draw a CQ zones lines and labels.
>*CQ zone is a division of the entire earth's surface into a total of 40 zones , which is used in amateur radio .*
### Demo anyone?
[Have a look](https://ha8tks.github.io/Leaflet.CQzones/examples/)
### Usage example
Include the Leaflet.VectorGrid, text-images, cqzones javasript file:
```bash
<script src="https://unpkg.com/leaflet.vectorgrid@latest/dist/Leaflet.VectorGrid.js"></script>
<script src="https://cdn.jsdelivr.net/npm/text-image/dist/text-image.js"></script>
<script src="https://ha8tks.github.io/Leaflet.CQzones/src/L.CQzones.js"></script>
```
After instantiating the map:
```bash
L.CQzones({
	color : 'rgba(255, 0, 0, 0.4)'
}).addTo(map);
```
### Options
- **color**: The color of the lines and labels. Default `rgba(255, 0, 255, 0.6)` 
