# Thessaloniki · Trip Map

A full-screen interactive map of every stop on the Thessaloniki trip, pinned and numbered by day, with a dashed line showing each day's walking order and the hotel (Ptolemeon 14) marked. The stop list floats over the map; click a stop to fly to it. Each pin's popup links out to Google Maps.

Coordinates come from OpenStreetMap. Ano Poli is an area, so its pin sits at the heart of the Upper Town; the Black Pearl is pinned at its mooring by the White Tower.

## Preview locally

Open `dist/index.html` in a browser (it loads Leaflet and map tiles from a CDN, so it needs a connection).

## GitHub Pages

The GitHub Actions workflow publishes `dist/` whenever `main` is updated.
