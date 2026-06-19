# Cubbard Road Marlboro — Parametric Site Study

This repository is the working parametric site/project model for the Cubbard Drive / Old Indian Road / Route 9W Marlborough, NY concept.

## Current status

- Repositories were initialized from an empty state.
- The active baseline is **Model B**, derived from the KML control hull and the latest photo-plan/fit-check geometry.
- The model is **schematic / planning-board preparation only**. It is not a legal survey, stamped civil plan, SWPPP, drainage report, wetland delineation, driveway permit plan, or building-permit package.

## What the app does

Open `index.html` in a browser. The app:

1. Uses WGS84 KML control points and a local ENU-feet schematic coordinate system.
2. Generates building, office, parking, truck court, yard, driveway throat, trailer-staging, and stormwater placeholders parametrically.
3. Computes disturbance area and compares it to the 43,560 sf / 1-acre NYSDEC construction stormwater threshold.
4. Flags whether engineered stormwater review is likely.
5. Exports GeoJSON, KML, CSV, and a JSON parameter file for the next engineer/CAD/GIS iteration.

## Important engineering rule

A pond is **not automatically required** by the KML. However, if this project becomes an industrial yard / warehouse / heavy civil equipment staging layout, the disturbed area will likely exceed 1 acre. That means the submission should assume engineered stormwater management and a SWPPP-level workflow unless the final layout proves otherwise.

Any proposed pond, basin, bioretention cell, infiltration basin, detention basin, retention basin, or impoundment must be engineered and reviewed.

## Data files

- `data/site_control.geojson` — KML control points and study hull.
- `data/parameters.json` — editable baseline parameters.
- `data/model_b_fit_check.csv` — Model B fit-check table.
- `assets/kml/Cubbard_Drive_Marlboro_ref.kml` — original KML reference file.

## Next required professional inputs

1. Boundary/topographic survey with contours.
2. Wetland/waterbody delineation and jurisdictional review.
3. Pre/post-development hydrology.
4. Truck/lowboy swept-path analysis.
5. Septic/well constraints and UCDOH review.
6. Zoning/site-plan feasibility review with the Town of Marlborough.
