# Bokkusu
A simple, but elegant DIY Eurorack Case
![Bokkusu with no modules in it](https://github.com/drChungus/Bokkusu/blob/main/07_Production/Images/IMG_20220323_113925.jpg?raw=true)

## Concept
Bokkusu (ボックス, "box" in Japanese) is a DIY case for Eurorack format. The main design principle was to create a no-compromise case for your Eurorack modules. Parts are easy to manufacture locally as all plywood panels are rectangle shapes, which is easy to order from a local woodworking shop. The box itself can then be assembled in your home with minimal tools and skills required. Finally, the rails and electronics can be added to finish up the build.
The box itself is made out of plywood cut precisely. The default size for the case is 6U by 84 HP. This can be tweaked by modifying the dimensions in the BOM sheet, however this is not yet tested or advised. It is highly recommended you get a good understanding of what parts go where as modified dimension can propagate to related parts.
The power supply to be used is outside the scope of this project, but I can recommend using something like the RT-65B by MEAN WELL. If you do not feel confident wiring mains voltage in your case having a wall adapter and a power distribution module is a safe bet, so you can avoid routing mains into the case. For this the uZEUS with a Flying Busboard or something similar could be a nice solution.

## Parts Needed
The parts needed for the construction can be divided into two groups: required and optional. Optional parts are nice to have, but are not needed for a functional case. However, it is recommended to consider adding these as the full potential of Bokkusu can be achieved and user experience in general can be improved greatly. There might be some additional parts and mods not listed here you can come up with that fits your personal needs.

#### Required:
- Main Wooden box
- Eurorack rails with threaded insert/sliding nuts
- Power supply
- Power bus
- Nails/glue and screws

#### Optional:
- Mains power connector and power switch
- Wooden front box: with an added cover the box can be closed to protect modules from dust or during transportation
- Latches for the front cover
- Handle: so the box can be moved around conveniently
- Box corners: to protect the box and surfaces the case is placed on


## Assembly
The steps advised to manufacture the case are as follows:
1. Order plywood panels from local woodworking shop based on the [BOM sheet](https://github.com/drChungus/Bokkusu/blob/92de9adcf3d267ceded35ebd778eedd955a3f600/05_Native/Part%20List%20and%20Sizes.xlsx)
2. Assemble the plywood box back and front using nails and wood glue.
3. Mounting power supply
4. Mounting power bus
5. Wiring
6. Adding rails
7. Adding handle
8. Adding front box latches
9. Adding box corners

As said, the construction is fairly simple and requires only little experience with woodworking and electronics. For your reference, if you feel comfortable to assembly an IKEA furniture, you should be good to go.

Here is an incomplete list of tools you will need to put the wooden box together and wire it up:
- hammer
- power drill
- rafter square, aka "speed" square
- pencil


### 1, Order Plywood Parts
You should start by ordering the plywood parts from the local woodwork shop. The [BOM sheet](https://github.com/drChungus/Bokkusu/blob/92de9adcf3d267ceded35ebd778eedd955a3f600/05_Native/Part%20List%20and%20Sizes.xlsx) contains all necessary parts for a box to be built with. This is for the back and the front cover. The dimensions are fine tuned to a 6U (2 rows) case in 84HP width. Yo can change these dimensions to your liking to get a case that better fits your needs: you can increase the size to get more rows, more HP, and even can make the back more shallow. The default sizes provide 100mm space behind the modules' front panels and a bit of breathing room on the sides. I personally recommend double checking the size of the rails you will use as oftentimes these are cut with a bit of an extra, so verify if your rails will fit the case's width.

### 2. Box Assembly: 
The box is made out of two main parts: the back (main case) and a front cover. They are very similar in construction. Both parts are made out of 2 shells neatly fitting into each other. The inner shells overlap, this ensures that the front will lock into the back.

For the assembly the use of small sized nails are recommended. I put nails in every 100 mm or so to fix the planes to each other. When putting in the nails, make sure that the nails are aligned in the center and go in a perpendicular direction. 
![nails](https://github.com/drChungus/Bokkusu/blob/a63eebb536a812f9ce75dd27daeb7e407150857b/05_Native/Drawings/nailAllignment.png)

Here is an animation showing how the planes are put together to form a two layer box structure. Note that parts are overlapping in a way that adding the rails locks the side panels that lock the top, bottom and back planes:

https://user-images.githubusercontent.com/43809251/184827646-06c8e346-b369-46a6-9610-f2ae52bee6b0.mp4

There is also a [3D PDF](https://github.com/drChungus/Bokkusu/blob/409654e104498041dc1a0ab759a63892f6ceada7/06_Preview/3D%20PDF/MAIN.PDF) showing how the parts are assembled. This is the most convenient way to examine the construction in 3D. Note that you will need to download the PDF file and most probably enable the 3D view specifically to make this work.

As the box is put together, this might be the perfect time for a paint job. Raw plywood most be treated properly to get a long lasting product. Feel free to experiment with different glazes or solid colors - the woodwork shop will most probably give you the spares from the plywood cutting.

### 3. Mounting Power Supply
The power supply of your choice is most convenient to be mounted before the rails are added. Make sure it is well secured and will not come loose when the case is moved around! I recommend you put it in the center to get a better center of gravity. This step is skipped if a power distribution module is used instead.
In any case it is quintessential that you compare the expected power draw of your modules to the power solution's capabilities. You can use [the Modulargrid website](https://www.modulargrid.net/) to plan out your rack and get a good estimate on the power draw. As a good rule of thumb, I would suggest mounting twice the power, since power peaks and power supplies' reduced efficiency in elevated temperatures can cause some trouble like brownouts and other inconveniences. 
![Bokkusu with the power bus installed](https://github.com/drChungus/Bokkusu/blob/a9f2d587c1d22ba212f90f18b7bbaecec2261af5/07_Production/Images/IMG_20220322_211800.jpg)


### 4. Mounting Power Bus
The power bus will distribute power throughout your case. Once again, the choice is your, I was using my older design for a modular and expandable, 5V enabled power bus board module:
![busModule](https://github.com/drChungus/Bokkusu/blob/a9f2d587c1d22ba212f90f18b7bbaecec2261af5/07_Production/Images/IMG_20200105_203700.jpg)

The number of modules and free slots on the bus will dictate if you need one or two buses. I tend to have a lot of skinny modules that give a 

5: DISCLAMER: Mains voltage is no joke, you can be seriously hurt if the wiring is not performed properly. Feel free to ask for assistance from someone with more experience or use a low-voltage input to the case.
I have opted for the MEAN WELL RT-65B for the power duties to be done. This 65W supply delivers sufficient current on +12V, -12V and +5V lines, that conveniently matches the Eurorack power lines. The wiring from the mains connector to the power supply and then to the Eurorack power bus can be seen below. A switch and a fuse can be added.
![Wiring diagram](https://github.com/drChungus/Bokkusu/blob/409654e104498041dc1a0ab759a63892f6ceada7/05_Native/Drawings/wiringDiagram.png)



## Images
![Loaded and ready 2 go](https://github.com/drChungus/Bokkusu/blob/main/07_Production/Images/DSC_0147.JPG?raw=true)
![In it's full glory](https://github.com/drChungus/Bokkusu/blob/main/07_Production/Images/DSC_0013.JPG?raw=true)
![Closed closeup](https://github.com/drChungus/Bokkusu/blob/main/07_Production/Images/DSC_0014%20(2).JPG?raw=true)

## Conclusion
Bokkusu is a high value, customizable alternative for commercially available Eurorack cases. As many build their own cases tailored for their own needs this project can be considered a solid foundation for a cost-effective and hackable solution.
Note that the two-layered shell and the use of plywood (depending on type of wood used) will result a quite heavy result, in other words, if mobility is a concern for you, the second layer of the wooden box structure should be omitted.
