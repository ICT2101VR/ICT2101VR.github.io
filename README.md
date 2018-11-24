# VR for SCTF
## 1. Introduction
SCTF VR is a virtual reality application is intended as a tool to educate users on riding etiquette and on safety with regards to cycling and personal mobility device usage in Singapore. The application will simulate the experience of riding through Singapore roads and park connectors. The application would inform the user if they are doing something that is unsafe or wrong.

## 2. Features

### 2.1 Player Gameplay
#### 2.1.1 Follow the instructions in the game to win!

![Instructions](https://media.giphy.com/media/3Foxq3qalSv554CbHw/giphy.gif)

#### 2.1.2 Unsafe behaviors will result in the deduction of your points!

![collision and deduction of points](https://media.giphy.com/media/9Y01uZrU3HXBXzNWuB/giphy.gif)

#### 2.1.3 Careful! making mistakes on 0 points result in a lost!

![collision and showing game over prompt](https://media.giphy.com/media/SGkRyIhFgSQfhbS9it/giphy.gif)

#### 2.1.4 Congratulations! you have made it to the endpoint :)

![touching win point and win prompt](https://media.giphy.com/media/9r2YcASn70dPJJY7tz/giphy.gif)

### 2.2 Trainer
#### 2.2.1 Choose your level to edit

![insert gif of mouse hovering over the levels and clicking one](https://puu.sh/C6GEn.gif)

#### 2.2.2 Select what variable to edit

![insert gif of mouse hovering over the env, ped, and vehicle buttons](https://puu.sh/C6GIW.gif)

#### 2.2.3 Update the level/pedesdtrian/environment variable!

![](https://puu.sh/C6GJJ.gif)

## 3. Getting Started (Downloading the game)

software requirements:
1) Web Browser
2) Web Server (e.g. python3 http.server module)

#### 3.1 Open up your terminal/CMD and CD into a folder of your choice.

    git clone https://github.com/aliciaxxteo/ICT2101_VR.git
   
#### 3.2 If you wish to serve the site from a python 3.0 server (same directory as html files):

    python -m http.server


#### 3.3 Go to your web browser and serve the url: "localhost:[port number]".
You will see the following login page:

![insert screenshot of login page](https://puu.sh/C6raW.png)


## 4. Guide

### 4.1 Login or Creating an account
#### 4.1.1 Login
![login](https://puu.sh/C6GLd.gif)

-Key in your username and password.

-Press the login button.

-Player will be directed to the next page (see PLAYER section 4.2 below).

#### 4.1.2 CREATE ACCOUNT PAGE

![insert gif of typing in the text boxes and selecting a player or trainer type. Press create and show the success message](https://puu.sh/C6Qe5.gif)

-Enter a username and password of your choice.

-Select whether you are a trainer or player.

-Press create to generate the account.

-You will be directed to the login page again.

### 4.2 PLAYER
#### 4.2.1 Start Player menu

![insert gif of looking at the individual buttons available (don't actually press the buttons)](https://puu.sh/C6GTw.gif)

-Player will be presented with three buttons on the Player menu: [View tutorial, Select Level, Logout]

-To interact with the buttons, look at it and press click on the mouse

#### 4.2.2 View tutorial

![insert gif of player menu page. Click the view tutorial button and show video playing](https://puu.sh/C6I2G.gif)

-Upon selecting the view tutorial button, a short video will play.

-Players can stop the video buy clicking on the back button or wait for it to finish playing.

-Players will then be brought back to the player menu page.


#### 4.2.3 Select Level

![insert gif of player menu page. Click the select level button and show the select level page.](https://puu.sh/C6H0d.gif)

-Upon selecting the view tutorial button, the different levels will be displayed.

![insert gif of select level page. Click a level button and show the select vehicle page.](https://puu.sh/C6Mts.gif)

-To choose a level, look at it and press click on the mouse. Players will be directed to the select vehicle page.

![insert gif of select level page. Click a view scoreboard button and show high score page.](https://puu.sh/C6Q5L.gif)

-To See the scoreboard look at it and press click on the mouse. Players will be directed to the Scoreboard page.

#### 4.2.4 Select Vehicle

![insert gif of select vehicle page. look around to show vehicles. Then look at the bicyle. dont need to click it ](https://puu.sh/C6HnG.gif)

-To select the vehicle for the level, look at it and press click on the mouse. The game will then start!

### 4.3 GAMEPLAY

see section [2.1](#21-player-gameplay "Gameplay") for gameplay.

### 4.4 TRAINER

See section [2.2](#22-trainer "Trainer") for how to edit levels as a trainer.

### 4.5 Video Gameplay

[![Watch the video](https://img.youtube.com/vi/6W_kGR9m2p8/maxresdefault.jpg)](https://www.youtube.com/embed/6W_kGR9m2p8)

## FAQ

Q: Is a VR headset compulsory to run "VR for SCTF"?

A: "VR for SCTF" can still run without a VR headset, although we recommend it for an immersive experience

Q: Can this application run on IOS or Android devices?

A: Yes, in fact, any device with web browsing capabilities can experience this application. 

Q: I have a problem/bug to report. Where do I go?

A: Please view the feedback section on this readme file

## Feedback
Let us know if you experience any problems or your general satisfaction!

https://docs.google.com/forms/d/e/1FAIpQLSdzHWjWxpSOktg6rXMzD_SMPlyzYYITJXXpEkew9fQbsELfSw/viewform?usp=sf_link
