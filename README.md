# ETH-OFTools OpenFOAM version 4.x and 6.x

This fork has taken the modified LEMOS and filtered noise inflow generator from the Chair of Building Physics (ETH Zurich) addons for OpenFOAM-2.3.x and attempts to make it compatible with the latest OpenFOAM release.
Compiles and validation on OpenFOAM-4.x.
Compiles on OpenFOAM-6.x.

A quick validation of the LEMOS inflow generator is included as an example. Another level of resolution and  more time averaging may produce even better results.

Special thanks to Vincenzo Sessa, the validation study was from his paper here:

Vincenzo Sessa, Zheng-Tong Xie, "Turbulence and dispersion below and above the interface of the internal
and the external boundary layers", Journal ofWind Engineering and Industrial Aerodynamics,
Vol.182, pp.189-201, 2018.

The validation study needs cfMesh for meshing:

https://cfmesh.com/cfmesh/

Link to original project:
https://github.com/ETH-BuildingPhysics/ETH-OFTools-2.3.X

## Version: 


## Original Authors:
* Marc Immer
* Marcel Vonlanthen

## How to cite:
If you use the Filtered Noise Inflow Generator BC (FilteredNoiseInflowGenerator or FilteredNoiseInflowGeneratorScalar), please cite the following:
Immer, Marc Christian. Time-resolved measurement and simulation of local scale turbulent urban flow. ETH-Zürich (2016). http://dx.doi.org/10.3929/ethz-a-010657618

## Installation:

addon can be installed separately by executing wmake in its folder.   


## Contents

### Boundary Conditions
* **FilteredNoiseInflowGenerator**     
   Variant of Kleins Filtered Noise turbulent inflow boundary condition
   Documentation is available in the Doctoral Thesis: http://e-collection.library.ethz.ch/view/eth:49140

