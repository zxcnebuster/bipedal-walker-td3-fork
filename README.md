The assignment was to train a bipedal robot to learn to walk efficiently in a 2D physics simulation. It should be sample efficient, learning with the least amount of interaction with the environment as possible, and also it should learn to walk quickly—eventually running as quickly and smoothly as possible.


This paper investigates the effectiveness of Twin Delayed Deep Determin- istic Policy Gradient with Forward-looking mechanism (TD3-FORK) to control bipedal locomotion in the BipedalWalker-v3 environments. TD3- FORK extends the TD3 algorithm by incorporating predictions of future states and rewards, enabling more informed decision-making. The perfor- mance of two TD3-FORK variants is analysed: TD3-FORK-S, employing single-step future state and reward predictions, and TD3-FORK-DQ, us- ing a two-step future state prediction. Results show that TD3-FORK-S achieves stable convergence and solves the standard environment, while TD3-FORK-DQ solves the harder version of the environment.


Mark: 80/100
