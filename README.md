# Natalia Lewandowska - PhD dissertation notes and general remarks

## Work structure

### Chapter "Iintrodution and main objectives"
+ interdisciplinary approach for blood flow modelling
+ definition of aterosclerosis
+ statistical data
+ main objectives: general(1) and specific(3)
+ main goal of PhD: define a new group of diagnostic parametres for carotid geometry
+ overview of dissertation 

### Chapter "Literature review - medical issues"
+ atherosclerosis - chemical causes
+ atherosclerosis - plaque structure, composition and shape
+ atherosclerosis - statistical data
+ atherosclerosis - diagnose and classification for plaque removal
+ atherosclerosis - postoperative complications (restenosis)
+ atherosclerosis - biomechanical causes

### Chapter  "Liteature review - CFD and methodology"
+ areas of research
+ artery geometry modelling: 2D, 3D
+ blood fluid model
+ inlet and outlet BC
+ CFD vs FSI: wall artery model
+ discretization schemes and turbulence modelling
+ spatial discretization
+ validation
+ conclusion and most significant observations so far
+ overview of CFD methods: consercative, meshless

### Chapter "Summary of research so far"
+ establishing of surgical patch shape and comparision with the nes used so far
+ influece of patch lenght and width for different arteries diameters
+ plaque shape and plaque deposition modelling
+ influence of the bifurcation angle between ICA and ECA of blood flow disturbances
+ meshing strategy and validation

### Chapter "CFD theory"
+ concept of general transport equation: convective and diffusive fluxes
+ constitutive equations: continuity and momentum equation
+ concept of discretization for partial differential equation
+ RANS vs DNS vs LES
+ wall function and y+: turbulence modelling and turbulence models for RANS

### Chapter "Fluid mechanics of blood flow"
+ flow in variable geometry channels
+ Cauchy tensor and concept of viscosity
+ separation of boundary layer and reversed flow, vortex creation
+ non-newtonian fluids with solid particles and infuence of BL separation and plaque deposition
+ plaque deposition under influence of geometry
+ predition for plaque deposition and its progress in time
+ wall shear stresses and velocity: OSI, TAWSS, RRT as the most significant parametres to blood flow analysis
+ pulsative flow: Reynolds number and Womersley velocity profile, Womersley nummber
+ pulsative flow: Windkessel model

### Chapter "Methodology: geometry and numerical scheme"
+ CA geometric description 
+ patient-specific geometries
+ Taguchi method: CA geometry models description
+ numerical study for ps geometry 00_left: validation data, mesh study (done in previous publication), comparision of different discretization schemes and turbulence models
+ boundary conditions implementations
+ final numerical setup

### Chapter "Results and discussion for models"
+ Taguchi table summary
+ WSS distribution in time in marked areas
+ velocity distribution in time in areas of interest
+ boundary layer thickness along the artery for models
+ pressure distribution along the CCA, ICA and ECA
+ velocity and RRT contours for couple of cases

### Chapter "Diagnostic parametr and its evaluation od patient specific geometries"
+ to be continued...

### Chapter "Conlusions"
+ establishing of final formula for diagnostic parameter
+ description of GUI for surgeon for selection of proper patch geometry??? (nie wiem czy to nie za dużo...._

### Appendices:
+ C script for Womersley velocity profile
+ C script for Windkessel pressure response
+ Python script for post-processing of data
+ Figures of CFD results for all geometries


