BROWPLATE- STL FILES
=
![BrowFilesMissingMarked](https://user-images.githubusercontent.com/81597534/183781826-befc6478-53d0-4efe-9d87-94befcec0bc8.png)

- BrowPlate.stl

- MagnetHolder.stl x4

- NanoHolder-A.stl

- NanoHolder-B.stl

- PCA9685Mount.stl

- PCA9685MountSupport.stl x4

- TPUBrow-L-V1.stl (MADE FOR TPU PRINTING)

- TPUBrow-R-V1.stl (MADE FOR TPU PRINTING)

MISSING FILES
= 
- BrowHolder-L.stl  (Need adjusting to fix servo buzz)

- BrowHolder-R.stl  (Need adjusting to fix servo buzz)

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

Brow Servos / Servo Horn Prep.
=

BrowHolders
=

Attaching the BrowPlate
=

Getting Wired
=

Raspberry Pi Zero W Prep
=

Magnet Holder Prep 
=

USE A SHARPY

EyeBrow Prep
=

USE A SHARPY

Setting the Brows Limits
=

BROWPLATE IS FINISHED!
=
Now onto the final step located in the 05-BrowPlate folder readme file.

https://github.com/CyberSyntek/Syntek-Edition-Head-Remix/tree/main/05-Skull

TO BE UPDATED
=
- Upload Missing parts once complete

- Image files
