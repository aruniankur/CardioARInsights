# Project Title - CardioARInsights

CardioAR Insights: Exploring the Human Heart through Augmented Reality

CardioAR Insights showcases the innovative integration of technology and education by offering a captivating exploration of the human heart using Marker based Augmented Reality (AR). Through our website, users can experience the dynamic functionality of the heart in action, utilizing AR technology to superimpose computer-generated imagery onto the real world marker. This interactive platform provides a unique and immersive perspective, demonstrating the potential of AR to revolutionize medical education and understanding.

### this page contain the code for  - https://aruniankur.github.io/CardioARInsights/

## Inspiration

The inspiration for CardioAR Insights emerged from a vision to reimagine medical education and patient engagement through innovative technology. Motivated by the transformative potential of augmented reality (AR), we embarked on a journey to create an immersive and interactive experience that transcends conventional learning methods. We were driven by a passion to merge technology with education in a creative manner, leveraging AR to provide a captivating exploration of the human heart and its complexities. Our goal is to inspire curiosity and deepen understanding while contributing to advancements in healthcare.
## Authors

- [@AruniAnkur](https://github.com/aruniankur)
- [@PriyangshuMandal](https://github.com/aruniankur)


## Demo

following is the Youtube Link to the Demo of our application :

[@Youtube](https://www.youtube.com/watch?v=BrRnBgtUAlY)




## Tech Stack

**Client:** Bootstrap 5, AR.js, A-frame.js , Three.js, Vite.js

**Software:** Blender (3d modelling Software)


## Features

To get the best of this, open the website in the phone.

[@CardioAR](https://aruniankur.github.io/CardioARInsights/)

Since we are using AR.js, we are using it's marker named as Hiro Marker :

[@HIRO-Marker](https://stemkoski.github.io/AR-Examples/markers/hiro.png)


**STEP TO USES THIS**

Step 1 : open the CardioAR link in the phone.

Step 2 : open the Marker on a fixed screen either on the laptop or another phone.

Step 3 : Click View AR button.

Step 4 : wait for few moment till the model get loaded.

Step 5 : Allow the website to access camera.

Step 6 : point the camera to the Marker.

Step 7 : you can see the human heart at the place of the marker.

Step 8 : Now, you can zoom in and out, rotate the heart as you wish.

Step 9 : Scroll down and you can see various button which control the opacity of the various part of the human heart.

Step 10 : Study heart interior with the help of our application.
## Installation

How to run it on the local host

```bash
    npm create vite
    // give name to the folder 'CardioAR' and choose , vanilla option then javascript 
    cd CardioAR
    npm install
```
    
now in that folder, delete the index.html an main.js 

Unzip our folder in the CardioAR.

```bash 
    npm run dev
```

if you want for phone

```bash 
    npm run dev -- --host
```
**Warning** : AR.js required https connection or localhost connection to run. 
By this method, if you npm does not provide a https link for local environment then the AR.js will not run.



## Error 

**Error 1** : 
```bash
Webcam Error Name: NotAllowedError Message: The request is not allowed by the user agent or the platform in the current context, possibly because the user denied permission
```

You have not provided the access to the camera. 

**OR**

you device or desktop don't have a camera.


**Error 2**:

```bash
Access this site over HTTPS to enter VR mode and grant access to the device Sensors.

Webcam Error Name: Message: WebRTC issue-! navigator.mediaDevices not present in your browser.

```

You Network is working on HTTP. Switch to HTTPS network or use a license network.
## FAQ



