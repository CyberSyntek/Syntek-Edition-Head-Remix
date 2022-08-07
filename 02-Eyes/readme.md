![Eyesexample](https://user-images.githubusercontent.com/81597534/183139319-f09b9724-7052-486b-930a-b22d75e43048.png)

ABOUT
=

The eye mechanism is a direct remix of Will Cogley's "Compact Animatronic Eye Mechanism" in which I have seperate both sides of the eyes to be independent mechanisms, modified to use independent eyelids, fit the eyeballs with cameras and reworked to allow for it to fit inside of the Syntek Edition InMoov skull. (Plus a few other changes.)

This mechanism could not have been done without the hard work of Will Cogley putting together his original eye mech. I would like to send out a huge thank you to Will for his hard work and for giving me permission to post the remixed files for others to use. Thanks Will!

NOTE: This eye mechanism is still compatible with Will's original eyes. You can head over to his site and download his eye files there if you are not planning on using cameras in your build. He also has various videos on his youtube channel relating to eye mechanisms and how to make realistic looking eyes as well as a resin cast kit for his original eyes with the files for those available on his website. 

Will Cogley's Website: http://www.nilheim.co.uk/

Here is a link to Will Cogley's "How to Make a Compact Animatronic Eye Mechanism with 3D Printing and Arduino" video. Give it a watch through as it may help as a reference for various things relating to this eye mechanism as well. https://youtu.be/ihXxbQefl1c

STL FILES
=

You will need the following files for both the Left and Right eyes. Example: L-Base.stl & R-Base.stl

- Base.stl

- BaseExtension.stl

- BottomEyelid.stl

- BottomEyelidConnector.stl

- EyeAdaptor.stl

- Eyeball-CamFitV1.stl (Requires Supports)

- EyeHolder.stl

- EyelidHolder.stl

- Eyelink.stl x2

- MainPivot.stl (Requires Supports)

- RasCamModuleHolder.stl

- ServoHolder.stl

- SmallPivot.stl (Requires Supports)

- TopEyelid.stl

- TopEyelidConnector.stl

ELECTRONICS (PER EYE)
=

x4 - MG90D Servo Motors (or similar in sized micro servos) - Total Needed = x8

NOTE: It is possible to put cameras in both eyes, but you really only need one.

x1 - 8MP Camera Module 77.6° Wide Angle Field View Camera for Raspberry Pi

x1 - Raspberry Pi Camera Module V2

x1 - 11.8" (30cm) Raspberry Pi Zero Camera Ribbon Flex Extension Cable 

NOTE: CAMERA RELATED ITEMS WILL CONTINUE IN THE BROWPLATE TUTORIAL!

SCREWS / BOLTS / ETC (PER EYE)
=

x8 Servo Screws - Total Needed = x16

x4 M2x6mm Screws - Total Needed = x8

x9 M2x7mm Screws - Total Needed = Upto x18

x8 M2x8mm Screws - Total Needed = x16

x3 M2x10mm Screws - Total Needed = x6

x10 M2x12mm Screws - Total Needed = x20

x3 M2x16mm Screws - Total Needed = x6

x3 M2x6mm Bolt - Total Needed = x6

x3 M2x7mm Bolt - Total Needed = x6

x1 M2x9mm Bolt - Total Needed = x2

x2 M2x28mm Bolt OR 25mm Threaded Rod - Total Needed = x4

x2 Du-Bro 2-56 Swivel Ball Link Connectors OR M2 sized Swivel Ball Link Connectors   - Total Needed = x4

#NOTE: I ordered a few batches of M2 connectors from various sellers, none of them were nearly as nice as the Du-Bro connectors. SMOOTH!



TUTOTIAL (Right Eye)
=

Note: Start with one side (L-Eye or R-Eye) until you reach the "Single Unit Base" section of this tutorial.


BaseConnectors to MainPlate
= 

Take x6 BaseConnector pieces and slot them into the MainPlate for whichever side eye you decide to start with. Screw them together from the bottom side using x6 M2x8mm screws. I will be using the right side eye in these examples. 

![001-BaseConnectorToMainPlate](https://user-images.githubusercontent.com/81597534/183090041-8436b93d-4ae6-4eb3-9403-0bdd41b33f2e.png)

Base to BaseConnectors
=

Place the Base on top of the BaseConnectors. Once the holes are lined up,screw them together with x6 M2-12mm screws.

![002-BaseToBaseConnector](https://user-images.githubusercontent.com/81597534/183090642-d331a9ee-f9ad-4673-be0a-a838b803b3c1.png)

Gluing the BaseConnectors
=

Apply a drop of superglue to where Base and BaseConnector are now joined at the bottom of the Base. This will prevent the baseconnectors from being able to rotate. Give the glue a few minutes to dry and come back. 

![Superglue1](https://user-images.githubusercontent.com/81597534/183108955-35bc3971-67f6-45ba-bdec-01f4cc284ff4.png)

#MORE GLUE!
=

Unscrew the x6 screws from the bottom of the Mainplate and remove the Base. Now you will be able to apply a bit more superglue with easier access to the bottom of the Base. After the glue dries you can either remove the x6 M2x12mm screws or leave them in, it doesn't really matter. (I leave them in for added strength.)

![Superglue2](https://user-images.githubusercontent.com/81597534/183110196-72fdbead-a54c-47d3-bd4d-9fda751a848e.png)

Single Unit Base
=

With the BaseConnectors superglued to the Base and locking them into place unable to rotate, we can now remove the Base as a single unit by simply removing the x6 screws on the bottom of the MainPlate and plug it back into the MainPlate BaseConnector slots when needing to do so. 

![003-GluedEyeBase](https://user-images.githubusercontent.com/81597534/183121338-0f12281c-2755-4570-abd0-49ab5833f36b.PNG)

#REPEAT THE ABOVE STEPS ON OPPOSITE EYE
=

Now you will need to repeat the steps above for the opposite side eye. Having these single unit pieces finished and out of the way will make things much easier as we keep progressing. We need to do them one at a time so we can apply the glue to the BaseConnectors more easily.

Eye Servo Setup
=

Now it is time to mount the L/R and U/D servos for the eye mechanisms. With your servos preset to 90° (centered) mount them as seen in the image below and screw them in using some servo screws. 

#Note: I used some standard size servo screws here to make sure they had a solid hold, but you should be able to use the servo screws that come with your servos.

The servo horns will be mounted facing towards the outsides of the mechanisms.

![005-EyeServos](https://user-images.githubusercontent.com/81597534/183121062-442a7469-d898-46f5-a4a3-00241b637558.png)

ServoHolder to Base & Eyelid Servo Setup
=

Slide your servo wires through the top holes on the ServoHolder. Screw the servos onto the ServoHolder using x2 Servo Screws then mount the ServoHolder onto the Base and screw it on using x3 M2x12mm screws. Now we will add the otherside x2 servo screws to secure the servos in place.

These servos will also be centered / set to 90° when mounted.

Finally we will add the servo horns onto the servos in the positions seen below. 

![06-ServoHolderServosToBase](https://user-images.githubusercontent.com/81597534/183127965-26979c00-c43d-49b3-8d6c-b6b64a11ca74.png)

EyelidHolder to Base
=

Now we will screw on the Eyelid holder to the side of the Base using x3 M2x7mm screws.

![07-EyelidHolder](https://user-images.githubusercontent.com/81597534/183221236-3030e186-a5c8-4b31-9f12-5e6a544f0d23.png)


BaseExtension to EyeHolder
=

Align and screw together the BaseExtension and the EyeHolder using a M2x12mm screw. Once you are sure it is lined up well, you may want to apply a drop of superglue to prevent it shifting as the servos move which could offset the eyes movement. 
![08-BaseExtension](https://user-images.githubusercontent.com/81597534/183222149-6ce3b23a-8830-4431-b611-c281fa502409.png)

Eye Connectors
=

Here we will want to use ideally x2 25mm threaded rods to screw into the the x2 EyeLinks and then adding a drop of superglue to secure them in place.

You will then screw on a 2-56 or M2 swivel ball link connector onto each of the rods.

I strongly recommend doing both eye's rods at the time as it will be easier to make sure both eye's rods are identical in length when adjusting the swivel ball link connectors.

#NOTE: I used M2x28mm bolts and cut the heads off the bolt which came out close to 25mm. 

![010-2-RodToEyeLink](https://user-images.githubusercontent.com/81597534/183297918-f764be4d-f21f-422d-a8c9-75206cdcf06e.png)

EyeLink to SmallPivot (THE DANGER ZONE I)
=

![SmallPivotRod000](https://user-images.githubusercontent.com/81597534/183301741-9ee249e6-4cd5-4165-a407-349697957f9b.png)

EyeLink to MainPivot (THE DANGER ZONE II)
=

![012-RodToMainPivot](https://user-images.githubusercontent.com/81597534/183299201-c1b35248-d16e-4148-b0cf-9699665dd04d.png)

EyeHolder to MainPivot (THE DANGER ZONE III)
=

![013-BaseExtensionToMainPivot](https://user-images.githubusercontent.com/81597534/183300020-828e3093-7186-4cd3-aac7-6657da01621b.png)

Rods to EyeAdaptor
=

![014-RodsToEyeAdaptor](https://user-images.githubusercontent.com/81597534/183300660-8cbddaab-ef8f-4144-97dc-f9fed1ff3514.png)

Eyeball to EyeAdaptor
=

![EyeballToEyeAdaptor](https://user-images.githubusercontent.com/81597534/183301399-32c9074c-156f-4dce-85a9-b1a4cae114c1.png)


Screw Check
=

![ScrewCheck](https://user-images.githubusercontent.com/81597534/183303628-55d80f54-686a-44ef-ad16-17b7ba46db5a.png)

BaseExtension to Base
=

![BaseExtensionToBase1](https://user-images.githubusercontent.com/81597534/183302776-f038e904-64d8-4351-8dc1-1eb96136cd5f.png)

Eyeball - Servo Horns
=

![EyeballServoHornHoles](https://user-images.githubusercontent.com/81597534/183304562-d8f53789-7792-4c62-a779-5d00c9bdf2e6.png)

Eyeball - Servo Check
=

Connect your servos and test your eyes using limited range Min/Max settings to make sure you do not have any strange movement occuring or offsets.

You can do this various ways such as using a servo tester or by running them in MRL. I have given examples of my servo limits in the MRL-Files section.

Trust me, it is better to do now than later, I know from experience. :)

Eyelids 
=

![Eyelids](https://user-images.githubusercontent.com/81597534/183305973-de99c9ac-338b-4fd4-af4d-7725bcfab284.png)

BaseBeams to Base
=

Screw the x3 BaseBeams to the base using x3 M2x16mm Screws. You CAN superglue these also, but it isn't absolutely necessary. 

![BaseBeams](https://user-images.githubusercontent.com/81597534/183306633-080aba24-2f60-4fd7-a9d0-6ded5732e833.png)

Base returns to MainPlate
=

Our eyes are finally ready to come back home to the MainPlate. Screw them in again from the bottom of the MainPlate using the x6 M2x8mm Screws (per eye).

Once the eyes are back on, flip the MainPlate over and screw on the CamCableClips for whichever side you are using a camera. 

#Note: If using two cameras, obviously put CamCableClips on both sides. :)

![CompleteEyes](https://user-images.githubusercontent.com/81597534/183307556-747e62b2-ebc0-4644-8d19-850c4bac3976.png)

Note# Using some M2x7mm Screws, You may attach the Raspberry Pi Camera V2 Module to the RasCamModuleHolder now or later on when we attach the Raspberry Pi Zero W.
To ensure the camera cables stay in the best condition until we attach them, I would suggest later. 

NOW YOUR EYE MECHANISM IS FINISHED!
=

It is time begin setting up the Jaw. 


*TO BE UPDATED*
=

- Alternative Camera fit eyes (I will be adding another camera fit eye file option in the near future) 
