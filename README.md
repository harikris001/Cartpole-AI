# CartPole AI - Reinforcement Learning

<img src="https://github.com/harikris001/Cartpole-AI/blob/master/docs/intro.png" width="850" height="362" />


Hey, This is a project of RL on the Cartpole Problem. The cartpole Environment is already present in the Gym package and i have tried to solve it through RL <br>

## Packages Used:
* gym
* Pytorch 2.0
* Stable-Baseline3
* Pyglet == 1.5.27
 _i noticed other versions throwing some error and found a solution in [`stackoverflow`](https://stackoverflow.com/questions/74314778/nameerror-name-glpushmatrix-is-not-defined) so i would reccomend this version_
 
 ### Setting Up Pytorch
 PyTorch is an optimized Deep Learning tensor library based on Python and Torch and is mainly used for applications using GPUs <br>
_I would recommend you to check official Pytorch website to install according to your cuda version_<br>
**The Pytorch need the exact version of Cuda to work normally**<br>
Pytorch website: [`pytorch`](https://pytorch.org/get-started/locally/)


## Creating Virtual Environment:
setting up a virtual environment will really help in Creating a seperatiion wwithin your workspace and PC<br>
**Run following to create a virtual environment**
* launch cmd 
* move to your desired directory
* Run the following:<br>
        ```python -m venv cpole```
* activate your virtual env using following:<br>
        ```.\cpole\Scripts\activate```<br>
to deactivte just type _deactivate_ in cmd

### Installing all necessary dependencies
To install all necessary packages for this particular project:
1. Either clone my repo or download the zip or copy paste the code and run them<br>
  Github clone Link: https://github.com/harikris001/Cartpole-AI.git <br>
2. Now activate venv and run:<br>
  ```pip install -r requirments.txt```
  

## Creating a New kernel in Jupyter Notebook
After installing Ipykernal run the following:<br>
```python -m ipykernal install --user --name=cpole```<br>
this will create a new kernel in your jupyter notebook. Now type in cmd ```jupyter notebook``` to launch jupyter notebook<br>

Run you Cells and wait


## Output 
The model completed its training in 20k steps,<br>
here is the results:<br>
|OUTPUT           |<img src="https://github.com/harikris001/Cartpole-AI/blob/master/docs/random_agent.gif" width="300" height="200" />|<img src="https://github.com/harikris001/Cartpole-AI/blob/master/docs/cartpole.gif" width="300" height="200" />|
|-----------------|------|------|
|Sl.NO            |1     |2     |
|Total Steps      |0steps|20K   |
|Completed Level  |False |True  |



## Refrences 
All my Refrences are attached below
* About Different Training Algorithms [`PPO`](https://stable-baselines3.readthedocs.io/en/master/modules/ppo.html)
* About Policy Evaluation [`evaluation`](https://stable-baselines3.readthedocs.io/en/master/common/evaluation.html)
* About DummyVecEnv [`Vectorized Environment`](https://stable-baselines3.readthedocs.io/en/master/guide/vec_envs.html)
* Getting gif output [`gif`](https://stable-baselines3.readthedocs.io/en/master/guide/examples.html#bonus-make-a-gif-of-a-trained-agent)
* Gym Documentation [`OpenAI Gym`](https://www.gymlibrary.dev/)