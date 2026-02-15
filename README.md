# FunSTA1_hw_mac
These instructions were created specifically for the University of Oulu's course 521292S Fundamentals of Sensing, Tracking and Autonomy 1. The goal is to guide how to run preimage calculators, visualizers and other tools inside a virtual environment on a Mac to complete course homework. This README contains instructions for how to set up a CONDA environment.

**STEP 1: Install CONDA**

- Get Miniconda or Anaconda from the website: https://www.anaconda.com/docs/getting-started/miniconda/main 

- Verify installation by writing in the terminal: **conda --version**



**STEP 2: Create your environment**

- Create an environment called FunSTA with Python 3.11 with this: **conda create -n FunSTA python=3.11 -y**

- For your environment, the name can obviously be different :) Also, if you want to create the environment by using a different Python version, just replace the 3.11 with your desired version. 



**STEP 3: Activate the environment**

- Activate the environment you just created by this: **conda activate your_environment_name**

- If activated correctly, you should see the environment name at the start of the terminal line --> For example: (environment_name) username@Mac foldername %


**STEP 4: Install packages for the virtual environment**

- To run the tools provided by the FunSTA 1 course, install the following packages to your environment by running:

  1. conda install pygame
  2. conda install numpy
  3. conda install matplotlib
  4. conda install scipy


**STEP 5: Try to run a tool inside the virtual environment**

- Run the code by writing: **python path/to/the/homework/tool/file**


**STEP 6: Daily usage**

- Activate:    conda activate your_environment_name
  
- Deactivate:  conda deactivate

- In case you want to delete the environment, use this:  conda env remove -n your_environment_name
