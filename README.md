# nsapple
apple watch app for nightscout users

This project was started awhile ago by Perceptus.org and has just been dusted off recently to help Loop users.  My eternal gratitude to Ken Stack for putting this project together and sharing it with the community.  Until "we" find the time to clean up the code, the following modifications will need to be done to use the watch app with NS.  Note:  if you're good with Swift, the "we" can be you.  Feel free to improve, this is open source after all.


1.  On Line 168 and Line 315 change the URL to your NS URL

•	nsapple WatchKit Extension >> InterfaceController.swift



2. Replace the word `perceptus` with your own unique word in the following locations.  Use the same word in every place (being careful not to accidentally delete any periods that may be on the same line)

•	nsapple >> nsapple.entitlements

•	nsapple WatchKit Extension >>  nsapple WatchKit Extension.entitlements

•	nsapple WatchKit Extension >>  Supporting Files >> Info.plist  

•	nsapple WatchKit App >> nsapple WatchKit App.entitlements 

•	nsapple WatchKit App >>  Supporting Files >> Info.plist 

•	The Bundle Identifier line in the three targets; nsapple, nsapple WatchKit Extention, and nsapple WatchKit App


3.  Press command-s to save the project.  

4.  Sign all four targets with your apple developer team

5.  Totally ignore the iPhone app on your iPhone for now...the NS URL entry is not yet active until "we" fix up the code.  Just use the Watch App version.  So, you'll find the nsapple app on your list of apps in your watch app...enjoy.

