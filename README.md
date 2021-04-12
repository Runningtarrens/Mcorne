# MagneticCorne
This is the Repository for a Magnetic Case for the Corne keyboard.

![MagneticCorne](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124343.jpg)

Content:

* Preface
* The case
* Bill of Materials
* How to print
* Files
* Tangented
* More Pics
* Legend


# Preface

If you build a lot of keyboards or repair them, you know the hassle of having to open the cases, screw/ unscrew and taking apart the whole thing everytime you need to reflow a solder point, an led or maybe even just reset the MCU. Also for any corne build youll need to have about 20 screws and 5 standoffs per half to just keep the halfs together. With the MagneticCorne you dont need to unscrew anything to access the PCB or any screw or standoff to use this case. The Case supports magnetic tenting legs and provides tenting holes for other tenting methods.


# The Case

![MagneticCorne2](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124131.jpg)
![MagneticCorne3](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210213_095158.jpg)
![MagneticCorne4](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210213_095136.jpg)

# Bill of Materials

To print this case youll need:
* about 120 gramms of Filament
* 16 Neodymium Magnets (14mm x 4mm x 2,5mm)
*  (Optional) 4 Neodymiom Magnets round (10mm x 1mm)

# How to print
 
 
Youll probably need to scale the files up to 1000%, because my CAD programm always exports in cm instead of mm, just for your information.
I always print in PLA, but you can use any filament for the case. 

## Slicing

### Settings for the Print:

* 0.10 layer hight
* 3 Parimeters
* 3 Top and Bottom layers
* 15% Infill
* 205°C Filament temp
* 60°C Bed Temp

### Getting the magnets in

To get the magnets in, the M600 command is used. The printer makes a pause and removes the filament from the extruder. While the print is pause, the magnets can be put into the pockets. Its important that you check and double check the polarity of the magnets, so that the halfs stick to eack other and dont repell each other. The holes are tight but have a bit of tolerance, it can be a bit of work getting the magnets in, depending on how accurate your printer is.

### Top
The print is paused in on the top half after the 42 layer or 4.2mm hight.
![MagneticCorne5](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/Bild_2021-04-12_140316.png)


#### Position of the Pockets for the Magnets
![MagneticCorne6](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/Bild_2021-04-12_140616.png)



### Bottom

The Bottom part is a bit more complex. It has, if you choose magnetig tenting and a transparent basis, 3 pauses. 2 to get the magnets in and 1 to just change the filament. If you dont want magnetic tenting and dont want another colour for the top part, youll need only one pause for the magnets.

#### Overview of the Part.

![MagneticCorne7](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/bottom%20slice.JPG)

#### First pause for the round magnets needet for the tenting

![MagneticCorne8](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/bot%20slice%201.JPG)


#### Second pause to change the filament

![MagneticCorne9](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/bot%20slice%202.JPG)


#### Third pause for the magnets to close the case

![MagneticCorne10](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/bot%20slice%203.JPG)


# Files

* corne split_top_rechts.stl
* corne split_bot_closed_rechts.stl
* corne split_top_rechts.3mf
* corne split_fase_bot_closed_rechts.3mf

The .stl are to slice yourself. There are also .3mf files which are already dialed in and provide the exact settings i use.


# Tangented

* Magnetic tenting legs - soon
* Keycaps - soon




# More Pics

![MagneticCornegif1](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210213_095457_1.gif)
![MagneticCornegif2](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210213_095457_2.gif)


#### Bottom

![MagneticCorne11](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124627.jpg)


#### Top underside

![MagneticCorne12](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124807.jpg)


#### Top upside

![MagneticCorne13](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124826.jpg)


#### USB Port

![MagneticCorne14](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124300.jpg)


#### TRS Port

![MagneticCorne15](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124229.jpg)


#### Detail view 

![MagneticCorne16](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124309.jpg)


#### Detail view close up

![MagneticCorne17](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124406.jpg)


# Legend

* MCU = Microcontroller unit
