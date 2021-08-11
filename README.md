[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135612-cbff24aa-7d12-11e8-9b6c-2b41e64b3bb0.gif "Trained Agent"

# Deep Q-Network (DQN)

## Environment

![Trained Agent][image1]

	• it's okay to have discreet actions (engine on or off)
	• Landing pad at coordinates (0, 0)
	• Coordinates are the first two numbers in state vector
	• Reward for moving from top-screen to landing-pad and zero speed (no use of engine) is about 100 .. 140 points (if lander move away from the landing-pad loses reward)
	• The episode finish when lander crashes or comes to rest (receiving additional -100 or +100)
	• Each leg with ground contact is +10 points
	• Firing the main engine is -0.3 point each frame
	• Firing the side engine is -0.03 point each frame
	• Solved is 200 points.
    • Landing outside the landing pad is possible, the fuel is infinite, so an agent can learn to fly and then land on its first attempt


## Resources

- [Human-Level Control through Deep Reinforcement Learning](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf)
- [Deep Reinforcement Learning with Double Q-Learning](https://arxiv.org/abs/1509.06461)
- [Dueling Network Architectures for Deep Reinforcement Learning](https://arxiv.org/abs/1511.06581)
- [Prioritized Experience Replay](https://arxiv.org/abs/1511.05952)
