# Making a Map in ArcGIS: London Underground Foot Traffic

Map of London Underground stations, with symbology showing how many people enter each station over one week (1 to 7 June). The map answers one question: **Where are the busiest London Underground stations?**

## Scenario

I am a GIS analyst for the Greater London Authority. The map shows Underground stations and highlights weekly entry counts, so the busiest stations stand out.

- **Audience:** Decision-makers at the Greater London Authority and Transport for London. They are map literate and will view the map on desktop computers or tablets.
- **Purpose:** Answer "Where are the busiest London Underground stations?"
- **Reuse:** The layout is designed as a template for a weekly map series, so the same design can be applied to a different week by swapping the data.

## Learning goals

- Add data to an ArcGIS Pro map
- Symbolise data using different methods (graduated symbols, colour ramps)
- Label features clearly without clutter
- Build a final print or screen layout

## Workflow

1. Download and store the raw data in `data/raw/`. Do not edit these files.
2. Clean and join the data, saving results to `data/processed/`.
3. Add the London Boroughs boundary layer and the station layer to the map.
4. Symbolise stations by weekly entries.
5. Label the busiest stations and the boroughs.
6. Build the layout, export it to `layouts/`, and save the project to `project/`.
7. Save progress screenshots to `screenshots/`.

## Data sources

All files for this map (station entries, borough boundaries, and the screenshot set) are stored in a shared Google Drive folder:

**[Google Drive: Map 1 files](https://drive.google.com/drive/folders/1Rf7AqHi-2kkEbUVQfsk9ZXIQn6YOoX48?dmr=1&ec=wgc-drive-%5Bmodule%5D-goto)**

| Dataset | Description | Location | Source |
|---|---|---|---|
| London Underground station entries | Weekly entries per station, 1 to 7 June | `data/raw/` | Google Drive folder above |
| London boroughs | Borough boundaries | `data/raw/` | Google Drive folder above |

## Repository

Project files are pushed to GitHub: [MumbaMumba789/Spatial-Mapping](https://github.com/MumbaMumba789/Spatial-Mapping)

## Folder guide

| Folder | Contents |
|---|---|
| `data/raw/` | Original downloads, unchanged |
| `data/processed/` | Cleaned and joined data |
| `project/` | ArcGIS Pro project (.aprx) and file geodatabase (.gdb) |
| `layouts/` | Final map exports (PDF / PNG) |
| `screenshots/` | Progress screenshots, numbered in order |
