# Navigation-Deep Reinforcement Learning Nanodegree-Project 1

## Project Details
This project trains an agent to collect yellow bananas and avoid blue bananas within the Unity Banana environment. The state has a length of 37 and contains information regarding the speed and the items in the path of the agent. The agent has four actions: move forward, move backward, move left and move right. The environment is considered solved when the average score is at least 13 over 100 consecutive episodes.\n", "\n", "This implementation is adapted from the Deep Q Network exercise in the Udacity Deep Reinforcement Learning Nanodegree.

## Getting Started
In order to run this agent, one must have Python 3, PyTorch, Unity, Jupyter Notebook, numpy, and matplotlib installed.\n", "\n", "The easiest way to set up all of the requirements and dependencies is to clone the Deep Reinforcement Learning Nanodegree repository on Github. One will need to create a new virtual environment with Python 3.6, install OpenAI gym and create a kernel within IPython. Once the notebook is open, the kernel should be selected from the Kernel dropdown menu. Detailed instructions for these steps can be found here:[Dependencies]( https://github.com/udacity/deep-reinforcement-learning#dependencies)
Finally, one will need to set up the Udacity Banana environment, by downloading the appropriate environment for your operating system from the links below.

* [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)

* [Mac](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)

* [Windows 32-bit](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)

* [Windows 64-bit](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

Once the environment is downloaded it should be put in the p1_navigation folder within the cloned repository and unzipped. That's it!

## Instructions
The easiest way to run the code is to open up the Navigation.ipynb in Jupyter Notebook and click Restart and Run All in the Kernel dropdown.
