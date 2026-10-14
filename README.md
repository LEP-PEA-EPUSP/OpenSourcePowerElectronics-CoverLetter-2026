# Open Source Power Electronics 2026

This repository contains the cover letter for the 2026 version Open Source Power Electronics platform developed by LEP-PEA-EPUSP. The platform is organized as a set of public repositories that document the hardware modules needed to build, study, and operate a modular power electronics system.

The 2026 release brings together the main inverter assembly, its processing and interface boards, the sensing and filtering stages, and the load infrastructure used for testing. Each repository provides the design material needed for replication and study, including manuals, schematics, layouts, and supporting test programs where applicable.

## Project repositories

- [OpenSourcePowerElectronics-HW-Inverter-2026](https://github.com/LEP-PEA-EPUSP/OpenSourcePowerElectronics-HW-Inverter-2026) - inverter module manuals, schematics, layout, and testing programs
- [OpenSourcePowerElectronics-HW-ProcessingModule-2026](https://github.com/LEP-PEA-EPUSP/OpenSourcePowerElectronics-HW-ProcessingModule-2026) - processing module manuals, schematics, layouts, and test material
- [OpenSourcePowerElectronics-HW-FilterBoard-2026](https://github.com/LEP-PEA-EPUSP/OpenSourcePowerElectronics-HW-FilterBoard-2026) - LCL filter board documentation for the inductor and capacitor boards
- [OpenSourcePowerElectronics-HW-TransformerBoard-2026](https://github.com/LEP-PEA-EPUSP/OpenSourcePowerElectronics-HW-TransformerBoard-2026) - transformer board manuals, schematics, and layouts
- [OpenSourcePowerElectronics-HW-AdapterBoard-2026](https://github.com/LEP-PEA-EPUSP/OpenSourcePowerElectronics-HW-AdapterBoard-2026) - adapter board manuals, schematics, layouts, and supporting files
- [OpenSourcePowerElectronics-HW-LoadBoard-2026](https://github.com/LEP-PEA-EPUSP/OpenSourcePowerElectronics-HW-LoadBoard-2026) - AC and DC load board documentation and layouts
- [OpenSourcePowerElectronics-SW-Inverter-UserInterface-2021](https://github.com/LEP-PEA-EPUSP/OpenSourcePowerElectronics-SW-Inverter-UserInterface-2021) - Software for HMI, updated in 2023
- [OpenSourcePowerElectronics-SW-PWM-2021](https://github.com/LEP-PEA-EPUSP/OpenSourcePowerElectronics-SW-PWM-2021) - Repository for microcontroller code destined for operation of PWM converters

## Purpose

This cover letter serves as a landing page for the 2026 platform and provides a single starting point for readers to navigate the individual repositories.

Users are invited to freely use and contribute to the development of the platform.

## License

If not otherwise noted, the following licenses apply:

Hardware: CERN-OHL-S v2
Software: GPLv3
Documentation: CC BY-SA-NC 4.0

## Conversion

It is important to note that the hardware project was initiated in 2015, and several individual collaborators have been responsible for designing different boards during the last decade. Such collaborators have used different tools in their work, which were most fit at the time being (considering their knowledge and existing software features).

Nowadays, KiCad has significantly evolved and finds widespread adoption, and is adopted for all recent developments.

Conversion or redesign in KiCad is scheduled to be gradually done, and in the meantime, external contributors can refer to the following:

KiCad Importers: https://docs.kicad.org/10.0/en/kicad/kicad.html#importing_a_project_from_another_eda_tool

Altium Student License: https://www.altium.com/education/students

Work in Progress: https://forum.kicad.info/t/importer-from-proteus-work-in-progress/71489

