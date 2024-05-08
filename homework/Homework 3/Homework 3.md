# **Homework 3**

<center><div style='height:2mm;'></div><div style="font-size:10pt;">梁昱桐 2100013116</div></center>
<center><span style="font-size:9pt;line-height:9mm"><i>Peking University</i></span>
</center>
1. **When the price of Fiori falls and the substitution effect is in a negative direction, then Fiori is a(an)**

   **A. luxury good.**
   **B. inferior good.**
   **C. Giffen good.**
   **D. None of the above is necessarily correct, and the substitution effect should always be in a positive direction in this case.**

   Answer: D

   

2. **Fiori's preferences can be represented by a utility function**
   $$
   U(x, y)=\min \{x, y\}
   $$
   **He faces prices of $(2,1)$, and his income is 12 . Then the prices change to $(3,1)$. What are the compensating and equivalent variations?**

   **A. 3, 3**
   **B. 3, 4**
   **C. 4, 4**
   **D. 4, 3**

   Answer: D

   

3. **Fiori uses two factors of production. Irrespective of how much of each factor is used, both factors always have positive marginal products, which imply that**

   **A. isoquants are relevant only in the long-run.**
   **B. isoquants have negative slope.**
   **C. isoquants are convex.**
   **D. isoquants can become vertical or horizontal.**
   **E. None of the above.**

   Answer: B

   

4. **In order for a taxicab to be operated in New York City, it must have a medallion on its hood. The medallion is expensive, but can be resold, and is therefore**

   **A. a fixed cost.**
   **B. a variable cost.**
   **C. an opportunity cost.**
   **D. a sunk cost.**

   Answer: A



5. **Suppose that Fiori faces a production function of $f\left(x_1, x_2\right)=3 x_1+x_2$. If the factor prices are 9 for Factor 1 and 4 for Factor 2, how much will it cost him to produce 50 units of output?**

   **A. 150**
   **B. 175**
   **C. 200**
   **D. 875**
   **E. 1,550**

   Answer: A



6. **Suppose Fiori uses labor and capital to produce brownies and the production exhibits constant returns to scale. Meanwhile, the real rental and the real wage are both constant. In this case, Fiori has made the optimal choice to maximize his profit, given $K, L>0$.**
   1. **If Fiori faces a standard Cobb-Douglas production function of $P(K, L)=K^\alpha L^{1-\alpha}$, prove that Fiori earns no profit.**
      $$
      \pi(K,L)=pK^\alpha L^{1-\alpha}-rK-wL
      $$
      If Fiori has made the optimal choice:
      $$
      \pi^*=\max_{(K,L)\in\mathbb R\times\mathbb R}{pK^\alpha L^{1-\alpha}-rK-wL}
      $$
      In which
      $$
      (K^*,L^*)=\arg \max_{(K,L)\in\mathbb R\times\mathbb R}{pK^\alpha L^{1-\alpha}-rK-wL}
      $$
      Assume that $\pi^*>0$ :
      $$
      \pi'=\pi(tK^*,tL^*)=p(tK^*)^\alpha (tL^*)^{1-\alpha}-r(tK^*)-w(tL^*)=t\pi^*>\pi^*\ \ \ \ t>0
      $$
      Which contradicts with the fact that $\pi^*$ is the optimal choice.
   
      Thus, $\pi^*\leqslant0$ .
   
      As we also have $\pi(0,0)=0$ , the optimal choice $\pi^*=0$ .
   
      
   
   1. **Prove that Fiori earns no profit in general.**
      $$
      \pi(K,L)=pP(K,L)-rK-wL
      $$
      If Fiori has made the optimal choice:
      $$
      \pi^*=\max_{(K,L)\in\mathbb R\times\mathbb R}{pP(K,L)-rK-wL}
      $$
      In which
      $$
      (K^*,L^*)=\arg \max_{(K,L)\in\mathbb R\times\mathbb R}{pP(K,L)-rK-wL}
      $$
      Assume that $\pi^*>0$ :
   
      Because $P(·)$ is constant returns to scale,
      $$
      \pi'=\pi(tK^*,tL^*)=pP(tK^*,tL^*)-r(tK^*)-w(tL^*)=t\pi^*>\pi^*\ \ \ \ t>0
      $$
      Which contradicts with the fact that $\pi^*$ is the optimal choice.
   
      Thus, $\pi^*\leqslant0$ .
   
      As we also have $\pi(0,0)=0$ , the optimal choice $\pi^*=0$ .



7. **Suppose Thompson owns a factory of producing Fiori and faces a production function of**
   $$
   f(K, L)=\sqrt{K L}
   $$
   **where $K$ and $L$ do not have to be integers. Currently, the wage and rent are both $\$ 1$ and Thompson needs to produce 10 units of Fiori. Meanwhile, there is an extra cost to alter the amount of capital used in production, and additional $\$ x$ is required for each unit of capital deviated from $K=5$, which was the former optimal level of capital used.**

   1. **Suppose $x=1$. Figure out the optimal production choice for Thompson and the associated cost.**
   
      The formal form of the optimization problem:
      $$
      \begin{aligned}
      \min &\ \ \ \ K+L+|K-5|\\
      s.t.&\ \ \ \ \sqrt{KL}=10
      \end{aligned}
      $$
   
      1. $K>5$
         $$
         \begin{aligned}
         \min &\ \ \ \ 2K+L-5\\
         s.t.&\ \ \ \ \sqrt{KL}=10
         \end{aligned}
         $$
         The Lagrangian function:
         $$
         L(K,L,\lambda)=2K+L-5-\lambda(KL-100)
         $$
         Do the calculations:
         $$
         \begin{cases}
         K=5\sqrt 2\\
         L=10\sqrt 2
         \end{cases}
         $$
         Where the capital meets the constriant that $K>5$ , and the cost is $20\sqrt 2-5\approx 23.284$.
   
      2. $K\leqslant5$
         $$
         \begin{aligned}
         \min &\ \ \ \ L+5\\
         s.t.&\ \ \ \ \sqrt{KL}=10
         \end{aligned}
         $$
         Simply take the boundary case:
         $$
         \begin{cases}
         K=5\\
         L=20
         \end{cases}
         $$
         The cost is 25.
   
      The first case has a lower cost, thus the optimal production choice is:
      $$
      \begin{cases}
      K=5\sqrt 2\\
      L=10\sqrt 2
      \end{cases}
      $$
      Where the cost is $20\sqrt 2-5\approx 23.284$.
   
      
   
   2. **When $x$ decreases to 0 , is the situation closer to a short-run case where the capital is fixed at 5 or to a long-run case?**
      
      In the long run, the object function is $K+L$ ，so the optimal choice is:
      $$
      \begin{cases}
      K=10\\
      L=10\\
      \text{cost}=20
      \end{cases}
      $$
      In the process while $x$ is approaching 0, solve the following question:
      $$
      \begin{aligned}
      \min &\ \ \ \ K+L+x|K-5|\\
      s.t.&\ \ \ \ \sqrt{KL}=10
      \end{aligned}
      $$
      where $x\in[0,1)$ .
      
      Do the calculations:
      $$
      \begin{cases}
      K=\frac{10}{\sqrt{1+x}}\\
      L=10\sqrt{1+x}\\
      \text{cost}=20\sqrt{1+x}-5x
      \end{cases}
      $$
      We can see the limit of these variables are exactly the values of these vaariables in the long-run, so the situation is closer to a long-run case.
      
      As a matter of fact, the term of $x|K-5|$ is a punishment for the deviation from $K=5$ , if $x$ is big enough, the producer won't make the change on capital which resembles the situation of short-term. In this way, if $x=0$ , the situation is exactly the long-run case.
      
      
   
8. **Profiteer Thompson operates a brownie factory. This year, he faces a cost of $C=20 * Q$ and a demand of $Q=100-P$.**
   1. **Figure out the optimal quantity to produce, the price of brownies and profit gained by Thompson.**
   
      His profit:
      $$
      \begin{aligned}
      \pi&=PQ-C\\
      &=(80-Q)Q
      \end{aligned}
      $$
      The optimal choice of $Q^*=40$
   
      Thus the optimal price $P^*=60$ , the maximized profit $\pi^*=1600$.
   
      
   
   1. **Thompson decides to operate for at least two years. Instead of maximizing a one-year profit, he intends to maximize the profit of two consecutive years in total. Suppose his cost remains the same for the following year, but the demand changes to $Q=200-P_1-P_2$, where $P_1$ is the price of brownies for this year and $P_2$ is the price for the following year. Figure out the optimal quantities and prices for both years and the total profit earned.**
      $$
      \begin{aligned}
      \pi&=\pi_1+\pi_2\\
      &=P_1Q_1-C+P_2Q_2-C\\
      &=(P_1-20)(100-P_1)+(P_2-20)(200-P_1-P_2)\\
      &=-P_1^2-P_1P_2-P_2^2+140P_1+220P_2-6000
      \end{aligned}
      $$
      First order condition:
      $$
      \begin{cases}
      \frac{\partial\pi}{\partial P_1}=-2P_1-P_2+140=0\\
      \frac{\partial\pi}{\partial P_2}=-2P_2-P_1+220=0\\
      \end{cases}
      \Rightarrow
      \begin{cases}
      P_1=20\\
      P_2=100
      \end{cases}
      \Rightarrow
      \begin{cases}
      Q_1=80\\
      Q_2=80
      \end{cases}
      $$
      The Hessian matrix:
      $$
      \begin{pmatrix} -2 & -1\\ -1 & -2 \end{pmatrix}
      $$
      This is a negative definite matrix, so the obtained extremum point is a maximum point.
   
      However, it can be seen that if $P_1=20$ , Thompson wins no profit in the first year, so it's possible that he produce any $Q_1\in[0,80]$
      
      Thus the optimal choices are:
      $$
      \begin{cases}
      P_1=20\\
      P_2=100
      \end{cases}
      \text{ and }
      \begin{cases}
      Q_1\in[0,80]\\
      Q_2=80
      \end{cases}
      $$
      The maximized profit is $\pi^*=6400$.
      
      

