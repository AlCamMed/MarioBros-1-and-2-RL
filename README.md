# MarioBros-1-and-2-RL

README.TXT

## Overview 

This project works with the OpenAI Super Mario Bros gym environment and analyzes the performance of two reinforcement learning algorithms on the first level of both Super Mario Bros 1 and 2. The goal of this project is to find which learning model can complete and consistently perform well in two separate environments that vary in level of difficulty.

## Description 

There are three main components to this project: the training folder, the testing folder, and Project.ipynb. 

There is an existing training folder in which a small sample size of pre-trained data can be found in labeled subfolders that specify which Mario environment, reward function, and model policy were used. This folder will be accessed when selecting a training dataset for a model to learn from during testing and by conducting additional model training more data can be added to this folder at any time. 

There also is an existing testing folder split into two subfolders for videos and data collected from the test runs. In the video folder, one can find recordings of a small sample of testing simulations, as after each test a video recording of the entire run is saved into a subfolder depending on the game. In the testing folder, there is also a data folder that stores text files containing in-game information and statistics about each test, being used to evaluate the performances, and is also split into subfolders specifying which Mario environment the test is from.

Project.ipynb is the main file the project uses to load and run all of the different experimentations with the models and environments. To run the project simply start at the top of the Jupyter Notebook, ensuring you have installed the necessary packages, and work your way down running the labeled cells. The current file is set up for the user to be able to run completely in a short time by generating new training data and a test result and video for one model. Due to the different aspects of the problem, some cells are to be skipped, or small modifications are needed to produce results for a certain Mario game environment, learning model, reward function, or training dataset. But this will not be a problem if you are just interested in producing any time of data. 

## Note to Graders

Due to GitHub space constraints, I cannot add the training and data folders to this repository, but I have included a project.zip file in my Gradescope submission with all of the structured folders and the existing sample pre-trained and test result datasets, alongside the Project.ipynb file. The inclusion of these folders is not required to run the Project.ipynb file, I have just included it in case you want to see a small smaple of the data I collected. The Project.ipynb file can still be run in a directory on its own and will work fine as it is set to generate a small amount of training data, instead of using pre-trained data, and will produce only one set of test results based on a newly generated training dataset. 
