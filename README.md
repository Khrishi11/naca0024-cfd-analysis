# NACA 0024 CFD Analysis

Individual coursework for Fundamental Aerodynamics, UWE Bristol (2022 to 2023). A 2D CFD study of the NACA 0024 symmetric aerofoil (24% thickness at 30% chord) in ANSYS Fluent.

## Method
1. Generated the aerofoil geometry from coordinate data
2. Ran a **mesh independence** and **domain size** study to pick settings that give accurate results without wasted cells
3. Simulated the aerofoil across a range of angles of attack (2, 6, 10 and 14 degrees) at subsonic free stream velocity
4. Repeated at transonic and supersonic speeds
5. Calculated lift and drag coefficients and compared against published experimental data

## Files
| File | Description |
|---|---|
| `report/NACA0024_CFD_Report.pdf` | Full report |
| `results/NACA0024_Results.xlsx` | Cl, Cd and pressure results |
| `geometry/NACA0024_coordinates.xlsx` | Aerofoil coordinates |
| `geometry/polylines/` | Polyline coordinate files for each angle of attack, imported into ANSYS |
| `geometry/NACA0015_coordinates.xlsx` | NACA 0015 coordinates from the initial set up |

## Tools
ANSYS Fluent, ANSYS DesignModeler and Meshing, Excel
