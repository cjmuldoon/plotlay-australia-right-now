# Data

One reading of public feeds at 8:50 am AEDT on Tuesday 24 November 2026 (2026-11-23T21:50:19.000Z UTC). Coordinates are WGS 84 longitude, latitude.

| File | What it is |
|---|---|
| `geometry/hotspots.geojson` | DEA Hotspots in the 24 hours, on land in an Australian state or territory (Himawari left out). `hours_since` before the snapshot; `industrial` true where within 400 m of an industrial site, landfill or solar farm in OpenStreetMap (`site`, `site_kind`) |
| `geometry/firms.geojson` | NASA FIRMS VIIRS and MODIS detections over Australia in the 24 hours, for comparison |
| `geometry/incidents.geojson` | NSW RFS major incidents and Queensland current bushfires, with the level each agency gave |
| `geometry/warnings.geojson` | The incidents at Advice level or higher with a mapped area |
| `geometry/zones.geojson` | 5 km round the hotspots (24 hours, last 6 hours) and round the warning areas |
| `geometry/fdr_nsw.geojson` | NSW fire weather districts drawn from their councils' 2021 LGAs, with today's and tomorrow's rating and 2021 residents |
| `geometry/major_roads.geojson` | Motorway to secondary roads inside warning areas (OpenStreetMap) |
| `geometry/eds.geojson` | Hospitals tagged with an emergency department near each warning area (OpenStreetMap) |
| `tables/people_near.json` | Residents within 5 km of hotspots and warning areas |
| `tables/people_by_state.csv` | The same by state |
| `tables/warnings_drive.json` | Per warning area: residents within a 15-minute drive, the nearest emergency department by road, roads crossing it |
| `tables/hotspot_clusters.csv` | Groups of hotspots within 5 km of each other and the residents round them |
| `tables/industrial_hotspots.csv` | The hotspots left out as industrial, with the site |
| `tables/fdr_nsw.csv` | NSW fire danger by district |
| `numbers.json` | Every figure on the showcase page |
| `feeds.json` | Each feed: when it was read, rows, filter, credit |

Licences: see `../NOTICE`.
