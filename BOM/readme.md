#Note - Links included are just for reference. If you can them find locally, cheaper or similar parts more easily, then please do so.

SERVOS REQUIRED
=
We will need a total of 15 micro servo motors for this head as well as a more standard sized 20kg servo. There are many options out there for roughly same sized micro servos, but please double check sizes of other brand servos to make sure they will fit correctly or not as some spaces do require roughly this size.

I am currently using x15 MG90D servos in my head, but I have some MG92B servos ordered and on the way. They have slightly higher torque and I'm going to experiment with using them in a few locations.

The MG90D servos are doing the job just fine, though I am noticing the jaw beginning to open without power to the servos a little bit. While this isn't an issue and can likely be fixed with an elastic band, I am hoping the MG92B's torque will prevent that from happening at all. I will update with confirmation once I have tested them in those spots.

- x1 - DS3218 20KG Servo (270° ver) - https://a.co/d/8i4HSLo

- x15 - Micro Servo Motors.

===================================================

These are where I got the MG90D and MG92B servo motors I am using.

- MG90D Servo Motors - https://www.adafruit.com/product/1143

- MG92B Servo Motors   https://www.adafruit.com/product/2307 

Recommended Micro Servos!
= 
- Brows - x4 - MG92B (Seem to run very smooth. MG90Ds had slight buzz from time to time.) 

- Jaw - x1 - MG92B (MG90D will sag a bit without power to the servo and struggles with small amount of degree movements. AKA not enough torque)

- Lat Jaw - x2 - MG92B or MG90D (Either should be fine. I tried both, no huge difference. MG90D MAYBE a bit smoother)

- Eyes - x8 - MG90D (Nice and speedy, not much need for the extra torque, good times.)

- RotNeck - x1 - DS3218 20KG Servo (270° ver) 

TOTAL SCREWS (Self-Tapping)
=
- x6 - M2x5mm Screws

- x8 - M2x6mm Screws

- x20 - M2x7mm Screws

- x28 - M2x8mm Screws

- x6 - M2x10mm Screws

- x24 - M2x12mm Screws

- x16 - M2x16mm Screws

TOTAL BOLTS / NUTS
=
- x6 - M2x6mm Bolts

- x6 - M2x7mm Bolts

- x4 - M2x8mm Bolts

- x2 - M2x9mm Bolts

- x2 - M2x16mm Bolts

- x2 - M2x20mm Bolts

- x4 - M2x28mm Bolt OR 25mm Threaded Rod 

- x6 - M2 Nuts

- x8 - M3x12 Bolts

- x4 - M3x16mm Bolts

- x2 - M4x16mm bolts. Note: I generally use slightly larger selftap screws on this for a stronger steady hold.

- x2 - Zipties

TOTAL SERVO SCREWS
= 
- x38 - Servo Screws

OTHER HARDWARE
=
- x4 - Du-Bro (2135) 2-56 x 1/2 Swivel Ball Link - https://a.co/d/0GZyHuL

  You can also use M2 Swivel Ball Links

- x2 - Du-Bro (181) 2-56 Threaded Ball Link - https://a.co/d/0wf1e1V

  You can also use M2 Threaded Ball Link.

- x4 - Du-Bro E-Z Connectors With Re-Usable Nylon Snap Ons - https://a.co/d/9076KMQ

- x1 - Y Servo Splitter Cable (Male to x2 Female) -  https://a.co/d/4Yzls2i

  You can make your own with some servo extension cables if unable to locate these. 

- x4 - Dupont Cables. (Arduino Nano to PCA9685) Perhaps a few more if MPU6050 is set up also.

- Krazy Glue/Super Glue (Please find locally for cheaper, but just incase) - https://a.co/d/6VbvxNa

- x2 - Zipties - You may find you want to use more to clean up the servo cables towards the end.

ELECTRONICS
=
- x1 - Arduino Nano (Brand or Generic)- https://a.co/d/9V0zZ5S  (I'm using generic without issue.)

- x1 - Mini B USB Cable (3FT) for the Arduino Nano - https://a.co/d/219j3qb

  If using either Jon Bailey's headstand set up (https://www.thingiverse.com/thing:4670770) or have the head attached to the body of your Inmoov (...I         think), 3FT should give you plenty of room to work with. The Mini B USB cable provided with the Arduino Nano will be too short. 

- x1 - PCA9685 (16-Channel 12-bit PWM/Servo Driver) - https://a.co/d/cDNK8FY / https://www.adafruit.com/product/815

  These are available from various sellers, though the adafruit versions seem to be reliable. I'm not sure if the adafruit versions come included with         components and or presoldered or not. I sourced my PCA9685 locally. Be sure to read comments from customers on cheaper model pages as some sellers have       used very cheap components on their versions and could fail or burn. I'm sure there are some great cheaper ones there, but always test them before     installing them into your robot.  
  
- A power supply. This may vary depending on how you are setting your head up. I gave some suggestions in the "Beginners guide to moving servos with a PCA9685 and MYROBOTLAB" youtube video on the main page.

- Cables from power supply to terminal block on the PCA9685 to power the servo motors.   
  
- x1 - MPU6050 - https://a.co/d/gO6KlX1 (There is a slot for one in the head, though I haven't experimented with it yet or included it in the service I have set up in the "MRL-Files" folder yet. (To be updated hopefully!)

PUPIL CAMERA RELATED ITEMS
=
![PupilCam](https://user-images.githubusercontent.com/81597534/182968849-65f36cae-66c5-4d69-b311-3d425277dec8.png)

Coming from the original Inmoov USB webcam pupil camera setup, I had decided I would stick with that route for my current pupil camera setup also by converting a Raspberry Pi Zero W into a webcam and using it in the same fashion. This isn't the most cost effective route for doing these things, but the size of the camera modules I found worked for the job. I am sure there are other options out there and I do plan on formatting the eyeball camera inserts for at least one other type of raspberry pi spy camera and will update those files here with a potential set up description when I have completed them. 

The following items are required for my current setup. 

- x1 - Raspberry Pi Zero W - https://a.co/d/f5wQHNF

  Raspberry Pi Zero, Zero W and Zero 2 W? should all work. There seems to be a shortage of them available during the time of writing this, but using what       ever you can locate should do the job.

- x1 - SD Card

- x1 - Micro USB cable (3ft) if not included with Raspberry Pi Zero W. 

- x1 - 8MP Camera Module for Raspberry Pi 77.6° Wide Angle Field View Camera Module for Raspberry Pi - https://a.co/d/1mauetZ 

  The link description says 5MP for some reason, but the cam cable has 8MP written on it as well as the comments confirming 8MP. These are available from       various sellers. 

- x1 - Raspberry Pi Camera Module V2 - https://a.co/d/2dx2Vhr

  Make sure you are using the V2. Unfortunetly it is very difficult to find just these boards without a camera included as we will NOT be using the included   camera due to needing a longer cable to be able to reach into the eyeball with enough cable slack to still function.

- x1 - 11.8" (30cm) Raspberry Pi Zero Camera Ribbon Flex Extension Cable - https://a.co/d/2RXyKAD

  We need a Raspberry Pi camera module > Raspberry Pi Zero camera cable.
  
===========================================================================

I recommend the following youtube video as a walkthrough for getting your Raspberry Pi Zero W's SD card formatted to function as a webcam. Her instructions are clear and the whole process takes about 2 minutes. 

"How to build a Raspberry Pi webcam | Easy beginner project!" - https://youtu.be/zmP1ZuV4kB8

The link she included in the video description is not the same as what she uses in the video. Here is the correct link to save you any headaches. https://github.com/showmewebcam/showmewebcam/tags

===========================================================================

NOTE: As this project progresses there will be other options available for how to set up other cameras and different connection methods available also. 

TOTAL NEODYMIUM MAGNETS
=
- x22 - Neodymium Magnets (10x3mm) - https://a.co/d/eTazw7q

- x4 - Neodymium Magnets (6x3mm) - https://a.co/d/bWqNBsL

I used the "NAZZO" brand of neodymium magnets found in the provided links as they are very strong and work well for our needs. I ordered two of the mixed sized packs as I was experimenting and wanted some size options to playu with. This is the link for the mixed pack I used. https://a.co/d/1fMVASk

Other options of that brand would be to get a pack of each of the sizes used if you are unable to source the needed neodymium magnet sizes needed locally.

- Neodymium Magnets (10x3mm) - https://a.co/d/eTazw7q

- Neodymium Magnets (6x3mm) - https://a.co/d/bWqNBsL

I will explore other potential sellers at some point and or list other potential options that others have located here in the future. 
