### Q

p123有如下的表述：

> Fortunately, GPI does not require that the policy be taken all the way to a greedy policy, only that it be moved toward a greedy policy.

这句话怎么理解？是否有严格的数学证明GPI的这种策略是收敛的？

### Q

non-greedy action的概率是$$\frac{\epsilon}{|\mathcal{A}(s)|}$$，是否应该为$$\frac{\epsilon}{|\mathcal{A}(s)|-1}$$？假设使得$$q(s,a)$$最大化的动作$$a$$只有一个的话？

### Q

使用greedy policy(ES)（注意不是$$\epsilon$$-greedy）复现书中的最优策略。