# Continuous Control Project - DRLND
## The Environment
The 20 agents version of the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment is used for this project.
<p align="center">
<img src="https://video.udacity-data.com/topher/2018/June/5b1ea778_reacher/reacher.gif" alt="Unity ML-Agents Reacher Environment">
</p>

In this environment, a double-jointed arm can move to target locations. A **reward** of **+0.1** is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

The **observation space** consists of **33 variables** corresponding to *position, rotation, velocity,* and *angular velocities* of the arm. 
Each **action** is a vector with **four numbers**, corresponding to *torque* applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

### Solving the Environment
The project has two separate versions of the Unity environment:

**The First Version**

The first version contains a single agent.
The task is episodic, and in order to solve the environment, the agent must get an average score of **+30** over 100 consecutive episodes.

**The Second Version**

The second version contains 20 identical agents, each with its own copy of the environment.
The environment is considered solved, when the average (over 100 episodes) of the **average scores**  (over all 20 agents) is at least **+30**.

## Getting Started
### Step 1: Activate the Environment

Clone this repository:
`git clone https://github.com/SuHamza/Continuous-Control-DRLND.git`

Then follow the instructions in the [DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies) to set up your Python environment. By following these instructions, you will install PyTorch, the ML-Agents toolkit, and a few more Python packages required to run this project.

### Step 2: Download the Unity Environment
Download a customized Unity Environment from one of the links below. You need only select the environment that matches your operating system:

**Version 1: One (1) Agent**
- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

**Version 2: Twenty (20) Agents**
- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)

Then, place the file in the main folder in the `Continuous Control DRLND` GitHub repository, and unzip (or decompress) the file.

### Step 3: Explore the Environment
After you have followed the instructions above, open `Continuous_Control.ipynb` and follow the instructions to run and train the agent.
