# Artificial Intelligence S-21 CSCI 6660-01 
# Fall 2021
# Submission by:    Mohammed Abbas (00717674) and Mohammed Mudassir (00712876)

# Reinforcement Learning: Solving the Rubik's Cube

# This project is developed to solve the classic rubik's cube

# In order to solve the problem of rubik's cube we have implemented various algorithms such as
#   -   Feature based Q-learning which is a powerful reinforcement learning technique
#   -   Pattern databases to measure the quality of near completed cubes

# In this project we have made an assumption that a rubik's cube can only execute 180 degree side turns so that 
# we are able to reduce the branching factor of the cube's state space tree

# The project also reaches a solution for a solved cube which has n number of random moves executed on it 

# There are four files in our project - namely:
#   **puzzle.py** contains the state representation of a Rubik's Cube, **State()**, as well as a few auxillary functions
#   that are used elsewhere in the application

#   **tests.py** and **others.py** includes a various test cases that can be executed to confirm the valid 
#   outcome of the cube's state representation

#   **Agent.py** contains the implementation of a reinforcement learning agent, which implements functionality of 
#   Q-Learning, and also uses a pattern database, to build up a Q-Table.


### Project execution

-> clone the repository 

`>>> python Agent.py (will run Q-Learning on a n=5 scrambled cube, and attempt to solve it) `

-> to change the number of moves to apply to the initial cube, change **n=5** to any value on the **line 22** in Agent.py

`>>> self.start_state = cube if cube is not None else n_move_state(n=5) `

##### Created by: Mudassir Mohammed and Mohammed Abbas
# Date: 12/10/2021