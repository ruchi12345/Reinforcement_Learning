## Reinforcement_Learning

Reinforcement learning is an interesting area of Machine learning. The rough Idea is that you have an agent and an environment. 
The agent takes actions and environment gives reward based on those actions, 
The goal is to teach the agent optimal behaviour in order to maximize the reward received by the environment.

![alt text](https://cdn-images-1.medium.com/max/1600/1*eRMfuUDrkII-LT99JVtVQw.png)

For example, have a look at the diagram. This maze represents our environment. Our purpose would be to teach the agent an optimal 
policy so that it can solve this maze. The maze will provide a reward to the agent based on the goodness of each action it takes.
Also, each action taken by agent leads it to the new state in the environment.

## Lunar-Lander

![alt text](https://cdn-images-1.medium.com/max/1600/1*i7lxpgt2K3Q8lgEPJu3_xA.png)

As you can see in the picture below, there is one space-ship. The task is to land the space-ship between the flags smoothly.
The ship has 3 throttles in it. One throttle points downward and other 2 points in the left and right direction. With the help of these, you have to control the Ship.

## The Mountain Car Problem

![alt text](https://cdn-images-1.medium.com/max/800/1*JjBfoFrKCoBxlraVZaEshw.jpeg)

The problem is  A car is on a one-dimensional track, positioned between two “mountains”. The goal is to drive up the mountain on the right; however, the car’s engine is not strong enough to scale the mountain in a single pass. Therefore, the only way to succeed is to drive back and forth to build up momentum.

The car’s state, at any point in time, is given by a vector containing its horizonal position and velocity. The car commences each episode stationary, at the bottom of the valley between the hills (at position approximately -0.5), and the episode ends when either the car reaches the flag (position > 0.5) or after 200 moves.

At each move, the car has three actions available to it: push left, push right or do nothing, and a penalty of 1 unit is applied for each move taken (including doing nothing). This means that, unless the can figure out a way to ascend the mountain in less than 200 moves, it will always achieve a total “reward” of -200 units.

## Acrobot-v1

![alt text](http://projects.rajivshah.com/images/training.gif)

The acrobot system includes two joints and two links, where the joint between the two links is actuated. Initially, the links are hanging downwards, and the goal is to swing the end of the lower link up to a given height.

## Bipedal Walker

![alt text](https://github.com/allanbreyes/bipedal-walker/blob/master/assets/demo.gif)

The problem is posed as a finite-horizon, non-deterministic Markov decision process (MDP), and is as interesting as it is difficult. The high dimensionality and continuous ranges of inputs (space) and outputs (actions) poses especially challenging examples of the lemmas of delayed reward, credit assignment, and exploration vs. exploitation. Moreover, while the MDP might guarantee convergence to a deterministic optimal policy in the limit, the dimensionality and continuous range poses the challenge that it cannot be enumerated in finite space complexity.

## Pendulum-v0

![alt text](https://github.com/shivaverma/OpenAIGym/blob/master/pendulam/pendulam.gif)

The inverted pendulum swingup problem is a classic problem in the control literature. In this version of the problem, the pendulum starts in a random position, and the goal is to swing it up so it stays upright.


## Research Infinite Solutions LLP

by Research Infinite Solutions (https://busreservation.ris-ai.com/) (https://www.bets-ai.com/)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
