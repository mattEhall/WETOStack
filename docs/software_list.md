
# Software Listing

This list contains software projects related to wind energy in some way.
The funding agencies and responsible labs vary.
A list of software that is specifically supported by WETO is at {ref}`weto-list`.


## Physics Simulators

- FLORIS: https://github.com/nrel/floris
- FLASC: https://github.com/nrel/flasc
- emu: https://github.com/nrel/emu_python
- moa: https://github.com/nrel/moa_python
- OpenFAST: https://github.com/openfast/openfast
- python-toolbox: https://github.com/openfast/python_toolbox
- matlab-toolbox: https://github.com/openfast/matlab_toolbox
- weio: https://github.com/ebranlard/weio
- SOWFA: https://github.com/nrel/sowfa
- Nalu-Wind: https://github.com/exawind/nalu-wind
- AMR-Wind: https://github.com/exawind/amr-wind
- WISDEM: https://github.com/wisdem/wisdem
- WEIS: https://github.com/wisdem/weis
- WindSE: https://github.com/nrel/windse
- CCBlade: https://github.com/WISDEM/CCBlade
- ROSCO: https://github.com/NREL/ROSCO
- ERF: https://github.com/erf-model/ERF
- DW TAP: https://github.com/NREL/dw-tap-app
- KiteFAST: https://github.com/openfast/kitefast
- MAFRIT: https://github.com/NREL/MAFRIT
- pBEAM: https://github.com/WISDEM/pBEAM
- PyFrame3DD: https://github.com/WISDEM/pyFrame3DD
- RAFT: https://github.com/WISDEM/RAFT
- WPGNN and PLayGen: https://github.com/NREL/WPGNN
- wtDigiTwin: https://github.com/ebranlard/wtDigiTwin

**Deprecated or no longer supported**

- ADAMS2AD: The MSC.ADAMS-to-AeroDyn (ADAMS2AD) interface is a software package for simulating the coupled dynamic response of horizontal-axis wind turbines.
- BladeFS: Blade Fatigue Static (BladeFS) is a MATLAB script that was developed to determine loads and deflections associated with fatigue and static structural testing of wind turbine blades using matrix based finite element analysis.
- HARP_Opt: Horizontal Axis Rotor Performance Optimization (HARP_Opt) utilizes a multiple-objective genetic algorithm and blade-element momentum theory flow model to design horizontal-axis wind and hydrokinetic turbine rotors.
- NAFNoise: NREL AirFoil Noise (NAFNoise) is a program that predicts the noise of any airfoil shape for five different types of noise sources.
- PROPID: PROP Inverse Design (PROPID) is aerodynamic design software developed by the University of Illinois at Urbana-Champaign. You can use it to design rotors.
- DrivePy: DrivePy is physics-based drivetrain model that sizes drivetrain components based on aerodynamic and operational loads for use in a systems engineering model. It also calculates costs based on empirical data collected by NREL's National Wind Technology Center.
- JacketSE: This is a module for static hydrodynamic, aerodynamic, and structural design and analysis of wind turbine jacket and towers within the Systems Engineering toolbox.
- Nacelle Systems Engineering Model and Hub Systems Engineering Model: nacelleSE and hubSE are models that size wind turbine hub system and drivetrain components based on key turbine design parameters and load inputs from a rotor model.
- RotorSE: This is a module for static aerodynamic and structural analysis of wind turbine rotors.
- TowerSE: This is a module for static aerodynamic and structural analysis of wind turbine towers.
- Turbine_costSE: turb_costSE is a set of models that link wind turbine component masses (and a few other key variables) to component costs.


## Design

- G2Aero: https://github.com/NREL/G2Aero
- Gear-SCouP: https://github.com/NREL/GEAR-SCouP
- HOPP: https://github.com/NREL/HOPP
- WISDEM/dakota_driver: https://github.com/WISDEM/dakota_driver

**Repository not found**

- INN Airfoil Tools: This software package contains code to perform airfoil inverse shape design using a sparsified invertible neural network model. This is a specialized deep learning architecture that enables both network weights to be shared to evaluate forward or inverse passes through the network. As a design tool, this network allows practitioners to specify aerodynamic and structural properties and generate shapes that satisfy those properties. 


## Grid load and demand models

- dGen: https://github.com/NREL/dgen
- dsgrid: https://github.com/dsgrid/dsgrid
- REopt: https://github.com/NREL/REopt.jl
- reV: https://github.com/NREL/rev
- reVX: https://github.com/NREL/reVX
- rex: https://github.com/NREL/rex
- MAGMA: https://github.com/NREL/MAGMA

## Cost models

- LandBOSSE: https://github.com/WISDEM/LandBOSSE
- HybridBOSSE: https://github.com/NREL/HybridBOSSE
- ORBIT: https://github.com/WISDEM/ORBIT
- CORAL: https://github.com/NREL/CORAL
- NRWAL: https://github.com/NREL/NRWAL
- WOMBAT: https://github.com/WISDEM/WOMBAT
- OpenOA: https://github.com/nrel/openoa
- FUSED-Wind: https://github.com/FUSED-Wind/fusedwind
- Marmot: https://github.com/NREL/Marmot

**Repository not found**

- JEDI (more macro than software)
- ORCA
- CREST: Cost of Renewable Energy Spreadsheet Tool

**Deprecated or no longer supported**

- LandOpExSE: This is a cost model for operational expenditures for land-based wind plants.
- NREL_CSM: NREL Wind Energy Cost and Scaling Model


## Preprocessors

- AirfoilPrep: https://github.com/WISDEM/AirfoilPreppy
- NuMAD: https://github.com/sandialabs/NuMAD

**Deprecated or no longer supported**

- AirfoilPrep: AirfoilPrep is a preprocessor for generating airfoil tables for AeroDyn.
- BModes: BModes is a finite-element code that provides dynamically coupled modes for a beam.
- IECWind: IECWind is a utility program used to create wind files for InflowWind-based programs.
- Modes: Modes generates mode shapes for wind turbine towers and blades.
- PreComp: PreComp is a code that provides span-variant structural properties for composite blades.
- SS_Fitting: SS_Fitting is a MATLAB toolbox designed to provide a state-space model based on the WAMIT output files.

**Included in OpenFAST**
- TurbSim: TurbSim is a stochastic, full-field, turbulence simulator primarily for use with InflowWind-based simulation tools.


## Postprocessors

All software listed here are no longer supported and are not hosted on GitHub.

- Crunch: Crunch is a software utility that performs several types of post-processing analyses for one or more files.
- GenStats: GenStats is a fairly simple utility that generates statistics for one or more files.
- GPP: GPP (pronounced "jeep") is a general-purpose postprocessor for wind turbine data analysis.
- MBC: MBC is a set of MATLAB scripts that performs multi-blade coordinate (MBC) transformation on wind turbine system models.
- MCrunch: MCrunch is a MATLAB-based postprocessor for wind turbine data analysis.
- MExtremes: MExtremes (pronounced em-extremes) is a set of MATLABscripts that generate extreme-event tables for one or more time series.
- MLife: MLife (pronounced em-life) is a set of MATLAB scripts that calculate fatigue life and statistics for one or more time series.


## Wild Life Impact

SSRS: https://github.com/NREL/SSRS


## Other

- CELAVI: https://github.com/NREL/celavi
- CEWAM: https://github.com/NREL/CEWAM
- GDX-pandas: https://github.com/NREL/gdx-pandas
- L-TERRA: https://github.com/NREL/L-TERRA
- NaTGenPD: https://github.com/NREL/NaTGenPD
- OSOS: https://github.com/NREL/osos
- R2PD: https://github.com/Smart-DS/R2PD
- Reegle Tagging API (CKAN Extension): https://github.com/REEEP/ckanext-climate-tagger
- sup3r: https://github.com/NREL/sup3r
- WindView: https://github.com/windview/client


(weto-list)=
## WETO Software

- FLORIS: https://github.com/nrel/floris
- FLASC: https://github.com/nrel/flasc
- emu: https://github.com/nrel/emu_python
- moa: https://github.com/nrel/moa_python
- OpenFAST: https://github.com/openfast/openfast
- SOWFA: https://github.com/nrel/sowfa
- Nalu-Wind: https://github.com/exawind/nalu-wind
- AMR-Wind: https://github.com/exawind/amr-wind
- WISDEM: https://github.com/wisdem/wisdem
- WEIS: https://github.com/wisdem/weis
- WindSE: https://github.com/nrel/windse
- ROSCO: https://github.com/NREL/ROSCO
- ERF: https://github.com/erf-model/ERF
- DW TAP: https://github.com/NREL/dw-tap-app
- RAFT: https://github.com/WISDEM/RAFT
- WPGNN and PLayGen: https://github.com/NREL/WPGNN
- wtDigiTwin: https://github.com/ebranlard/wtDigiTwin
- HOPP: https://github.com/NREL/HOPP
- LandBOSSE: https://github.com/WISDEM/LandBOSSE
- HybridBOSSE: https://github.com/NREL/HybridBOSSE
- ORBIT: https://github.com/WISDEM/ORBIT
- NRWAL: https://github.com/NREL/NRWAL
- WOMBAT: https://github.com/WISDEM/WOMBAT
- OpenOA: https://github.com/nrel/openoa
- NuMAD: https://github.com/sandialabs/NuMAD
- SSRS: https://github.com/NREL/SSRS
- CORAL: https://github.com/NREL/CORAL
- MoorPy: https://github.com/nrel/moorpy