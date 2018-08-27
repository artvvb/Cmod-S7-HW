Cmod S7-25 Out-Of-Box Demo
==============

Description
--------------
This project is a a simple Vivado demo using the Cmod S7-25's LEDs, RGB LED, buttons, and USB-UART bridge, written in Verilog. When programmed onto a Cmod S7, the demo will cycle the board's RGB LED from Blue to Green to Red to Black. The other LEDs will light up in sequence. Whenever one of the two buttons is pressed, "Button # Pressed!" is sent to a connected serial terminal emulator using the USB-UART bridge.
 
Requirements
--------------
* **Cmod S7-25**: To purchase a Cmod S7, see the [Digilent Store](https://store.digilentinc.com/cmod-s7-breadboardable-spartan-7-fpga-module/)
* **Vivado 2018.2 Installation**: To learn how to get Vivado, see the [Installing Vivado and Digilent Board Files Tutorial](https://reference.digilentinc.com/vivado/installing-vivado/start).
* **Serial Terminal Emulator Application**: For more information see the [Installating and Using a Terminal Emulator Tutorial](https://reference.digilentinc.com/learn/programmable-logic/tutorials/tera-term).
* **MicroUSB Cable**
 
Demo Setup
--------------
1. Download and extract the most recent release ZIP archive from this repository's [Releases Page](https://github.com/Digilent/Cmod-S7-25-OOB/releases).
2. Open the project in Vivado 2018.2 by double clicking on the included XPR file found at "\<archive extracted location\>/vivado_proj/Cmod-S7-25-OOB.xpr".
3. In the *Flow Navigator* panel on the left side of the Vivado window, click **Open Hardware Manager**.
4. Plug the Cmod S7 into the computer running Vivado using a MicroUSB cable.
5. Open a serial terminal emulator (such as TeraTerm) and connect it to the Cmod S7's serial port, using a baud rate of 9600.
6. Click "Open target" in the green bar at the top of the window. Select "Auto connect" from the drop down menu.
7. Click "Program device" in the green bar at the top of the window. In the "Program Device" Wizard, enter "\<archive extracted location\>vivado_proj/Cmod-S7-25-OOB.runs/impl_1/top.bit" into the "Bitstream file" field. Then click **Program**.
8. The demo will now be programmed onto the Cmod S7. See the *Introduction* section of this README for a description of how this demo works.

Next Steps
--------------
This demo can be used as a basis for other projects, either by adding sources included in the demo's release to those projects, or by modifying the sources in the release project.

Check out the Cmod S7's [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/cmod-s7/start) to find more documentation, demos, and tutorials.

If there are any issues with running this demo, contact Digilent Support through the FPGA section of the [Digilent Forum](https://forum.digilentinc.com).

Additional Notes
--------------
For more information on how this project is version controlled, refer to the [Digilent Vivado Scripts Repository](https://github.com/digilent/digilent-vivado-scripts)