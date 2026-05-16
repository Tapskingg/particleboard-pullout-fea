# Particleboard Pull-Out FEA

Finite element modelling and validation of screw pull-out behaviour in particleboard using LS-DYNA.

---

## Overview

This project investigates orthotropic material modelling and fracture behaviour in particleboard under screw withdrawal loading.

The work was carried out in collaboration with IKEA of Sweden and Linköping University as part of a Master’s Thesis in Mechanical Engineering.

The objective was to develop and validate simulation models capable of predicting pull-out behaviour more accurately than existing industrial simulation approaches.

---

## Engineering Problem

Pull-out forces of screws and connectors are critical in furniture product development, particularly for structural integrity and assembly performance.

Particleboard exhibits highly anisotropic and heterogeneous behaviour, making accurate fracture and pull-out prediction challenging under finite element analysis.

The project focused on:
- Orthotropic material modelling
- Fracture propagation
- Contact interaction
- Mesh convergence
- Experimental correlation
- Simulation validation

---

## Methods

### Software & Tools

- LS-DYNA
- HyperMesh
- ANSYS
- MATLAB
- CAD modelling

### Simulation Approaches

Three different material modelling approaches were evaluated:

1. MAT_143 (Wood damage model)
2. MAT_122 + MAGD damage accumulation
3. MAT_221 orthotropic simplified damage model

### Validation

Simulation models were validated against:
- Tensile testing
- Shear testing
- Bending testing
- Physical screw pull-out experiments

---

## Key Results

| Metric | Result |
|---|---|
| Tensile prediction accuracy | Up to 99% |
| Shear prediction accuracy | Up to 98% |
| Bending prediction accuracy | Up to 99% |
| Pull-out validation | Compared against experimental data |

Key findings:
- Orthotropic material behaviour strongly influences pull-out response
- Mesh density significantly affects crack propagation prediction
- Premature shear failure remains a major modelling limitation

---

## Engineering Topics

- Finite Element Analysis (FEA)
- Orthotropic material behaviour
- Fracture mechanics
- Failure modelling
- Contact mechanics
- Simulation validation
- Mesh convergence analysis
- Structural mechanics

---

## Future Improvements

- Advanced fracture propagation modelling
- Improved contact interaction definitions
- Refined particleboard material calibration
- More advanced nonlinear failure models

---

## Related Publication

**Simulating Pull-Out Fracture in Particleboard**  
Linköping University — MSc Mechanical Engineering
