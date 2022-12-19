---
layout: exercise
title: Principal agent problem in the labour market
version: 0.0.0
goals: [III.B.3]
---

The following figure includes two graphs...
Consider the labour market model, where workers can exert two discrete levels of effort, $\underline{e}$ and 0. The equilibrium (no-shirking) wage in this case is given by the following wage curve: $$w^N=B+\underline{u}+\frac{1-t}{tj}\underline{u}$$ where $B$ denotes the unemployment benefit, \underline{u} the disutility of effort, $t$ the probability of contract termination, and $j$ the unemployment rate.
Now, consider also the model of product markets, where firms face $b$ barriers to enter the market. Remember that a firm's expected profits are given by the following expression:
$$\hat{\pi}^E=-b(1+\rho)w^n\alpha_l+(1-b)(p-(1+\rho)w^n\alpha_l)$$ where $\rho$ is the opportunity cost of capital, $\alpha_l$ is the labour input requirement for a unit of output, and $p$ is the price of the good.
\textit{Note that $w^N$ denotes the no-shirking (equilibrium) wage and $w^n$ the nominal wage.}

1. Consider $j=1-H$ with $H$ being the employment rate. Explain why there will always be unemployment in the market. In other words, why $H=1$ cannot be an equilibrium. \textit{Think how $H$ affects $w^N$. What should $w^N$ be if $H=1$?}
2. The wage curve described in Equation (1) shows all the possible Nash equilibria in the labour market, but it doesn't determine which equilibrium will prevail. In order to find the equilibrium $(w,H)$ we need to find that amount of wage that results in the number of firms in the market neither increasing nor decreasing (i.e. the amount of wage that brings the products market in equilibrium). Assume that $\alpha_l=\frac{1}{\gamma}$, where $\gamma$ is the productivity of labour, and write the condition that needs to hold for a firm to enter the market. Solve for the real wage $\frac{w^n}{p}$.
3. See the graph and assume $\rho=0.05, \gamma=0.9$ and $b=0.2$. What is the value of $w^c$? Interpret. 
4. Increase the value of $b$ to 0.4. Which of the two curves is affectedf and how? What is the effect to the number of firms entering/exiting the market?
5. Consider now the case where a firm has monopsony power. In this case the unemployment rate is affected by the hours the firm hires, $h$, i.e. $$j(h)=1-\frac{qh}{1-h}$$ where q is the rate of current workers quitting their job in any period. Write the expression of the no-shirking wage in this case.
6. See the right graph and assume $\underline{u}=0.03, t=0.7$ and $q=..$. What are the equilibrium values of $w$ and $H$?
7. Increase the value of $q$ to .. Which of the two curves is affected and how?
8. How would the hours of hiring affect the no-shirking wage ($w^N$)? Show this effect mathematically and explain the intuition. 


{% include graph.html category="ExLectures" graph="WageMonopsony" %}
