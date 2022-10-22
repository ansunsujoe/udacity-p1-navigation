# udacity-p1-navigation

In this project, we will be training a DQN agent to navigate and collect yellow bananas in a square world.

## Project Details

This task is single-agent and episodic and has a discrete action space. The high-level goal is to collect yellow bananas while avoiding blue bananas.

**State Space**: contains 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction.

**Action Space**: Either forward, backward, left, or right (4 actions).

**Rewards**: We will get a reward of +1 for collecting a yellow banana and a reward of -1 for collecting a blue banana.

**Goal**: In order to solve the environment, our  agent must get an average score of +13 over 100 consecutive episodes.

## Getting Started

**Step 1:** Clone the Udacity deep-reinforcement-learning project.

```
git clone https://github.com/udacity/deep-reinforcement-learning.git
```

**Step 2:** Copy the folder called "python" in the Udacity deep-reinforcement-learning project into the root directory of this project. This contains the code required to run a Unity environment.

**Step 3**: Open the Jupyter notebook "Navigation.ipynb" and run the first cell in Step 1 in order to install all the necessary Python packages and the unityagents package.

## Instructions

Here are the steps that are required in order for you to be able to train a DQN agent on the Banana environment.

**Step 1:** Run all the cells in sections 1-5 of Navigation.ipynb. This will set up all the classes and functions needed for training a DQN.

**Step 2:** At the beginning of section 6 of the notebook, replace the file path of the Banana Environment with the file path for your executable.

```
# Create environment
env = BananaEnvironment(fp="/your-file-path")
```

**Step 3:** Tweak any hyperparameters that you want in the initialization of the agent or the calling of the train_dqn method in Section 6.

**Step 4:** Run the code cell in section 6 and watch your DQN being trained!