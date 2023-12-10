# MarioBros-1-and-2-RL

README.TXT

## Overview 

This project works with the OpenAI Super Mario Bros gym environment and analyzes the performance of two reinforcement learning algorithms on the first level of both Super Mario Bros 1 and 2. The goal of this project is to find which learning model can successfully complete and consistently perform well in two separate environments which vary in level of difficulty.

## Description 

There are three main components to this project: the training folder, the testing folder, and Project.ipynb. 

There is an existing training folder in which a small sample size of pretrained data can be found in labeled subfolders that specify which Mario environment, reward function, and model policy was used. This folder will be accessed when selecting a training dataset for a model to learn from during testing and by conducting additional model training more data can be added to this folder at any time. 

There also is an existing testing folder split into two subfolders for videos and data collected from the test runs. In the video folder one can find recordings of a small sample of testing simulations, as after each test a video recording of the entire run is saved into a subfolder depending on the game. In the testing folder there is also a data folder which stores text files containing in-game information and statistics about each test, being used to evaluate the performances, and is also split into subfolders specifying which Mario environment the test is from. There are some existing files in this data folder which correlate to some of the video files stored and also some files showcasing results from tests done on much larger training datasets, which are unfortunately not available due to size constraints but can be generated by the user anytime. 

Project.ipynb is the main file the project uses to load and run all of the different experimentations with the models and environments. In order to run the project simply start at the top of the Jupyter Notebook, ensuring you have installed the necessary packages, and work your way down running the labeled cells. The current file is set up for the user to be able to run completely in a short time and generate new test results and a video for one model. Due to the different aspects of the problem there are some cells which are to be skipped or in which small modifications are needed in order to produce results for a certain Mario game environment, learning model, reward function, or training dataset. Make sure you have the training and testing folders set up in the same directory as the notebook so that the pertained data can be reached and the newly generated data stored properly. 

## Note to Graders

Unfortunately due to GitHubs space constraints I cannot add the training and data folders onto this repository, but I have included a zip file in my Gradescope submission with all of the structured folders and the Project.ipynb file ready to be downloaded and run without any issues. I apologize for the inconvenience.
