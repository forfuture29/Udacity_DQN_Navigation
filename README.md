# Udacity_DQN_Navigation

The goal of this project is to solve the Banana Environment from Unity Engine with the tasks as follows:


Task : Collect yellow banana as many as possible

State Sizes  : 37

Action Sizes : 4

Reward:  +1 (Yellow Banana), -1 (Blue Banana)

Enviroment Solved:  Average Reward for the lastest 100 episodes >=13.0



# Getting Started

1. First, we have to set up the environment by following the instructions in the [DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies)
2. Download the Unity environment based on your operating system as below:
 <br />Linux: [Click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
 <br />Mac OSX: [Click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
 <br />Windows (32-bit): [Click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
 <br />Windows (64-bit): [Click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

Then, place the file in the p1_navigation/ folder in the DRLND GitHub repository, and unzip the file.




# How to run the code

You can run the code from both Nagivation.ipynb and Report.ipynb. I recommend to run the code in Report.ipynb. The instructions have been divided into 7 steps which all you have to do is to follow each step consecutively. Please note that you need to import the environment by changing the `file_name` parameter to match the location of the Unity environment that you downloaded.

- **Mac**: `"path/to/Banana.app"`
- **Windows** (x86): `"path/to/Banana_Windows_x86/Banana.exe"`
- **Windows** (x86_64): `"path/to/Banana_Windows_x86_64/Banana.exe"`
- **Linux** (x86): `"path/to/Banana_Linux/Banana.x86"`
- **Linux** (x86_64): `"path/to/Banana_Linux/Banana.x86_64"`
- **Linux** (x86, headless): `"path/to/Banana_Linux_NoVis/Banana.x86"`
- **Linux** (x86_64, headless): `"path/to/Banana_Linux_NoVis/Banana.x86_64"` 

