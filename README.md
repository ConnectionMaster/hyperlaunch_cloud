# Google Drive Wrapper for Hyperspin/HyperLaunch

This wrapper fronts Hyperspin/HyperLaunch/HyperLaunch.exe with a wrapper 
that allows you to pull roms/isos/etc from your Google Drive.

![Alt text](http://i.imgur.com/O0izf18.png "Optional title")

#####1. Simply rename the real HyperLaunch to HyperLaunch_real.exe and copy all files to your HyperLaunch directory.

![Alt text](http://i.imgur.com/1a50rV8.png)

#####2. Run our replacement HyperLaunch.exe to log into your GDrive Account. 

![Alt text](http://i.imgur.com/RrrPpYW.png)

<b>NOTE: You only have to log in once - the program saves your login to the "cred.bin" file - delete to change user.<b>

#####3. Copy the response code and paste it into the command window:

![Alt text](http://i.imgur.com/CI7gua2.png)
![Alt text](http://i.imgur.com/CJl04U1.png)

#####4. The program includes a GDConfig.ini file that has a couple of options; a path to your local rom files and whether you want the wrapper to delete the downloaded rom files after you're done playing them (defaults to true).
 
![Alt text](http://i.imgur.com/hiBbcJn.png)

#####5.Copy the 'cred.bin' file and the 'GDConfig.ini' file to your Hyperspin root (where Hyperspin.exe is).

![Alt text](http://i.imgur.com/kbY9H4X.png)

#####6. You're all set! Run Hyperspin and play as normal, the wrapper will download any rom you don't have locally from your google drive under roms/system_name/game_name - the names will need to correlate to what HyperLaunch looks for (look to the directory names in Hyperlaunch\Settings for naming your GDrive folders).

Example from the command line:
![Alt text](http://i.imgur.com/xW1hO85.png)
![Alt text](http://i.imgur.com/q1embWw.png)

![Alt text](http://i.imgur.com/SdHiRPm.png)
