***EDIT Patch sends 12 inputs, instead of 15 that refers to the title. 


Kinect12Inputs

https://github.com/AntonVsound/kinect15inputsWek



- Sends 12 features including x,y,z for Left Hand (relative to the head), x,y,z for Right Hand (relative to the head), accelerometer on x,y axis for Left Hand, accelerometer on  x,y for Right Hand, dH for Distance between left and right hand, dF for Distance between left and right foot.
- Sends to port 6448 using /wek/inputs OSC messages

-This patch was made in Max/Msp 7 (OS X Yosemite v 10.10.3).

-External objects/applications used 

1) OSC package http://cnmat.berkeley.edu/downloads
2) Synapse http://synapsekinect.tumblr.com/post/6305020721/download

-In order to make this match work:

1)Make sure Kinect is plugged.
2)Open Synapse (external application).
3)Open max patch.
4)Done! (just a small reminder, you need to hold the Ψ (“psi”) position for several seconds in front of the camera. After doing so, the skeleton appears). 



-The accelerometer features allow unique sound manipulation Personally I used it to control the modulation rate on a synthesizer. 

-These features could be used for a dancing performance, a theatre show controlling music/sound or/and visuals.Another use could be for  an interactive room/installation.  
