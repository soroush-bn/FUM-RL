# FUM-RL

## Resources 
#### learning RL
- Reinforcement Learning: An Introduction Book by Andrew Barto and Richard S. Sutton [(link)](https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf)
- David Silver lectures [(youtube link)]()
- Deep RL course by Surgey Levine [(youtube link)]()
- Hugging face hands-on courses [(link)](https://huggingface.co/learn/deep-rl-course/unit1/introduction)
- Reinforcement Learning Algorithms: An Overview And Classification. [arxive](https://arxiv.org/pdf/2209.14940.pdf)

#### Interpretable RL
- [A survey on interpretable reinforcement learning](https://arxiv.org/abs/2112.13112)
- summary of the above survey can be found [(here)](https://github.com/soroush-bn/interpretable-RL)

#### Prototypycal RL
- ProtoX [(arxive)](https://arxiv.org/abs/2211.03162)
- ProtoCad [(arxive)](https://arxiv.org/abs/2211.12774)
- RSSM [arxive](https://arxiv.org/pdf/1801.10395.pdf) [youtube](https://www.youtube.com/watch?v=6E7yJUiYL6c)



## What we have done so far

* Implementing ProtoX paper code [(link)](https://github.com/soroush-bn/ProtoX)
* Training PPO agent for supermario bros 
* Helper functions for preprocessing Pong enviroment [(notebook)](https://colab.research.google.com/drive/12t8ujGsGklMKQ7qlKnxTtsEiFhHaeFAA#scrollTo=gcOYiesTnhzy)



## Future works
* Impementing ProtoCad [link](https://github.com/soroush-bn/ProtoCAD)



## Tools and Frameworks

- we use gymnasium as the main library for our experiments [(docs)](https://gymnasium.farama.org/)
-- some papers used gym which is a depricated version of gymnasium; you can see differences and migration tips [here]()
- check [here](https://gymnasium.farama.org/environments/third_party_environments/) for third-party enviroment integrated with gym
- [stable baseline3](https://github.com/DLR-RM/stable-baselines3) is a great repository that implemented most of the RL algorithms. [see doc](https://stable-baselines3.readthedocs.io/en/master/), you can find pre-trained agents for many gym games on [stable baseline zoo](https://github.com/DLR-RM/rl-baselines3-zoo)
- some useful examples of stable baseline3 [link](https://github.com/DLR-RM/stable-baselines3/blob/master/docs/guide/examples.rst)
- a great visualization and logger tool [commet:link](https://www.comet.com/get-started)

## Extras 
- an overview on RL methods based on model [link](https://www.researchgate.net/figure/Classification-of-RL-algorithms_fig2_344441173)
