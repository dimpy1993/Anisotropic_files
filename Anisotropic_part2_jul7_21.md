#### **In the presence of harmonic trap**

Potential confinement, $U(x,y)= \kappa(x^2+y^2)/2$

Langevin Equation in the presence of harmonic trap,
$$
\frac{\partial x}{\partial t} =-\kappa x[\bar\Gamma  + \frac{\Delta \Gamma}{2}  \cos 2 \theta(t)]-\frac{\kappa y}{2}\Delta \Gamma  \sin 2 \theta(t)+ v_p \hat n_x (t) + \xi _x(t)
\\ \frac{\partial y}{\partial t} =-\frac{\kappa x}{2}\Delta \Gamma  \sin 2 \theta(t)-\kappa y[\bar\Gamma  - \frac{\Delta \Gamma}{2}  \cos 2 \theta(t)]+ v_p \hat n_y (t) + \xi _y(t)
$$
**Perturbative Expansion**: 

Define $R\equiv (x,y)^T$, the above equation can be reduce as 
$$
\dot R(t)= -\kappa\Big[\bar\Gamma \mathbb{I}  + \frac{\Delta \Gamma}{2} \mathbb{M}(t)\Big]R(t)+v_p \bold {\hat n}(t)+ \xi(t)
\\ \text {where} \ \mathbb{M}(t) = \left[
\matrix{
  \cos 2\theta(t) & sin 2\theta(t)\\
  sin 2\theta(t) & -\cos 2\theta(t)\\
  
}
\right]
$$
Perturbative expansion is 
$$
R(t) =R_0(t)-\bigg(\frac{\kappa \Delta \Gamma}{2}\bigg)R_1(t)+\bigg(\frac{\kappa \Delta \Gamma}{2}\bigg)^2R_2(t)+ \mathcal{O}\bigg(\frac{\kappa \Delta \Gamma}{2}\bigg)^3
$$
Substituting equation 12 in 11, we obtain
$$
\dot R_0(t)=-\kappa \bar \Gamma R_0(t) + \xi(t)+ v_p \bold{\hat n}(t)
\\ \dot R_1(t)=-\kappa \bar \Gamma R_1(t)+ \mathbb{M}(t)R_0(t)
\\ \dot R_2(t)=-\kappa \bar \Gamma R_2(t)+ \mathbb{M}(t)R_1(t)
$$
Taking R(0)=0, solving the above equations
$$
R_0(t)= \int_0^t e^{-\kappa \bar\Gamma(t-t^\prime)}\xi(t^\prime)dt^\prime+ v_p\int_0^t e^{-\kappa \bar\Gamma(t-t^\prime)}\bold{\hat n}(t^\prime)dt^\prime
\\R_1(t)= \int_0^t e^{-\kappa \bar\Gamma(t-t^\prime)} \mathbb{M}(t^\prime)R_0(t^\prime)dt^\prime
\\\\R_2(t)= \int_0^t e^{-\kappa \bar\Gamma(t-t^\prime)} \mathbb{M}(t^\prime)R_1(t^\prime)dt^\prime
$$
The equal time correlation matrix 
$$
\langle R_i(t)R_j(t)\rangle_{\xi,\theta_0} =\langle R_{0,i}(t)R_{0,j}(t)\rangle_{\xi,\theta_0} - \bigg(\frac{\kappa \Delta \Gamma}{2}\bigg)\langle R_{0,i}(t)R_{1,j}(t)\rangle_{\xi,\theta_0}+\bigg(\frac{\kappa \Delta \Gamma}{2}\bigg)^2 \bigg[\langle R_{1,i}(t)R_{1,j}(t)\rangle_{\xi,\theta_0}\\+  2\langle R_{0,i}(t)R_{2,j}(t)\rangle_{\xi,\theta_0}\bigg] +\mathcal{O}\bigg(\frac{\kappa \Delta \Gamma}{2}\bigg)^3
$$

4. **Calculation of $\langle R_{0}(t)R_{0}(t)\rangle_{\xi,\theta_0} $**

$$
\langle R_{0}(t)R_{0}(t)\rangle_{\xi,\theta_0}=\int_0^t dt^\prime\int_0^t dt^{\prime \prime}e^{-\kappa \bar\Gamma(t-t^\prime)}e^{-\kappa \bar\Gamma(t-t^{\prime\prime})}\langle \xi(t^\prime)\xi(t^{\prime \prime})\rangle_{\xi,\theta_0}\\+v_p^2\int_0^t dt^\prime\int_0^t dt^{\prime \prime}e^{-\kappa \bar\Gamma(t-t^\prime)}e^{-\kappa \bar\Gamma(t-t^{\prime\prime})}\langle \bold{\hat n}(t^\prime)\bold{\hat n}(t^{\prime \prime})\rangle_{\xi,\theta_0}
\\\langle R_{0}(t)R_{0}(t)\rangle_{\xi,\theta_0}=2K_BT e^{-2\kappa \bar\Gamma t}\int_0^t dt^\prime\int_0^t dt^{\prime \prime}e^{\kappa \bar\Gamma(t^\prime+t^{\prime\prime})}\langle \bar\Gamma \mathbb{I}  + \frac{\Delta \Gamma}{2} \mathbb{M}(\theta(t^\prime))\rangle_{\xi,\theta_0}\delta(t^\prime-t^{\prime\prime})
\\+v_p^2e^{-2\kappa \bar\Gamma t}\int_0^t dt^\prime\int_0^t dt^{\prime \prime}e^{\kappa \bar\Gamma(t^\prime+t^{\prime\prime})}\bigg[\frac{\mathbb{I}}{2}e^{-D_r(t^\prime+t^{\prime\prime}-2 \min(t^\prime,t^{\prime\prime}))}+\frac{\mathbb{M}(\theta_0)}{2}e^{-D_r(t^\prime+t^{\prime\prime}+2 \min(t^\prime,t^{\prime\prime}))}\bigg]
\\ \text{Considering the case of } t^\prime > t^{\prime\prime},
\\ \langle R_{0}(t)R_{0}(t)\rangle_{\xi,\theta_0} =\frac{K_B T}{\kappa}\mathbb{I}\bigg(1- e^{-2\kappa\bar \Gamma t}\bigg) + K_B T \Delta \Gamma \mathbb{M}(\theta_0) \bigg(  \frac{e^{-4 D_r t}- e^{-2\kappa \bar\Gamma t}}{2\kappa \bar\Gamma-4D_r}\bigg) \\+ \frac{v_p^2e^{-2\kappa \bar\Gamma t}}{2}\mathbb{I}\times 2\int_0^t dt^{\prime \prime}\int_{t^{\prime \prime}}^t dt^{\prime } \ e^{\kappa \bar\Gamma(t^\prime+t^{\prime\prime})}e^{-D_r(t^\prime-t^{\prime\prime})}\\+\frac{v_p^2e^{-2\kappa \bar\Gamma t}}{2}\mathbb{M}(\theta_0)\times 2\int_0^t dt^{\prime \prime}\int_{t^{\prime \prime}}^t dt^{\prime } \ e^{\kappa \bar\Gamma(t^\prime+t^{\prime\prime})}e^{-D_r(t^\prime+3t^{\prime\prime})}
\\ \langle R_{0}(t)R_{0}(t)\rangle_{\xi,\theta_0} =\frac{K_B T}{\kappa}\mathbb{I}\bigg(1- e^{-2\kappa\bar \Gamma t}\bigg) + K_B T \Delta \Gamma \mathbb{M}(\theta_0) \bigg(  \frac{e^{-4 D_r t}- e^{-2\kappa \bar\Gamma t}}{2\kappa \bar\Gamma-4D_r}\bigg) \\+ v_p^2 \mathbb{I} \bigg[ \frac{1-e^{-(D_r+\kappa \bar \Gamma)t}}{(\kappa \bar \Gamma)^2 -D_r^2}-\frac{1-e^{-2\kappa \bar \Gamma t}}{2\kappa \bar \Gamma(\kappa \bar \Gamma-D_r)}\bigg]+\frac{v_p^2\mathbb{M}(\theta_0)}{(\kappa \bar \Gamma-D_r)}\bigg[ \frac{e^{-4D_rt}-e^{-(D_r+\kappa \bar \Gamma)t}}{(\kappa \bar \Gamma -3D_r)}-\frac{e^{-4D_rt}-e^{-2\kappa \bar \Gamma t}}{2(\kappa \bar \Gamma-2D_r)}\bigg]
$$



**The $x$ and $y$ components are** 
$$
\langle x_{0}^2(t)\rangle_{\xi,\theta_0} =\frac{K_B T}{\kappa}\bigg(1- e^{-2\kappa\bar \Gamma t}\bigg) + K_B T \Delta \Gamma \cos 2\theta_0 \bigg(  \frac{e^{-4 D_r t}- e^{-2\kappa \bar\Gamma t}}{2\kappa \bar\Gamma-4D_r}\bigg) \\+ v_p^2  \bigg[ \frac{1-e^{-(D_r+\kappa \bar \Gamma)t}}{(\kappa \bar \Gamma)^2 -D_r^2}-\frac{1-e^{-2\kappa \bar \Gamma t}}{2\kappa \bar \Gamma(\kappa \bar \Gamma-D_r)}\bigg]+\frac{v_p^2\cos 2\theta_0}{(\kappa \bar \Gamma-D_r)}\bigg[ \frac{e^{-4D_rt}-e^{-(D_r+\kappa \bar \Gamma)t}}{(\kappa \bar \Gamma -3D_r)}-\frac{e^{-4D_rt}-e^{-2\kappa \bar \Gamma t}}{2(\kappa \bar \Gamma-2D_r)}\bigg]
\\ \text{and}
\\\langle y_{0}^2(t)\rangle_{\xi,\theta_0} =\frac{K_B T}{\kappa}\bigg(1- e^{-2\kappa\bar \Gamma t}\bigg) - K_B T \Delta \Gamma \cos 2\theta_0 \bigg(  \frac{e^{-4 D_r t}- e^{-2\kappa \bar\Gamma t}}{2\kappa \bar\Gamma-4D_r}\bigg) \\+ v_p^2  \bigg[ \frac{1-e^{-(D_r+\kappa \bar \Gamma)t}}{(\kappa \bar \Gamma)^2 -D_r^2}-\frac{1-e^{-2\kappa \bar \Gamma t}}{2\kappa \bar \Gamma(\kappa \bar \Gamma-D_r)}\bigg]-\frac{v_p^2\cos 2\theta_0}{(\kappa \bar \Gamma-D_r)}\bigg[ \frac{e^{-4D_rt}-e^{-(D_r+\kappa \bar \Gamma)t}}{(\kappa \bar \Gamma -3D_r)}-\frac{e^{-4D_rt}-e^{-2\kappa \bar \Gamma t}}{2(\kappa \bar \Gamma-2D_r)}\bigg]
$$
**The cross correlation function** 
$$
\langle x_{0}(t)y_{0}(t)\rangle_{\xi,\theta_0} =\Delta D \sin 2\theta_0 \bigg(  \frac{e^{-4 D_r t}- e^{-2\kappa \bar\Gamma t}}{2\kappa \bar\Gamma-4D_r}\bigg)+\\\frac{v_p^2\sin 2\theta_0}{(\kappa \bar \Gamma-D_r)}\bigg[ \frac{e^{-4D_rt}-e^{-(D_r+\kappa \bar \Gamma)t}}{(\kappa \bar \Gamma -3D_r)}-\frac{e^{-4D_rt}-e^{-2\kappa \bar \Gamma t}}{2(\kappa \bar \Gamma-2D_r)}\bigg]
$$
where $\Delta D= K_B T \Delta \Gamma$
