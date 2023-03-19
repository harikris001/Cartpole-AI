# CartPole AI - Reinforcement Learning

<p>Hey everyone,Iam back with another RL Project, <br>This time we are training our agent to play the game Cartpole that comes with gym package. This is a really easy and quick RL project that helped me to understand RL and its baics.</p>
  
  
  ## Packages Used:
  * gym
  * pyglet==1.5.27 <br>
   _i noticed that this version of pyglet works perfectly, others return error so i recommend this version or else you can experiment for yourself_
  * Pytorch 2.0
  * Stable-Baselines3
  * ipykernal
  
  ### Setting up Pytorch
  Pytorch is a deep learning python package that is used for deep Reinforcement Learning and other appplications of it. This package will help you to accelerate       your Reinforcement Learning. This package works like a charm if you have a GPU on your machine<br>
  _I would recommend you to visit the website to install pytorch based on your Os and Cuda version_ <br>
  **The Pytorch need the exact version of Cuda to work Properly**
  
  Pytorch website: [`PyTorch`](https://pytorch.org/get-started/locally/)
  
  ## Creating Virtual Environment:
  setting up a virtual environment will really help in Creating a seperatiion wwithin your workspace and PC<br>
  **Run following to create a virtual environment**
  * launch cmd 
  * move to your desired directory
  * Run the following:
  ```python -m venv cpole```<br>
  * activate your virtual env using following:<br>
  ```.\mario\Scripts\activate```<br>
  to deactivte just type _deactivate_ in cmd
  
  ### Installing all your Dependencies
  Either clone my repo or download the zip or copy paste the code and run them<br>
  Github clone Link: https://github.com/harikris001/Cartpole-AI.git <br>
  Now in command prompt type:<br>
  ```pip install -r requirments.txt```
  
  
  ## Creating a New kernel in Jupyter Notebook
  After installing Ipykernal run the following:<br>
  ```python -m ipykernal install --user --name=cpole```<br>
  ***note: the name of kernel should be same as venv name***
