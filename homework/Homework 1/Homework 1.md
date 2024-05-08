# Homework 1

<center><div style='height:2mm;'></div><div style="font-size:10pt;">梁昱桐 2100013116</div></center>
<center><span style="font-size:9pt;line-height:9mm"><i>Peking University</i></span>
</center>



1. **Suppose Fiori spends all his income on brownies and hotpots, then which of the following situation is plausible?**

   **A. Both brownies and hotpots are inferior goods.**

   **B. Both brownies and hotpots are luxuries.**

   **C. Brownies are neither inferior goods nor luxuries, and hotpots are inferior goods.**

   **D. Brownies are luxuries, and hotpots are neither inferior goods nor luxuries.**

Answer: D

Take partial derivatives of $M$ with respect to both sides simultaneously.
$$
\begin{aligned}
P_1Q_1+P_2Q_2&=M\\
P_1\frac{\partial Q_1}{\partial M}+P_1\frac{\partial Q_1}{\partial M}&=1\\
\frac{P_1Q_1}{M}E_{Q_1.M}+\frac{P_2Q_2}{M}E_{Q_2.M}&=1\\
t_1E_{Q_1.M}+t_2E_{Q_2.M}&=1\\
\end{aligned}
$$

$$
\begin{aligned}
\begin{cases}
t_1E_{Q_1.M}+t_2E_{Q_2.M}=1\\
t_1+t_2=1\\
t_1,t_2>0
\end{cases}
\end{aligned}
$$

A: $E_{Q_1.M}<0,E_{Q_2.M}<0$ , not plausible.

B: $E_{Q_1.M}>1,E_{Q_2.M}>1$ , not plausible.

C: $0<E_{Q_1.M}<1,E_{Q_2.M}<0$ , not plausible.

D: $E_{Q_1.M}>1,0<E_{Q_2.M}<1$ , plausible.



2. **Other things being equal, the lower the magnitude of own-price elasticity of demand, \_\_\_\_**

   **A. the less likely the profitability of a price increase.**

   **B. the more likely the profitability of a price increase.**

   **C. the greater the responsiveness in quantity demanded to a price change.**

   **D. the lower the corresponding increase in firm revenue.**

Answer: B

A & B: For a type of good with low own-price elasticity, the higher the price is, the more profit the producer can obtain for the consumers have no choice but to buy them.

C: Low own-price elasticity literally means small responsiveness in demand to a price change.

D: the lower the magnitude of own-price elasticity of demand, the smaller the price, can't determine whether revenue increase or not.



3. **Poorer countries have a \_\_\_\_ demand for wheat because they usually \_\_\_\_ .**

   **A. less elastic; find other substitutes.**

   **B. less elastic; can't find other substitutes.**

   **C. more elastic; can't find other substitutes.**

   **D. more elastic; find other substitutes.**

Answer: B



4. **Recent research estimates that the short-run price elasticity of demand for gasoline in the U.S. is $-0.3$, and the long-run price elasticity of demand is $-1.4$. What happens if the government increases the federal gasoline tax?** 

   **A. Consumer expenditures on gasoline increase in the short-run and long-run.**

   **B. Consumer expenditures on gasoline decline in the short-run and increase in the long-run.**

   **C. Consumer expenditures on gasoline increase in the short-run and decline in the long-run.**

   **D. Consumer expenditures on gasoline decrease in the short-run and long-run.**

Answer: C

In the short-run, the demand is inelastic, the revenue increase as the demand decrease.

In the short-run, the demand is elastic, the revenue increase as the demand increase.



5. **A demand function is given as**
   $$
   \log Q_x=a-b\log P_x+ c\log P_y+d\log M
   $$
   

   **where $P_x$  is the price of the good $x$, $P_y$ is the price of a second good $y$ and $M$ is income. Suppose $a$ , $b$ , $c$ , $d$ are positive numbers, then the second good $y$ must be**

   **A. a normal good.**

   **B. an inferior good.**

   **C. a substitute for the good $x$ .**

   **D. a complement for the good $x$ .**

Answer: C

A & B: $E_{Q_y,M}$ can't be calculated.

C & D: $E_{Q_x,P_y}=c>0$



6. **Suppose the demand of Fiori for brownies has a constant elasticity of $-\epsilon$ （ $\epsilon>0$ ）:**
   
   1. **Suppose $\epsilon = 1$ and Fiori purchases 10 brownies when the price is $1 .Derive the demand function and the inverse demand function for him.**
   
      Demand function: 
      $$
      \begin{aligned}
      \ln Q&=-\ln P+\ln 10\\
       Q&=\frac{10}{P}
      \end{aligned}
      $$
      Inverse demand function:
      $$
      P=\frac{10}{Q}
      $$
      
   2. **If the price of brownie increases, will Fiori spend more or less purchasing it? （Do not assume $\epsilon=1$ here）**
      $$
      \begin{aligned}
      E&=\frac{\partial Q/Q}{\partial P/P}=-\epsilon\\
      \Rightarrow\frac{\partial Q}{\partial P}&=-\frac{Q}{P}\epsilon
      \end{aligned}
      $$
      
      $$
      \begin{aligned}
      M&=PQ\\
      \frac{\partial M}{\partial P}&=Q+\frac{\partial Q}{\partial P}P\\
      &=(1-\epsilon)Q
      \end{aligned}
      $$
      
   
      Therefore:
   
      If $0<\epsilon<1$ , Fiori spends more.
   
      Else if $\epsilon=1$ , Fiori spends the same.
   
      Else $1<\epsilon$ , Fiori spends less.




7. **Fiori wants to buy coffee and bread. The price of coffee and the quantity purchased are given as $P_1$ and $Q_1$. Similarly, $P_2$ and $Q_2$ correspond to bread. Simplify the notation with ( $P_1$, $Q_1$, $P_2$, $Q_2$ ). Fiori buys the goods according to the following rule** 
   $$
   P_1Q_1+ P_1Q_2 + P_2Q_1 + P_2Q_2=4
   $$
   
   **Fiori's purchase yesterday was (1, 1, 1, 1).**
   
   1. **If the price of coffee increases by 10% today and the price of bread is unchanged, Fiori still buys one unit of bread. What is the arc price elasticity of demand for coffee?**
      $$
      \begin{aligned}
      \begin{cases}
      P_1^{'}Q_1^{'}+ P_1^{'}Q_2^{'} + P_2^{'}Q_1^{'} + P_2^{'}Q_2^{'}=4 \\
      P_1^{'}=1.1\\
      P_2^{'}=1\\
      Q_2^{'}=1\\
      \end{cases}
      \end{aligned}
      \Rightarrow
      Q_1^{'}=\frac{19}{21}
      $$
   
      $$
      \begin{aligned}
      \overline{E_{Q_1,P_1}}&=\frac{\Delta Q_1/\overline{Q_1}}{\Delta P_1/\overline{P_1}}\\
      &=\frac{-\frac{2}{21}/\frac{20}{21}}{\frac{1}{10}/\frac{21}{20}}\\
      &=-\frac{21}{20}
      \end{aligned}
      $$
   
      
   
   2. **If the price of coffee and the amount of bread purchased are held constant, what is the cross-price elasticity of demand for coffee with respect to the price of bread at the point of (1, 1, 1, 1) ?**
   
      Take $P_1$ and $Q_2$ as constants:
      $$
      \begin{aligned}
      P_1dQ_1+P_2dQ_1+Q_1dP_2+Q_2dP_2&=0\\
      (P_1+P_2)dQ_1+(Q_1+Q_2)dP_2&=0\\
      \frac{\mathrm dQ_1}{\mathrm dP_2}&=-\frac{Q_1+Q_2}{P_1+P_2}\\
      \end{aligned}
      $$
      
      $$
      \begin{aligned}
      E_{Q_1,P_2}&=\frac{\partial Q_1}{\partial P_2}\frac{P_2}{Q_1}\\
      &=-\frac{\frac{Q_2}{Q_1}+1}{\frac{P_1}{P_2}+1}\\
      &=-1
      \end{aligned}
      $$
      

8. **The theoretical model we discussed in class shows that a producer can maximize the revenue by setting the price at the point of unit-elastic demand. However, in reality we observe that producers frequently adjust prices. Explain why producers may alter prices over time rather than keeping the price constant.**

   In a perfect competition market, the producers can't alter the price, because producers are price-takers and they face a perfect elastic demand curve.

   However, if some of the producers gain a status of monopolization, they are endowed with some abilities to set their price to maximize their profits.

   1. The reasons might be the fluctuation of the demand function. The reasons are the variables that affect the demand function, such as the equilibrium of its substitutes and complements, the preferences of buyers, the income and the interferences from government like taxes and subsidies.

   2. However, if take the costs into account, the best production for the producer is not the unit-elastic point, it is a bit more left in the graph. It's the intersection of the two curves: marginal revenue curve and the marginal cost curve.

      So the chosen price is not only depended on the demand function, its also depended on the marginal cost. 

      1. In the short-run, the reasons might be: the price of the raw materials and the price of labor force.
      2. In the long-run, the rent of the warehouse and the development of technology can also be the reason to affect the price.
   3. Furthermore, the alter prices might due to the price discrimination, the producers can set different prices for different people or at different times. The producers can gain more profit (surplus) , and the price alters.
