# rlpack-tf

This repository contains implementations of some reinforcement learning algorithms. The pytorch version of rlpack is [here](https://github.com/jfpettit/rl-pack) but it is targeted mainly at simplicity and clarity so that beginners can easily understand the code. rlpack-tf focuses more on performance, but also still tries to maintain readability. Much of the code is inspired by OpenAI's SpinningUp [course](https://spinningup.openai.com/en/latest/index.html). In the future, I'll update it for [TensorFlow 2.0](https://www.tensorflow.org/) and for the resulting update of DeepMind's Sonnet [library](https://sonnet.readthedocs.io/en/latest/).

Currently this code includes implementations of [Advantage Actor Critic (A2C)](https://openai.com/blog/baselines-acktr-a2c/) and [Proximal Policy Optimization (PPO)](https://openai.com/blog/openai-baselines-ppo/). The SpinningUp page also includes clear, concise algorithm explanations. 

In the future, I'll likely extend this library to include [Deep Deterministic Policy Gradients (DDPG)](https://arxiv.org/abs/1509.02971), [Twin Delayed DDPG (TD3)](https://spinningup.openai.com/en/latest/algorithms/td3.html) and [Soft Actor Critic (SAC)](https://spinningup.openai.com/en/latest/algorithms/sac.html). However, there is no schedule for when these algorithms will be released. 

## Installation

You can install rlpack-tf with the following:

```
git clone https://github.com/jfpettit/rlpack-tf.git
cd rlpack-tf
pip install -e .
```


