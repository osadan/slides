___
# WEB VR / STEREO
___
---
- status
- development enviornment 
- tools and community 
- code
- problems
- chalenges
---
### development enviornment
----
1. oculus rift 
2. browser / Chrome 64.* , firefox 54.*
3. gtx > 970
4. 2 hdmi inputs
---
###  tools and community
----
1. three.js
2. web vr slack
3. oculus rift forms
4. mozilla forms
---
### code
----
1. canvas => working stright through the gpu 
2. uses api to render the canvas scene into the rift lanes
3. use third part library to handle all the api processes
4. use two cameras on the canvas scene each camera show single image
5. use gamepad api to handle the controls of the rift
---
### problams
----
* the api ,browsers and the oculus softawre are not stable enough
* we had issues almost every time the gtx driver was updated
* we switched twice the cable of th rift connecting the headset 
---
### chalenges
----
- tiles - add openlayers to display the stereo - (put canvas inside canvas)
- projection 
- navigating - create good ui navigate and manage the view
- connecting between two rifts - share knolwadge while discovring
- don't let the user change the focus - create few points for each image and move the image while the user discovring  
