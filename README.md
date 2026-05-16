# Cross-National Patterns in Crime and Prison Population Indicators

This repository contains an interactive map built from Eurostat crime and prison population data.

## Project description

The map visualizes selected crime and criminal justice indicators for eight European countries:

- Denmark
- Netherlands
- Austria
- Finland
- Sweden
- Iceland
- Norway
- Switzerland

Users can navigate the map by:

- Year: 2008 or 2023
- Variable: intentional homicide, prison population, rape, sexual violence, and sexual assault

## Data sources

The data were downloaded from Eurostat:

- `crim_off_cat` — Police-recorded offences by offence category
- `crim_pris_cap` — Prison capacity and number of persons held

The downloadable CSV included in this repository contains the long-format raw-count data used to build the map.

## Files

- `index.html` — interactive map page
- `lab4_leaflet_real_map_data.csv` — dataset used for the map
- `README.md` — project description

## GitHub Pages instructions

To publish this map:

1. Create a new GitHub repository.
2. Upload `index.html`, `lab4_leaflet_real_map_data.csv`, and `README.md`.
3. Go to **Settings** → **Pages**.
4. Under **Build and deployment**, select:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Click **Save**.
6. After GitHub Pages finishes publishing, the map will be available at the Pages URL.

Prepared on 2026-05-07.
