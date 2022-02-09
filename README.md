# CS 425/525 Assignments #
This repository contains the assignments for the course CS425/525 Brain Inspired Computing (Spring 2022). 

To run the assignments, you will need to setup a programming environment. The basic requirements are listed below:
* Python 3.7 or higher
* Numpy, Scipy, Matplotlib, Jupyter Notebook/lab
* PyTorch 1.2 or higher (Cuda compatibility is not required)


There are two ways to set up an environment with the basic requirements:

## The Easy Way ##
We strongly recommend you to use the ilab machines for the purpose of running the assignments. All students registered for CS 425/525 have access to the ilab machine through the CS computing account. If you do not have a CS computing account, please read the following webpage and follow the instructions to get a CS account: https://resources.cs.rutgers.edu/docs/new-users/getting-started/. 

With your CS account enabled, simply go to: https://weblogin.cs.rutgers.edu. Login through your CS account credentials. And click on any of the ilab machines to continue. 
More details here: https://resources.cs.rutgers.edu/docs/using-cs-weblogin-to-access-ilab-machines/

Once you are connected to the ilab machine, open a terminal and activate the python environment using ```source activate python37```

Note: You might need to add the environment path variable to your bashrc to run the above command. This needs to be done just once. To do this, follow the following steps:
1. Open the terminal and enter your bashrc with vim editor using: ```vim ~/.bashrc```
2. Press Insert to enter the edit mode in vim and add the following line to the end of your bashrc file: ```export PATH="$PATH:/koko/system/anaconda/bin"```
3. Press Esc to exit the edit mode. Type :wq to save and exit vim. 
4. Source your bashrc using the following command: ```source ~\.bashrc```
5. You should now be able to activate the environment: ```source activate python37```

Once you have activate the environment, go to the directory where your assignment file resides and run jupyter lab using: ```jupyter lab```
This will open Jupyter lab in a browser, and you will be able to access your assignment file, edit it, and run it. 

## The Difficult Way ##
We strongly recommend you to use ilab using the method described above, and we are here to help if you have any issues connecting to ilab. However, if you want to setup the programming environment on your own local machine, you will need to first create an anaconda environment (https://www.anaconda.com/products/individual). Then activate the conda environment and install Pytorch (https://pytorch.org/). All other required packages come preinstalled with anaconda distribution. 

Activate the environment, go to the directory where your assignment file resides and run jupyter lab using: ```jupyter lab```
This will open Jupyter lab in a browser, and you will be able to access your assignment file, edit it, and run it. 

## Running the Assignments ##
Simply download the assignment files and follow the steps outlined in the easy way or difficult way. 

