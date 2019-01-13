I began by trying to train a single agent under various noise settings. Under every setting, the agent destabilized after
a brief period of learning. The first agent I trained was under the base noise settings, with theta = 0.15 and sigma = 0.2.

![](uploads/dot15dot2.png)

The second time, I tried to altered the noise settings by increasing theta to 0.75 and decreasing sigma to 0.1.

![](uploads/dot75dot1.png)

The third time, theta was set to 0.3, a small increase from the original noise settings, and sigma was kept at the original 
0.2

![](uploads/dot3dot2.png)

Though it still failed like the others, the variance that the noise distribution caused looked more promising. There are 
several points on the plot where it looks as if the agent has discovered some new policy that it wants to build on and 
transition to. It reaches higher than the other two noise settings before falling off. I then used these noise settings to
train 20 agents simultaneously.

![](uploads/dot3dot2twenty.png)
