This repository contains a User-defined subroutine developed for finite element simulations using Abaqus. 

The subroutine consists of a:
    UMATHT - A user-defined material for heat transfer analysis. Computing the Degree of Cure based on an implemented cure kinetic model, glass transition temperature and the constitutive conducitivities, valid for composite materials as well as pure resin materials. 
    The heat balance equation takes into accoun the heat of reaction and can predict the thermal behaviour as the material cures. 
    UEXPAN - A user-defined expansion for a thermoset, using inputs passed as SDV's from the UMATHT to the UEXPAN allows for determining the chemical shrinkage and thermal expansion using a complex thermal expansion model to predict the cure-induced strains arising in the thermoset. Can be coupled with the fibre thermal expansion for the constitutive composite, orthotropic thermal expansions. 
    UMAT - Constitutive law of composite is implemented and takes into account the developing young's modulus of the thermoset with curing as well as utilising an approach for modelling the bending properties of a fibre fabric to account for the build-up of fibre stiffness with curing. 

The UMATHT and UMAT is presented and demonstrated to predict the thermal behaviour and overall cure shrinkage behaviour for the load-transferring part well in a study by Jørgensen et al. 2024 DOI: https://doi.org/10.5281/zenodo.11396017

The UMAT is described in a Software Impact paper. DOI: 
