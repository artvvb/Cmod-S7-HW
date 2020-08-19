# Cmod S7 Hardware Repository

This repository contains the Vivado projects and hardware designs for all of the demos that we provide for the Cmod S7, across multiple tools. As some demos also require software sources contained in Vitis workspaces, this repository should not be used directly. The [Cmod-S7](https://github.com/ArtVVB/Cmod-S7) repository contains all sources for these demos across all tools, and pulls in all of this repository's sources by using it as a submodule.

For additional documentation on individual demos, and for instructions on how to use them with your Cmod S7, visit their pages on the Digilent Wiki, linked below.

| Name and Wiki Link | Description |
|--------------------|-------------|
| [Cmod S7-25 Out-of-Box Demo](https://reference.digilentinc.com/reference/programmable-logic/cmod-s7/oob-demo/staging) | A simple hardware-only design using the LEDs, buttons, and USBUART Bridge |
| [Cmod S7-25 Microblaze XADC Demo](https://reference.digilentinc.com/reference/programmable-logic/cmod-s7/xadc-demo/staging) | Uses a Microblaze soft core processor and analog input pins to measure and print voltages |

For more information about the Cmod S7, visit its [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/cmod-s7/start) on the Digilent Wiki.

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked in the table of demos, above.

Demos were moved into this repository during 2020.1 updates. History of these demos prior to these updates can be found in their old repositories, linked below:
* [Cmod S7-25 Out-of-Box Demo](https://github.com/Digilent/Cmod-S7-25-OOB)
* [Cmod S7-25 Microblaze XADC Demo](https://github.com/Digilent/Cmod-S7-25-XADC)