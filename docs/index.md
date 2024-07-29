# Welcome to Mcorne

![28816_Mcorne_Banner](https://user-images.githubusercontent.com/65970993/142192291-f98b4d5c-05fb-46df-812c-ea15619faf7e.jpg)

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.






This is the Repository for a Magnetic Case for the Corne keyboard.


![20211104_104911](https://user-images.githubusercontent.com/65970993/142194100-e0e1e61c-e03f-4065-9170-004b7698ddeb.jpg)


This is the Repository for a Magnetic Case family for the Corne keyboard. There are 5 different version, so its easy to lose track of all the different versions or even to find the rigth one for your Corne and intented use case. So here is a overview with a quick summary of the features of the different cases and links to the different repositories.



Content:

* Preface
* The case
* Bill of Materials
* How to print
* Files
* Tangented
* More Pics
* Legend
* License
  

# Preface

Rework of the documentation on a special page: https://runningtarrens.github.io/Mcorne/


If you build a lot of keyboards or repair them, you know the hassle of having to open the cases, screw/ unscrew and taking apart the whole thing everytime you need to reflow a solder point, an led or maybe even just reset the MCU. Also for any corne build youll need to have about 20 screws and 5 standoffs per half to just keep the halfs together. With the Mcorne you dont need to unscrew anything to access the PCB or any screw or standoff to use this case. The Case supports magnetic tenting legs and provides tenting holes for other tenting methods.

Feel free to join the Discord Server, if you have questions about the case or just want to have a chat: https://discord.gg/TRQFN7fyU5


# The Case

![MagneticCorne2](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210412_124131.jpg)
![MagneticCorne3](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210213_095158.jpg)
![MagneticCorne4](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/20210213_095136.jpg)

# Bill of Materials

To print this case youll need:
* about 120 gramms of Filament
* 16 Neodymium Magnets (14mm x 4mm x 2,5mm)
* (Optional) 4 Neodymium Magnets round (10mm x 1mm)

Getting the right Magnets can be Hard. Hier are a list of sources i could find or people provided me:

* Europe:
* USA: [Ebay.com](https://www.ebay.com/itm/255362762463?hash=item3b74ce86df:g:I6YAAOSwLGxj5~dE&amdata=enc%3AAQAIAAAA4Dw5q5Iaz04OmhxHfPwu8k07GHBo7GwbV78mkknv9z1LJtW8EaM5w4%2BSH7qRupMZynmEo%2FcYvYoQUVCkhMq%2Fv2LbzTyd7T9DZ8iL7wkGtd%2Bo6yrR314zF5pcIP2%2BBKjTWxMPVYLN3%2BubwSLDq2Galkm0FqFl%2FZXGUN2%2BTN2dHdycdtO09tp%2Fo4Vs4yeQB6syOIESobyuEBhoNur8iQ5FjgA6CRerepnlfRRZ3P8fu9Vq9Ak06Z9%2F%2FHslnbwE5xtVcj2HeqcWrp0wzFRXSeRc3FeCLpfYIxDQMqS3Mt2r6bG5%7Ctkp%3ABk9SR9qimoqPYw)


# How to print
 
 I always print in PLA, but you can use any filament for the case. ABS/ASA and Filament that require an enclosure are difficult to work with, because if you want to put the magnets in, you have to open the enclosure and might be having problems with warping or cracked prints because of that.

## Slicing

### Settings for the Print:

* 0.10 layer hight
* 3 Parimeters
* 3 Top and Bottom layers
* 15% Infill
* 205°C Filament temp
* 60°C Bed Temp

### Getting the magnets in

To get the magnets in, the M600 command is used. The printer makes a pause. While the print is pause, the magnets can be put into the pockets. Its important that you check and double check the polarity of the magnets, so that the halfs stick to each other and dont repel each other. The holes are tight but have a bit of tolerance, it can be a bit of work getting the magnets in, depending on how accurate your printer is.

### Top
The print is paused on the top half after the 42 layer or 4.2mm hight.
![MagneticCorne5](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/Bild_2021-04-12_140316.png)


#### Position of the Pockets for the Magnets
![MagneticCorne6](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/Bild_2021-04-12_140616.png)



### Bottom

The Bottom part is a bit more complex. It has, if you choose magnetig tenting and a transparent basis, 3 pauses. 2 to get the magnets in and 1 to just change the filament. If you dont want magnetic tenting and dont want another colour for the top part, youll only need one pause for the magnets.

#### Overview of the Part.

![MagneticCorne7](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/bottom%20slice.JPG)

#### First pause for the round magnets needed for the tenting

![MagneticCorne8](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/bot%20slice%201.JPG)


#### Second pause to change the filament (different colour)

![MagneticCorne9](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/bot%20slice%202.JPG)


#### Third pause for the magnets to close the case

![MagneticCorne10](https://github.com/Runningtarrens/MagneticCorne/blob/main/pics/bot%20slice%203.JPG)


### Tenting Legs

![MagneticTentingLegs](https://github.com/Runningtarrens/Mcorne/blob/main/pics/tenting%20legs.JPG)

Print 4 of them upright. But you need a prim to have enough surface that sticks to the build plate or it will get loose while printing.




# Files

## latest files

* corne split_bot_rechts_v4.stl
* corne split_top_right_reinforced_tentless_v4.stl
* corne split_top_right_reinforced_v4.stl
* magnet_tenting_30mm.stl

Version v4 is the latest for the case. I made some corrections so the inner keys ( T and Z dont scratch on the case).
I only uploaded the right side as .stl but you can just mirror it in your slicer software to get the left version of it. 


The .stl are to slice yourself. (There are also .3mf files which are already dialed in and provide the exact settings i use.).
The .3mf are in rework for now.


# Tangented

* Magnetic tenting legs - Added to the files directory
* Mcorne Travel Case - Added to the Travel Case directory
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

# License

Print and modify all you want, but please dont sell my desgin (digital or printed).


