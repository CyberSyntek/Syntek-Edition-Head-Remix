BROWPLATE- STL FILES
=
![BrowPlatePieces](https://user-images.githubusercontent.com/81597534/184551367-bfd048d5-0dfe-45dc-8314-b08591e4f559.png)

- BrowHolderL-V1.stl

- BrowHolderR-V1.stl

- BrowPlate.stl

- MagnetHolder.stl x4

- NanoHolder-A.stl

- NanoHolder-B.stl

- PCA9685Mount.stl

- PCA9685MountSupport.stl x4

- TPUBrow-L-V1.stl (MADE FOR TPU)

- TPUBrow-R-V1.stl (MADE FOR TPU)

ELECTRONICS
=
For more detailed information on electronics & hardware needed, please refer to the BOM folder readme file.

https://github.com/CyberSyntek/Syntek-Edition-Head-Remix/tree/main/BOM

- x5 - MG90D or MG92B Servos Motors.

  Note: I have currently been using MG90D servo motors for these parts. I believe the MG92B may work better having a bit more torque, but I don't have enough   on hand at the moment. I will update when I get a chance to try some. 

- Arduino Nano + Mini B USB Cable (3FT)

- PCA9685

- Raspberry Pi Zero W + SD Card + Micro USB (3ft) if not included with Raspi Zero W. 

- MPU6050 (Currenly optional. It is slotted on the BrowPlate, but I need to experiment still)

SCREWS / BOLTS / CONNECTORS
=
- x6  - M2x5mm Screws

- x6  - M2x7mm Screws + x2 - If a second "Rasberry Pi Zero W"

- x8  - M2x8mm Screws

- x10 - M2x16mm Screws

- x10 - Servo Screws

- x4 - Du-Bro E-Z Connectors With Re-Usable Nylon Snap Ons

MAGNETS
=
- x4 - 10x3mm Neodymium Magnets
 
- x4 - 6x3mm Neodymium Magnets

  Note: Info on BOM

OTHER
=
- x4 - Strands of either ABS or PETG filament Filament

- Superglue

- TPU to print eyebrow files. 

TUTORIAL
= 
SERVO PREP - Ball Joint
=

Set servo to 90°/centered. We will want to drill the 5th from the center hole on the servo horn to be able to screw in the remaining Ball Joint we had left over from the 03-Jaw tutorial. With the Ball Joint now attached, attach the servo horn as shown in the image with the horn facing away from the wires. 

![0001-BallJointPrep](https://user-images.githubusercontent.com/81597534/184398430-7a90440d-1e74-44ee-b37c-05cf4b79ba62.png)

Servo to BrowPlate + (MPU6050)
=
We will want to screw the servo to the brow plate with x2 Servo Screws as shown below with the servo horn facing towards the back. If you decide you will be using a MPU6050, it will be easiest to install it at this point also using x2 M2x5mm Screws.

![0002-ServoMPU6050](https://user-images.githubusercontent.com/81597534/184401630-10c4579c-5fc5-4d59-b19a-0637534efc8d.png)

Arduino Nano Mounts (NanoHolders)
= 
Screw on NanoHolder-A and NanoHolder-B to the BrowPlate using x4 M2x7mm Screws. The Arduino Nano should be able to click in at any point so you can either put it now or later. 

![0003-NanoHolders](https://user-images.githubusercontent.com/81597534/184411546-8c7348aa-0177-4f57-a54a-95bf96e041e1.png)

PCA9685MountSupports to BrowPlate
=
Screw in the x4 PCA9685MountSupports from the bottom side of the BrowPlate using x4 M2x8mm Screws

![0004-PCA9685MountSupports](https://user-images.githubusercontent.com/81597534/184405682-3ce6215b-bcc3-4167-a140-5f57245f66de.png)

Attaching the PCA9685 and PCA9685Mount
=
Screw on the PCA9685Mount to the PCA9685MountSupports using x4 M2x8mm Screws followed by screwing on your PCA9685 to the PCA9685Mount using x4 M2x5mm Screws.

![0005-PCA9685Mount](https://user-images.githubusercontent.com/81597534/184411847-eb45e49a-f329-4ca9-a200-41086866c358.png)

Brow Servos
=
Mount x4 Servos onto the BrowPlate using x8 Servo Screws.

![BrowServos](https://user-images.githubusercontent.com/81597534/184503892-fd801b1e-3737-4cc9-89a9-8c8e9d2dc638.png)

Servo Horn Prep
=
We are going to want to attach our EZ connectors to the appropriate servo horns for each servo in this step. You will want to drill the holes in the servo horn wide enough to be able to push the EZ connectors through so that they can rotate easily enough and not be too stiff. Once through you will push on the nylon snap connectors so they are secured to the servo horns. With the servos all set to 90° / center you will want to attach the prepared servo horns to the correct servos as seen below. Inner Brow servos horns Inwards (5th from center holes) , OuterBrow servo horns facing outwards. (6th from center holes) 

![BrowHornPrep](https://user-images.githubusercontent.com/81597534/184552459-4df05534-7973-4306-91a2-35bb915cf932.png)

BrowHolders
=
Screw on the BrowHolder-L & BrowHolder-R using x3 M2x16mm Screws each. (x2 should be fine)

![0007-BrowHolders](https://user-images.githubusercontent.com/81597534/184553178-948b1251-d3c0-4520-a5ae-41f146a52c0d.png)



Attaching BallLinkConnector
=
You will now want to snap on the BallLinkConnector to the Ball Link on the servo so that it is hanging through the BrowPlate.

![0008-BallLinkConnector](https://user-images.githubusercontent.com/81597534/184553333-c46ef5b0-7255-4d82-b814-7a1b68ecf949.png)


Attaching the BrowPlate
=

Attach the BrowPlate to the BaseBeams using x6  M2x16mm Screws. Now lift the jaw to within range to snap on the connector. You may need to move the servo horn downwards to allow yourself enough space to be able to snap it on by hand.  

![0009-BrowPlate](https://user-images.githubusercontent.com/81597534/184553610-d5744f7a-f032-442a-882d-471784bc8f18.png)




Getting Wired
=

???????????????????

- INSERT PIC

Raspberry Pi Zero W Prep
=

???????????????????

Magnet Holder Prep 
=

???????????????????

USE A SHARPY

- INSERT PIC


EyeBrow Prep
=

???????????????????

- INSERT PIC

USE A SHARPY

Setting the Brows Limits
=

???????????????????

- INSERT PIC OR VIDEO

BROWPLATE IS FINISHED!
=
Now onto the final step located in the 05-BrowPlate folder readme file.

https://github.com/CyberSyntek/Syntek-Edition-Head-Remix/tree/main/05-Skull

TO BE UPDATED
=
- Upload Missing parts once complete

- Image files
