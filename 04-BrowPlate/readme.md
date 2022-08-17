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

- x5 -Micro Servos

  Note: I currently am using x5 MG90D servo motors for these parts. I believe the MG92B may work better having a bit more torque, but I don't have them     just yet. I will update when I get a chance to try them after they arrive.  

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

Arduino Nano to PCA9685
=
Now to connect the Arduino Nano to the PCA9685 using 4 dupont cables.

![0010-NanoWires](https://user-images.githubusercontent.com/81597534/184553676-4955ed6c-6fbd-4854-8fdc-24a092c353a4.png)

Progress Check
=
At this stage the head should be looking like a bad hair day. If yours resembles this then we are good to move on. 

![ProgressCheck](https://user-images.githubusercontent.com/81597534/184553942-e2bfb78f-d6cf-4e3d-85b5-3a623d894cf7.png)

Servo Cables to PCA9685
=
Now want to begin connecting the servo wires to the PCA9685. If you are planning on using my setup so that you are able to use any of the files I write up for the head to use with myrobotlab (nixie) then you will want to plug them in according to the pin layout shown below.

![PCA9685Layout](https://user-images.githubusercontent.com/81597534/184562621-ab86552a-33be-4cf7-be9b-b51eb6afa6e3.png)

On the PCA9685Mount file you will see the open area on the left side highlighted in the red circle. We will want to slide the following servo cables through that area. You should be able to fit them all in withough too much trouble. The last one or two can get a bit tight so give other cables slack as needed to help them be able to slide up. 

![0011-CableSlot](https://user-images.githubusercontent.com/81597534/184563797-5bbc0ca7-e16a-4979-8d02-f39d99ef52ef.png)

- LateralJaw - (Left side cable) This will be joined by the right side cable with the Y cable once through the slot.

- Jaw

- RightInnerBrow

- RightOuterBrow

- LeftInnerBrow

- LeftOuterBrow

- LeftLowerLid

- LeftUpperLid

- LeftEyeUD

- LeftEyeLR

With all your servo cables now plugged in you should only have Pin 0 and Pin 9 open on the PCA9685. On the right side your servo cables will still be loosely hanging off to the side as seen above. 

Raspberry Pi Zero W Prep
=
Now we will connect the eye's pupil camera cable to the Raspberry Pi Zero W.

![RaspiConnected](https://user-images.githubusercontent.com/81597534/184564069-f5715761-39df-4b91-944c-722522c9390a.PNG)

We will want to take care of those loose wires now and try and push them into the opening seen below. Grab your Raspberry Pi Zero W and screw it in using x2 M2x7mm Screws which will hold the wires in place. If you have your camera placed in the left eye or are not using a camera at all, you can use zipties between the PCA9685MountSupports to hold the cables in place.

![0012-RaspiZeroW](https://user-images.githubusercontent.com/81597534/184564542-f81e98c0-17fe-49cf-86c6-0a621a8805c8.png)

You may wish to unplug a few of the right side servo wires one at a time (Unless you labeled your cables) and wrap them around the other plugged in wires to reduce wire slack as some of them can get close to the eyebrow servo EZ connectors and could potentially get snagged. Obviously plug back in anything you unplug following doing so. :)

Getting Wired
=
Now we can plug in cables we had routed through the neck earlier. At the time of writting this, I am so far only needing to connect GND/V+, Mini B USB and a Micro USB.

![0013-GettingConnected](https://user-images.githubusercontent.com/81597534/184565675-d454f505-97da-4ae0-8784-7154c5dc77b7.png)

Now plug everything in and confirm that everything works.

![0015-Plugin](https://user-images.githubusercontent.com/81597534/184566719-07e2a650-4a99-464a-905e-b0cce44cbeb6.png)

WORD OF WARNING
=
https://user-images.githubusercontent.com/81597534/184579363-48b3a739-7e1d-4e5d-9d5e-3c093b12aab9.mp4

Magnet Holder Prep 
=
To prepare the magnet holders you will need to get cut a few strands of PETG or ABS filament. The length doesn't really matter at this stage beyond being too short so give yourself a few inches to work with. You will want to slide the filament pieces into the MagnetHolders so that the filament curves away from the MagnetHolder pieces as seen in the image below. You will then want to apply a single drop of super glue into the Magnet holders and push the magnet in so that it is all the way in and flat. (Check to make sure your magnets fit okay prior to applying glue) There is a likely chance that some of the glue has worked its way through the bottom of the MagnetHolder into the shaft where the filament is inserted while pushing down on the magnet, but just make sure they don't easily fall out otherwise you may need to apply a tiny drop of super glue at the top of the MagnetHolder to keep the filament in place. 

![0016-Magholders](https://user-images.githubusercontent.com/81597534/184574458-85283aee-433c-47ec-a190-c8070611c29f.png)

Alternatively you don't need to use filament on these as there are other options out there, this just seemed like a cheap way to use something we already have. You can also use something like GoldenRod/GoldenWire for RC airplanes here that comes in various stiffnesses and widths or perhaps some kind of instrument wires. (I haven't tried yet) Whatever is used needs to be stiff enough that it will still be able to push, but flexible enough to bend through the MagnetHolders. 

Here is an example of the length which you will likely want to aim for that will allow you a little bit of room still to play with adjustments.

![MagHoldLength](https://user-images.githubusercontent.com/81597534/184576473-14e1e2ee-97f9-44f3-acba-893fb260664f.PNG)

Setting the Brows Limits
=
Before we connect the MagnetHolders we prepared we will need to set our Eyebrow servo limits. If you are using my MRL-Files config you will see that I have them currently set between a Min:40 (Brows Down) / Max:140 (Brows Up) range. We will want to move the servos into their Max/Up position.

![Browset01](https://user-images.githubusercontent.com/81597534/184577789-8b034e6a-159f-42a0-a37c-9527741d566d.png)

Loosen the screws at the top of the EZ connectors so that you are able to slide the filament into them. Push the filament all the way through until the top of the MagnetHolder is pressed against the MagnetHolder. You will want to adjust the filament so they magnets are facing mostly forwards but with a slight angle towards the direction needed. Left brows > Slight left angle. 

Double check them to make sure they are all leveled the same and then finally tighten the EZ connector screws so that they are locked into position.

![0017-BrowSet](https://user-images.githubusercontent.com/81597534/184578457-52147721-909d-430f-bfa8-4bd61918ab90.png)

EyeBrow Prep
=
Take x4 6x3mm neodymium magnets and place them on the MagnetHolder magnets. At this time it is a good idea to mark them with a marker so that we know the polarity of the magnets. One at a time, remove the magnets and with the marked side of the magnet facing towards the prints, glue the magnets into the TPUeyebrows using a single drop of super glue and repeat this step for all four magnets. 

![Mag0001](https://user-images.githubusercontent.com/81597534/185183871-24f7a9e4-8683-4bce-a983-ea65c4c4581c.png)

![BADTPUMagnet](https://user-images.githubusercontent.com/81597534/184579129-51f12e56-7051-4b91-a8b4-494420bf019a.PNG)

We will put these aside for the moment until we have completed the next steps.

BROWPLATE IS FINISHED!
=
Now onto the final step located in the 05-BrowPlate folder readme file.

https://github.com/CyberSyntek/Syntek-Edition-Head-Remix/tree/main/05-Skull
