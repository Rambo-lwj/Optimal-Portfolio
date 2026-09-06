Lagrangian equation for efficient frontier without risk-free asset:

$$L(x,\lambda)=1/2\omega^T \Sigma \omega + \lambda（m- \omega ^T \mu) +\gamma (1- \omega ^T 1)  \quad (1)$$  

solve using method of lagrange, get allocation of portfolio on efficient frontier without risk-free asset:

$$\omega = \Sigma ^{-1} ( \lambda \mu + \gamma 1)$$   
                           
$\lambda=\frac{Am-B}{AC-B^2}$ , $\gamma=\frac{C-Bm}{AC-B^2}$, $A=1 \Sigma ^{-1} 1$ , $B=1 ^T \Sigma ^{-1} \mu$ , $C=\mu ^T \sum ^{-1} 1$  , 
m is target return.

Lagrangian equation for efficient frontier with risk-free asset:

$$L(x,\lambda)= 1/2 \omega ^T \Sigma \omega + \lambda （m-rf- \omega ^T (\mu -rf1)) \quad (2)$$

solve using method of lagrange, get allocation of portfolio on efficient frontier with risk-free asset:

$$\Sigma=\frac{(m-rf)\Sigma ^-1(\mu -rf1)}{(\mu -rf1)^T \Sigma ^-1 (\mu -rf1)}$$        
                      
tangency portfolio satisfy both equation (1) and equation (2).
Thus, allocation of tangency portfolio:

Volatility of tangency portfolio:
