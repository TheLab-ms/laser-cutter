# Laser Cutter

# Info

* 500mmx700mm cutting space
* Clone of http://www.thunderlaser.com/products/nova-laser-cutter.html
* Laser Tube Replacement: https://www.ebay.com/itm/EFR-ZN-ZS1250-80W-CO2-Sealed-Laser-Tube-US-Stock/183439121099

# Tools

* Inkscape - Vector graphics software.  Used to convert images to vector graph
* RDWorks - Laser cutter software to file, adjust, set your parameters/settings. You can even design in it.  Does both Vector and Raster in the same job

# On/Off
Laser switch on/off 
Main Power on/off.
The Emergency Stop is only for Emergencies. IT WILL FIRE A LASER PULSE - EVEN with the door OPEN.

# Focus

We assume a fixed height.  Ensure top of material is TODO distance from head.

# Home 
*	Default 0,0. In upper left
* Laser will automatically home on start.
* Setting new home position.  Origin on control panel will set the new Home position wherever the laser head is positioned. 

## Resetting new Home
* In RDWorks, the green square is where the laser will start.
* Laser ignores white square around image.
* Starts where the Origin is set

## Frame
* Once job is loaded, click "Frame" on Laser Cutter to see outline of file loaded.

## Load Job to Laser Cutter
* Once job is ready, Click "Download" button
  * Yes, even though you are uploading job, it's the download button

## Starting a job
* In RDWorks, you have 2 options.
* [Start] turns on the blower & immediately starts the job. 
* [Download] adds the job to the job queue on the laser.  This is accessed via the [Files] button.  [Files] lets you scroll thru the jobs.  Select one and press [Enter]. The screen shows the job in color, with the setting for each color.  Press [Start/Pause] to start the job.
* The Blower comes on automatically

# Pausing a job
* Press [Start/Pause]. To restart a job press  [Start/Pause] again.

# Stopping a job
* Press [Start/Pause]. Press[Esc]
* or 
* Press [Reset].  Use the [Esc] or [Enter] key to reboot if needed.

# Max Speed
* Current recorded max speed is 200mm/s


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
* https://docs.google.com/document/d/1Vb5_RDzhgYXnt1x8TM49Li398bMSygKMwKeBQtKmEYM/edit

# Troubleshooting

## Image Mirrored and/or Wrong X/Y home
* Main Menu>Config(S)>System Setting
* Please make sure "X Axis Mirror" and "Y Axis Mirror" are checked
* Ensure "Laser Head" radio box is in top left corner.
