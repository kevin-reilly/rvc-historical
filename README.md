# rvc-historical

This is the repo for a historical map of downtown Rockville Centre, NY


# Using Geo JSON

Use [this link](https://leafletjs.com/examples/geojson/) for Leaflet details on using GeoJSON.

## Using Geo JSON as a File Reference

Use Ajax to incorporate GeoJSON files by references, rather than directly embedded in the HTML.

Embed this script in the header:

`<script src="/js/leaflet-0.7.2/leaflet.ajax.min.js"></script>`
    
Put this code in the map div:

`var geojsonLayer = new L.GeoJSON.AJAX("file");`

`geojsonLayer.addTo(map);`
 
