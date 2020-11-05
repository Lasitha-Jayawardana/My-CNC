# My-CNC
3 Axis CNC Milling Machine

## Grbl

Download Latest grbl version. (Current Version : https://github.com/gnea/grbl/releases/tag/v1.1h.20190825).

Copy grbl folder to "C:\Users\Lasitha\Documents\Arduino\libraries" path.

Edit Files in grbl folder as Commit "Limit Switch Debouncing Changed". 

Open Arduino IDE and goto File -> Examples -> grbl.

Upload to Arduino.

## OpenCNCPilot

Change the GRBL Settings as the Grbl Settings Files.

##### Add Macros :
Return to Zero -> 
    
    G90 G0 X0 Y0

    G90 G0 Z0.0
  
Probe and set Zero ->

    N10 G38.2 Z-2 F20
    N30 G10 L20 P1 Z0
    N20 G91 G0 Z1
    
## Tools

FlatCam.  (https://bitbucket.org/jpcgt/flatcam/downloads/).

OpenCNCPilot. (https://github.com/martin2250/OpenCNCPilot/releases).

InkScape (https://inkscape.org/release/1.0.1/windows/).

