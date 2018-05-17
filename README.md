# Reinforcement_Learning_Tutorials_in_Chinese
# 强化学习中文教程

这个GitHub Repo是我个人在学习强化学习过程中所做的笔记。

如果发现任何错误或者有任何的建议，欢迎issue或者联系我：gityiheng@gmail.com 或者 yiheng.zhu@bristol.ac.uk

# 索引

## 1. 强化学习基础（David Silver版本）

1.1. 马尔科夫决策过程（Markov Decision Process）：马尔科夫决策过程是强化学习框架中用来描述环境的模型。

1.2. 动态规划（Dynamic Programming）：动态规划用马尔科夫决策过程作为环境的模型，用策略评估和策略改进来得到基于最优价值函数的最优策略。

1.3. 无模型预测（Model-Free Prediction）：估计一个未知MDP的价值函数。用策略得出价值函数，也叫预测问题。

1.4. 无模型控制（Model-Free Control）：优化一个未知MDP的价值函数。用价值函数得出策略，也叫控制问题。

1.5. 价值函数近似（Value Function Approximation）：通过函数近似来用更少的参数来表示价值函数。

1.6. 策略梯度方法（Policy Gradient）：不借助价值函数而是直接对策略进行参数化和优化。

1.7. 学习和规划的整合（Integrating Learning and Planning）：把学习和规划整合到同一个框架中，包括基于价值的学习、基于策略的学习和基于模型的学习。

1.8. 探索与应用（Exploration and Exploitation）：在有限的资源中，在收集新信息和利用现有信息之间的权衡也是强化学习中的一个重要课题。

### 强化学习基础参考文献

1. David Silver的讲义：http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html

2. David Silver在UCL的视频课程：https://www.youtube.com/watch?v=2pWv7GOvuf0

3. Sutton, R.S. and Barto, A.G., 1998. Reinforcement learning: An introduction. Cambridge: MIT press.

4. 基础强化学习问题和代码的简单实现：https://github.com/dennybritz/reinforcement-learning

5. Szepesvári, C., 2010. Algorithms for reinforcement learning. Synthesis lectures on artificial intelligence and machine learning

## 2. 强化学习重要算法

2002 - Natural Policy Gradient

### 强化学习参考文献

1. Kakade, S.M., 2002. A natural policy gradient. In Advances in neural information processing systems (pp. 1531-1538).

## 3. 深度强化学习

Deep Reinforcement Learning that Matters (2017)：深度强化学习算法实验的可再现性（可重复性）和规范操作。

### 深度强化学习编年史

2013 - Deep Q-Networks (DQN)：从高维视觉输入中直接学习控制策略。

2015 - Trust Region Policy Optimization (TRPO)：具有可扩展性并且可以优化大规模非线性策略，这两点都是之前的无模型策略搜索难以实现的。

2015 - Deep Deterministic Policy Gradient (DDPG)：解决了DQN无法处理的动作空间是连续的问题。

2016 - Asynchronous Advantage Actor-Critic (A3C)：在多核CPU上实现异步强化学习，实现与基于GPU的experience replay类似的稳定更新效果。

2016 - Actor-Critic with Experience Replay (ACER)

2017 - Hindsight Experience Replay (HER)

2017- Proximal Policy Optimization (PPO)：PPO只用一阶优化方法就取得了TRPO的数据效率和可靠的性能。

2017 - Actor-Critic using Kronecker-Factored Trust Region (ACKTR)

### 深度强化学习参考文献

1. Arulkumaran, K., Deisenroth, M.P., Brundage, M. and Bharath, A.A., 2017. A brief survey of deep reinforcement learning. arXiv preprint arXiv:1708.05866.

2. Henderson, P., Islam, R., Bachman, P., Pineau, J., Precup, D. and Meger, D., 2017. Deep reinforcement learning that matters. arXiv preprint arXiv:1709.06560.

3. Kober, J., Bagnell, J.A. and Peters, J., 2013. Reinforcement learning in robotics: A survey. The International Journal of Robotics Research, 32(11), pp.1238-1274.

4. Mnih, V., Kavukcuoglu, K., Silver, D., Graves, A., Antonoglou, I., Wierstra, D. and Riedmiller, M., 2013. Playing atari with deep reinforcement learning. arXiv preprint arXiv:1312.5602.

5. Schulman, J., Levine, S., Abbeel, P., Jordan, M. and Moritz, P., 2015, June. Trust region policy optimization. In International Conference on Machine Learning (pp. 1889-1897).

6. Lillicrap, T.P., Hunt, J.J., Pritzel, A., Heess, N., Erez, T., Tassa, Y., Silver, D. and Wierstra, D., 2015. Continuous control with deep reinforcement learning. arXiv preprint arXiv:1509.02971.

7. Mnih, V., Badia, A.P., Mirza, M., Graves, A., Lillicrap, T., Harley, T., Silver, D. and Kavukcuoglu, K., 2016, June. Asynchronous methods for deep reinforcement learning. In International Conference on Machine Learning (pp. 1928-1937).

8. Kakade, S.M., 2002. A natural policy gradient. In Advances in neural information processing systems (pp. 1531-1538).

9. Wang, Z., Bapst, V., Heess, N., Mnih, V., Munos, R., Kavukcuoglu, K. and de Freitas, N., 2016. Sample efficient actor-critic with experience replay. arXiv preprint arXiv:1611.01224.

10. Andrychowicz, M., Wolski, F., Ray, A., Schneider, J., Fong, R., Welinder, P., McGrew, B., Tobin, J., Abbeel, O.P. and Zaremba, W., 2017. Hindsight experience replay. In Advances in Neural Information Processing Systems (pp. 5048-5058).

11. Schulman, J., Wolski, F., Dhariwal, P., Radford, A. and Klimov, O., 2017. Proximal policy optimization algorithms. arXiv preprint arXiv:1707.06347.

12. Wu, Y., Mansimov, E., Grosse, R.B., Liao, S. and Ba, J., 2017. Scalable trust-region method for deep reinforcement learning using Kronecker-factored approximation. In Advances in neural information processing systems (pp. 5285-5294).

13. https://github.com/openai/baselines

14. http://rll.berkeley.edu/deeprlcourse/

# 安装Jupyter Notebook

```bash
pip3 install --upgrade pip
pip3 install jupyter
```

打开命令窗口，输入`jupyter notebook`打开Jupyter。
