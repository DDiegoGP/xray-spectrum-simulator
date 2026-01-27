# X-Ray Tube Spectrum Simulator

Interactive simulator for X-ray spectrum analysis in medical diagnostics.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/TU_USUARIO/TU_REPO/HEAD?urlpath=voila%2Frender%2Fxray_simulator.ipynb)

⚠️ **IMPORTANTE:** Reemplaza `TU_USUARIO` y `TU_REPO` en el badge anterior con tu información de GitHub.

## Features

- Canonical and experimental tube configuration
- Filtration and ripple analysis
- Automatic quantitative metrics
- Advanced visualization (differential view, K-edge)
- Data export (CSV, PNG)

## Usage

Click the "launch binder" badge above and wait 20-30 seconds for the simulator to load.

## Author

Master's in Biomedical Physics - Universidad Complutense de Madrid

## Technical Details

- Real NIST-based K-edge calculations
- Kramers law for Bremsstrahlung
- Characteristic X-ray lines (Kα1, Kα2, Kβ1, Kβ2)
- Exponential attenuation with K-edge discontinuity
- Ripple integration over 16 voltage levels
