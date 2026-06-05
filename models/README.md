# Models

This directory contains modified CAD models for the UMI Hand.

## Background

The original UMI Hand design uses a linear rail that is not readily available in Japan. To enable assembly using components that can be purchased domestically, several CAD models were modified.

These modifications were created and validated at Nakamura Laboratory, The University of Electro-Communications.

## Modified Parts

### gripper-bottom_plate

Modified to match the dimensions and mounting-hole locations of the linear rail available in Japan.

### gripper-grip

Modified accordingly to maintain compatibility with the updated gripper-bottom_plate.

## File Types

### STEP Files (.step)

STEP files are provided for CAD editing and further design modifications. These files can be imported into CAD software such as Fusion 360, SolidWorks, and FreeCAD for customization and future development.

Examples:
- gripper-bottom_plate-v1.step
- gripper-grip-v1.step

### STL Files (.stl)

STL files are provided for direct 3D printing. These files can be imported into slicer software such as Bambu Studio, Cura, or PrusaSlicer without additional CAD processing.

Examples:
- gripper-bottom_plate.stl
- gripper-grip.stl

## Notes

- The remaining parts are identical to the original UMI Hand design.
- Please refer to the BOM directory for the corresponding parts list available in Japan.

## Revision History

### v1.0

- Adapted the design for a Japan-available linear rail.
- Updated:
  - gripper-bottom_plate
  - gripper-grip
