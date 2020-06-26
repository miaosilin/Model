---
title: Notes on Contract Theory_2.2Moral Hazard_Multitasks
url:Notes on Contract Theory_2.2Moral Hazard_Multitasks_url
tags: Contract Theory
categories: Models
date:   2020-06-23
---

*Silin Miao*

*Renmin University of China*

*miaosilin@ruc.edu.cn*



# Moral Hazard_Multitasks

***Trade off***: 防止代理人在不同任务之间套利



$P$: principal;    $A$: agent;    $x_i$: production of agent $i$;    $a\in A$: effort of agent $A$;    $c(a)$ is convex; $c'>0, $ $ c''\le0$ ;

all utilities are VNM formula;     $\underline U$ is $A$'s preserved utility;

one-time choice of a vector of efforts $a=\left(a_{1} \ldots \ldots a_{n}\right)$ with cost $c(a),$ which brings expected gross benefits $B(a)$ for the principal and generates a vector of information signal $x_{i}=a_{i}+\varepsilon_{i} \quad$ for every task, where $\varepsilon \sim(0, \Sigma)$, $\Sigma$ is a $\quad n \times n \quad$ matrix
Also $w(x)=\alpha+\beta_{1} x_{1}+\beta_{2} x_{2}+\ldots+\beta_{k} x_{k}=\alpha+\beta^{T} x \quad$, and $u(w)=-\exp (-r \hat{w}) (CARA)$ The risk-neutral P's problem is
$$
\operatorname{Max}_{\{\alpha, \beta, a\}} E V[B(a)-w(x)]=EV[B(a)-\alpha-\beta^{T} a]
$$

$$
s.t. (IR) E u(w)-c(a) \geq E(\underline{U}) \\
(\mathrm{IC}) \quad a \in \arg \max _{a} E u(\hat{w})
$$

$\mathrm{IR}: \mathrm{ACE}=\alpha+\beta^{T} a-c(a)-\frac{1}{2} r \beta^{T} \Sigma \beta \geq \underline{U} ; \\ \mathrm{IC}: \beta^{T}=\frac{\partial c(a)}{\partial a_{i}}=c_{i}(a), \frac{\partial \beta^{T}}{\partial a}=\left[c_{i j}\right]$
$\therefore \alpha=\underline{U}-\beta^{T} a+\frac{1}{2} r \beta^{T} \Sigma \beta+c(a) .$ 

Substituting $\alpha$ into $E V \quad(\mathrm{SPE}),$ equivalently we have
$$
T C E=\operatorname{Max}_{\beta, a} B(a)-\frac{1}{2} r \beta^{T} \Sigma \beta-c(a)
$$
Differentiating with respect to $a,$ we have
$B^{\prime}(a)-r \Sigma \beta \frac{\partial \beta^{T}}{\partial a}-c_{i}(a)=0 .$ Because $\frac{\partial \beta^{T}}{\partial a}=c_{i j},$ and $c_{i}(a)=\beta^{T},$ we get
$$
\begin{array}{l}
B^{\prime}(a)=\beta\left(r \Sigma\left[c_{i j}\right]+I\right) \\
\beta=\frac{B^{\prime}(a)}{I+r \Sigma\left[c_{i j}\right]}
\end{array}
$$


[Note $]$ If $a$ and $x$ are both one dimension variable, i.e. $x=a+\varepsilon, c(a)=\frac{b a^{2}}{2}$
expression (4) reduces to $\beta=\frac{1}{1+r b \sigma^{2}}$