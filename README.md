# Grid-Forming and Grid-Feeding Models for Matlab/SimPowerSystem

## Introduction
After the european project [Migrate](https://www.h2020-migrate.eu), generic simulation models for grid forming converters has been developped.

The package in this repository are a set of Grid-Forming and Grid-Feeding inverter models for Matlab/SimpowerSystem. It is intended as a simulation library for researchers, engineers, teachers or students that is easy to use or modify.

## Terms of use
The package is distributed as MIT license
While not required by the terms of the license, we do request that publications derived from the use of the models explicitly cite the following references:
T. Qoria, Q. Cossart, C. Li, X. Guillaud, F. Colas, F. Gruson and X. Kestelyn (2018). WP3-Control and Operation of a Grid with 100% Converter-Based Devices. Deliverable 3.2: Local control and simulation tools for large transmission systems. MIGRATE Project, Tech. Rep.

T. Qoria, F. Gruson, F. Colas, G. Denis, T. Prevost and X. Guillaud, "Inertia effect and load sharing capability of grid forming converters connected to a transmission grid," 15th IET International Conference on AC and DC Power Transmission (ACDC 2019), Coventry, UK, 2019, pp. 1-6, doi: 10.1049/cp.2019.0079.

Please see the LICENSE file for details

## Getting started
### Requirements
* Matlab (>R2016a)
* Simulink (>R2016a)
* Simscape electrical Specialized Technology (>R2015a)

Note: the recommended Matlab versions is above R2021a, VSCLib can be run on version before but it is not fully tested

## Installation
1. Download the library from this repositery
> or
1. Clone this repositery
2. Choose your release
3. type the following command from the folder where you have extracted the library.
```shell
setup_VSC_Lib
```
> or
3. add the Library folder in your Matlab path and refresh your simulink library browser
4. Check that a new library named 'VSC4SPS' has been added in the library browser of Simulink

