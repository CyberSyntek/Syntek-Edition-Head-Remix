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

08/22/2022
=
- I will be experimenting today further today with the batch of MG92B servos I received. So far I have swapped out the Jaw and LateralJaw MG90D servos for the MG92B servos and the results are listed below.

Jaw -  the higher torque MG92B servo is a much better result. The MG90D was not able to handle smaller refined movements due to being over loaded and the jaw would slightly sag without power to the servo. It still works, but more torque has resolved those issues and alloows for limiting the jaw to more so prevent tapping sounds when the robot is speaking. Obviously it is still plastic to plastic at this point so it isn't completely silent without limiting.

Myself or anyone else building this head may want to consider altering the bottom of the front mask and top of the jaw with expanding them slightly inwards so that we can slot in space for small rubber inserts or something along those lines as that would really quiet the jaw down and make calibrating for noise prevention much more of an easy task. 

LateralJaw - no real change. Either work. 

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
