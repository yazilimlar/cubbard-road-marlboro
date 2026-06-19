# Planning Board Parametric Scope — Cubbard Road Marlboro

## Project intent

Create a controlled parametric concept package for a potential heavy civil equipment storage / warehouse / staging yard layout. The current model is for early feasibility and discussion only.

## Baseline program

| Element | Model B Seed |
|---|---:|
| Warehouse | 210 ft × 160 ft = 33,600 sf |
| Front office/support | 60 ft × 50 ft = 3,000 sf |
| Visitor/employee parking | 14,700 sf |
| Truck apron/circulation court | 8,100 sf |
| Rear service / equipment yard | 20,000 sf |
| Route 9W internal entry throat | 7,150 sf |
| Lower-left stormwater pond placeholder | 5,550 sf |
| Lower-right stormwater / bioretention placeholder | 7,362.5 sf |
| 100-ft trailer staging bays | 4 bays × 1,800 sf = 7,200 sf |
| Static 100-ft lowboy envelope | 1,200 sf |
| Static 70-ft load envelope | 840 sf |

## Stormwater screening logic

The app calculates:

```text
Total conceptual disturbance =
building + office + parking + truck apron + yard + driveway + stormwater grading placeholders
```

If this value is greater than **43,560 sf**, the app flags:

```text
SWPPP / engineered stormwater likely required.
```

This is a screening flag only. Final determination requires a licensed civil engineer.

## Pond/basin decision rule

Do not present the pond as required unless the hydrology proves it.

Recommended wording:

> The current concept reserves stormwater management space. The final BMP type — detention basin, infiltration basin, bioretention, subsurface chambers, swales, or pond-like structure — will be determined by survey, soil testing, wetland constraints, and pre/post-development hydrology.

## Engineering inputs required before final layout

- Surveyed property boundary and easements.
- 2-foot contours where required and detailed grading around access/yard areas.
- Soil borings/percolation/infiltration data.
- Seasonal high groundwater data.
- Wetland/waterbody delineation.
- NYSDOT access/drainage review if Route 9W access is proposed or modified.
- Lowboy/truck swept-path analysis.
- Septic/well layout and protection plan.
- Maintenance access/easements for any permanent stormwater BMP.
