# Bokkusu
A simple, but elegant DIY Eurorack Case
![Bokkusu with no modules in it](https://github.com/drChungus/Bokkusu/blob/main/07_Production/Images/IMG_20220323_113925.jpg?raw=true)

## Concept
Bokkusu (ボックス, "box" in Japanese) is a DIY case for Eurorack format. The main design principle was to create a no-compromise case for your Eurorack modules. Parts are easy to manufacture locally as all plywood panels are rectangle shapes, which is easy to order from a local woodworking shop. The box itself can then be assembled in your home with minimal tools and skills required. Finally, the rails and electronics can be added to finish up the build.
The box itself is made out of plywood cut precisely. The default size for the case is 9U by 84 HP. This can be tweaked by modifying the dimensions in the BOM sheet, however this is not yet tested or advised. It is highly recommended you get a good understanding of what parts go where as modified dimension can propagate to related parts.
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


1: 
2: 2 shells, proper nails, paint job

Here is an animation showing how the planes are put together to form a two layer box structure. Note that parts are overlapping in a way that adding the rails locks the side panels that lock the top, bottom and back planes:

https://user-images.githubusercontent.com/43809251/184827646-06c8e346-b369-46a6-9610-f2ae52bee6b0.mp4

As an alternative there is a [3D PDF](https://github.com/drChungus/Bokkusu/blob/409654e104498041dc1a0ab759a63892f6ceada7/06_Preview/3D%20PDF/MAIN.PDF) showing how the parts are assembled. This is the most convenient way to examine the consructionin 3D.

3: with threaded insert or nuts
4:
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
