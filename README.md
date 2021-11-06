# MultiarmedBandit
Lets say there is an array of slot machines that each return rewards according to different distributions. You may repeatedly choose a slot machine, observe the reward, and gain the reward. With a finite number of selections, how do you maximize reward?

The problem is fundamentally about a tradeoff between exploitation and exploration. On the one hand, you want to choose slot machines that you have observed return high rewards in the past. On the other hand, you want to test new slot machines that may have even greater rewards.

MAB.ipynb simulates this problem and implements the UCB algorithm as a solution to this problem. The idea is to balance exploitation and exploration by choosing the slot machine that maximizes a function with one term indicating the observed quality and one term indicating the relative previous exploration of that slot machine.
