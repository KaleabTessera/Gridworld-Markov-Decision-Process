# Gridworld-Markov-decision-process
## Markov Decision Process (mdp) in a Gridworld Environment
### Problem
- 7x7 gridworld as an MDP:
- Given a state and an action, you should be able to execute the action and return a new state and reward.
- The actions are the cardinal directions and are deterministic. The states are just the cell the agent is currently in. Assume the third row from the top is all obstacles, except the right-most cell. The initial state is the bottom left, and the goal the top left.
- There is no discounting. The reward for reaching the goal is 20, and -1 for each action.

## Implementation
- Random Agent
- Greedy Agent following a value function calculated using value iteration. 

## Installation 
```
pip install -r requirements.txt
```