# Airborne 0.3.17

- Smoother Mac trend-map playback: native MapKit polygons and renderers stay resident, and week changes update their paint instead of rebuilding the SwiftUI map.
- Weekly playback data is prepared in the background while the live map is visible.
- Existing local markers, week fades, popovers, and map zoom controls are preserved.
