## Actor-Critic-from-scratch-RL
<h3>Goal:</h3>

* The goal is to understand the concept of policy gradient algorithms, to implement the  TD actor-critic algorithm and apply it to solve OpenAI gym environments.

<h3>Part 1:</h3>

* Implemented TD actor-critic algorithm from scratch.
  * Defined 3 separate networks actor, critic, and policy.
  * Actor is used to take an action based on the decision given by critic network. Policy network is used to predict probabilities to act by actor network.

<h3>Part 2:</h3>

* Solved Grid-world, Open AI 'Lunar Lander-v2' and 'Cartpole-v1' complex environments. (i.e. refer report for results)

<h3>Insights:</h3>

* The actor-critic algorithm performed well on grid world, converged sooner. I tried different setups for Lunar Lander with different hidden nodes and optimizer learning rates, small learning rates provided better results. 

* On cartpole the actor-critic took around 450 episodes to converge on contrary to DQN in less than 100 episodes. So, actor-critic takes a lot of time exploring and converges slower compared to value-based approximation algorithms.

