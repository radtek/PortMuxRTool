# SensorDots Port MuxR Tool

A GUI application to aid with the control and operation of Port MuxR boards. Multiple boards can be controlled and chained together using this tool.

## Installation

Requires .NET 4.0

## Mono Instructions

Runs out of the box with mono (you might need to run as sudo or change ownership of the serial port):

mono PortMuxRTool.exe

If compiling with the latest version of mono, you might need to run the following:

xbuild /p:TargetFrameworkVersion="v4.5"

As the 4.0 target doesn't get installed.

When running under mono, it shows all serial ports (rather than just ones found active). You might need to scroll down to reach the last item on the dropdown list.

## Versions

   - 1.0.0.0 - Release Version