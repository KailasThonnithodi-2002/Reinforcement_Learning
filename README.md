# Reinforcement_Learning
Investigating the 3 methods of reinforcement learning through implementations on RL based problems. The following code is heavily inspired by Philip Castiglione github repository. link will be here. 
https://github.com/PhilipCastiglione/SIT215_Project


## Training Agents
###qlearning.py 
A python file that produces q-learning agents for each of the problems discussed in the report
###random.py 
A python file that produces random agents for each of the problems discussed in the report (there is only one instance of the random agent as it can be universally used in the problems discussed in the report)
###tdlearner.py
A python file that produces temporal difference learning agents for each of the problems discussed in the report

## Running_programs
###driver.py
Manages the execution of an agent based on the gym environment provided. It will train, update and identify the performance of the specific agent. The function will be plotted using the matploblib, producing a rewards count, concerning the number of iterations performed on the agent.
###run.py
The output of the performance of a specific agent on the problem. An agent which is not being analysed should be commented out if they are not being used.  
