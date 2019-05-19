# nsapple
apple watch app for nightscout users

This project was started awhile ago by Perceptus.org and has just been dusted off recently to help Loop users.  My eternal gratitude to Ken Stack for putting this project together and sharing it with the community.  Until "we" find the time to clean up the code, the following modifications will need to be done to use the watch app with NS.  Note: if you're good with Swift, the "we" can be you.  Feel free to improve, this is open source after all.


1.  Download the code for nsapple-pod branch

[click here to download](https://github.com/kdisimone/nsapple/archive/nsapple-pod.zip)

2. Open the project and use the search tool in Xcode to replace all the the word `replace-me` instances with your own unique word in 10 places. Note that 7 of them will automatically replace just by pushing the `replace all` button...but the final three in the list will require you to click on the file name and then manually type to replace the `replace-me`, as shown in the screenshots. Use the same word or words-with-hyphens (**being careful not to accidentally delete any periods that may be on the same line**).  This word should be unique to you so be slightly creative so that the phrase you picked isn't being used by someone else's developer account already (like katie123 is already being used by me, so you won't be able to build with that one). 

![files](https://github.com/Kdisimone/images/blob/master/replace-me.png)
![files](https://github.com/Kdisimone/images/blob/master/replace-me2.png)

3.  Sign all four targets with your apple developer team. You can verify that you've made the replacements correctly if you see your unique phrase in the Bundle Identifier information.

![sign](https://github.com/Kdisimone/images/blob/master/sign-target4.png)

4.  When the build is successful, a white screen will appear on your phone and tell you to go use your watch settings app. **You can close that app that pops open after the build...the actual URL entry for your Nightscout site is done in your iPhone's Watch app.**  So, open your Watch app on iPhone (has an icon of an Apple watch as the logo). Find your nsapple app on your list of apps in your Watch app, wait for it to install (or press `install` if you don't have automatic installations turned on). Then open that app by tapping on the name.

![sign](https://github.com/Kdisimone/images/blob/master/tap-here.png)

5. Enter your Nightscout site's URL

![sign](https://github.com/Kdisimone/images/blob/master/ns-url.png)
