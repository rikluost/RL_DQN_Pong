# Pong RL DQN implementation

Teaching a machine to play an Atari game PONG using reinforcement learning, code adapted from (Geron 2019) and TF-Agents tutorials. The use of the code was to compare convergence performance with different optimizers, loss functions and replay buffer sizes.

The research and use of Reinforcement Learning (RL) algorithms have gained interest since the ground-breaking demonstration by DeepMind took place on 2013 (Mnih, et al., 2013). In that demonstration they showed how a deep learning model could learn to play 1970’s Atari 2600 games from the scratch. Not only did it learn to play the games, but its performance matched or surpassed the best human experts.

The jupyter notebook implementation here utilises TF-Agents RL library for Python, which can simulate various envi-ronments, such as Atari games. It is based on TensorFlow and is developed at Google.

Specific libraries:

- tensorflow, keras
- gym Atari environment (pip install gym[atari])

Software versions:

- Python 3.7.9
- TensorFlow 2.4

References:

- Mnih, V., Kavukcuoglu, K., Silver, D., Graves, A., Antonoglou, I., Wierstra, D., & Riedmiller, M. A. (2013). Playing atari with deep reinforcement learning CoRR, abs/1312.5602. Retrieved from http://arxiv.org/abs/1312.5602
- Geron, A. (2019). Hands-on machine learning with scikit-learn, keras, and tensorflow: Concepts, tools, and techniques to build intelligent systems (2nd ed.). O’Reilly UK Ltd.
- Sutton, R. S., & Barto, A. G. (2018). Reinforcement Learning: An Introduction (2nd ed.). Cambridge: MIT Press.
- Lillicrap, T., P., Hunt, J., Pritzel, A.,Heess, N., Erez, T., Tassa, Y., Silver, D., Wierstra, D. (2016 ) Continuous control with deep reinforcement learning. Retrieved from http://arxiv.org/abs/1509.02971 
- Zhang, S. & Sutton, R. S., 2017. A Deeper Look at Experience Replay. [Online] Available at: https://arxiv.org/abs/1712.01275
- Mnih, V. et al., 2015. Humanlevel control through deep reinforcement learning, s.l.: Nature, 518(7540):529–533.
- Lin, L. -J., 1992. Self-improving reactive agents based on reinforcement learning, planning and teaching., s.l.: 8(3-4):293–321.
- IUBH International University of Applied Sciences, 2020. Reinforcement Learning DLMAIRIL01. Erfurt: IUBH.
