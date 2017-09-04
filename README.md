# laser-cutter

# Pre-requisites

* Inkscape
* RDWorks

# Steps to use
## Check the following

* Check water level
* Check is "safe state" (TBD)
* Ensure grate is clear of materials

## Convert to Plotter

* Open Inkscape
* Import PNG to import
* Select (click on imported) image
  * If you don't, you'll need to click it again in the next step
* Click Path -> Trace Bitmap
  * Will open new window
  * Click "Live Preview"
  * Click "Brightness cutoff"
  * Click OK
  * Close Window
* Click File -> Save As
  * Save as type: Desktop Cutting Plotter (AutoCAD DXF R14) (*.dfx)
  
## Print to cutter

* Click File -> New
* Click File -> Import
  * Select your .dfx file
  * Click OK to accept defaults

### Reverse Image

* Click "Select" button (arrow button in top left)
  * Select entire image
  * Click Draw -> Horz Mirror
  
### Start print

* IP:  10.220.4.200
* Click Start

# References

* http://www.atxhs.org/wiki/Laser_Cutter_Materials
* http://www.atxhs.org/wiki/Blue_Laser_Cutter_Settings
* https://wiki.milwaukeemakerspace.org/spacedocumentation/lasercuttermateriallibrary
* https://wiki.milwaukeemakerspace.org/spacedocumentation/lasercutterhowto
* https://wiki.milwaukeemakerspace.org/equipment/lasercutter2
