![Open CV Github Frame](https://github.com/TH-Activities/saturday-hack-night-template/assets/90635335/78554b37-32b2-4488-a10c-5c68098d7776)






# ROCK PAPER SCISSORS GAME
Rock Paper identification with TensorFlow and OpenCV.
Overview :
This repository contains the source code for a Rock, Paper identication implemented using TensorFlow, Keras, and OpenCV. The game uses a Convolutional Neural Network (CNN) trained on a dataset of hand gestures to recognize and classify the player's moves in real-time.

Features
Real-time Gesture Recognition: Utilizes OpenCV to capture video frames from the webcam and TensorFlow to classify hand gestures as Rock, Paper, or Scissors.

Machine Learning Model: The core of the gesture classification is a pre-trained CNN built with TensorFlow and Keras, capable of accurate recognition.

User-friendly Interface: The game displays the live webcam feed with the recognized gesture overlaid, providing an interactive and engaging user experience.

Requirements :
Python 3.x
TensorFlow
OpenCV
NumPy
## Team members
1. Athira K
2. Elizabeth Reji
3. Arathy Biju
4. Abhirami J P
## Link to product walkthrough
[link to video](https://drive.google.com/file/d/1o9ZttEYcq8VjStfY-kSro4P5Ci_I-bKN/view?usp=sharing) web cam is not recorded ,rock or paper is identified based on the hand shown to the webcam
## How it Works ?
1. we planned to make a game that captures hand movement and compares it with randomely generated symbols of rock ,paper,scisssors and determine a winner
2. 
2. Capture Hand Gestures:
Implement hand detection to recognize Rock, Paper, or Scissors gestures. You can use a pre-trained model or build your own using techniques like contour detection.

Game Logic:
Determine the game logic based on the detected hand gesture. For example:

If the hand forms a fist, it's Rock.
If the hand is open, it's Paper.
If the hand shows two fingers (peace sign), it's Scissors.
Display Results:
Show the user's gesture and the computer's randomly generated gesture on the screen.

Determine Winner:
Compare the user's gesture with the computer's gesture to determine the winner based on the Rock, Paper, Scissors rules.

Repeat or Quit:
Allow the user to play again or exit the gameame that captures hand movement and compares it with randomely generated symbols of rock ,paper,scisssors and determine a winner
2. but we ended up making a program which identifies gestures shown by the user as rock or paper or scissors.
## Libraries used
TensorFlow, Keras, and OpenCV
## How to configure
Instructions for setting up project
## How to Run
Instructions for running
