# VR Draw (A Draw Oculus Experience

An open source project demonstrating how to draw in virtual reality. And it is forked from https://github.com/dilmerv/VRDraw.git.

## VR Draw Main Scene (With Hands)

***Important Be sure to select "Hands Only Or Controller And Hands" in the OVRCameraRig Hand Tracking Support***
VRHandDrawing.unity is the main scene for hand drawing implementation and few examples created while running with the Oculus Quest are shown below:

<img src="https://github.com/dilmerv/VRDraw/blob/master/docs/images/handdraw_1.gif" width="300">

<img src="https://github.com/dilmerv/VRDraw/blob/master/docs/images/handdraw_2.gif" width="300">

<img src="https://github.com/dilmerv/VRDraw/blob/master/docs/images/handdraw_3.gif" width="300">

## VR Draw Main Scene (With Controller)

***Important Be sure to select "Hands Only Or Controller And Hands" in the OVRCameraRig Hand Tracking Support***

VRDrawing.unity is the main scene for controller drawing implementation and few examples created while running with the Oculus Quest are shown below:

<img src="https://github.com/dilmerv/VRDraw/blob/master/docs/images/demo_1.gif" width="300">

<img src="https://github.com/dilmerv/VRDraw/blob/master/docs/images/demo_2.gif" width="300">

<img src="https://github.com/dilmerv/VRDraw/blob/master/docs/images/demo_3.gif" width="300">

<img src="https://github.com/dilmerv/VRDraw/blob/master/docs/images/demo_4.gif" width="300">

## VR Draw testing in the editor

It always takes time to run and test in the Oculus device so instead I provide you with a few tools to help you test your changes within Unity.

1- Enable AllowEditorControls by searching for VRDrawLeft and VRDrawRight game objects in the hierarchy and updating the property in the VRDraw.cs inspector. 

<img src="https://github.com/dilmerv/VRDraw/blob/master/docs/images/instructions_1.png" width="300">

2- Hit Play in the editor and use VR headset and controllers to move around, draw, and bring draw UI options:

### Movement and drawing
* Left arrow, right arrow, down arrow, up arrow – Movement
* Press and hold triggers – Emulate drawing

### VR Draw Options
* Press X - Opens left controller drawing options
* Press A - Opens right controller drawing options
* Left arrow, right arrow, down arrow, up arrow - To move through drawing options
* Press Y - Select drawing option on left controller
* Press B - Select drawing option on right controller
