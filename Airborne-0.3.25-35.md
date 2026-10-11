# Airborne 0.3.25

- Adds a native weekly Briefing on macOS and iOS with watched-illness evidence, source, reporting date, geography, freshness, and links into illness details and the map. Each measure keeps its own evidence; the briefing does not calculate a combined personal-risk score.
- Adds Simple and Analyst modes to the native illness map. Simple starts with one measure and a clear legend. Analyst retains independent fill and marker signals, geography choices, saved combinations, playback, and selected-place evidence. Switching modes preserves the other mode's settings.
- Keeps missing or unsupported evidence unavailable rather than implying zero or no change. HHS-region marker evidence remains available where supported; generalized HHS-region fills are not supported.

- Improves small-percentage precision and historical FluView evidence dates. Current CDC data coverage is preserved.
