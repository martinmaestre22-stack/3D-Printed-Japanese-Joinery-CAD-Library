# 3D-Printed Japanese Joinery CAD Library

This repository contains parametrized Autodesk Inventor CAD files for five traditional Japanese joinery geometries adapted for 3D printing and mechanical characterization.

## Included joint geometries

The CAD library includes the following Japanese joints:

1. Koshikake kama Tsugi
2. Koshikake Ari Tsugi
3. Kanawa Tsugi
4. Isuka/Sumikiri Isuka Tsugi
5. Arikata

## File formats

Each joint folder includes:

- `.ipt`: native Autodesk Inventor parametrized part files
- `.iam`: Autodesk Inventor parametrized assembly file
- `.stp`: neutral CAD exchange file
- `.stl`: manufacturing file for 3D printing

## Selected assembly clearances

The final CAD models include the selected clearances obtained from the tolerance characterization stage.

| Joint geometry | Selected clearance |
|---|---:|
| Koshikake kama Tsugi | 0.40 mm |
| Koshikake Ari Tsugi | 0.35 mm |
| Kanawa Tsugi | 0.70 mm |
| Isuka/Sumikiri Isuka Tsugi | 0.30 mm |
| Arikata | 0.40 mm |

## Usage

Open the `.ipt` and `.iam` files in Autodesk Inventor to inspect and modify the parametrized geometry. The `.stp` files can be used for CAD exchange with other software, while the `.stl` files can be used for slicing and 3D printing.

## Purpose

The purpose of this repository is to provide reusable parametrized CAD models of Japanese joinery geometries for future design, fabrication, and mechanical testing of 3D-printed modular assemblies.

## Authors

Martin Said Maestre Romero  
Jonathan Camargo Leyva  
Department of Mechanical Engineering  
Universidad de los Andes  
Bogotá D.C., Colombia
