![Eyesexample](https://user-images.githubusercontent.com/81597534/183139319-f09b9724-7052-486b-930a-b22d75e43048.png)

ABOUT
=

The eye mechanism is a direct remix of Will Cogley's "Compact Animatronic Eye Mechanism" in which I have seperate both sides of the eyes to be independent mechanisms, modified to use independent eyelids, fit the eyeballs with cameras and reworked to allow for it to fit inside of the Syntek Edition InMoov skull. (Plus a few other changes.)

This mechanism could not have been done without the hard work of Will Cogley putting together his original eye mech. I would like to send out a huge thank you to Will for his hard work and for giving me permission to post the remixed files for others to use. Thanks Will!

NOTE: This eye mechanism is still compatible with Will's original eyes. You can head over to his site and download his eye files there if you are not planning on using cameras in your build. He also has various videos on his youtube channel relating to eye mechanisms and how to make realistic looking eyes as well as a resin cast kit for his original eyes with the files for those available on his website. 

Will Cogley's Website: http://www.nilheim.co.uk/

Here is a link to Will Cogley's "How to Make a Compact Animatronic Eye Mechanism with 3D Printing and Arduino" video. Give it a watch through as it may help as a reference for various things relating to this eye mechanism as well. https://youtu.be/ihXxbQefl1c

EYE STL FILES
=
You will need the following files for both the Left and Right eyes. Example: L-Base.stl & R-Base.stl

![EyepartsDisplay](https://user-images.githubusercontent.com/81597534/183741857-ce01d005-8207-4b04-9cdb-a2d95ebeae02.png)

- Base.stl

- BaseBeam.stl x3

- BaseExtension.stl

- BottomEyelid.stl

- BottomEyelidConnector.stl

- EyeAdaptor.stl

- Eyeball-CamFitV1.stl (Requires Supports)

- EyeHolder.stl

- EyelidHolder.stl

- EyeLink.stl x2

- MainPivot.stl (Supports can help)

- RasCamModuleHolder.stl

- ServoHolder.stl

- SmallPivot.stl (Supports can help)

- TopEyelid.stl

- TopEyelidConnector.stl

ELECTRONICS (PER EYE)
=

For more detailed information on electronics & hardware needed, please refer to the BOM folder readme file.

x4 - MG90D Servo Motors (or similar in sized micro servos) - Total Needed = x8

NOTE: It is possible to put cameras in both eyes, but you really only need one.

x1 - 8MP Camera Module 77.6° Wide Angle Field View Camera for Raspberry Pi

x1 - Raspberry Pi Camera Module V2

x1 - 11.8" (30cm) Raspberry Pi Zero Camera Ribbon Flex Extension Cable

SCREWS / BOLTS / ETC (PER EYE)
=

x8 Servo Screws - Total Needed = x16

x4 M2x6mm Screws - Total Needed = x8

x9 M2x7mm Screws - Total Needed = x14 (x18 If double camera)

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

THE DANGER ZONE!!!
=
The following three steps are nicknamed THE DANGER ZONE I, II & III. 

While they are not actually dangerous, it is easy to mess them up doing this the wrong way.  

We will be needing to apply a tiny bit of superglue to the ends of the bolts just to give them a little bit of extra hold due to it is possible for the bolts to come loose over time with the servos constantly moving around and rotating around them. This can be very tricky if not being careful and will likely result in needing to reprint a few pieces. Luckily they are small pieces, but it is nice to avoid needing to do that.  

WARNING: You do NOT want to apply a drop of superglue directly on them from above as the glue will sink in from around the screw and fuse the pieces that we need to rotate together!

The best method I have found to do this is to squeeze a drop of superglue out into the lid of the storage bottle, run the tip of the bottle (Or anything small and thin really) against that single drop and gently rub a very small amount around on the needed area located at the end of the bolts WITHOUT squeezing anymore superglue out. Rub, no squeeze!

Always do this with the end of the bolt facing downwards as gravity is your friend. Even as it is drying you will want to rotate the pieces a little bit just to make sure that no glue has worked its way through and it can still move freely.

EyeLink to SmallPivot (THE DANGER ZONE I)
=
Take an M2x6mm bolt and run it through the EyeLink into the Small pivot. You will want to tighten it enough that is can still rotate freely, but you want to avoid it having any play between the pieces that could cause potential offset in the eye movements. This is more easily achieved if using a flat bottom head bolt, but should be possible with most shaped M2 screws if careful.  

Once you are sure that there is little to no play and that the screw is tight enough, but can still move friction freely.... it is time to enter "THE DANGER ZONE". You will want apply a tiny bit of superglue to the end of the bolt showing through the top of the SmallPivot. 

![SmallPivotRod000](https://user-images.githubusercontent.com/81597534/183301741-9ee249e6-4cd5-4165-a407-349697957f9b.png)

EyeLink to MainPivot (THE DANGER ZONE II)
=
Screw the EyeLink to the MainPivot from the top using an M2x6mm screw. Flip it over and carefully enter "THE DANGER ZONE" again.

![012-RodToMainPivot](https://user-images.githubusercontent.com/81597534/183299201-c1b35248-d16e-4148-b0cf-9699665dd04d.png)

EyeHolder to MainPivot (THE DANGER ZONE III)
=
Attach the EyeHolder to the middle of the MainPivot screwing in a M2x6mm bolt from the bottom. This one is the most dangerous, but you are almost there. Flip it over and defeat "THE DANGER ZONE" with a tiny bit of super glue. 

![013-BaseExtensionToMainPivot](https://user-images.githubusercontent.com/81597534/183300020-828e3093-7186-4cd3-aac7-6657da01621b.png)

You Survived THE DANGER ZONE
=
You did it! That was the most difficult part of this project! Good job friend! :)

Pivots to EyeAdaptor
=
Slot the Small Pivot and MainPivot into the EyeAdaptor gently. 

![014-RodsToEyeAdaptor](https://user-images.githubusercontent.com/81597534/183300660-8cbddaab-ef8f-4144-97dc-f9fed1ff3514.png)

Eyeball to EyeAdaptor
=
While this step is not overly difficult it can be a little tricky so take your time. 

You will want to place your camera into the slot in the Eyeball and snake the camera cable through the open slot on the EyeAdaptor. As the Eyeball camera slot is not overly tight it is easy for the camera to come loose when trying to push the Eyeball onto the EyeAdaptor. Don't panic!

It is easiest to push the EyeBall onto the EyeAdaptor a little bit and slowly push it down. Even if the camera comes loose from its slot, you will be able to adjust it back into the slot by moving the cable around. The further you push the EyeAdaptor in the easier this becomes. The main thing to be careful of is that you are not pushing it in so far that you are crushing the camera if it isn't aligned or that it has become so tight that you cannot align it back into its slot by moving the camera's cable around easily as the cable is fragile. The EyeAdaptor will hold it in place once it is fully on, so just take it slow and try and align it closer to when the EyeAdaptor is getting closer to being fully inside the Eyeball. 

![EyeballToEyeAdaptor](https://user-images.githubusercontent.com/81597534/183301399-32c9074c-156f-4dce-85a9-b1a4cae114c1.png)

Screw Check
=
Make sure to check the bottom of the Base and see if any of the tips of the Servo Screws are sticking out. This will depend on which servo screws you use, but if any tips are sticking out then cut them off. Having the screws stick out here can damage your camera cable or less likely... your servo cables if you are unlucky. It is best to cut them flush with the bottom of the Base.

![ScrewCheck](https://user-images.githubusercontent.com/81597534/183303628-55d80f54-686a-44ef-ad16-17b7ba46db5a.png)

BaseExtension to Base
=
Align the BaseExtension on its slot on the Base and hold it in place with your finger. From the bottom of the Base you will want to line up the RasCamModuleHolder with the holes and run x3 M2x10mm screw threw both the RasCamModuleHolder and Base into the BaseExtension.

![BaseExtensionToBase1](https://user-images.githubusercontent.com/81597534/183302776-f038e904-64d8-4351-8dc1-1eb96136cd5f.png)

Eyeball - Servo Horns
=
Following the image below, you will want to attach swivel ball link connectors to the servo horns using x2 M2x8mm screw. The L/R eye servo horn hole you will be attaching the swivel ball link connector to is the 2nd from the center of the servo horn. The U/D servo horn hole will be the 4th from the center.

It is possible to do this stage before entering "THE DANGER ZONE" so that you can attach one or two of the swivel ball link connectors to make sure that the eye is facing forward directly without having any offsets and needing to unscrew the swivel ball link connector a bit until it lines up. They will all need to be the same length so it is possible to just connect one, remove it and adjust the rest of the rod lengths to match the one you know lines up well. 

Alternatively, even if you have completed "THE DANGER ZONE" you can screw it on, check for offsets, and unscrew the swivel ball link connector a bit with the rod still attached to the pivots with some care. Either way should be fine and will be your choice. 

![EyeballServoHornHoles](https://user-images.githubusercontent.com/81597534/183304562-d8f53789-7792-4c62-a779-5d00c9bdf2e6.png)

Eyeball - Servo Check
=
Connect your servos and test your eyes using limited range Min/Max settings to make sure you do not have any strange movement occuring or offsets.

You can do this various ways such as using a servo tester or by running them in MRL. I have given examples of my servo limits in the MRL-Files section. Trust me, it is better to do now than later, I know from experience. :)

Eyelids 
=
Now that you have confirmed your eye works without issue and there is no offsets, it is time to move onto the Eyelids.

Before we install the eyelids onto the mechanism, I would recommend that you check your eyelids can close to a flush position. This will very much depend on your print settings and if little obstructions in the print will prevent them from closing all the way or not. This may not be needed, but it is easiest to check now. 

Screw in some bolts into both sides of the eyelids so they are held together. Try closing them and check for any spaces between them. If they will not close all the way, hold them up against a light and check to see where they are being onbstructed from. Very often any obstruction in the printing will be close to the corners on both sides of the eyelids on both the Top and Bottom eyelids. Having good light here will be the key to see where the issue is. 

You can use a small file or sand paper to very lightly rub those areas with the bolts still in the eyelids and check them again. You will not need to do much sanding/filing here so go slowly until you are happy enough with the results assuming you even have any obstructions. :)

Now you are ready to get them onto the mechanism!

![Eyelid-prep](https://user-images.githubusercontent.com/81597534/183733727-e3fc8b31-5e05-4eae-80dd-d168ccf5a027.png)

You will want slightly screw in a M2x7mm bolt from the Base side, just enough so that it can grip the LowerEyelid. Next, slightly screw in a M2x9mm bolt from the EyelidHolder side so that it also grips the LowerEyelid. Now hold the TopEyelid in place and slowly tighten each sides bolts a little bit to that the eyelids are able to hang in place. Now that you have your hands free you can go ahead and carefully tighten the M2x7 bolt all the way (If you used a bottom side flatheaded bolt). Remeber that this is a pretty thin part so be sure not to over tighten or you may risk cracking it. 

The EyelidHolder side you will not have to tighten all the way if using an Mx9mm bolt. A M2x8mm bolt may also work, although I wanted to avoid the risk of the Eyelids coming loose from the screw for less troubleshooting. Just make sure it is screwed in enough to hold the eyelids, but not rub against the eye with the eye turning L/R. 

You can now take the TopEyeLidConnector (shorter) and attach it to the TopEyelid using an M2x7mm bolt. Next the BottomEyelidConnector (longer) will be attached to the BottomEyelid using another M2x7mm bolt.

Now you can attach the corresponding EyelidConnectors to the top and bottom servo horns using M2x7mm screws into the 6th hole from the center holes of the servo horns as seen in the image below.

You may want to test the Eyelid servos at this point just to make sure the Eyelid Connectors are holding to the Eyelids, nothing is too tight or too loose and that everything is moving okay as it will a more tricky to adjust things once we have everything attached.

![Eyelids](https://user-images.githubusercontent.com/81597534/183305973-de99c9ac-338b-4fd4-af4d-7725bcfab284.png)

BaseBeams to Base
=
Screw the x3 BaseBeams to the base using x3 M2x16mm Screws. You CAN superglue these also, but it isn't absolutely necessary. 

![BaseBeams](https://user-images.githubusercontent.com/81597534/183306633-080aba24-2f60-4fd7-a9d0-6ded5732e833.png)

Base returns to MainPlate
=
Our eyes are finally ready to come back home to the MainPlate. Screw them in again from the bottom of the MainPlate using the x6 M2x8mm Screws (per eye).

You will want to make sure to run both the U/D and the L/R servo cables inbetween the BaseConnectors located under the ServoHolder containing the Eyelid Servos as shown in the image below so that they run off to the side.

![EyeCables](https://user-images.githubusercontent.com/81597534/183519468-60ac2825-6e58-492e-b5e5-fcbcd7a348a5.png)

Once the eyes are back on, flip the MainPlate over and screw on the CamCableClips for whichever side you are using a camera. 

#Note: If using two cameras, obviously put CamCableClips on both sides. :)

![CompleteEyes](https://user-images.githubusercontent.com/81597534/183307556-747e62b2-ebc0-4644-8d19-850c4bac3976.png)

Note# Using some M2x7mm Screws, You may attach the Raspberry Pi Camera V2 Module to the RasCamModuleHolder now or later on when we attach the Raspberry Pi Zero W in the "04-BrowPlate" folder tutorial. 

To ensure the camera cables stay in the best condition until we attach them, I would suggest waiting unless you have everything ready to mount it to a headstand or your robot. 

You will need to attach the Raspi Zero W camera cable to the Module prior to mounting it to the RasCamModuleHolder and then sneak the cable through the CableClips as seen in the image below. The cable will come up and through the slot under the Eyelid servos. Once the cable is clear you can clip on the 8MP camera's cable onto the V2 Cam module.

![CameraCable](https://user-images.githubusercontent.com/81597534/183520058-456ac23a-7021-4bc8-a57a-a52243bfaefd.png)

NOW YOUR EYE MECHANISM IS FINISHED!
=
It is time to begin setting up the Jaw. This tutorial will be continued in the "03-Jaw" folder section page. 


*TO BE UPDATED*
=
- Alternative Camera fit eyes (I will be adding another camera fit eye file option in the near future) 
