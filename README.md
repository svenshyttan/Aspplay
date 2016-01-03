# Aspplay
Stereo to bark

A tiny little C# program to run on Rapberry Pi and play dog.mp3 on the stereoplayer
The program itself monitor a MySql table on my Synology NAS, if it allows to run/play/bark:
- is it a workday
- is it within right timeframe
- is the cam set to active
- do we have a "PING" connction with the NAS, since I turn it off every night for approx 4 hour.
if so then enter the program av execute the the rest off the logic/program.
Update table for the cam on:
- barkcounter
- motion detection time for the event, when it was fired (the motion)
- 

