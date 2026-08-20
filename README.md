------------------------------------
ATtiny85 USB PCB
------------------------------------
KiCad PCB design and manufacturing files for an ATtiny85 USB board.

Project Overview
-

This project is a PCB design created in KiCad as part of my hands-on PCB design and layout learning.

The project includes the KiCad schematic, PCB layout, and manufacturing output files.

Learning Exercise
-
This project was completed as a learning exercise based on an existing YouTube PCB design tutorial.

The purpose of the project was to gain practical experience with:

    KiCad schematic capture
    Component placement
    PCB layout
    Routing
    Design Rule Checking (DRC)
    Footprint assignment and verification
    PCB design organization
    Gerber generation
    Drill-file generation
    Preparing a design for PCB fabrication

This project is intentionally documented as a tutorial-based learning project rather than an independently originated PCB design.

Design Process
-
The project followed the general PCB development workflow:

1. Review the circuit and schematic
2. Assign and verify component footprints
3. Import the design into the PCB Editor
4. Define the board outline
5. Place components
6. Route PCB traces
7. Review clearances and layout
8. Run Design Rule Checking (DRC)
9. Generate manufacturing files
10. Review the resulting Gerber and drill files

Tools
-
    KiCad 9.0
    KiCad Schematic Editor
    KiCad PCB Editor
    KiCad Gerber Viewer

Project Files
-
KiCad Design Files

The repository contains the source design files required to open and inspect the project in KiCad:

    .kicad_pro — KiCad project file
    .kicad_sch — KiCad schematic
    .kicad_pcb — KiCad PCB layout

Manufacturing Files
-
Manufacturing outputs include:

    Gerber files
    Drill files
    PCB fabrication files
    Gerber/drill archive

PCB Design
-
The PCB layout includes:

    Component placement
    Through-hole and/or SMD component footprints as applicable
    Signal routing
    Power routing
    Ground connections
    Board outline
    Silkscreen
    Solder-mask layers

Design Verification
-
The design was reviewed using KiCad's PCB design-rule checking tools.

Verification performed:
    Electrical/PCB Design Rule Check (DRC)
    Footprint verification
    Board outline verification
    Manufacturing file verification
    Gerber review
    Clearance verification

Manufacturing
- 
Gerber and drill files were generated from the KiCad PCB design for the purpose of learning the PCB fabrication workflow.

The manufacturing files are included in this repository for inspection.

Project Status
-
Status: Completed as a learning exercise.

Future work may include independently redesigning or modifying the board to further develop PCB layout and engineering skills.

Future Improvements
-
Potential future revisions may explore:

    Independent component placement
    Alternative routing strategies
    Improved ground/return paths
    Design-for-manufacturing considerations
    Design-rule optimization
    Component substitutions
    PCB layout improvements based on independent analysis

Tutorial / Reference
-
This project was created while following:

Tutorial: KiCAD 7 PCB Layout in 5 steps

Creator: The Circuit Archive

Link: https://www.youtube.com/watch?v=3FGNw28xBr0&list=PLB5qGiy3BHlAJEgiv8YGyFJRMpOSFMpng

Disclaimer
-
This repository represents a personal learning exercise. It should not be considered an independently developed commercial hardware design.

The original tutorial/project creator is credited above.
