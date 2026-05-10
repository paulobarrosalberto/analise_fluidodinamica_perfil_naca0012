# CFD Analysis of NACA0012 Airfoil using ANSYS Fluent

Computational Fluid Dynamics (CFD) simulation of the NACA0012 airfoil using Reynolds-Averaged Navier-Stokes (RANS) equations and the Spalart-Allmaras turbulence model in ANSYS Fluent.

---

## Objectives

- Evaluate aerodynamic coefficients (CL and CD)
- Analyze pressure and velocity fields
- Investigate wake behavior
- Validate CFD methodology against NASA benchmark data

---

## Simulation Setup

| Parameter | Value |
|---|---|
| Airfoil | NACA0012 |
| Reynolds Number | 6 × 10⁶ |
| Flow Regime | Subsonic |
| Solver | ANSYS Fluent |
| Turbulence Model | Spalart-Allmaras |
| Mesh Strategy | Boundary layer refinement |
| Target y+ | ≈ 1 |

---

## Numerical Methodology

The simulation employs:

- RANS equations
- Finite Volume Method (FVM)
- Second Order Upwind discretization
- Pressure-based steady solver

The turbulence closure is performed using the Spalart-Allmaras model.

---

## Mesh

Boundary layer refinement was applied to properly resolve the viscous sublayer.

![Mesh](media/mesh.png)

---

## Results

### Pressure Coefficient Distribution

![Cp](media/cp_distribution.png)

### Velocity Contours

![Velocity](media/velocity_contour.png)

### Pressure Contours

![Pressure](media/pressure_contour.png)

---

## Main Results

| Coefficient | Value |
|---|---|
| CL | ~0 |
| CD | 0.0079 |

---

## Validation

The computational setup follows NASA NACA0012 validation guidelines.

Reference:
https://turbmodels.larc.nasa.gov/naca0012_val.html

---

## Tools

- ANSYS Fluent
- ANSYS Meshing
- CFD
- Python
- Finite Volume Method

---

## Author

Paulo Alberto Barros  
Computational Engineering | CFD | FEM | CAE
