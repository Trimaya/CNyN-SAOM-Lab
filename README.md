# CNyN-SAOM-Lab

Scripts used in the development of a Control System for the Sputtering Process at the Laboratory of Synthesis and Optical Analysis of Materials (SAOM-Lab) under Professor Roberto Sangines.

# 🔬 Reactive Magnetron Sputtering Control – MATLAB & Python Scripts

This repository contains MATLAB & Python scripts developed during my undergraduate thesis:  
**"Desarrollo de un sistema de control para el proceso de pulverización catódica reactiva"**  
(*Development of a Control System for the Reactive Cathodic Sputtering Process*), completed at CNyN-UNAM in 2023.

## 📄 Project Summary

The project focuses on real-time analysis of plasma emission during the reactive sputtering of Si₃N₄ thin films. Using optical emission spectroscopy (OES) data, I developed modules in MATLAB to monitor and quantify plasma stability, enabling more controlled and reproducible deposition conditions.

## 🧠 Key Features

- `Visual_Plasma.m`  
  Computes emission line intensities using both Gaussian fitting and numerical integration methods.

- `comparador.m`  
  Compares both integration methods to validate the use of faster numeric integration for real-time applications.

- `pendientes.m`  
  Calculates emission slope over time to assess plasma stability.

- `PromPendientes.m`  
  Aggregates slope data into confidence intervals using statistical analysis.

- `Prueba30_30.m`  
  Determines overall plasma stability by verifying a sequence of stable intervals.

- `Covarianza.m`  
  Performs Principal Component Analysis (PCA) to correlate gas flow with plasma behavior and replicate synthesis conditions.

## 💡 Applications

These tools are intended to support the development of **automated control systems for thin-film synthesis** using reactive magnetron sputtering. They may also be adapted for other real-time plasma monitoring and analysis tasks in nanomaterials research.
