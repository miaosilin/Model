---
title: Investments in general and specific skills
url: Investments in general and specific skills_url
tags: Labor Economics
categories: Notes ;Models
date:   2020-06-22

---

# Investments in general and specific skills

Continued investment leads to earning growth.

What type of investment during the worker's career? Training.

***incomplete contracts***: 

1. Certain events are not (easily) observable by outside parties, in particular by courts. Therefore, writing contracts that are contingent on these nonveriable events might be impossible or too costly.
2. There is in multitude of future contingencies, and often even describing them is difficult.

## Assumption

A firm and a worker are matched together, and because of labour market frictions, they cannot switch partners, so wages are determined by **bargaining**.

- **The timing of events:**

- - The firm decides how much to invest, at the cost $rk$. 

  - The worker and the firm bargain over the wage $w$. 
  - If there is disagreement, the worker receives an outside wage $\bar{w}$ , and the firm produces nothing, so its payoff is $-rk$.

Bargaining can be represented by the Nash solution with asymmetric bargaining powers. 

**Equilibrium concept**: Subgame Perfect Nash Equilibrium------backward induction.



## Investments without Binding Contracts

$k$ is the amount of physical capital of the firm; 

$f(k)$ is the total output of the firm. Standard assumptions on $f$ : increasing, continuous and strictly concave.

The (asymmetric) Nash solution to bargaining between two players, $1$ and $2$, is given by maximizing 
$$
(payoff \left._{1}-\text { outside option }_{1}\right)^{\beta}\left(\text { payoff }_{2}-\text { outside option }_{2}\right)^{1-\beta}
$$

> 对称信息的纳什谈判解：$x^{N S}=\arg \max _{x \in X}\left(u_{1}(x)-d_{1}\right)\left(u_{2}(x)-d_{2}\right)$, 
>
> 不对称信息的纳什谈判解：$x^{N S}=\arg \max _{x \in X}\left(u_{1}(x)-d_{1}\right)^{\beta}\left(u_{2}(x)-d_{2}\right)^{1-\beta}$($\beta\in [0,1]$ is bargaining power of player 1)
>
> If both utilities are linear and defined over their share of some pie, and the set $X \subset \mathbb{R}^{2}$ is given by $x_{1}+x_{2} \leq 1$, then the solution to (1) is given by
> $$
> (1-\beta)\left(x_{1}-d_{1}\right)=\beta\left(x_{2}-d_{2}\right)
> $$
> with $x_{1}=1-x_{2},$ which implies the linear sharing rule:
> $$
> x_{2}=(1-\beta)\left(1-d_{1}-d_{2}\right)+d_{2}
> $$
>
> Intuitively, player 2 receives a fraction $1-\beta$ of the net surplus $1-d_{1}-d_{2}$ plus his outside option, $d_{2}$

In the context of the model here, the Nash bargaining solution amounts to choosing the wage, $w,$ so as to maximize:
$$
(f(k)-w)^{1-\beta}(w-\bar{w})^{\beta}
$$
The cost of investment, $r k,$ does not feature in this expression, since these **investment costs are sunk**.
In other words, the profits of the firm are $f(k)-w-r k,$ while its outside option is $-r k$, So the difference between payoff and outside option for the firm is $f(k)-w$



### Equilibrium

the wage resulting from the Nash solution will be
$$
w(k)=\beta f(k)+(1-\beta) \bar{w}
$$
This expression emphasizes the dependence of the equilibrium wage on the capital stock of the firm.(强调物质资本与外部选择).

Therefore, firm profits are:
$$
\begin{aligned}
\pi(k) &=f(k)-w(k)-r k \\
&=(1-\beta)(f(k)-\bar{w})-r k
\end{aligned}
$$

Profit maximization:
$$
(1-\beta) f^{\prime}\left(k^{e}\right)=r（次优）
$$

In comparison, the efficient level of investment that would have emerged in a competitive labor market, is given by
$$
f^{\prime}\left(k^{*}\right)=r（社会最优）
$$
The concavity of $f$ immediately implies that $k^{e}<k^{*},$ thus there will be underinvestment.（公司必须赚回之前给员工的学费，因此会减少员工培训后的工资）



### Underinvestment

> Because of bargaining, the firm is not the full residual claimant of the additional returns it generates by its investment.
> **Holdup problem**; once the firm invests a larger amount in physical capital, it is potentially "held up" by the worker. （公司会受到员工的敲竹杠）
>
> A fraction $\beta$ all the returns are received by the worker, since **the wage that the firm has to pay is increasing in its capital stock.**

Sign a contract of the form $w(k)$ before investment. This wage schedule would satisfy $w^{\prime}\left(k^{*}\right)=0$ and encourage the efficient level of investment.
This wage schedule would avoid the holdup problem.



## General Versus Specific Training

***Firm-specific training:*** Skills that will increase his or her productivity only with the current employer.

***General training:*** contribute to the worker's general human capital, increasing his productivity with a range of employers.

In practice actual training programs could (and often do) provide a **combination** of firm-specific and general skills.



### Stylized model (without discounting):

- At time $t=0,$ there is an initial production of $y_{0},$ and also the firm decides the level of training $\tau,$ incurring the cost $c(\tau) .$ Assume that $c(0)=0, c^{\prime}(0)=0, c^{\prime}(\cdot) \geq 0$ and $c^{\prime \prime}(\cdot)>0$（成本函数为凸）
- At time $t=1 / 2,$ the firm makes a wage offer $w$ to the worker, and other firms also compete for the worker's labor. The worker decides whether to quit and work for another firm (competitive labor markets: suppose that there are many identical firms who can use the general skills of the worker, and the worker does not incur any cost in the process of changing jobs $)$ 
- At time $t=1,$ there is the second and final period of production, where output is equal to $y_{1}+f(\tau),$ with $f(0)=0, f^{\prime}(\cdot)>0$ and $f^{\prime \prime}(\cdot)<0$ （生产函数是凹函数）



### First Best Training(firm specific training)

A social planner wishing to maximize net output would choose a positive level of training investment, $\tau^{*}>0,$ given by
$$
c^{\prime}\left(\tau^{*}\right)=f^{\prime}\left(\tau^{*}\right)
$$
The fact that $\tau^{*}$ is strictly positive immediately follows from the fact that $ c^{\prime}(0)=0 $ and  $f^{\prime}(0)>0$. 

There will be underinvestment in general training

Suppose the firm invests some amount $\tau>0 .$ For this to be profitable for the firm, at time $t=1,$ it needs to pay the worker at most a wage of
$$
w_{1}<y_{1}+f(\tau)-c(\tau)
$$

to recoup its costs. Assume that ***no costs of changing employer***

Despite the fact that a social planner would choose a positive level of training investment, $\tau^{*}>0,$ the pre-Becker view was that this economy would fail to invest in training.

The mistake in this reasoning was that it did not take into account the worker's incentives to invest in his own training.



### The Becker Model

First note that at $t=1,$ the worker will be paid $w_{1}=y_{1}+f(\tau)$;
 $\tau^{*}$ is the efficient level of training given by
$$
c^{\prime}\left(\tau^{*}\right)=f^{\prime}\left(\tau^{*}\right)
$$
In the unique subgame perfect equilibrium, in the first period the firm will offer the following package: training of $\tau^{*}$ and a wage of
$$
w_{0}=y_{0}-c\left(\tau^{*}\right)
$$
Then, in the second period the worker will receive the wage of
$$
w_{1}=y_{1}+f\left(\tau^{*}\right)
$$

either from the current firm or from another firm.

The efficient level of training will be achieved with firms bearing none of the cost of training, and workers financing training by taking a wage cut in the first period of employment（如果企业不承担培训成本，而工人在就业的第一阶段通过减薪来为培训提供资金，那么培训的效率就会提高）(可以通过反证法证明)

（第一期的工资低，掌握专业技术后第二期的工资高）

***Application:***

> some of the historical apprenticeship programs where young individuals worked for very low wages and then "graduated" to become master craftsmen; 
>
> pilots who work for the Navy or the Air Force for low wages, and then obtain much higher wages working for private sector airlines;
>
> securities brokers, often highly qualified individuals with MBA degrees, working at a pay level close to the minimum wage until they receive their professional certification; 
>
> or even academics taking an assistant professor job at Harvard despite the higher salaries in other departments.



### Training with Incomplete Contracts

***But*** the firm can't make a credible commitment to providing training in the amount of $\tau^{*}$

For example, the firm can pretend to offer the workers training , and them use them as cheap labour——incomplete contract.

（典型的敲竹杠，答应做了却没有实施，当做廉价劳动力使用，让人无可奈何）

- **The timing of events:**

- - At time $t=-1 / 2,$ the firm makes a training-wage contract offer $\left(\tau^{\prime}, w_{0}\right) .$ Workers accept offers from firms. 

  - At time $t=0,$ there is an initial production of $y_{0},$ the firm pays $w_{0}$ and also unilaterally decides the level of training $\tau,$ which could be different from the promised level of training $\tau^{\prime}$ 

  - At time $t=1 / 2,$ wage offers are made, and the worker decides whether to quit and work for another firm.

  -  At time $t=1,$ there is the second and final period of production, where output is equal to $y_{1}+f(\tau)$

    

完美(信贷和劳动力)市场的贝克尔模型和不完全契约(或严重信贷约束)的模型得出的一般结论是，一般培训不会有企业赞助的投资。这一结论是根据这两个模型的共同假设得出的，即劳动力市场是竞争性的，因此在雇佣关系后期，企业将永远无法收回其在一般技能方面的培训支出。但这也未必现实，在许多情况下，公司承担了一般培训投资的很大一部分(有时是全部)成本。

比如学徒计划，MBA第一年的培训等。



### Basic framework

Consider the following two-period model.

- In period $1,$ the worker and / or the employer choose how much to invest in the worker's general human capital, $\tau$
- There is no production in the first period. In period $2,$ the worker either stays with the firm and produces output $y=f(\tau),$ where $f(\tau)$ is a ***strictly increasing and concave function.***
- The worker is also paid a wage rate, $w(\tau)$ as a function of his skill level (training) $\tau$, or he quits and obtains an outside wage.
- The cost of acquiring $\tau$ units of skill is again $c(\tau),$ which is again assumed to be ***continuous, differentiable, strictly increasing and convex***, and to satisfy $c^{\prime}(0)=0$
- There is no discounting, and all agents are ***risk-neutral.***
- Assume that all training is technologically general in the sense that$f(\tau)$ is the same in all firms.
- If a worker leaves his original firm, then he will earn $v(\tau)$ （outside option）in the outside labor market.
- Suppose

$$
v(\tau)<f(\tau)
$$

​		That is, despite that fact that $\tau$ is general human capital, when the worker separates from the firm, he will get a lower wage than his marginal product in the current firm. 

- The fact that $v(\tau)<f(\tau)$ implies that there is ***a surplus*** that the firm and the worker can share when they are together. Also note that $v(\tau)<f(\tau)$ is ***only possible in labour markets with frictions***- otherwise, the worker would be paid his full marginal product, and $v(\tau)=f(\tau)$
- Let us suppose that this surplus will be divided by asymmetric Nash bargaining with worker bargaining power given by $\beta \in(0,1)$

$$
w(\tau)=v(\tau)+\beta[f(\tau)-v(\tau)]
$$

​		As usual, equilibrium wage rate $w(\tau)$ is ***independent*** of $c(\tau)$

- othe level of training is chosen first, and then the worker and the firm bargain over the wage rate; at this point the training costs are already sunk, so they do not feature in the bargaining calculations (***bygones are bygones***)
- Assume that $\tau$ is determined by the investments of the firm and the worker, who independently choose their contributions, $c_{w}$ and $c_{f},$ and $\tau$ is given by

$$
c(\tau)=c_{w}+c_{f}
$$

- Assume that $\$ 1$ investment by the worker costs $\$ p$ where $p \geq 1$ (提升1美元的产出对于工人的支出是p元 ，衡量工人的信贷约束)

- When $p=1,$ the worker has access to perfect credit markets and when $p \rightarrow \infty,$ the worker is severely constrained and cannot invest at all.

- The worker and the firm ***simultaneously decide*** their contributions to training expenses, $c_{w}$ and $c_{f}$ The worker receives an amount of training $\tau$ such that $c(\tau)=c_{w}+c_{f}$

- The firm and the worker ***bargain over the wage for the second period***, $w(\tau),$ where the threat point of the worker is the ***outside wage***, $v(\tau),$ and the threat point of the firm is ***not to produce***. 

- Production takes place.

- Given this setup, the contributions to training expenses $c_{w}$ and $c_{f}$ will be determined noncooperatively.（由双方效用最大化的选择决定）

  ### Equilibrium

- More specifically, the firm chooses $c_{f}$ to ***maximize profits***:
  $$
  \pi(\tau)=f(\tau)-w(\tau)-c_{f}=(1-\beta)[f(\tau)-v(\tau)]-c_{f}\\
  s.t. \quad c(\tau)=c_{w}+c_{f}
  $$

  The worker chooses $c_{w}$ to ***maximize utility***:
  $$
  u(\tau)=w(\tau)-p c_{w}=\beta f \mid(\tau)+(1-\beta) v(\tau)-p c_{f}\\
  s.t. \quad c(\tau)=c_{w}+c_{f}
  $$

  subject to the same constraint.

The first-order conditions are:
$$
\begin{array}{l}
(1-\beta)\left[f^{\prime}(\tau)-v^{\prime}(\tau)\right]-c^{\prime}(\tau)=0 \quad \text { if } c_{f}>0 \\
v^{\prime}(\tau) \mid+\beta\left[f^{\prime}(\tau)-v^{\prime}(\tau)\right]-p c^{\prime}(\tau)=0 \quad \text { if } c_{w}>0
\end{array}
$$
Inspection of these equations implies that generically, one of them will hold as a strict inequality, therefore, one of the parties will bear the full cost of training.

1. 完全竞争市场下，$c_f=0$，公司不会支付培训
2. $p \rightarrow \infty$时，工人信贷约束十分严重，无法通过信贷来培训
3. 一般情况，公司没有受到限制，所以一美元的培训支出对公司来说就是一美元

In contrast, suppose there are labor market imperfections, so that the outside wage is less than the productivity of the worker, that is
$$
v(\tau)<f(\tau)
$$
Gap between marginal product and market wage is not enough to ensure firm-sponsored investments in training.

Consider the case with no wage compression, that is the case in which a marginal increase in skills is valued appropriately in the outside market.
Mathematically this corresponds to
$$
v^{\prime}(\tau)=f^{\prime}(\tau) \text { for all } \tau
$$
Substituting for this in the first-order condition of the firm, 

 we immediately find that if $c_{f}>0,$ then $c^{\prime}(\tau)=0$
So in other words, there will be no firm contribution to training expenditures.（不存在***外部市场工资压缩***时，当外部选择与内部生产同比例增长的时候，公司还是不会支付培训费用。）

在***外部市场工资压缩***的情况下，公司愿意支付一部分一般培训费用。
$$
v^{\prime}(\tau)<f^{\prime}(\tau) 
$$
结论，公司从一个更熟练训练的工人那里获得了更多的支持，并有动力提高工人的技能。并且工资可以通过培训将外部的工资压缩部分转化为内部的工资压缩，可以比员工自己培训的公司要支付的工资低，也就是$w^{\prime}(\tau)<f^{\prime}(\tau)$（比外部市场少一点剥削，但还是有剥削）

<img src="https://cdn.mathpix.com/snip/images/OsFmdMXPAdM1QbbIFvuJb7xGDFsLmeHkk40z0JklwsA.original.fullsize.png" style="zoom: 50%;" />

***从压缩的工资结构出发，技能溢价与培训投入之间存在u型关系，进一步降低技能溢价可能会增加培训。但同时，培训到一定程度，由于工资压缩，工人接受培训的兴趣也在减少。***

上述讨论在外部汇报一定的情况下讨论，现在将$v(\tau)$内部化，讨论更一般的均衡；

## Basic Model of Adverse Selection and Training

不确定工人的外部选择$v(\tau)$，就会出现逆向选择问题：

### Timeline

- Firms make wage offers to workers. At this point, worker ability is unknown.
- Firms make training decisions, $\tau$
- Worker ability is revealed to the current employer and to the worker.
- Employers make second period wage offers to workers.
- Workers decide whether to quit.
- Outside firms compete for workers in the "secondhand" labor market. At this point, these firms observe neither worker ability nor whether the worker has quit or was laid off
- Production takes place.

### Equilibrium

（外部公司不知道工人的类型，是一个不完全信息动态博弈）

First, note that all workers will leave their current employer if outside wages are higher.

In addition, a fraction $\lambda$ of workers, irrespective of ability, realize that they form a bad match with the current employer, and leave whatever the wage is.
The important assumption here is that firms in the outside market observe neither worker ability nor whether a worker has quit or has been laid off.（外部公司社招时不确定工人的能力，也不能确定他离开公司是主动的还是被开除了）
However, worker training is publicly observed.

These assumptions ensure that in the second period each worker obtains his expected productivity conditional on his training.（公司只能通过数学期望估计工人的能力）

That is, his wage will be independent of his own productivity, but will depend on the average productivity of the workers who are in the second-hand labour market.（工人的工资不仅取决于自己的能力，还取决于整个市场的能力的平均水平）

By Bayes's rule, the expected productivity of a worker of training $\tau,$ is
$$
v(\tau)=\frac{\lambda p f(\tau)}{\lambda p+(1-p)}
$$
Anticipating this outside wage, the initial employer has to pay each high ability worker $v(\tau)$ to keep him. This observation, combined with (6), immediately implies that there is wage compression in this world, in the sense that
$$
v^{\prime}(\tau)=\frac{\lambda p f^{\prime}(\tau)}{\lambda p+(1-p)}<f^{\prime}(\tau)
$$

so the adverse selection problem introduces wage compression, and via this channel, will lead to firm-sponsored training.（逆向选择导致了二级劳动力市场的完美贝叶斯均衡必然存在工资压缩，并且通过这个渠道，公司可以进行一般技能培训）(所以社招的风险会更大)

Firm profits as a function of the training choice can be written as
$$
\pi(\tau)=(1-\lambda) p[f(\tau)-v(\tau)]-c(\tau)
$$

The first-order condition for the firm is
$$
\begin{aligned}
\pi^{\prime}(\tau) &=(1-\lambda) p\left[f^{\prime}(\tau)-v^{\prime}(\tau)\right]-c^{\prime}(\tau)=0 \\
&=\frac{(1-\lambda) p(1-p) f^{\prime}(\tau)}{\lambda p+(1-p)}-c^{\prime}(\tau)=0
\end{aligned}
$$
Main results follow from these conditions.

存在逆向选择的培训投资一定不是最优的。

1. a fraction $\lambda$ of the high ability workers quit, and the firm does not get any profits from them; 

2. even for the workers who stay, the firm is forced to pay them a higher wage, because they have an outside option that improves with their training,

3. i.e., $v^{\prime}(\tau)>0 .$ This reduces profits from training, since the firm has to pay higher wages to keep the trained workers.

公司有着不太完全的买方垄断势力，外部的工资压缩给了公司提供一般技能培训的动力。

***但培训也有其他的含义***：有组织政治的含义，效率工资的含义，应该多角度看待。

这种视角可能产生多重均衡：***低流动率低外部选择高公司一般技能培训，和高流动率高外部选择低公司一般技能培训（中国和美国）***



## Investment in Specific Training



Since bargaining will be ex post, holdup problems.（专用性培训有敲竹杠问题）

By investing in his firm-specific skills, the worker is increasing the firm's profits.（专用性投资最直接提升企业利润）

Therefore, the firm would like to encourage the worker to invest.（公司希望工人进行专用性投资）
However, given the timing of the game, wages are determined by a take-it-leave-it offer by the firm after the investment.
Therefore, holdup problem.（因此，就出现了敲竹杠的问题。）
since firm-specific skills difficult to verify, contractual solutions are imperfect.（因为公司的专用性投资很难被证实，该契约的解就不是最优的）

How can we improve the worker's investment incentives?
General solution: make worker's earnings conditional on specific skills.（一般的解决方法：让专用性培训成为收入提高的必要条件）
One imperfect but realistic solution: increase the bargaining power of the worker.（另一个现实的方法：提升工人的谈判能力）
For example, the firm may purposefully give access to some important assets to the worker（公司故意将重要资产给员工做抵押）
The firm may change its organizational form in order to make a credible commitment not to hold up the worker.（公司改变组织结构承诺不敲竹杠）
Alternative: the firm may develop a reputation for not holding up workers who have invested in firm-specific human capital.（公司建立不敲竹杠的声誉）

公司也不会选择最优的组织结构保证培训，因为要向员工保证不会敲竹杠，***公司考虑的是自身的利益，而不是和员工的总收入***

With these features, some jobs may play the role of stepping stones because they reveal information about the skills and productivity of the worker in a range on other jobs.（第一份工作可能是将来工作升职的垫脚石）

Workers quit not only because they have received bad news in their current job but also because they have learned about their ability and can therefore go and work for higher-quality jobs.

### Model

#### timeline

- At time $t=0,$ the worker decides how much to invest in firm-specific skills, denoted by $s,$ at the cost $\gamma(s) . \gamma(s)$ is strictly increasing and convex, with $\gamma^{\prime}(0)=0$（专用性投资的成本）
- At time $t=1,$ the firm makes a wage offer to the worker.
- The worker decides whether to accept this wage offer and work for this firm, or take another job.
- Production takes place and wages are paid.

Let the productivity of the worker be
$$
y_{1}+f(s)
$$
where $y_{1}$ is also what he would produce with another firm.
since $s$ is specific skills, it does not affect the worker's productivity in other firms.
First best:（最优水平）
$$
\gamma^{\prime}\left(s^{*}\right)=f^{\prime}\left(s^{*}\right)
$$
Suppose that the worker wage as a function of firm-specific skills is
$$
w_{1}(s)=y_{1}+\beta f(s)（给工人的分成比例）
$$

Now at time $t=0,$ the worker maximizes
$$
y_{1}+\beta f(s)-\gamma(s)
$$

Solution:
$$
\beta f^{\prime}(\hat{s})=\gamma^{\prime}(\hat{s})
$$

Here $\hat{s}$ is strictly positive, so giving the worker bargaining power has improved investment incentives.

However, $\hat{s}$ is also strictly less than the ***first-best investment level*** $s^{*}$

What about firm profits?
$$
\pi_{\beta}=(1-\beta) f(\hat{s})
$$
If the firm could choose (or manipulate) $\beta$ without constraints, then it would set $\bar{\beta}$ such that
$$
\frac{\partial \pi_{\beta}}{\partial \beta}=0=-f(\hat{s}(\bar{\beta}))+(1-\bar{\beta}) f^{\prime}(\hat{s}(\bar{\beta})) \frac{d \hat{s}(\bar{\beta})}{d \beta}
$$

where $\hat{s}(\beta)$ and $d \hat{s} / d \beta$ are given by the first-order condition of the worker, (10) The firm would certainly choose $\bar{\beta}<1$, since with $\bar{\beta}=1$, we could never have $\partial \pi_{\beta} / \partial \beta=0$（公司不会给工人全部的培训收入，因为如果这样，公司就不赚钱，没有激励投资培训）

But $\beta=1$ would maximize firm-specific skills.
The reason why the firm would not choose the structure of organization that achieves the best investment outcomes is that it cares about its own profits, not total income or surplus.（企业之所以不选择能够获得最佳投资结果的组织结构，是因为企业关心的是自身的利润，而不是总收入或盈余。）

也可以考虑给工人一定的股权，sell the firm

### Promotions

An alternative arrangement to encourage workers to invest in firm-specific skills is to design a ***promotion scheme***.
Consider the following setup.
Suppose that there are two investment levels, $s=0,$ and $s=1$ which $\operatorname{costs} c$
Suppose also that at time $t=1,$ there are two tasks in the firm, difficult and easy, D and E.
Assume outputs in these two tasks as a function of the skill level are
$$
y_{D}(0)<y_{E}(0)<y_{E}(1)<y_{D}(1)
$$

Therefore, ***skills are more useful in the difficult task***, and ***without skills the difficult task is not very productive.***

Now imagine the firm chooses the wage structures such that
$$
y_{D}(1)-y_{E}(1)>w_{D}-w_{E}>c
$$
and then ***ex post decides whether the worker will be promoted***.
Again by backward induction, we have to look at the decisions in the final period of the game.

When it comes to the promotion decision, and the worker is unskilled, the firm will naturally choose to allocate him to the easy task (***his productivity is higher in the easy task and his wage is lower***)
If the worker is skilled, and the firm allocates him to the easy task, his profits are $y_{E}(1)-w_{E}$
If it allocates him to the difficult task, his profits are $y_{D}(1)-w_{D}$

The wage structure in (11) ensures that profits from allocating him to the difficult task are higher.

Therefore, with this wage structure the firm has **made a credible commitment to pay the worker a higher wage if he becomes skilled**, because it will find it profitable to promote the worker

Next, going to the investment stage, the worker realizes that when he does not invest he will receive $w_{E},$ and when he invests, he will get the higher wage $w_{D}$
since, again by $(11), w_{D}-w_{E}>c,$ the worker will find it profitable to undertake the investment.



### Labour Market Learning and Mobility

***很大程度上，专有性投资可以视为自己目前工作的匹配程度（人岗匹配）***

Important idea: firm-specific skills are (at least in part) ***a manifestation of the quality of the match*** between a worker and his job.

Moreover, jobs are ***"experience goods,***" meaning that workers can only find out whether they are a good match to a job (and to a firm) by working in that firm and job. Therefore, this type of learning does not take place immediately.

These ideas captured by learning and matching models :

Let the (population) ***probability that the worker is a good match*** be
$$
\mu_{0} \in(0,1)
$$
A worker in any given job can generate one of two levels of output, 

> high, $y_{h},$ and low $y_{l}<y_{h}$              good match $\rightarrow y_{h} \quad$ with probability $p$
>                                                                                        $y_{l} \quad$ with probability $1-p$
> and                                                    bad match $\rightarrow \begin{array}{cc}y_{h} & \text { with probability } q \\ y_{l} & \text { with probability } 1-q\end{array}$


$$
p>q
$$
Consider a worker with belief $\mu$
If this worker produces output $y_{h},$ then Bayes's rule implies that his posterior (belief) next period should be（根据所观察到的行为依据贝叶斯法则做信息更新）
$$
\mu_{h}^{\prime}(\mu) \equiv \frac{\mu p}{\mu p+(1-\mu) q}>\mu
$$
Similarly, following an output realization of $y_{1},$ the belief of the worker will be
$$
\mu_{l}^{\prime}(\mu) \equiv \frac{\mu(1-p)}{\mu(1-p)+(1-\mu)(1-q)}<\mu
$$

Finally, let us also assume that every time a worker changes jobs, he has to incur a training or mobility cost equal to $\gamma \geq 0$

Under these assumptions, we can write the net present discounted value of a worker with belief $\mu$ recursively using simple dynamic programming arguments.（可以算一个工人收入的净现值）（工人可以预测自己产生高绩效的可能性，以及高绩效概率带来的工资的一生收入折现）
$$
\begin{aligned}
V(\mu)=& w(\mu)+\beta\left[(\mu p+(1-\mu) q) V\left(\mu_{h}^{\prime}(\mu)\right)\right.\\
&+(\mu(1-p)+(1-\mu)(1-q)) \times 
\max \left\{V\left(\mu_{l}^{\prime}(\mu)\right) ; V\left(\mu_{0}\right)-\gamma\right\}
\end{aligned}
$$
An immediate result from dynamic programming is that if the instantaneous reward function, here $w(\mu),$ is strictly increasing in the state variable, which here is the belief $\mu$
Therefore, the value function $V(\mu)$ is strictly increasing.
This implies that there will exist some cutoff level of belief $\mu^{*}$ such that workers will stay in their job as long as
$$
\mu \geq \mu^{*}
$$
and they will quit if $\mu<\mu^{*}$

 Let $\bar{\mu}=\inf \left\{\mu: \mu_{\prime}^{\prime}(\mu)>\mu^{*}\right\} （下确界）.$ Then a worker with beliefs $\mu>\bar{\mu}$ will not quit irrespective of the realization of output.
Workers with beliefs $\mu \in\left[\mu^{*}, \bar{\mu}\right]$ will **quit the job if he generates low output.**（觉得自己不太匹配的工人，一产出低就会觉得自己不适合这份工作，就可能辞职）

Provided that $\mu_{0} \in(0,1), \mu$ will never converge to 0 or 1 in finite time. Therefore, a worker who generates high output will have higher wages in the following period, and a worker who generates low output will have lower wages in the following period. Thus, in this model worker wages will move with past performance.
It can be easily proved that if $\gamma=0$, then $\mu^{*}=\mu_{0} .$ This implies that when $\gamma$ is equal to 0 or is very small, a worker who starts a job and generates low output will quit immediately. Therefore, as long as $\gamma$ is not very high, t***here will be a high likelihood of separation in new jobs.***（如果离职成本很低的话他们就离职了）
Next consider a worker who has been in a job for a long time. Such workers will on average have high values of $\mu,$ since they have never experienced (on this job) a belief less than $\mu^{*}$. This implies that the average value of their beliefs must be high. Therefore, workers with long tenure are unlikely to quit or separate from their job.（做一份工作长时间的人，对自己的good match的信念较高，就不太可能离职）

长期工作的工人工资不会有很大的变化。相比之下，刚开始工作的工人工资变异性更大。

#### What will happen to wages when workers quit?

If $\gamma=0$, wages will necessarily fall when workers quit (since before they quit $\left.\mu>\mu_{0}, \text { whereas in the new job } \mu=\mu_{0}\right(如果离职成本为零，人们会换到自己匹配的工作，即使牺牲一定工资))$
If, on the other hand, $\gamma$ is non-infinitesimal, （如果离职成本不是无穷小，他们会等到有足够收入了再换更匹配的工作）workers will experience a wage gain when they change jobs, since in this case $\mu^{*}<\mu_{0}$ because they are staying in their current job until this job is sufficiently unlikely to be a good match.
This last prediction is also consistent with the data, where ***on average workers who change jobs experience in increase in wages.***