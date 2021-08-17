<h1 align="center"><strong>airPiano</strong>
</h1>
<h1 align="center"><img src="./data/icons/airPiano_icon_dark_gradient_256.png"></h1>
<h5 align="center"><strong>A software with which you can play piano in the air, or play a bigger piano with the computer keyboard.</strong>
</h5>

<h5 align="center">

<br>

[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/powered-by-electricity.svg)](https://forthebadge.com)

</h5>

# :page_with_curl: Contents

1. [Features](#Features)
2. [Installation](#Installation)
3. [Screenshots](https://github.com/Karthikeshwar1/Araam#screenshots)
4. [Credits](https://github.com/Karthikeshwar1/Araam#credits)
5. [License](https://github.com/Karthikeshwar1/Araam#license)

<br>

# :sparkles: Description

## Featurs:

This program has two components:
* airPiano: Play piano with fingers in the air
* keyPiano: Play piano with the computer keyboard.
* Record/Play/Skip-to-start: Record audio from microphone and play it, or select any audio file and play piano with it.
* Sustain-controls: For keypiano, sustain can be turned on (sound will play even if the piano key is released) or off (sound will play as long as the key is pressed or until it stops)

## Working:

airPiano works by hand-tracking with the help of [mediapipe](https://mediapipe.dev/) framework. A finger is down, if, say for index finger (from image below) the tip (8) is below the distal part (7). The audio plays when the key is down.

<h1 align="center"><img src="./data/icons/hand_landmarks.png" ></h1>

source: [Mediapipe](https://google.github.io/mediapipe/solutions/hands.html)

<br>

# 🛠️ Installation

Coming soon!

<br>

# 🎞️ Screenshots

<h1 align="center"><img src="./data/icons/screenshot%20(3).png"></h1>

<h1 align="center"><img src="./data/icons/screenshot%20(2).png"></h1>

<h1 align="center"><img src="./data/icons/screenshot%20(1).png"></h1>


<br>

# 🧾 Credits

Program is written in Python with the help of the following amazing tools:
* [PyQt5](https://riverbankcomputing.com/software/pyqt)
* [PyAutoGUI](https://pypi.org/project/PyAutoGUI/)
* [Mediapipe](https://mediapipe.dev/)
* [OpenCV](https://opencv.org/)
* and several other python packages.

App icon was created by me.

# License

[![License: GPL AGPLv3](https://img.shields.io/badge/License-GPLv3-blue.svg)s](https://choosealicense.com/licenses/agpl-3.0/)

<br>
