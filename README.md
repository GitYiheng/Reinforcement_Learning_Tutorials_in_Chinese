# Reinforcement_Learning_Tutorials_in_Chinese
# 强化学习中文教程

这个GitHub Repo是我个人在学习强化学习过程中所做的笔记，基本都是基于David Silver的讲义的 [1, 2]。

如果能帮助到正在学习的同学我会非常开心。

如果发现任何错误，欢迎issue或者联系我：gityiheng@gmail.com

# 索引

1. 马尔科夫决策过程（Markov Decision Process）：马尔科夫决策过程是强化学习框架中用来描述环境的模型。

2. 动态规划（Dynamic Programming）：动态规划用马尔科夫决策过程作为环境的模型，用策略评估和策略改进来得到基于最优价值函数的最优策略。

3. 无模型预测（Model-Free Prediction）：估计一个未知MDP的价值函数。用策略得出价值函数，也叫预测问题。

4. 无模型控制（Model-Free Control）：优化一个未知MDP的价值函数。用价值函数得出策略，也叫控制问题。

5. 价值函数近似（Value Function Approximation）：通过函数近似来用更少的参数来表示价值函数。

6. 策略梯度方法（Policy Gradient）：不借助价值函数而是直接对策略进行参数化和优化。

7. 学习和规划的整合（Integrating Learning and Planning）：把学习和规划整合到同一个框架中，包括基于价值的学习、基于策略的学习和基于模型的学习。

8. 探索与应用（Exploration and Exploitation）：在有限的资源中，在收集新信息和利用现有信息之间的权衡也是强化学习中的一个重要课题。

# 参考文献

1. http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html

2. https://www.youtube.com/watch?v=2pWv7GOvuf0

3. Sutton, R.S. and Barto, A.G., 1998. Reinforcement learning: An introduction. Cambridge: MIT press.

4. Szepesvári, C., 2010. Algorithms for reinforcement learning. Synthesis lectures on artificial intelligence and machine learning

5. https://github.com/dennybritz/reinforcement-learning
