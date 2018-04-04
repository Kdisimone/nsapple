# nsapple
apple watch app for nightscout users

This project was started awhile ago by Perceptus.org and has just been dusted off recently to help Loop users.  My eternal gratitude to Ken Stack for putting this project together and sharing it with the community.  Until "we" find the time to clean up the code, the following modifications will need to be done to use the watch app with NS.  Note:  if you're good with Swift, the "we" can be you.  Feel free to improve, this is open source after all.

Currently this is for mg/dl.  Still needs mmol support.  Feel free, again, to contribute code support where you can.


1.  Change the default URL on **TWO LINES** (Line 168 and Line 315) to your NS URL.

![URL](https://github.com/Kdisimone/images/blob/master/nsapple_URL.png)

*******************
**Did you notice it was TWO LINES that needed a URL updated in the previous step?  Screenshot just showed one of the lines as an example, but you need to do both.  Ok, good.**
********************

2. Replace the word `perceptus` with your own unique word in the following 5 files.  Use the same word in every place (being careful not to accidentally delete any periods that may be on the same line).  This word should be unique to you so be slightly creative.  Some of the files have dropdown menus to find where you need to edit; the screenshots show them.

![files](https://github.com/Kdisimone/images/blob/master/nsapple_files.png)

![dropdown](https://github.com/Kdisimone/images/blob/master/nsapple_dropdown1.png)
![dropdown](https://github.com/Kdisimone/images/blob/master/nsapple_dropdown2.png)
![dropdown](https://github.com/Kdisimone/images/blob/master/nsapple_dropdown3.png)

3. Now replace the word `perceptus` in the Bundle Identifier line in the three targets; nsapple, nsapple WatchKit Extention, and nsapple WatchKit App

![bundleID](https://github.com/Kdisimone/images/blob/master/nsapple_bundleID.png)

4.  Press command-s to save the project, and sign all four targets with your apple developer team.

![sign](https://github.com/Kdisimone/images/blob/master/nsapple_build.png)

5.  Totally ignore the iPhone app on your iPhone for now...the NS URL entry is not yet active until "we" fix up the code.  Just use the Watch App version.  So, you'll find the nsapple app on your list of apps in your watch app...enjoy.

