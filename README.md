[View the live demo](https://wcbn.github.io/maps/)

### Ten Easy Steps
1. Create a mapbox account and open the [Studio](https://www.mapbox.com/studio/)
2. Download the kml file from the FCC
3. `npm install -g togeojson`
4. `togeojson file.kml > file.geojson`
5. Create a new [Dataset](https://www.mapbox.com/studio/datasets/) and import file.geojson
6. Export the dataset to a new [Tileset](https://www.mapbox.com/studio/tilesets/)
7. Open your style in the style editor
8. Create a new layer with this tileset as the source
9. Use the style URL on a new map project
10. Write down how to do this so you won't forget :)
