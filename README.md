# MarioBros-1-and-2-RL

README.TXT

## Overview 

This project works with the OpenAI Super Mario Bros gym environment and analyzes the performance of two reinforcement learning algorithms on the first level of both Super Mario Bros 1 and 2. The goal of this project is to find which learning model can complete and consistently perform well in two separate environments that vary in level of difficulty.

## Description 

Project.ipynb is the main file the project uses to load and run all of the different experimentations with the models and environments. To run the project simply start at the top of the Jupyter Notebook, ensuring you have installed the necessary packages, and work your way down running the labeled cells. The current file is set up for the user to be able to run completely in a short time by generating new training data and a test result and video for one model. Due to the different aspects of the problem, some cells are to be skipped, or small modifications are needed to produce results for a certain Mario game environment, learning model, reward function, or training dataset. But this will not be a problem if you are just interested in producing any type of data. The Project.ipynb file can be run in a directory on its own as it will create the folder structure needed to generate a small amount of training data, instead of using pre-trained data, and will produce only one set of test results based on the newly generated training dataset. Due to space constraints I was not able to add folders with pre-trained datasets and existing testing results, but I do have a zip file on hand so if you would like to view them feel free to reach out. 

The training folder is where trained data can be found in labeled subfolders that specify which Mario environment, reward function, and model policy were used. This folder will be accessed when selecting a training dataset for a model to learn from during testing and by conducting additional model training more data can be added to this folder at any time.

The testing folder is split into two subfolders for videos and data collected from the test runs. In the video folder one will store recordings of the testing simulations as after each test a video recording of the entire run is saved into a subfolder depending on the game. The data folder will store text files containing in-game information and statistics about each test, being used to evaluate the performances, and is also split into subfolders specifying which Mario environment the test is from. 

Lables: Folder labels with MOD_R stand for training or testing done with models that use a modified reward function. SMB stands for the Super Mario Bros 1 env. LL stands for The Lost Levels env. Some other files are also labeled with PPO or A2C specifying which model they store information of. 
