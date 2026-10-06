# Airborne 0.3.11

- The trend map's Positivity layer now works for flu, using CDC FluView clinical lab results. A state without enough recent flu tests shows its HHS region instead, marked "(HHS region N)"; New York's figure excludes New York City.
- A flu state badge's details also show how its HHS region's positivity is moving.
- If CDC's data service is down when Airborne refreshes, the map keeps the last good scan and tries again sooner.
