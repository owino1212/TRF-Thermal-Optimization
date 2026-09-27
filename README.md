# TRF Thermal Optimization Dataset & CAD Repository This repository contains the digital assets, numerical simulation datasets, CAD models, and analysis scripts supporting the research article: > **Computational Optimization and Thermal Performance of a Tilting Rotary Furnace for Artisanal Metal Recovery in Western Kenya** --- ## 📌 Overview This project numerically evaluates and optimizes the crucible material, profile geometry, wall thickness, and operating tilt angle for a small-scale (20 kg batch capacity) tilting rotary furnace (TRF) designed for informal metal recycling. * **Primary Software:** Autodesk Fusion 360, Python 3.x, R * **Key Findings:** A 10 mm cylindrical graphite crucible operated at a 45° tilt achieves an optimal operating temperature of ~1800 °C, ~70% thermal efficiency, and low specific energy consumption (0.375–0.417 kWh/kg). README.md

Directory / File	Type	Description
CAD_Models/	Directory	CAD assemblies and digital prototypes
CAD_Models/TRF_3D_Assembly.f3d	File	Parametric 3D digital prototype (Autodesk Fusion 360 format) 
CAD_Models/TRF_Assembly_Step.step	File	Neutral STEP interchange file for universal CAD viewer compatibility
Simulation_Data/	Directory	Raw numerical output and material property files
Simulation_Data/Transient_Thermal_Logs.csv	File	Time-series thermocouple logs sampled at 10-second intervals (N=10 runs) 
Simulation_Data/Material_Properties.json	File	Thermophysical properties matrix (emissivity, conductivity, density) 
Scripts/	Directory	Data extraction and statistical analysis scripts
Scripts/Extract_Thermal_Fields.py	File	Python automation script for parsing thermal fields and logging heat flux 
Scripts/Statistical_ANOVA.R	File	R code executing multi-factorial ANOVA and Tukey HSD post-hoc tests 
LICENSE	File	Creative Commons Attribution 4.0 International (CC BY 4.0) license file 
README.md	File	Project overview, navigation guide, and citation instructions
