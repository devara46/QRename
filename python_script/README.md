## GOALS

Instead of georeferencing from zero in [digitasi](https://github.com/devara46/digitasi), this code was created to assist with georeferencing files using a QGIS world file. 
Since QGIS world files don't account for image orientation, the scanned maps need to be rotated manually to face the correct direction. 
This code strives to rename and rotate the maps automatically by dividing the scanned maps into 20 segments and finding the segment containing the QR code as a reference point.

## INPUT

- MFD_FILE : dictionary containing the value of each respective code
- SOURCE : folder containing all the scanned maps
- RESULT : folder to store the processed maps

## Proses

