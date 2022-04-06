# Telepresence robotic car, controllable over the internet (WIP)

This project, is essentialy one which allows you to control a motorized robotic car through the internet. 

Who wouldnt want a creepy little robotic car to be placed in your respective hourse where you can walk around and have a "not-zoom" converation with anyone when you are not in at the moment

![image](https://user-images.githubusercontent.com/13113194/162027037-34645f74-b0bd-400a-85ad-5de2ae5d1968.png)
Inspired from https://www.kickstarter.com/projects/rossatkin/smartipresence-cardboard-telepresence-robot

The project essentially plays off a 
1. Raspberry Pi 4
2. Motor L298 Motor Driver
3. Raspberry OS
4. Mobile Phone (a space, for the moment)
5. Replit account (for a quick hosting server environment) for the mobile based remote

The core components of this, are going to be 
1. The remote control app / web
![image](https://user-images.githubusercontent.com/13113194/162033424-4b714909-ac61-4e24-9b2d-c8549e418def.png)

At v1, we would start with just the navigation controls (left, right, etc), with the video. 

MVP would not include the video off hand (we would use a Zoom like control to view


2. The web server. The intructions fired from the remote would be routed through the web server onto an internet enabled Raspberry Pi (RPi 4 Model B). 
The server enviroment I chose to use to kick-start is replit, due to it low cost to get started, and flexible / free plans

3. Finally, the client bot. Which would essneitlally just read off instructions off the server and exeute without any intellegance of its own to start with. For the video server, I would explore Twilios API's as that seems to be something that can pull off the job we are trying to achieve. 
4. 
