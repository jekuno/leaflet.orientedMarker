# leaflet.orientedMarker
==================

Leaflet OrientedMarker is a [Leaflet](http://leafletjs.com/) plugin which allows to manage oriented Markers dynamically.

Demo
----

Check out the [demo](http://gismartwaredev.github.io/leaflet.orientedMarker/)

Usage
-----

  * Download the `Leaflet.orientedMarker.js`
  * Include the file after you included `leaflet.js` 
  * Initialize the orientedMarkers with `L.orientedMarker().addTo(map)` **after** you initialized your `map`
  * To modify orientation, call `activateOrientation()` on marker object
  * To finish, call `validateOrientation()` on marker objet
