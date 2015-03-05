# Google Drive Wrapper for Hyperspin/HyperLaunch

This collection of tools allows you to stream your rom collection from cloud storage to a HyperLaunch-enabled frontend such as HyperSpin.

You can stream from your own cloud storage files:

![Alt text](http://i.imgur.com/O0izf18.png "Optional title")

Or from a friend's set of files (if they share it with you):

![Alt text](http://i.imgur.com/KSD9Pn4.png "Optional title")

Note: The following instructions assume Hyperspin is set up with Hyperlaunch within its own directory (eg Hyperlaunch\Hyperlaunch.exe is in your Hyperspin directory).

##### 1. Simply rename the HyperLaunch.exe to HyperLaunch_real.exe and copy all files from the repo to your HyperLaunch directory.

![Alt text](http://i.imgur.com/1a50rV8.png)

##### 2. Run our replacement HyperLaunch.exe to log into your GDrive account, click accept, and paste the response code into the command window. this will create a file called 'cred.bin' that can be removed at any time to sign in with another account or remove the wrapper's access to your GDrive. You only have to do this once. Also, make a copy of 'cred.bin' and put it in your Hyperspin directory - it will be needed for the frontend later.

![Alt text](http://i.imgur.com/RrrPpYW.png)
![Alt text](http://i.imgur.com/CI7gua2.png)
![Alt text](http://i.imgur.com/CJl04U1.png)


##### 3. Under HyperLaunch\Settings\[System_Name]\Emulators.ini, add your google drive folder names you want to use to search for roms separated by a pipe ( | ) - the wrapper will search for both the local paths on your GDrive as well (in the example, both "Nintendo-DS" and "Nintendo - Nintendo DS" would be searched for on GDrive).
![Alt text](http://i.imgur.com/K3NXHMz.png)


##### 4. In the HyperLaunch Directory, run "cloud_db_gen.exe [system_name]" to create an xml file database of all your files both local and cloud-based where [system_name] is the Name in Hyperlaunch\Settings\* - example:
	cloud_db_gen.exe "Nintendo DS"

![Alt text](http://i.imgur.com/bh4aixu.png)


This will make a new xml in HyperLaunchHQ\Databases\[system_name] - move it to wherever you want it (most likely your hyperspin database directory).
![Alt text](http://i.imgur.com/vHnA4YC.png)

##### 5. Run your frontend and pick the game - enjoy :)

![Alt text](http://i.imgur.com/oPWcpaI.png)

![Alt text](http://i.imgur.com/x4yw8mw.png)

PROTIP: If you want the wrapper to save the games you download instead of deleting them, modify Hyperlaunch\GDConfig.ini and set DELETE_AFTER=False.

Cheers!
