# Cubsat

A CubeSat (2U) satellite project covering CAD design, structural analysis, and documentation.

## Repository Structure

```
VB_Cubsat/
├── satellite parts/
│   ├── 2U_draft1/                  - 2U draft CAD part
│   ├── 3d stl satellite/           - Scalable 3D prints (STL) of parts
│   ├── ansys satellite/            - IGES model for ANSYS analysis
│   ├── antenna deployment/         - Antenna deployer designs
│   ├── Cubesat Josh Chang/         - Early frame assembly + parts + STLs
│   ├── Cubesat Updated/            - Latest frame design, parts, tests, renderings
│   ├── Renderings/                 - CAD renderings
│   ├── stl files/                  - Additional STL part files
│   ├── Assem new.*                 - Main assembly (SLDASM, STL, IGS, parasolid, zip)
│   ├── Assem1/2/3.SLDASM           - Assembly variants
│   ├── *.SLDPRT                    - Individual parts (plates, pins, hinges, flange)
│   └── *.JPG                       - Assembly screenshots
├── step files/
│   └── Assem new step*.STEP        - Neutral STEP CAD exports of the assembly
├── ansys results/
│   └── model analysis of cubesat*  - ANSYS Workbench project + FEA results
├── battery recycling/
│   ├── Advanced Battery Recycling.docx  - Battery recycling report
│   └── ansys/                          - Battery assembly IGES for analysis
├── satelite doc files/
│   ├── architecture .jpeg          - Satellite architecture diagram
│   └── Power_Budget.pdf            - Power budget documentation
├── vijay exam file.docx / .pdf    - Project exam documents
└── README.md
```

## Purpose

Design and structural verification of a 2U CubeSat, including solar panels, antenna deployment mechanisms, and internal components, validated with FEA analysis in ANSYS.