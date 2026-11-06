# Parker Truss Design, Load Testing, and Failure Analysis

Structural engineering project involving the design, fabrication, analytical evaluation, and physical load testing of a bamboo-chopstick Parker truss bridge.

## Project Overview

The bridge was designed as a statically determinate Parker truss to reduce material use while targeting high load capacity.

The project included:
- structural determinacy checks
- member-force analysis
- virtual-work / unit-load calculations
- 3D modeling
- physical fabrication
- experimental load testing
- theory–experiment comparison

## Key Results

- Bridge self-weight: 0.24 kg
- Theoretical capacity: 20.10 kgf (197.1 N)
- Measured failure load: 14.20 kgf (139.3 N)
- Measured / predicted: 70.6%
- Difference from theoretical prediction: 29.4%

## Engineering Interpretation

The experimental bridge failed 29% below the strength predicted by the simplified linear model. Inspecting the failure process pointed to three primary drivers of the premature failure:

- **Early buckling of compression members:** the slender bamboo members in compression buckled before the predicted capacity was reached; the linear member-force analysis did not include buckling.
- **Joint elasticity from manual wire-wrapping:** the hand-tied joints loosened and deformed under load instead of acting as the idealized pinned joints assumed in the analysis.
- **Loading eccentricity:** the load was not applied perfectly at the intended position, and the fabricated truss was not perfectly vertical or symmetric, introducing bending that the analysis did not account for.

Other sources of uncertainty included differences between the fabricated and theoretical dimensions, the elastic modulus of bamboo taken from reference data, and the 0.24 kg self-weight neglected in the original calculation.

## Project Portfolio

[View the full project portfolio](Parker_Truss_Design_Load_Testing_Portfolio.pdf)
