# Model Notes

## Source
These notes are based on the supplied STAAD.Pro screenshots and project archive. They are descriptive, not a design certification.

## Model features visible in the source
- Multi-storey 3D analytical frame with plate elements.
- Fixed-base supports shown at the bottom of columns.
- Horizontal seismic cases labelled +X, -X, +Z and -Z.
- Dead and live load cases.
- Deflection and plate stress post-processing.
- Beam force output.
- Concrete-design views for beam 526 and member 531.
- Analysis completion dialog reports 0 errors, 5 warnings, and 9 notes.

## Member 531 design screenshot
The supplied design dialog shows:
- Design code: IS 456
- Section dimensions: 0.450 m × 0.450 m
- Fy: 415 MPa
- Fc: 25 MPa
- Required steel area: 951 mm²
- Steel percentage: 0.67%
- Displayed design forces: Pu = -23.2 kN, Mz = 47.43 kN·m, My = 13.09 kN·m
- Bar size: 12; bar count: 12

These are values visible in the screenshot and should be checked against the native STAAD.Pro design report. The user identifies member 531 as a column.

## Important checks before relying on the model
1. Inspect the five warnings from the analysis/design run.
2. Verify the seismic directions and parameters.
3. Verify material properties and units.
4. Confirm load combinations and applicable code requirements.
5. Confirm the displacement table includes the controlling nodes and cases.
6. Confirm the concrete-design output indicates a satisfactory check, not only a reinforcement calculation.
7. Have the model independently reviewed before any real-world application.
