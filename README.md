# ETH-OFTools-2.3.X

This fork has taken the filtered noise inflow generator from the Chair of Building Physics (ETH Zurich) addons for OpenFOAM-2.3.x and attempts to make it compatible with the latest OpenFOAM release.
Compiles and passes basic tests on OpenFOAM-4.x.
Compiles on OpenFOAM-6.x.

just build with wmake libso :)

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

