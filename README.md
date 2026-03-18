# 1D Axial Finite Element Analysis of Hollow Human Femur

## Overview
This project presents a one-dimensional finite element analysis (FEA) of a simplified hollow human femur subjected to axial compressive loading. The numerical formulation is implemented in Python and validated using ANSYS Mechanical.

## Objective
- Compute axial deformation and stress distribution in the femur shaft  
- Evaluate structural safety based on cortical bone strength limits  
- Validate Python FEM results with ANSYS simulation  

## Geometry
- Length: 0.48 m  
- Outer diameter: 25.1 mm  
- Inner diameter: 11.3 mm  
- Hollow circular cross-section representing cortical bone  

## Material Properties
- Young’s Modulus: 16 GPa  
- Yield Strength: 90 MPa  
- Ultimate Strength: 160 MPa  

## Loading and Boundary Conditions
- Axial compressive load: 50,000 N  
- Proximal end fixed  
- Load applied at distal end  

## Methodology
- Femur discretized into linear bar elements  
- Global stiffness matrix assembled  
- Boundary conditions applied  
- Nodal displacements solved using SciPy  
- Stress and strain computed from displacement field  

## Results
- Uniform compressive stress along shaft  
- Micrometer-level axial deformation  
- Stress below yield strength indicating elastic behaviour  
- Python results show good agreement with ANSYS simulation  
## Files
- ansys_results – ANSYS simulation outputs
- documentation– Detailed project report 
- python_code – Python FEM implementation  
- python_graph– Generated deformation and stress plots  
 
