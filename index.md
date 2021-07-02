# Phone Controlled Robotic Arm
I am working on a robotic arm powered by Arduino. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Ruiqi Liu | Lynbrook High School | Mechanical Engineering | Incoming Sophomore

[![Headstone Image](https://www.linkpicture.com/q/IMG_0370.jpg)](https://www.linkpicture.com/view.php?img=LPic60df40fb0e590339483990)

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1625243052/video_to_markdown/images/youtube--4JyxNyno2K0-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=4JyxNyno2K0 "Final Milestone"){:target="_blank" rel="noopener"}

# Final Milestone
My final milestone is getting the sensor to work, which turned out to be the most difficult milestone. I added a switch on the app. When the switch was enabled, the claw would automatically close around anything that got too close, and when nothing was close it would open. This also works if the arm moves toward something; it will grab it if it is within range.


# Second Milestone
My second milestone is to get the app to control the arm via bluetooth. This was done using an ESP-32 chip, which is like an Arduino with bluetooth capabilities. Using the MIT App Inventor, I made an app with 4 sliders to control the 4 servos, and the ability to connect to the ESP-32 with bluetooth. I no longer need the computer program to control the arm, although I can still use it along with the app.
[![Second Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1624900553/video_to_markdown/images/youtube--GCNGNOH1TPk-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/GCNGNOH1TPk "Second Milestone"){:target="_blank" rel="noopener"}

# First Milestone

My first milestone is to finish building the arm, and to get the motors to control it. There are 4 servos, which are powered by an Arduino and a 6V battery pack. The servos control rotation of the base, opening and closing of the claw, and motion of the arm (forward/backward/left/right). They are controlled by an Arduino computer program where you can enter degree numbers and that will rotate each servo individually to any degree (between 0 and 180).
[![First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1624292482/video_to_markdown/images/youtube---N_VIP6raiM-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=-N_VIP6raiM "First Milestone"){:target="_blank" rel="noopener"}

This is the circuit diagram with the servos.
[![image](https://www.linkpicture.com/q/Screen-Shot-2021-06-27-at-11.30.40-AM_1.png)](https://www.linkpicture.com/view.php?img=LPic60df4169119ea1666372217)
