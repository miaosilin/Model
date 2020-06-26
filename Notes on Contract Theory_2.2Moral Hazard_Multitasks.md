---
title: Notes on Contract Theory_3.1Moral Hazard_Multiple agents
url: Notes on Contract Theory_3.1Moral Hazard_Multiple agents_url
tags: Contract Theory
categories: Notes ;Models
date:   2020-06-20
---

*Silin Miao*

*Renmin University of China*

*miaosilin@ruc.edu.cn*



# Moral Hazard_Multiple agents1

广义团队生产问题; hierarchy; 合作，监督，合谋，晋升

1. ***Unobservable individual output:*** output produced by the agents is a single aggregate output $Q$ with conditional distribution $F(Q|a)$ 

   （团队生产：观测不到个人产出，只能观测到总产出）

2. ***Observable individual output:*** each agent produces an individual output $q_i$ which imperfectly correlated with the other agents' outputs.

   （松散团队：能够观测到个人产出，但是个人产出相互关联：解决方法：相对绩效评价RPE(tournament）

## Unobservable individual outputs: free-ride problem

$P$: principal;    $A$: agent;    $x_i$: production of agent $i$;    $a\in A$: effort of agent $A$;    $c(a)$ is convex; $c'>0, $ $ c''\le0$ ;

all utilities are VNM formula;     $\underline U$ is $A$'s preserved utility;    $Q$ aggregate output 

### 证明“三个和尚没水喝”：

Consider a risk neutral principal engaged in a contractual relation with $n$ risk neutral agents, which produce some deterministic aggregate output $Q=Q\left(a_{1}, a_{2}, \ldots, a_{n}\right)$ by a vector of individual hidden efforts $a=\left(a_{1}, a_{2}, \ldots, a_{n}\right)$.  Suppose that 
$$
\frac{\partial Q}{\partial a_{i}}>0, \quad \frac{\partial^{2} Q}{\partial a_{i}^{2}}<0 , \frac{\partial^{2} Q}{\partial a_{i} \partial a_{j}}>0
$$
 It means that different agents' efforts are complementary（团队中每个人的努力是互补的）. 

Agent's utility function is
$$
U=u_{i}\left(w_{i}\right)-c_{i}\left(a_{i}\right) .
$$
 Define a partnership to be a vector of output-contingent compensations for each agent: ​
$$
w(Q)=\left(w_{1}(Q), w_{2}(Q), \ldots, w_{n}(Q)\right) \\
\sum w_{i}(Q)=Q（每个人知道他人的努力，愿意分享Q）
$$
Here， assume that principals compete for agents(合伙制企业，所有代理人都是老板，把Q分完）.

The first-best vector of effort is uniquely defined by（社会最优$a^*$）

$$
a_{i}^{*} \in \arg \max Q\left(a^{*}\right)-\sum c_{i}\left(a_{i}^{*}\right) \\
\Rightarrow \frac{\partial Q\left(a^{*}\right)}{\partial a_{i}}=c_{i}^{\prime}\left(a_{i}^{*}\right)
$$

In Nash equilibrium under asymmetric information, each agent's optimal effort（非社会最优$a^{NE}$：信息不对称/不考虑转移支付）

$$
\begin{array}{l}
a_{i}^{N E} \in \arg \max w_{i}(Q)-c_{i}\left(a_{i}^{N E}\right)（每个人不知道他人的努力，因此只在乎自己的利益） \\

\Rightarrow \frac{d w_{i}(Q)}{d Q} \frac{\partial Q}{\partial a_{i}}=c_{i}^{\prime}\left(a_{i}^{N E}\right)
\end{array}
$$
The expression $(7)$ indicates that only if each agent gains full marginal return from his (optimal) effort $a_{i}^{*},$ the efforts level with Nash equilibrium will attain the first-best efforts level.（反证法证明纳什均衡努力水平小于社会最优努力水平）
Formally it requires that
$$
\frac{d w_{i}(Q)}{d Q}=1 \Rightarrow w_{i}(Q)=Q（每个人付出努力就要得到全部的产出，需要n个Q，然而只有1个Q）
$$

But it contradicts the budget constraint condition that $\sum w_{i}(Q)=Q,$ so the firs best can't

$$
\text { reach and } a_{i}^{N E}<a_{i}^{*}
$$

### Budget breakier------Holmstrom contract

If we introduces a budget breaker into the organization, who pay each agent $w_{i}(Q)=Q,$ there exists a Nash equilibrium where all agents supply their fist-best efforts and the third party-residual claimant pays out $n Q\left(a^{*}\right)$ in equilibrium. 

It requires that each agent make an up-front payment $z_{i}$ to the budget breaker such that（若有老板愿意付nQ，可达社会最优，需代理人提前交租金z）
$$
(P I R) \sum z_{i}+Q\left(a^{*}\right) \geq n\left(Q^{*}\right) \Rightarrow \sum z_{i}-(n-1) Q\left(a^{*}\right) \geq 0 （委托人参与约束）\\
(\mathrm{AIR}) \quad z_{i} \leq Q\left(a^{*}\right)-c_{i}\left(a_{i}^{*}\right) \Rightarrow Q\left(a^{*}\right)-\sum c_{i}\left(a_{i}^{*}\right) \geq \sum z_{i}-(n-1) Q\left(a^{*}\right) （代理人参与约束）
$$
Hence we can rewrite AIR as
$$
Q\left(a^{*}\right)-\sum c_{i}\left(a_{i}^{*}\right) \geq \sum z_{i}-(n-1) Q\left(a^{*}\right) \geq 0
$$

It means that the first best attains, so the Holmstrom contract is a profitable contract.（预算打破者/剩余索取者可实现社会最优）

#### Comment

Holmstrom's breaker is very different from Alchian-Demsetz's residual claimant, who participates in production activities in firm.

霍尔姆斯特伦契约在现实中并不真实，因为如果预算约束达到平衡，他将一无所得;如果公司或团队表现得比最好时好，他将得到负报酬。实际上，为了保持预算平衡，委托人必须向代理人支付两部分边际努力——对作出努力的代理人的全部边际贡献和对其他代理人的剩余边际贡献。此外，它要求代理人有足够的财富，但若如此，代理人就自己干了。

### Mirrlees contract


The contract is

$$
\left\{\begin{array}{l}
b_{i}, \text {if } Q=Q\left(a^{*}\right) \\
k（惩罚） , \text { otherwise}
\end{array}\right\} \text { and } k \geq c_{i}\left(a_{i}^{*}\right)-b_{i} \text { for all } i（连坐机制）
$$
There indeed exists a Nash equilibrium where all agents supply their first-best efforts under this contract, which assure $k=0$ and $\sum b_{i} \geq \sum c_{i}\left(a_{i}^{*}\right)$ (Pareto condition). And if $Q\left(a^{*}\right) \geq \sum b_{i},$ the budget breaker has incentive to implement the contract. 

The Mirrlees contract is equivalent to a debt contract, where $D=Q\left(a^{*}\right)-\sum b_{i}$

连坐的惩罚机制倒逼团队生产达到社会最优，相当于债务契约。

#### Comments

Although the Mirrlees contract is more realistic than the Holmstrom contract, and needn't huge wealth for agents, it is vulnerable to an important weakness-multiple equilibria.（1. 欺负老实人；2. 每个人平均努力；都是纳什均衡）

 For example, if some agents shirk, other agents have to burden all the work to avoid penalties. Extremely, if all other agents do nothing, the agent $i$ has to do all the work in order to provide $Q\left(0, \ldots, \hat{a}_{i}, \ldots, 0\right)=Q\left(a^{*}\right) .$ But the Holmstrom contract has no the problem.

会导致欺负老实人的行为，解决方法是利用老乡，或声誉或非正式组织来约束。



