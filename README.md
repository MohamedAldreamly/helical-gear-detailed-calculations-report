Helical Gear Stress Analysis (Analytical + ANSYS FEA)

This project presents the design and structural analysis of a helical gear pair using both analytical gear design equations and finite 
element analysis (FEA) performed in ANSYS Mechanical.

The objective of this study is to evaluate the bending stress at the gear tooth root and the surface contact stress responsible for 
pitting failure, and to compare the analytical results with numerical simulations.

Project Overview

The study was conducted in several stages:
Analytical Gear Design
2D Finite Element Analysis
3D Finite Element Model
Comparison between analytical calculations and FEA results
The results show a strong agreement between the analytical calculations and the numerical simulation, validating the modeling approach.

Gear Parameters

The analyzed system consists of a helical gear pair designed with the following main parameters:
Gear type: Helical Gear
Pressure angle: 20°
Helix angle: (project value)
Face width: (project value)
Material: Steel
Applied torque: 20 N·m

These parameters were used to perform the analytical stress calculations and to build the CAD model in SolidWorks.

Analytical Calculations
Two main failure modes were evaluated using classical gear design equations:
Tooth Bending Stress
The bending stress was calculated using the Lewis bending equation, considering:
Tangential force
Gear geometry
Lewis form factor
Dynamic factor Kv
Surface Contact Stress (Pitting)
The contact stress between gear teeth was estimated using the Hertz contact stress formulation, which evaluates the maximum
compressive stress at the tooth interface.

The analytical calculations provided baseline values for:
Bending stress
Surface pitting stress
Safety factors
Finite Element Analysis (ANSYS)
The CAD model was imported into ANSYS Workbench for numerical simulation.

2D Model

A 2D model was initially developed to reduce computational cost.
However, this model was not sufficient for representing the behavior of a helical gear, because:

The helix angle cannot be represented in 2D
Axial load components are neglected
Contact becomes a line instead of a 3D contact patch
Therefore, the results from the 2D model were considered only as a preliminary verification.
3D Sector Model
To better represent the real gear behavior while keeping the model computationally manageable, a 3D sector model was created.

The geometry included:
Several teeth from each gear
A portion of the gear body to preserve realistic stiffness
Contact Definition

The contact between the mating tooth flanks was defined using:
Contact type: Frictionless
Formulation: Augmented Lagrange
Interface treatment: Adjust to Touch
Mesh Strategy

A locally refined mesh was applied in critical regions:
Tooth contact surfaces
Tooth root fillet

This allowed accurate capture of both:
Contact pressure
Bending stress
Results

The finite element simulation showed that:
The maximum bending stress occurs at the tooth root, consistent with classical gear theory.
The contact pressure distribution appears in the tooth contact region, forming a localized contact patch.
The obtained values were found to be close to the analytical calculations, confirming the validity of the modeling approach.

Tools Used
SolidWorks – Gear geometry modeling
ANSYS Workbench / Mechanical – Finite Element Analysis
Classical Gear Design Equations – Analytical calculations
Key Engineering Concepts Covered
Gear tooth bending stress
Pitting surface stress
Helical gear force components
Contact mechanics
Finite element modeling
Mesh refinement for contact problems

