# Oberlin College: Campus Health, Safety & Wellness

An interactive map of health and safety resources on the Oberlin College campus.

**View the map:** https://shaswatgajurel.github.io/Health_Safety_Awareness/

## The map

[`Map/map.html`](Map/map.html) is a single self-contained Leaflet page. Layers:

- AEDs
- Menstrual products
- First aid cabinets
- Blue-light emergency phones
- Accessible parking
- Campus buildings

The street view uses standard [OpenStreetMap](https://www.openstreetmap.org/copyright) tiles,
and the satellite view uses Esri World Imagery. Neither needs an API key.

To run it locally, serve the folder with any web server (for example
`python3 -m http.server`) and open `Map/map.html`. OpenStreetMap may refuse tile requests
from a page opened directly as a file.

### Data caveats

- **Blue-light phones** come from Oberlin Safety & Security's published list, recovered
  from a ~2006 Internet Archive snapshot. Oberlin no longer publishes a per-location list,
  so some phones may have moved or been removed. Coordinates are approximate.
- **Accessible parking:** Oberlin publishes no campus-wide ADA parking map. Only the lot
  behind Finney Chapel is confirmed; the others are inferred.

For current information, contact Oberlin Campus Safety or the Office for Disability and Access.

## License & credit

© 2026 Shaswat Gajurel. Licensed under [CC BY 4.0](LICENSE).
You may use and adapt this work for any purpose **as long as you credit Shaswat Gajurel**.
