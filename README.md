# Implementing-RL-DQN-algorithm-on-video-games

This project was done for academic purposes, in colaboration with my dear research fellow Vincent CANIPEL. For me the goal was to learn how to implement an RL algorithm. The code mainly follows the instructions given in this tutorial: https://www.youtube.com/watch?v=5fHngyN8Qhw
We adapted this algorithm in order to make it able to be used in two different games, based on different environment.
The algorithm is quite efficient for Lunar Lander.
Concerning Space Invader, the results are not that good. It could be explained by the low number of epochs set for such a complex game (even with such a low value the training lasted almost a day) and also the heavy size of the frames that are interpreted by the algorithm. Even though we reduced the size of the frames thanks to preprocessing techniques, it remains heavy.
