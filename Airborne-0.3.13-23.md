# Airborne 0.3.13

- The trend map has a Fill picker: paint the states by wastewater level, ED visits, admissions level or test positivity, each with its own color scale and legend.
- Pressing a state badge opens a popover with each metric's current value, with its level for wastewater and admissions (ED visits and positivity have no levels), a direction line and a nine-week sparkline.
- Gray outlines mark the ten HHS regions CDC uses for regional data, with a Settings toggle to turn them off.
- Markers stay put: they no longer twitch every half second, and they no longer vanish after a press, a zoom switch or a refresh.
- When a data source fails to load, the map shows gray states for that fill instead of the last scan's colors.
