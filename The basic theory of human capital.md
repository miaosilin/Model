---
title: Career Concerns
url: Career Concerns_url
tags: Labor Economics
categories: Notes ;Models
date:   2020-06-20

---

# Career Concerns

***Career concern:*** reasons to exert effort unrelated to current compensation, which is a common phenomenon in public sector

***more standard***: anticipation of future compensation



### Assumption:

1. the firm, the worker, and the market all share prior belief about η (thus there is no asymmetric information and adverse selection; 能力是确定值

2. they all observe $x_t$ each period.
3. only worker sees $a_t$ (moral hazard/hidden action).
4. no contracts contingent on output (and wages are paid at the beginning of each period).

### Two period

Output produced is equal to
$$
x_{t}=\underbrace{\eta}_{\text {ability }}+\underbrace{a_{t}}_{\text {effort }}+\underbrace{\varepsilon_{t}}_{\text {noise }} \quad t=1,2
$$
$a_{t} \in[0, \infty)$

$\varepsilon_{t} \sim \mathcal{N}\left(0,1 / h_{\varepsilon}\right)$,    h:precision（工作绩效准确程度,可从噪声中获得对能力的感知）

$\eta \sim \mathcal{N}\left(m_{0}, 1 / h_{0}\right)$， the prior on $\eta$ has a normal distribution with mean $m_{0}$

$\eta,\varepsilon_{1},\varepsilon_{2}$ are independent.

$x^{t-1}=\left\{x_{1}, \ldots, x_{t-1}\right\}$ is the history of his output realizations.

$w_{t}\left(x^{t-1}\right)$ is the wage of worker at time t given history $x^{t-1}$
$$
\begin{aligned}
w_{t}\left(x^{t-1}\right) &=\mathbb{E}\left(x_{t} | x^{t-1}\right) \\
&=\mathbb{E}\left(\eta | x^{t-1}\right)+a_{t}\left(x^{t-1}\right) 
\end{aligned}
$$
$a_{t}\left(x^{t-1}\right)$ is the effort that the agent will exert given history $x^{t-1}$

$a_{t}\left(x^{t-1}\right)$ is perfectly anticipated by the market along the equilibrium path.

Cost function is convex.$c^{\prime}(\cdot)>0, \quad c^{\prime \prime}(\cdot)>0$, $\quad c^{\prime}(0)=0$

Instantaneous utility function of the agent is
$$
u\left(w_{t}, a_{t}\right)=w_{t}-c\left(a_{t}\right)
$$
T period(for now T=2)
$$
U(w, a)=\sum_{t=1}^{T} \beta^{t-1}\left[w_{t}-c\left(a_{t}\right)\right]
$$
First best level of effort $a^{f b}$ again solves  $c^{\prime}\left(a^{f b}\right)=1$

So the world can be summarized as:
$$
\begin{array}{l}
\text { period } 1:\left\{\begin{array}{l}
\text { wage } w_{1} \\
\text { effort } a_{1} \text { chosen by the agent (unobserved) } \\
\text { output is realized } x_{1}=\eta+a_{1}+\varepsilon_{1}
\end{array}\right. \\
\text { period 2: }\left\{\begin{array}{l}
\text { wage } w_{2}\left(x_{1}\right) \\
\text { effort } a_{2} \text { chosen } \\
\text { output is realized } x_{2}=\eta+a_{2}+\varepsilon_{2}
\end{array}\right.
\end{array}
$$
Backward induction immediately implies
$$
a_{2}^{*}=0
$$

Therefore:
$$
\begin{aligned}
w_{2}\left(x_{1}\right) &=\mathbb{E}\left(\eta | x_{1}\right)+a_{2}\left(x_{1}\right) \\
&=\mathbb{E}\left(\eta | x_{1}\right)
\end{aligned}
$$
The problem is the estimation of $\eta$ given information  $x_{1}=\eta+a_{1}+\varepsilon_{1}$
The only difficulty is that $x_{1}$ depends on first period effort.
In equilibrium, the market will anticipate the correct level of effort $a_{1}$ （PBE中，可以预测出第一期努力程度,但市场预测的工人努力程度与工人真实努力程度存在误差）



Let the conjecture of the market be $\bar{a}_{1}$ （市场预测努力程度）

Define
$$
z_{1} \equiv x_{1}-\bar{a}_{1}= \eta+\varepsilon_{1}
$$
as the deviation of observed output from this conjecture.（市场预测的努力+噪音）

 Once we have $z_{1},$ standard normal updating formula implies that
$$
\eta | z_{1} \sim \mathcal{N}\left(\frac{h_{0} m_{0}+h_{\varepsilon} z_{1}}{h_{0}+h_{\varepsilon}}, \frac{1}{h_{0}+h_{\varepsilon}}\right)
$$

Interpretation:

1. 解释:我们从先验m0开始，根据z1中包含的信息更新h。我们赋予这个新信息的权重取决于它相对于之前信息的精确度。它的$h_\varepsilon$相对于$h_0$越大，新信息就越重要。)
2. 后验信息的方差将小于前验信息和新信息的方差)



Therefore, equilibrium wages satisfy
$$
w_{2}\left(x_{1}\right)=\frac{h_{0} m_{0}+h_{\varepsilon}\left(x_{1}-\bar{a}_{1}\right)}{h_{0}+h_{\varepsilon}}
$$
The optimization problem of the agent:
$$
\max _{a_{1}}\left[w_{1}-c\left(a_{1}\right)\right]+\beta\left[\mathbb{E}\left\{w_{2}\left(x_{1}\right) | \bar{a}_{1}\right\}\right]
$$
Substituting from above and dropping $w_{1}$

$$
\max _{a_{1}} \beta \mathbb{E}\left\{\frac{h_{0} m_{0}+h_{\varepsilon}\left(x_{1}-\bar{a}_{1}\right)}{h_{0}+h_{\varepsilon}} | \bar{a}_{1}\right\}-c\left(a_{1}\right)
$$
Important: both $\eta$ and $\varepsilon_1$ are uncertain to the agent as well as to the market.

Therefore
$$
\max _{a_{1}} \beta \mathbb{E}\left\{\frac{h_{0} m_{0}+h_{\varepsilon}\left(\eta+\varepsilon_{1}+a_{1}-\bar{a}_{1}\right)}{h_{0}+h_{\varepsilon}} | a_{1}\right\}-c\left(a_{1}\right)
$$


And since $a_{1}$ is not stochastic (the agent is choosing it), we have
$$
\max _{a_{1}} \beta \frac{h_{\varepsilon}}{h_{0}+h_{\varepsilon}} a_{1}-c\left(a_{1}\right)+\beta \mathbb{E}\left\{\frac{h_{0} m_{0}+h_{\varepsilon}\left(\eta+\varepsilon_{1}-\bar{a}_{1}\right)}{h_{0}+h_{\varepsilon}}\right\}
$$

The first-order condition is:（将后验信念设为一个值）
$$
c^{\prime}\left(a_{1}^{*}\right)=\beta \frac{h_{\varepsilon}}{h_{0}+h_{\varepsilon}}<1=c^{\prime}\left(a_{f b}\right)
$$

First result: equilibrium e¤ort is always less than first this.(非最优)

Reason: two "leakages" :(非社会最优的两个原因)

1. increases in output that the agent does not capture): the payoff from higher effort only occurs next period, therefore its value is discounted to $\beta,$（对努力的回报总是后一期支付）
2.  the agent only gets credit for a fraction $h_{\varepsilon} /\left(h_{0}+h_{\varepsilon}\right)$ of her effort, the part that is attributed to ability.（收到噪声的影响，新的信念总是会有所折扣）

The characterization of the equilibrium is completed by imposing $\bar{a}_{1}=a_{1}^{*}$, This was not necessary for computing $a_{1}^{*},$ but is needed for computing the equilibrium wage $w_{1}$ （计算均衡工资时，要考虑后验信念）

Recall that
$$
\begin{aligned}
w_{1} &=\mathbb{E}\left(y_{1} | \text { prior }\right) \\
&=\mathbb{E}(\eta)+\bar{a}_{1} \\
&=m_{0}+a_{1}^{*}
\end{aligned}
$$
We immediately obtain:
$$
\begin{array}{l}
\frac{\partial a_{1}^{*}}{\partial \beta}>0 \\
\frac{\partial a_{1}^{*}}{\partial h_{\varepsilon}}>0 \\
\frac{\partial a_{1}^{*}}{\partial h_{0}}<0
\end{array}
$$

1. Greater $\beta$ means that the agent discounts the future less, so exerts more effort because the first source of leakage is reduced（两期的关联越强（第一个leakage越弱），代理人更努力），

2. Greater $h_{\varepsilon}$ implies that there is less variability in the random component of performance. This, from the normal updating formula, implies that any given increase in performance is more likely to be attributed to ability, so the agent is more tempted to **jam the signal by exerting more effort**. （运气的噪音越大，说明任何给定的产出提升都更有可能归因于能力，因此agent更倾向于通过施加更多的努力来干扰信号）
3. The intuition for the negative effect of $h_{0}$ is similar.（能力的噪音越小，代理人就越不会努力，代理人就越没有动力去jam the signal）



###  Multiperiod Career Concerns(T = 3)



Considered the same model with three periods.
This model can be summarized by the following matrix
$$
\begin{array}{ll}
w_{1} & a_{1}^{*} \\
w_{2}\left(x_{1}\right) & a_{2}^{*} \\
w_{3}\left(x_{1}, x_{2}\right) & a_{3}^{*}
\end{array}
$$
With similar analysis to before, the first-order conditions for the agent are
$$
\begin{array}{c}
c^{\prime}\left(a_{1}^{*}\right)=\beta \frac{h_{\varepsilon}}{h_{0}+h_{\varepsilon}}+\beta^{2} \frac{h_{\varepsilon}}{h_{0}+2 h_{\varepsilon}} \\
c^{\prime}\left(a_{2}^{*}\right)=\beta \frac{h_{\varepsilon}}{h_{0}+2 h_{\varepsilon}}
\end{array}
$$
First result:

$$
a_{1}^{*}>a_{2}^{*}>a_{3}^{*}=0
$$


More generally, in the $T$ period model, the relevant first-order condition is
$$
c^{\prime}\left(a_{t}^{*}\right)=\sum_{\tau=t}^{T-1} \beta^{\tau-t+1} \frac{h_{\varepsilon}}{h_{0}+\tau h_{\varepsilon}}
$$
With $T$ sufficiently large, it can be shown that there exists a period $\bar{\tau}$ such that



In other words, workers work too hard when young and not hard enough when old -
compare assistant professors to tenured faculty.
important: these effort levels depend on the horizon (time periods), but not on past realizations.
$$
a_{t<\bar{\tau}}^{*} \geq a_{f b} \geq a_{t>\bar{\tau}}^{*}
$$
workers work too hard when young and not hard enough when old（年轻时太努力，年老时不够努力）

compare assistant professors to tenured faculty.（助理教师和老教师）

important: these effort levels depend on the horizon (time periods), but not on past realizations.（工作努力程度取决于时间范围（期数），而不是过去的成就）

当能力不是固定不变的，而是随着时间的推移而演变时，也会得出类似的结果。(只要它遵循一个正常的过程，这一期依据过去的能力，加一个噪声)。





