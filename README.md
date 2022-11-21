Welcome to the Syntek Edition Head Remix!
=
![TempMainSnip](https://user-images.githubusercontent.com/81597534/185224203-c23ec7ba-048f-4d5d-99dd-087661b16766.PNG)


TEMP WARNING.
=
While all the files are here and the head is available for you to make now, it is still in the early phase of me experimenting with it so do be warned that minor changes and updates may occur over the following few weeks as I futher play with it and look for improvements. So far everything works for the most part, but slight alterations may still need to happen for performance improvement. I will remove this "TEMP WARNING" section once I have explored a bit more.

I have added an UPDATES/NOTES section at the bottom of this page to help keep you upto date with changes, updates, improvements, added things, etc 

ABOUT
=
On this page you will find all of the Syntek edition remixed head stl files, components needed, step by step put together tutorials and information relating to getting it running in myrobotlab (MRL). Future updates and files shall be available here as well. :)

As I am still early into the experimenting phase of this head also, I expect that there will be a number of updates to improve this page, files and write ups in the weeks to come. Stay tuned!

WHAT IS SYNTEK?
=
An introduction to Syntek (My InMoov Robot)

https://user-images.githubusercontent.com/81597534/182945941-7be97dca-e8e5-45d9-b666-c8eca6ea6b64.mp4

CURIOUS ABOUT INMOOV?
= 
If you were unfamiliar with InMoov robot and or are now more curious about it, you should head over to the InMoov website and find out more about the project  by clicking the image below as THIS project page is directly related to the InMoov project. 

<a href="https://www.inmoov.fr" />
<img src="https://user-images.githubusercontent.com/81597534/182956653-22bd5be5-dd2f-44b9-a1f5-d61002d9dd43.PNG" />

WHAT IS THE SYNTEK EDITION REMIXED HEAD?
= 
It is a mostly magnetically held remixed edition of Gael Langevin (InMoov Founder)'s InMoov robot head that has been fit with independent eyes, eyelids, eyebrows and an additional axis in the jaw. This head is controlled via a PCA9685 micro controller, an Arduino Nano and MYROBOTLAB and can be built to function independently or as part of your InMoov robot. 

FIRST TIME USING A PCA9865 AND MYROBOTLAB?
=
No problem! Here is my "Beginners guide to moving servos with a PCA9685 and MYROBOTLAB" video to help you get started.

[![Beginners guide to moving servos with a PCA9685 and MYROBOTLAB](https://user-images.githubusercontent.com/81597534/182962139-453537c9-c836-4992-8144-bc1f8d35aa70.jpg)](https://youtu.be/unIUJA24uBI  "Beginners guide to moving servos with a PCA9685 and MYROBOTLAB")

And while we are at it, here is a bonus link to the MYROBOTLAB (MRL) homepage: http://myrobotlab.org/

-BOM- 
=
For a full detailed list of the electronics, hardware and everything needed, please refer to BOM readme file. 

https://github.com/CyberSyntek/Syntek-Edition-Head-Remix/tree/main/BOM

TUTORIALS
= 
The tutorials begin here!

https://github.com/CyberSyntek/Syntek-Edition-Head-Remix/tree/main/01-MainPlate

MRL-FILES (MYROBOTLAB)
=
This section contain my MRL (myrobotlab) service set up, pin layouts and various code updates relating to the operations of the new head.

https://github.com/CyberSyntek/Syntek-Edition-Head-Remix/tree/main/MRL-Files

Note: Future updates to this section will be listed below under "UPDATES". 

UPDATES / NOTES
= 

11/21/2022
=

My goodness, there has been ALOT of chaos in my life recently. My apologies for not having further updated recently. LOTS of issues with my current landlord and urggg, things became chaotic. 

Anyway, as just a small update, I have aded the current files I am using which I mentioned in the previous update note below that use the JX PDI-1109 x12 and JX PDI-1181 x3 servos into a temp folder located at https://github.com/CyberSyntek/Syntek-Edition-Head-Remix/tree/main/JXrefit. 

Using these servos and files greatly helps performance in general. The previous jaw servos needed more torque to perform well so those have been upgraded to the PDI-1181 fit. (Slightly larger/more torque) as well as the rest of the head using PDI-1109 servos which are very slightly differently sides than MG90 size servos hence needing to refit ... everything. :D

I haven't ran into any issues with them yet, no buzzing at any time, just smooth servo glory. 

On that note I will be reworking this github page to use the JX refit parts and servos when I get the time and making the MG90 sized versions a thing of the past. Though I will likely leave them up in a seperate folder as an option for people still wanting to use those. 

- I also added the Teeth Fit Hinge Cover and Teeth as an option for people wishing to have lower jaw teeth. 
https://github.com/CyberSyntek/Syntek-Edition-Head-Remix/tree/main/03-Jaw/TeethFitHingeCover

I am currently experimenting with MRL with the help of the MRL team and beginning to tackle more of the software sides of things. Once I have made more progress on that I will start to put together a more plug and play Service setup to make using this head much easier for everyone to use within MRL. Hopefully I can add that stuff at the same time as the tutorial reworks come into play. 

Hopefully things will not be as crazy as they have been as of recently and the tutorial reworks and further updates will keep coming. 

09/04/2022
=

I'm currently making a JX Servo edition of this head which will use the following servos to replace MG90D/MG92B. 

- x12 - JX PDI-1109

- x3 - JX PDI-1181

The PDI-1181 is a slightly larger servo so it will have more torque on all 3 jaw motors. The JX servos seem to be the quiested, no buzz and better performance servos out of the 7 different micro servos I bought and tested. They should really improve overall performance in general. 

I will leave the current stuff available also for those wishing to use MG90D/MG90S type servos, but eventually I will be leaning more towards the JX servo set up as that is what I will be using and calibrating/coding with. 

I'll also be putting up an adaptor/frontskull merged file which will allow me to cut some of the widened jaw side down to help with the look. It will be optional of course. 

I've also made an optional 2nd edition of the jaw cover which has x4 screw holes slotted in it with an additional fit to jaw size teeth file for those of you wanting to add lower jaw teeth. They can be scary, but fun... I haven't tested the refit teeth in my head yet as I'm waiting on most of my JX servos to arrive still.  

Lots to come shortly. :)

08/27/2022
=
The jaw files from 03-Jaw have been updated. There were some slignt alignement issues in the previous files which have been fixed up. The jaw lip is thickened up to work with the AdjustableInsert.stl in the 05-Skull folder to allow for adjustable rubber inserts to be placed in the upper jaw to silence it any banging noise. 

The Eyeball-Cam1Fit.stl file has also been updated as there was a slight layer gap in the original file. It seemed to print fine, but that gap is now filled. I also added an alternative eyeball design for those wanting some variation. It is the same eye fit for the same camera, but has some grooves cut into it for a slightly different look. "Eyeball-Cam1Fit-Design1.stl"

I haven't got around to updating the images to match the new parts yet, so if you notice the differences or wonder why, THAT is why. :)

- I just added Eyeball-Cam2Fit.stl and Eyeball-Cam2Fit-Design1.stl which are fit for a different camera type and hook up. I will update the info once I have further explored how to connect it. This camera was a Ray Edgely request so he may have more info on how to connect it. :)

![RayCam](https://user-images.githubusercontent.com/81597534/187042699-c93ead60-17f0-4fe1-8bd2-d3e1fb40845b.PNG)

The camera it is fit for is as seen in the link below.

Arducam 1/4 Inch 5 Megapixels Sensor Mini Camera Module with Flex Cable for Raspberry Pi: https://a.co/d/bh3joRY


Other news. 

- 2/3 of the experimental servos I have ordered to test have arrived, I'll compare them all soon. 

- I believe I found a decent Matte paint protection spraypaint for protecting against the eyebrows marking up matte paints.... for those who paint their prints in matte anyway. 3rd brand seemed to be the charm. Krylon - Clear Matte. Still need to repaint everything and test it to make sure it is scratch resistant enough, but so far it isn't nearly as shiny as the other matte clear coats and doesn't seem to darken the paint like the last two. 

08/25/2022
=
I found some minor alignemnt issues with the jaw and went through all parts and fixed to make perfectly aligned. My apologies to anyone who printed so far, they should still work just these ones will be right on the money for anyone as picky as myself. :)

The updated files for the new jaw are in the "ExperimentJaw" folder. The jaw piece itself has a thicker lip and is meant to go with the insert for the FrontSkull which is also located in that file. This is still in the experiment stage, but should drastically reduce noise produced by the jaw.   

Just like all current files, please print at your own risk as things are still in development. Once confirmed these files all work well I will move them to the 03-Jaw folder and update the files there.

08/24/2022
=
Updated the Jaw.stl. The holes on the last file were a bit on the looser side and have been tightened up on current one. 


08/22/2022
=

*EDIT* ALL OF THE BELOW WAS WRITTEN PRIOR TO TESTING MG92Bs AT VARIOUS SPEEDS. 

I had ran everything at full speed mostly looking for buzzing and making sure they performed well. THey do........ at full speed. Once I started experimenting with different speeds, wow.... they are jittery at slow speeds. I.... urggg. lol. Not sure what to do think right now and looking into other servo options. I almost perfered the MG90Ds as they ran smooth at any range. The jaw would slightly sag without power to the servo, but was smooth moving at all speeds. The main issue was it didn't have enough torque to do fine small movements which resulted in louder jaw closing tapping sounds which wasn't great for speaking. I'm actually working on a work around to help prevent any jaw noises regardless of which servo is used right now so... if that works...., might even be able to prevent the under power jaw sag with an elastic band. XD 

Will further update upon more experiments. 


EXPERIMENT RESULTS WITH MG92B (slightly higher torque) SERVOS SWAPPED FROM MG90DS IN A FEW LOCATIONS.

- Jaw -  the higher torque MG92B servo is a much better result. The MG90D was not able to handle smaller refined movements due to being over loaded and the jaw would slightly sag without power to the servo. It still works, but more torque has resolved those issues and alloows for limiting the jaw to more so prevent tapping sounds when the robot is speaking. Obviously it is still plastic to plastic at this point so it isn't completely silent without limiting.

Myself or anyone else building this head may want to consider altering the bottom of the front mask and top of the jaw with expanding them slightly inwards so that we can slot in space for small rubber inserts or something along those lines as that would really quiet the jaw down and make calibrating for noise prevention much more of an easy task. 

- LateralJaw - no real change. Either work. 

- Eyebrows - MG92B servos seem to work better for the brows. No buzzing what so ever and handle smoothly. The MG90D servos were doing fine, but they were slightly buzzy once and awhile. MG92B servos are slightly taller than the MG90D servos so they do not fit flat into the holders where you screw them in. Either I'll need to make some printed spacers or adjust the browplate to fit those ultimately as those seem to be the better choice. Whether that is because of the added height angling into the browholders better or the extra torque (Maybe a combo of both?) I'm honestly not sure at this point. However they perform!

The general outlook so far is looking as such. 

- Brows - x4 - MG92B Servos

- Jaw - x1 - MG92B

- Lat Jaw - x2 - MG92B or MG90D (Either should be fine)

- Eyes - x8 - MG90D

- RotNeck - x1 - DS3218 20KG Servo (270° ver) (Unless I find something with a bit more torque that can work well. Will be investigating)

I grabbed my MG92B and MG90D from the Adafruit shop. They shipped quickly and were decently priced. They also restock quickly if ever out of stuff, usually a few days. 

MG92B Servo - https://www.adafruit.com/product/2307

MG90D Servo - https://www.adafruit.com/product/1143

=======================================================

- I will be adding a how to prep your servos for grouping tutorial write up. This will be especially important when picking your servos to mirror match sides of the head and will save you alot of sanity during the calibration stages. That will be prepared soon. 

=======================================================

- I had located a bit of an issue regarding the lateral jaw servo horns getting flexed by the threading on the self tapping screws causing a little bit of offset which resulted in a louder sounding jaw close. The "ServoConnector" jaw part has now been updated to a V2 version to take bolts and nuts to help prevent this issue. A few of the images int he jaw tutorial have not been updated to match the look of the updated part. BOM and material list in the tutorial have been adjusted to match "servoconnectorV2" - 08/22/2022

08/21/2022
=
- TPUbrows file I realized is still fitted for the prior "browsholder" file so I will need to adjust that also. The current ones up should still work without issue, but it should be easier on the servos with the adjustments. 


=======================================================

- A 2nd version camera fit eyeball and eyeadaptor has been prepared for an alternative raspberry pi camera. I'll add that once I get the information together for that and an idea of how to actually connect it. The camera fits, not sure how it will be connected yet as it was a request fit. Waiting for feedback. :)

=======================================================

- If you have explored enough you may have realized I haven't updated the MRL-Files section yet. This is mostly due to the above and wanting to experiment first as servo min/max ranges may alter as I swap different servos. 

=======================================================

- BUG: There is currently a bug in MRL relating to the IdleTimeout: causing some odd movements if the timer is set too low. Luckily none of the motors are under so much strain that we need a low set time out timer so that we can avoid this bug for the moment. The MRL team are aware of it now so we will see if that bug gets squashed eventually. Once I do update the files, the timers will be set to the higher settings I am using so you may not even realize. Just it is a thing, you should be aware. :) 

=======================================================

You may or may not be aware, but I am currently experimenting with various spray paint clear matte coats. For those of you not painting or even painting in none matte paints if using a protective coat,  this shouldn't matter. I personally do paint my bot and like matte shades due to the non reflective light texures when used on the face. I find more glossy paints to be less photogentic. The issue with the matte paint is currently it is getting marked up with the eyebrows moving back and forth. Matte paint generally is very easy to scratch/mark up, so I'm looking for work arounds to still be able to use it. 

I've tried two different matte clear coats so far, both were kind of a miss. The first one darkened the matte paint alot and was much more light reflective than I was hoping for. The 2nd brand was not much darker, but even more reflective than the first one. The hunt continues. :) 
