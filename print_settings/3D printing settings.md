# 3D Printing Settings

The following settings were used to print the modified UMI Hand components at Nakamura Laboratory.

## Tested Configuration

| Item              | Value           |
| ----------------- | --------------- |
| Printer           | Bambu Lab P2S   |
| Nozzle            | 0.4 mm          |
| Rigid Material    | Bambu PLA Basic |
| Flexible Material | Bambu TPU 95A   |
| Last Tested       | 2026-06-11      |

## PLA Settings for Rigid Components

The following settings were used for the modified rigid structural components.

| Parameter            | Value                   |
| -------------------- | ----------------------- |
| Layer Height         | 0.20 mm                 |
| Initial Layer Height | 0.20 mm                 |
| Wall Loops           | 3                       |
| Top Shell Layers     | 6                       |
| Bottom Shell Layers  | 6                       |
| Infill Density       | 20%                     |
| Infill Pattern       | Gyroid                  |
| Supports             | Enabled where necessary |
| Build Plate Adhesion | Default                 |
| Nozzle Temperature   | 200°C                   |
| Bed Temperature      | 60°C                    |

## TPU Settings for Finger Pads

The following settings were used for the flexible finger pad components.

| Parameter             | Value                       |
| --------------------- | --------------------------- |
| Material              | Bambu TPU 95A               |
| Layer Height          | 0.20 mm                     |
| Initial Layer Height  | 0.20 mm                     |
| Wall Loops            | 4                           |
| Top Shell Layers      | 8                           |
| Bottom Shell Layers   | 8                           |
| Sparse Infill Density | 95%                         |
| Sparse Infill Pattern | Lines                       |
| Nozzle Temperature    | 250°C                       |
| Bed Temperature       | 40°C                        |
| Cooling Fan           | 0%                          |
| Auxiliary Fan         | 0%                          |
| Outer Wall Speed      | 20 mm/s                     |
| Inner Wall Speed      | 25 mm/s                     |
| Infill Speed          | 25 mm/s                     |
| Top Surface Speed     | 20 mm/s                     |
| Initial Layer Speed   | 15–20 mm/s                  |
| Supports              | Avoid if possible           |
| Brim                  | Recommended for small parts |

## Notes and Validation

* The modified PLA components were successfully printed and assembled into a functional UMI Hand.
* The flexible finger pad components were successfully printed using TPU 95A with a 0.4 mm nozzle on the Bambu Lab P2S.
* For TPU printing, it is recommended to dry the filament before printing and feed it directly from a dry box when possible.
* Total printing time for all modified PLA parts is less than 12 hours on the P2S.
* Users who intend to modify the material, nozzle diameter, or filament brand should perform additional validation regarding dimensional accuracy, assembly compatibility, and mechanical performance.
