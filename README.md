# Converter for punch files

When stiffness is performed there is an output file that is has a .pch extension. The file contains displacement values for the nodes that have the applied load on them. This .pch or punch file has extra data that is not needed and is repetitive, and can be automated to reduce build time for report.

## Project Plan

Create a python GUI that when executed will receive an file that would be a punch file. Once file is selected then the program will use regex to find the values that are required to build the report. Then the data be used to build a stiffness values that are meant to be recorded for model documentation.

## Issues

The biggest issue for is if the load case number or load case name is not defined correctly. In turn could cause stiffness result to not be recorded correctly. To prevent this in the future could build a script that would take in node list and generate the load to run in analysis.

## Python Libs

Sphinx to document, Probably not needed but wanted to learn a bit about it
Pytest with coverage, Testing and work like its real life.
