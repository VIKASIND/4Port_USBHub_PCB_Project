# 4-Port USB Hub PCB Project
This repository contains the design files for a 4-port USB hub created using KiCad. The project includes the schematic, PCB layout, and 3D renders of the final board. The USB hub design provides an efficient and compact solution to expand USB connectivity for any device.

Project Overview
The 4-port USB hub is designed to expand a single USB connection into four individual ports, making it ideal for connecting multiple devices like flash drives, keyboards, and other peripherals to a computer.


![3D Render of the PCB](Screenshot%202024-09-29%20084229.png))

Features
4 USB Ports: Supports up to 4 devices with USB 2.0/3.0 compatibility.
Compact Design: Designed for easy integration into various projects.
Powered Hub: Can be modified to support self-powered or bus-powered configurations.
Protection Components: Includes protection diodes and resistors to ensure safe and reliable operation.
3D Render of the PCB


![Circuit Diagram- PCB](./images/usb-hub-3d.png)



The above image shows a 3D render of the PCB designed in KiCad. It provides a visual representation of the layout, component placement, and overall board design.

Circuit Diagram
The USB hub design is based on standard USB hub controllers with the appropriate supporting components (resistors, capacitors, diodes, and ICs) to ensure functionality and protection. Here's a high-level overview of the circuit:

USB Hub Controller: The main controller IC that manages the distribution of data across the four USB ports.
Decoupling Capacitors: Placed near the power pins of ICs to filter out noise.
Protection Diodes: Used to protect the board from voltage spikes and incorrect power connections.
Crystal Oscillator: Provides the necessary clock signal for the hub controller.
Refer to the schematic in the repository for more detailed information.

KiCad Project Files
The design files for this project are available in the KiCad folder. It includes:

Schematic: The circuit schematic of the USB hub.
PCB Layout: The printed circuit board design.
3D Model: A 3D model of the PCB generated using KiCad's built-in 3D viewer.
To view and edit these files, download KiCad and open the project.

Getting Started
Prerequisites
KiCad: Download and install the latest version of KiCad to view and modify the design files.
3D Viewer: KiCad’s 3D viewer can be used to inspect the 3D models of the PCB.**
