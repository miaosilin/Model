---
title: Notes on Contract Theory_1.1Moral Hazard_Single Task
url: Notes on Contract Theory_1.1Moral Hazard_Single Task_url
tags: Contract Theory
categories: Notes ;Models
date:   2020-06-20
---

# Moral Hazard_Single Task

Moral hazard: hidden action

## 2.1.1 Standard model: symmetric information

$P$: principal;    $A$: agent;    $x_i$: production of agent $i$;    $a\in A$: effort of agent $A$;    $c(a)$ is convex; $c'>0, $ $ c''\le0$ ;

all utilities are VNM formula;     $\underline U$ is $A$'s preserved utility



$P$'s object function: $ V(x,w)=v(x-w)$                          $v'>0,  v''\le0$  concave

$A$'s object function: $U(w,a) = u(w)-c(a)$                     $u'>0,u''\le0$ concave



 $P$'s mathematic program: 
$$
\begin{align}
\max \limits_{\{a,w(x_i)\}}\sum_{i=1}^np_i(a)v(x_i-w(x_i)) \\
s.t. \sum_{i=1}^np_i(a)u(w(x_i))-c(a)\ge\underline U 
\end{align}
$$
The lagrange function:
$$
\underset{\left.a, w\left(x_{i}\right)\right\}}{\operatorname{Max}} \sum_{i=1}^{n} p_{i}(a) v\left(x_{i}-w\left(x_{i}\right)\right)+\lambda\left[\sum_{i=1}^{n} p_{i}(a) u\left(w\left(x_{i}\right)\right)-c(a)-\underline{U}\right]
$$
According to concave program's rule 
$$
\lambda = \frac{v'(x_i-w^{FB}(x_i))}{u'(w^{FB}(x_i))}, i\in \{1,2,...,n\}
$$


$r_P$ and $r_A$ is  $P$'s and $A$'s Arrow-Pratt meassure of absolute risk aversion respectively, The bigger r is, the more risk averse principal/agent is 
$$
\frac{dw^{FB}}{dx_i}=\frac{r_P}{r_P+r_A}
$$

1. $r_P=0,r_A>>0,\frac{dw}{dx}=0$, fixed wage

2. $r_A=0,\frac{dw}{dx}=1$, A get all marginal production

3. The bigger $r_A$ is ,the bigger proportion of fixed wage is.

   

### Proposition : 

1. If P is risk neutral and A is risk averse, P should offer A constant wage provide full insurance;

   	2. If A is risk neutral and P is risk averse, P should sell his firm to A at a certain price;
      	3. If both P and A are risk neutral, P should sell his firm to A;
         	4. If both P and A are risk averse, they  share risk according to a certain proportion. Proposition 1-3 are special case of proposition 4.

## 2.1.2 Standard model: asymmetric information

$a \in\left\{a^{H}, a^{L}\right\}, c\left(a^{H}\right)>c\left(a^{L}\right)$

 $$ for all the $k=1,2, \ldots, n-1$  

$$
\sum_{i=1}^{k} p_{i}^{H}<\sum_{i=1}^{k} p_{i}^{L} \\
\sum_{i=1}^{n} p_{i}^{H}=\sum_{i=1}^{n} p_{i}^{L}=1
$$
代理人A的激励相容约束（IC)
$$
\sum_{i=1}^{n} p_{i}^{H} u\left(w\left(x_{i}\right)\right)-c\left(a^{H}\right) \geq \sum_{i=1}^{n} p_{i}^{L} u\left(w\left(x_{i}\right)\right)-c\left(a^{L}\right)  \\
\Rightarrow \sum_{i=1}^{n}\left(p_{i}^{H}-p_{i}^{L}\right) u\left(w\left(x_{i}\right)\right) \geq c\left(a^{H}\right)-c\left(a^{L}\right)
$$
So, the $P^{\prime}$ 's problem is
$$
\operatorname{Max}_{w\left(x_{i}\right)} \sum_{i=1}^{n} p_{i}^{H} v\left(x_{i}-w\left(x_{i}\right)\right) \\
\text {s.t. }(\mathrm{IR}) \sum_{i=1}^{n} p_{i}^{H}(a) u\left(w\left(x_{i}\right)\right)-c\left(a^{H}\right) \geq \underline{U}\\
(\mathrm{IC}) \sum_{i=1}^{n}\left(p_{i}^{H}-p_{i}^{L}\right) u\left(w\left(x_{i}\right)\right) \geq c\left(a^{H}\right)-c\left(a^{L}\right)
$$
According to concave program's rule
$$
\frac{v^{\prime}\left(x_{i}-w\left(x_{i}\right)\right)}{u^{\prime}\left(w\left(x_{i}\right)\right)}=\lambda+\mu\left(1-\frac{p_{i}^{L}}{p_{i}^{H}}\right)
$$
信息不对称会带来更高成本的激励，低于社会最优水平
$$
\beta=\frac{1}{1+r b \sigma^{2}}
$$


$\beta$：提成比例； r：风险规避程度； b努力的边际成本（b越大表明能力越低）；  $\sigma^2$产出的方差

