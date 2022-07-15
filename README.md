# Gesture-Controlled-Call-SMS-Messaging
This project is a proof of concept that improves on mobile phone hands-free functionality while driving for accessibility. We were inspired for this project because older cars weren't made with hands-free tech included, and 3rd party voice-controlled hands-free tech never worked quite right in our experience. Also, it will allow for people unable to speak to control their phone safely while driving when getting an incoming call.

## How It's Made:
**Tech used:** Java, TwiML(Twilio’s XML based), SWIG, Git, debugged using Eclipse, Leap Motion Visualizer

We integrated Twilio framework for texts and voice calls with gesture detection on the Leap Motion Controller to send messages and calls simply by making a hand motion.

## What is a Leap Motion Controller?
You might be wondering what a Leap Motion Controller is! Well, it's a dongle made by Ultraleap with a USB interface, which means it can be connected right to your phone, although our prototype does run on a PC. Here's a picture:

![image](https://user-images.githubusercontent.com/42983801/200339170-e450489d-f17b-4c14-9249-ec2e21a0e97e.png)

# Awards
Won Best Use of Twilio API Prize among 600 participants at University at Buffalo Hackathon 2018.

## Optimizations

We wrote this prototype to be ran on a computer but would make an android app with Java or iOS app with Swift. 

One improvement we would make is with the hardware itself. We would modify the Leap Motion hardware to have a male USB-C plug along the long edge so that it could be plugged directly into the bottom of a mobile phone while it's mounted on a dashboard magnet like so:

![image](https://user-images.githubusercontent.com/42983801/200352966-002e9c32-15c8-4ab5-85b7-7c4176a537ed.png)
