# Cubbard Road Marlboro — Model B 3D Measurement Engine

This repository is the working **Model B-only** parametric site and 3D measurement study for the Cubbard Drive / Old Indian Road / Route 9W Marlborough, NY concept.

## Current status

- **Model B is the only active baseline.**
- All prior/alternate baseline language has been removed from the active project narrative.
- The active baseline is derived from the KML control hull and the latest photo-plan / fit-check geometry.
- The model is **schematic / planning-board preparation only**. It is not a legal survey, stamped civil plan, SWPPP, drainage report, wetland delineation, driveway permit plan, or building-permit package.

## What the app does

Open `index.html` in a browser. The app:

1. Uses WGS84 KML control points and a local ENU-feet schematic coordinate system.
2. Builds the Model B warehouse, office/support, parking, truck court, equipment yard, entry throat, trailer staging, stormwater reserve placeholders, and heavy-haul path parametrically.
3. Creates a lightweight 3D measurement view for conceptual building massing and site takeoff.
4. Calculates indoor area, interior volume, outdoor operational area, outdoor/indoor ratio, wall surface area, flat/pitched roof area, disturbance area, acres, study-hull utilization, and simple slope checks.
5. Supports OBJ mesh import for conceptual mesh surface-area and closed-mesh volume calculations.
6. Provides placeholders for future GLB/GLTF, PLY/LAZ, GeoTIFF DTM/DSM, and USDZ/RoomPlan-derived imports.
7. Imports or pastes a photo manifest from `yazilimlar/cubbard-marlboro-pics` and tracks scale-reference notes.
8. Exports measurement results as CSV and measurement objects as JSON.
9. Computes disturbance area and compares it to the 43,560 sf / 1-acre NYSDEC construction stormwater screening threshold.
10. Flags whether engineered stormwater review is likely.

## Important measurement rule

Normal photos and AI-generated renderings are not measurement evidence by themselves. Any quantity derived from photographs must be tied to a known scale reference, survey control, LiDAR, controlled photogrammetry, or user-entered dimensions. AI-generated concept images are visualization only.

## Confidence grading

- **A** — survey, LiDAR, stamped CAD/BIM, controlled metric source.
- **B** — drone photogrammetry with ground control points or known control scale.
- **C** — photo-calibrated schematic geometry or manual dimensions with known references.
- **D** — visual-only / conceptual / unverified geometry.

## Important engineering rule

A pond is **not automatically required** by the KML. However, if this project becomes an industrial yard / warehouse / heavy civil equipment staging layout, the disturbed area will likely exceed 1 acre. That means the submission should assume engineered stormwater management and a SWPPP-level workflow unless the final layout proves otherwise.

Any proposed pond, basin, bioretention cell, infiltration basin, detention basin, retention basin, or impoundment must be engineered and reviewed.

## Data files

- `data/site_control.geojson` — KML control points and study hull.
- `data/parameters.json` — editable Model B baseline parameters and measurement defaults.
- `data/model_b_fit_check.csv` — Model B fit-check table.
- `data/measurement_objects.json` — measurement object definitions used by the app.
- `data/measurement_results.csv` — baseline Model B measurement output.
- `assets/kml/Cubbard_Drive_Marlboro_ref.kml` — original KML reference file.

## Baseline Model B measurement summary

- Warehouse: 210 ft × 160 ft × 32 ft.
- Office/support: 60 ft × 50 ft × 18 ft.
- Warehouse floor area: 33,600 sf.
- Office floor area: 3,000 sf.
- Total indoor area: 36,600 sf.
- Total interior volume: 1,129,200 cf / 41,822 cy.
- Outdoor operational area, excluding stormwater and trailer staging: 49,950 sf.
- Outdoor/indoor ratio: 1.36:1.
- Current disturbance screening area, excluding trailer staging to avoid double-counting within yard areas: 99,462.5 sf / 2.28 acres.

## Next required professional inputs

1. Boundary/topographic survey with contours.
2. Wetland/waterbody delineation and jurisdictional review.
3. Pre/post-development hydrology.
4. Truck/lowboy swept-path analysis.
5. Septic/well constraints and UCDOH review.
6. Zoning/site-plan feasibility review with the Town of Marlborough.
7. Survey-controlled elevations or LiDAR/photogrammetry for slope, surface-area, and volume calculations beyond schematic assumptions.
