# XTMCU02-Rev4_1_Design-Documentation_Public.zip - Package content

This document describes the contents of this PCB/PCBA documentation package.

## Package Content

    |-- Altium_Project_280027-004/                 # Folder containing Altium project files
        |-- doc/                                   # Folder containing documents in ascii format
            |-- PCB_documentation.txt              # Markdown file for generation of PCB_documentation
            |-- PCB_specification.txt              # Markdown file with PCB manufacturing specifications
            |-- PCBA_documentation.txt             # Markdown file for generation of assembly specifications
            |-- Release_Notes.txt                  # Markdown file with project release notes
        |-- Dimensions.PCBDwf                      # Altium Draftsman drawing of PCBA
        |-- Drill_Drawing.PCBDwf                   # Altium Draftsman drill drawing
        |-- MCU.Harness                            # Altium MCU sheet harness definitions
        |-- MCU.SchDoc                             # Altium Schematic sheet
        |-- PCB_LayerStackup.PCBDwf                # Altium Draftsman drawing of layer stackup
        |-- Power.SchDoc                           # Altium Schematic sheet
        |-- Top-Level.Harness                      # Altium Top-Level sheet harness definitions
        |-- Top-Level.SchDoc                       # Altium Schematic sheet
        |-- XTMCU02.PcbDoc                         # Altium PCB Document
        |-- XTMCU02.PrjPcb                         # Altium PCB Project File
    |-- PCB_Doc_290052-004/                        # Folder containing documents for PCB manufacturing
        |-- Gerber/                                # Folder containing gerber files
            |-- Gerber-290052-004.apr              # Aperture data
            |-- Gerber-290052-004.EXTREP           # Gerber file extension report
            |-- Gerber-290052-004.G1               # Gerber file for Mid-Layer 1
            |-- Gerber-290052-004.G2               # Gerber file for Mid-Layer 2
            |-- Gerber-290052-004.GBL              # Gerber file for Bottom Layer
            |-- Gerber-290052-004.GBO              # Gerber file for Bottom Overlay
            |-- Gerber-290052-004.GBS              # Gerber file for Bottom Solder Mask
            |-- Gerber-290052-004.GM1              # Gerber file for Board Outline
            |-- Gerber-290052-004.GP1              # Gerber file for Internal Plane 1
            |-- Gerber-290052-004.GP2              # Gerber file for Internal Plane 2
            |-- Gerber-290052-004.GTL              # Gerber file for Top Layer
            |-- Gerber-290052-004.GTO              # Gerber file for Top Overlay
            |-- Gerber-290052-004.GTP              # Gerber file for Top Paste Mask
            |-- Gerber-290052-004.GTS              # Gerber file for Top Solder Mask
            |-- Gerber-290052-004.REP              # Gerber file generation report
            |-- Gerber-290052-004.RUL              # Design rules export file
            |-- Gerber-290052-004-macro.APR_LIB    # Project macros
        |-- NC_Drill/                              # Folder containing NC drilling files
            |-- NC_Drill-290052-004.DRR            # Altium NC Drill report file
            |-- NC_Drill-290052-004.LDP            # Drill file to layer pair mapping report
            |-- NC_Drill-290052-004-RoundHoles.TXT # NC Drill file for thru-holes
            |-- NC_Drill-290052-004-SlotHoles.TXT  # NC Drill file for slot shaped thru-holes
        |-- PCB_Doc-290052-004.PDF                 # PCB Manufacturing Documentation in pdf format
    |-- PCBA_Doc_280027-004/                       # Folder containing documents for board assembly
        |-- BOM-280027-004.xlsx                    # Bill of Materials in Excel format
        |-- PCBA_Doc_280027-004.PDF                # PCBA Manufacturing Documentation in pdf format
        |-- Pick_Place-280027-004.txt              # ascii file for Pick and Place machine
        |-- Test_Point_Report-280027-004.txt       # ascii file with coordinates of test points
    |-- 3D_Print_280027-004.PDF                    # 3D-view of PCBA in pdf format
    |-- PCB_Prints_280027-004.PDF                  # Print of all PCB layers in pdf format
    |-- PDF3D_280027-004.PDF                       # PCBA in PDF3D format
    |-- readme.md                                  # This file
    |-- STEP_Model_280027-004.step                 # 3D model of PCBA in step format

## Viewing project documents

### Altium Designer project files

An [Altium Designer Viewer Licence](https://www.altium.com/altium-designer-viewer) is necessary for accessing the Altium project design files.

### Gerber and NC Drill files

Gerber files and NC Drill files can be viewed using any generic gerber viewer software capable of reading Gerber RS-274X format. [Gerbv](http://gerbv.geda-project.org/) is a free/open source gerber viewer that can open these files.

### Viewing step model

The step model file contains the PCBA in 3D step format. The model may be imported into most 3D CAD tools. To view the model, use a simple step viewer like
[STP Viewer](http://stpviewer.com/).

## Altium project missing files

When opening Altium project, some files may be reported as missing. These files are for internal use in Novelda, and are not relevant to the data contained within the Altium project.
