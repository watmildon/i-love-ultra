# Ultra is so so so so good

This repository is my love letter to Ultra. The best thing going for making maps with OpenStreetMap data. If you have an ultra file you'd like to contribute, pull requests welcome.

## Ultra Files

| File | Description |
|------|-------------|
| [Benches-In-Parks.ultra](Benches-In-Parks.ultra) | Colors parks by bench count using Turf's collect function to aggregate points within polygons. |
| [Colorize-Features-By-Last-Edit-Year.ultra](Colorize-Features-By-Last-Edit-Year.ultra) | Colors all OSM features on an orange-to-blue gradient based on when they were last edited. |
| [Colorize-Highway-By-Last-Edit-Year.ultra](Colorize-Highway-By-Last-Edit-Year.ultra) | Colors roads on an orange-to-blue gradient based on their last edit timestamp. |
| [Courthouses-Exaggerated.ultra](Courthouses-Exaggerated.ultra) | Scales courthouse buildings 100x from their centroid using Turf's transformScale. |
| [FireStation-Buffer.ultra](FireStation-Buffer.ultra) | Creates concentric buffer rings around fire stations showing coverage at 0.25, 0.5, 0.75, and 1km. |
| [FireStation-Buffer-fancy.ultra](FireStation-Buffer-fancy.ultra) | Same as above but uses Turf's difference to create donut-shaped rings for consistent transparency. |
| [HighSchool-Voronoi.ultra](HighSchool-Voronoi.ultra) | Generates Voronoi polygons around high schools showing nearest-school service areas. |

