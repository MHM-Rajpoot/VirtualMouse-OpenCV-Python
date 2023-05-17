 __Virtual Mouse__
 
Computer Vision Mouse


__Introduction:__

Overview: 
In this documentation, we will explore the concept of controlling the mouse cursor on a computer using hand gestures and computer vision techniques. This innovative approach eliminates the need for traditional input devices like a mouse or touchpad and enables users to interact with the computer using hand movements.

Document Scope: 
The scope of this documentation is to provide comprehensive instructions and guidance for utilizing a system that allows controlling the mouse cursor on a computer using hand gestures and computer vision techniques. It covers the necessary steps from installation and setup to gesture recognition and mouse control actions. The document aims to cater to users who are interested in exploring alternative input methods and leveraging computer vision technology for intuitive and hands-free computer interaction.


__Architecture and Design:__

System Architecture: 
The system architecture for controlling the mouse through computer vision using hand gestures involves multiple components working together to enable real-time hand tracking, gesture recognition, and mouse control.

Data Flow: 
An Image is captured then it is passed to classifier to check for any hands in it then if a hand is found all 20 points are labeled on the image and an array of these points is returned for further processing to guess the pose of the hand.


__Installation and Setup:__

This software has no installer; you just download the folder and run VirtualMouse.exe. FInally, Press ESC to exit the program. 


__Functionality and Features:__

This software allows the user to use his hand as a tracking device like a mouse. 
Following actions can be performed by as shown below
  Click 						
  Movement of Cursor
  Right Click					   
  Scroll Down
  Scroll Up
   
These 20 points are recognized and decision is made what to do from above mentioned actions


__APIs and Integration:__

Following are the dependencies for this project
opencv
mediapipe
pyautogui
Troubleshooting and Support:

Make sure when you download the folder there should be a dependencies folder in it else you program won't run.

__Version History, Updates and License:__

This is the first version for this software; later versions will add on more gestures and better UI.

Here,
1.0.0 represents software Update.Hardware Requirement Update.Minor Update

This product can only be available for Personal Use (Non commercial / Non profitable Use Only)
