# Washington State EV Registrations Map

This repository contains an interactive map visualizing electric vehicle registrations by ZIP code in Washington State.

The map is generated using Python with the `pandas`, `requests`, `folium`, and `matplotlib` libraries.

Data Sources:
- ZIP Code Centroids: [Link to your ZIP centroid data source - if you have a public link]
- Washington State EV Data: [https://data.wa.gov/Transportation/Electric-Vehicle-Population-Data/f6w7-q2d2](https://data.wa.gov/Transportation/Electric-Vehicle-Population-Data/f6w7-q2d2)

The interactive map (`ev_registrations_map.html`) can be viewed directly in your web browser or hosted using GitHub Pages.

## How to View the Map

1. Clone this repository or download the `ev_registrations_map.html` file.
2. Open the `ev_registrations_map.html` file in your web browser.

## How to Recreate the Map

1. Open the provided Python notebook in Google Colab or a local Python environment with the necessary libraries installed.
2. Run the code cells in the notebook to download the data, process it, and generate the Folium map.
3. The map will be saved as `ev_registrations_map.html`.

## GitHub Pages

This map can be hosted directly from this repository using GitHub Pages. Once enabled, the map will be accessible via a public URL.
