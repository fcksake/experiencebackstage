# experiencebackstage
supporting files to run experience mockups in LA office. This repo contains the show files for running webcam streaming for live puppeteering. Instructions for connecting touchosc for show functions as well as on-board audio instructions.,

PRE-SHOW

SOFTWARE YOU NEED:
Oculus LINK,
OBS Studio,
touchdesigner,
zoom,
Oculusmirror.exe,
TouchOSC


Environment setup:
Open zoom, enter meeting of whatever research session it is 
DO NOT JOIN AUDIO Upon joining the meeting, your audio may auto-connect and at this point you may get some feedback if your microphone is open and/or your speakers are turned up. To stop this, click the up arrow next to the mic symbol and select “Leave Computer Audio” 

Now open Meta Quest Link 
https://www.meta.com/help/quest/509273027107091/?srsltid=AfmBOooWfwdboIyxG6RvoWeSMy8668okdLk13djwv4GoBpKX1C0Spl_S 
Must have the headset hardwired connected to the PC (you may need to unplug a camera to do this) 
Now open Oculus mirror
File path should be something like: C:\Program Files\Oculus\Support\oculus-diagnostics
File is called oculusmirror.exe
You should not see anything playing on the headset unless the participant is in Oculuslink
OBS Studio (cameras for live streaming VR plus realtime participant capture over zoom )
1. Open OBS Studio 32.0.1
2. On startup, it should look something like this

3. Make sure your cameras are enabled
4. Make sure Oculusmirror is enabled

5. Move the entire window over to Monitor 2 (right most monitor). This is important for when it’s time to screenshare on zoom, you can keep the main monitor enabled




TOUCHDESIGNER:
1. Open [videopuppetfeed.toe]
2. The file will not have any cameras active upon startup. 

3. You must go into [videodevin1], [videodevin2], [videodevin3], [videodevin4] and individually activate the cameras. Do this for all the camera feeds
toggle this from off to on on all cameras


Feed will look something like this after the cameras are activated. You may encounter an issue with [videodevin4] or [videodevin3]
If there’s an issue, it’ll look something like this: 
This means that the camera is still active in OBS. 
4. Hop over to OBS and identify the camera still in use: 

5. Double click on the video capture device in the sources panel and click deactivate on the camera
6. Hop back over to TouchDesigner and re-toggle the camera that had an error.
voila! It fixed
7. Time for full screen: Open [window2] first and then open [window1]






ON-BOARD SOUND: 
Unplug on-board speaker from usb-c cable (speaker should’ve been charging overnight)
Go over to project machine station to ensure Avantree module is on and in standby mode. Hold the center button on the on-board speaker and then click the “CONNECT/DISCONNECT” button on the Avantree module
Once connected, make sure the KO2 is powered on and test sound. 




POST SHOW:
