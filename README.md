# SLINKY

MATLAB code that generates the 3D geometry of a slinky coil and the tubes that connect it, from a few physical parameters.

## What it does

- `slinky_/slinky.m` builds the coil as a parametric helix from the point density, tube diameter, coil radius, number of revolutions and total length, and derives the pitch and the coil angle from them.
- `slinky_/con_tube.m` builds the inlet and outlet tubes with their bends (depth and bend radius) that connect to the coil.
- `slinky_/turntube.m` builds the turn section.
- `slinky_/app1.mlapp` is a MATLAB App Designer front end, and `final_slinky.mlx` is the live script that puts the pieces together.
- `for_redistribution*.rar` hold a compiled standalone build of the app (MATLAB Runtime required).

## Run

Open `slinky_/SLINKY.prj` in MATLAB, or run `final_slinky.mlx`. Tested only as MATLAB code; no toolboxes beyond core MATLAB are used in the geometry functions.

## Status

University coursework in energy systems. The geometry generators work; there is no further documentation of the parameter values used.
