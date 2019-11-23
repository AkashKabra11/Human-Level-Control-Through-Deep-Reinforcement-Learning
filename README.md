## Human-Level Control through Deep Reinforcement Learning

### Guidelines:
This folder contains two subdirectories: DQN and Double_DQN. They contain the code, GIFs, and graphs for average losses and rewards. 
To run the code, simply run the iPython Notebooks in the respective subdirectories. The code works directly without any dependance issues on Google Colab, and you will need to install Keras and OpenAI's gym on your environment to run it locally. This can be done running the shell commands "pip3 install keras" and "pip3 install gym"

### Implementation Details:
We have used Keras for all implementations and matplotlib to visualize the graphs for rewards and losses. While we're getting good results for Breakout, Pong had us face some issues due to a dearth of computational resources. We could train for 1.5 to 2 million frames only, as compared to 50 million frames used in the paper. To use the same code for PONG, please change hyperparameters to  --> ENV_NAME = 'Pong-v0' in the respective jupyter notebooks. 

