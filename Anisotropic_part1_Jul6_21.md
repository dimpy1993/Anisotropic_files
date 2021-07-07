Asymmetric  [Ellipsoid]  active particle:

​     An asymmetric active particle undergoes self-propulsion with a velocity $v_p \bold {\hat n} (t)$ along its longer axis in 2-dimension. The angle between the x-axis of the lab frame and long axis of the ellipsoid at time $t$ is represented by $\theta(t)$. The component of the orientation vector $\bold{\hat n}(t)$ w.r.t the lab frame can be expressed as $\bold {\hat n}(t)\equiv \Big(\cos \theta(t),\sin \theta(t)\Big)$.

In the body frame, the equation of motion of the centre of mass pf the particle is given as
$$
\frac{\partial \tilde x}{\partial t}=v_p+ \Gamma_{\parallel}F_x\cos \theta(t)+ \Gamma_{\parallel}F_y \sin \theta(t) +\Gamma_{\parallel} \tilde\eta_x(t)\\
\frac{\partial \tilde y}{\partial t}=\Gamma_{\perp}F_x\cos \theta(t)+ \Gamma_{\perp}F_y \sin \theta(t) +\Gamma_{\perp} \tilde\eta_x(t)
\\ \frac{\partial \theta}{\partial t}  = \Gamma_{\theta} \tau + \tilde\eta_{\theta}
$$

where $F_x$ and $F_y$ are the forces acting on the particle along the $x$ and $y$ directions (in the lab frame), respectively and $τ$ is the torque acting on the particle.

In the lab frame, the displacements are related to the body frame as
$$
δx = \cos θ \delta \tilde x − sin θδ \tilde y,\\
δy = \cos θδ \tilde y + sin θδ \tilde x.
$$
Substituting equation(1) in equation(2), we have

$$
\frac{\partial \bold x_i}{\partial t} = \Gamma_{ij} \bold F_j + v_p \hat{ \bold n}_i(t) + \bold {\xi}_i(t)
$$
where 
$$
\left[
\matrix{
  \xi_x(t) \\
  \xi_y(t) \\
  
}
\right]=\left[
\matrix{
  \Gamma_{\parallel} \\
  \Gamma_{\perp}\\
  
}
\right]\left[
\matrix{
  \cos \theta(t) & -\sin \theta(t) \\
  \sin \theta (t) & \cos \theta(t)\\
  
}
\right]\left[
\matrix{
  \tilde \eta_x(t) \\
  \tilde\eta_y(t) \\
  
}
\right]
\\ \text{The corretation of thermal fluctuation in the body frame are }\\
⟨\tilde \eta⟩ = 0 \text{  and  } ⟨\tilde \eta_i (t) \tilde \eta_j (t^\prime )⟩ = 2D_i δ_{ij} δ(t − t^\prime)
\\ \text{where  } D_{\parallel} = K_BT \Gamma_{\parallel},D_{\perp} = K_BT \Gamma_{\perp}
$$


 The coupled Langevin equation in the presence of an external force $F$ and torque $\tau$  are 
$$
\partial_t r_i = \Gamma_{ij} (\theta (t)) \  F_j + v_p \hat n_i (t) + \xi _i(t),
\\ where \ \Gamma_{ij}(\theta (t)) = \bar\Gamma \delta_{ij} + \frac{\Delta \Gamma}{2} M_{ij} (\theta(t))
\\ \partial_t \theta = \Gamma_{\theta} \tau + \xi_{\theta}(t)
$$

$$
\bar \Gamma = \frac{\Gamma_{\parallel} +\Gamma_{\perp}}{2}, \Delta \Gamma = \Gamma_{\parallel} -\Gamma_{\perp} \  and \ M_{ij} (\theta(t)) = \left[
\matrix{
  \cos 2\theta(t) & sin 2\theta(t)\\
  sin 2\theta(t) & -\cos 2\theta(t)\\
  
}
\right]
$$

   $\xi_i(t)$ and $\xi_{\theta}$ are the Gaussian random noise with zero mean and 

$\langle \xi_{\theta}(t) \xi_{\theta}(t\prime) \rangle = 2 K_B T \ \Gamma_{\theta} \ \delta(t-t\prime)= 2 D_r \ \delta(t-t\prime)$

for a fixed angle $\theta (t)$,   

$\langle \xi_i(t) \xi_j(t\prime) \rangle = 2 K_B T \ \Gamma_{ij}(\theta (t)) \ \delta(t-t\prime)$



**Calculation of $\langle \hat n_i (t_1) \hat n_j (t_2) \rangle _{\theta_0}$, the average is taken for fixed initial angle**$\theta_0$

$\theta(t_1)\equiv \theta_1,\theta(t_2)\equiv \theta_2$
$$
\langle \hat n_i (t_1) \hat n_j (t_2) \rangle_{\theta_0} =\left[
\matrix{
  \langle \cos \theta_1 \cos \theta_2 \rangle & \langle \cos \theta_1 \sin \theta_2\rangle\\
  \langle \sin \theta_1 \cos \theta_2 \rangle & \langle \sin \theta_1 \sin \theta_2\rangle\\
  
}
\right]
$$
$2 \langle \cos \theta_1 \cos \theta_2 \rangle = e^{-D_r(t_1+t_2-2 \min(t_1,t_2))} + \cos 2\theta_0 e^{-D_r(t_1+t_2+2 \min(t_1,t_2))}$

$2 \langle \sin \theta_1 \sin \theta_2 \rangle = e^{-D_r(t_1+t_2-2 \min(t_1,t_2))} - \cos 2\theta_0 e^{-D_r(t_1+t_2+2 \min(t_1,t_2))}$

$2 \langle \cos \theta_1 \sin \theta_2 \rangle = \sin 2\theta_0 e^{-D_r(t_1+t_2+2 \min(t_1,t_2))} $

$2 \langle \cos \theta_2 \sin \theta_1 \rangle = \sin 2\theta_0 e^{-D_r(t_1+t_2+2 \min(t_1,t_2))} $

Substituting, we have
$$
\langle \hat n_i (t_1) \hat n_j (t_2) \rangle_{\theta_0} = \frac{\delta_{ij}}{2}e^{-D_r(t_1+t_2-2 \min(t_1,t_2))}+\frac{M_{ij}(\theta_0)}{2}e^{-D_r(t_1+t_2+2 \min(t_1,t_2))}
$$





**Langevin equation without trap**:
$$
\frac{\partial r_i }{\partial t}=  v_p \hat n_i (t) + \xi _i(t)
 \\\implies r_i(t) -r_i(0) =\int_0^tv_p \hat n_i(t\prime) dt\prime +\int_0^t \xi_i(t\prime)dt\prime
\\ \implies \Delta r_i(t)= \int_0^tv_p \hat n_i(t\prime) dt\prime +\int_0^t \xi_i(t\prime)dt\prime
$$
Mean Square Displacement (MSD) :-
$$
\langle \Delta x^2(t) \rangle_{\theta_0} =v_p^2\int_0^t dt_1^\prime\int_0^t dt_2^\prime \  \langle \hat n_i(t_1^\prime) \hat n_i(t_2^\prime) \rangle_{\theta_0}+\int_0^tdt_1^\prime\int_0^t dt_2^\prime \  \langle\xi_i(t_1\prime)\xi_i(t_2\prime)\rangle_{\theta_0}
\\ \langle \Delta x^2(t) \rangle_{\theta_0}=v_p^2\int_0^t dt_1\prime\int_0^t dt_2\prime \ [ \frac{1}{2}e^{-D_r(t_1\prime+t_2\prime-2 \min(t_1\prime,t_2\prime))}+\frac{M_{xx}(\theta_0)}{2}e^{-D_r(t_1\prime+t_2\prime+2 \min(t_1\prime,t_2\prime))}] + 
\\ 2 K_B T \ \int_0^tdt_1\prime\int_0^t dt_2\prime \  \langle\Gamma_{xx}(\theta (t_1\prime))\rangle_{\theta_0} \ \delta(t_1\prime-t_2\prime)
\\ \text{Considering } t_1\prime > t_2\prime,
\\ \langle \Delta x^2(t) \rangle_{\theta_0}=2v_p^2\int_0^t dt_2\prime\int_{t_2\prime}^t dt_1\prime \ \ [ \frac{1}{2}e^{-D_r(t_1\prime-t_2\prime)}] +2v_p^2\int_0^t dt_2\prime\int_{t_2\prime}^t dt_1\prime \ \frac{M_{xx}(\theta_0)}{2}e^{-D_r(t_1\prime+3t_2\prime )}
\\+ 2 K_B T \ \int_0^tdt_1\prime\int_0^t dt_2\prime \ [\bar\Gamma  + \frac{\Delta \Gamma}{2} \langle \cos 2 \theta(t_1\prime))\rangle_{\theta_0} ]\ \delta(t_1\prime-t_2\prime)
\\ \langle \Delta x^2(t) \rangle_{\theta_0}=2v_p^2\int_0^t dt_2\prime\int_{t_2\prime}^t dt_1\prime \ \ [ \frac{1}{2}e^{-D_r(t_1\prime-t_2\prime)}] +2v_p^2\int_0^t dt_2\prime\int_{t_2\prime}^t dt_1\prime \ \frac{M_{xx}(\theta_0)}{2}e^{-D_r(t_1\prime+3t_2\prime )}
\\+ 2 K_B T \ \int_0^tdt_1\prime\int_0^t dt_2\prime \ \bar\Gamma \ \delta(t_1\prime-t_2\prime)+ 2 K_B T \frac{\Delta \Gamma}{2}  \ \int_0^tdt_1\prime\int_0^t dt_2\prime \ \cos 2 \theta_0 e^{-4D_r t_1\prime}  \ \delta(t_1\prime-t_2\prime)
\\ \text{Take }\tau_r = \frac {1}{2D_r},\tau_1(t)=\frac{1-e^{-D_rt}}{D_r},\tau_4(t)=\frac{1-e^{-4D_rt}}{4D_r}
\\ \langle \Delta x^2(t) \rangle_{\theta_0}=2\tau_r v_p^2[ t-\tau_1(t)]+\frac{2\tau_rv_p^2}{3} \cos 2\theta_0 [\tau_1(t)-\tau_4(t)]+2 K_B T \ \bar\Gamma t+ K_B T \Delta \Gamma  \ \cos 2 \theta_0 \tau_4(t)
$$

Similarly,
$$
\langle \Delta y^2(t) \rangle_{\theta_0}=2\tau_r v_p^2[ t-\tau_1(t)]-\frac{2\tau_rv_p^2}{3} \cos 2\theta_0 [\tau_1(t)-\tau_4(t)]+2 K_B T \ \bar\Gamma t- K_B T \Delta \Gamma  \ \cos 2 \theta_0 \tau_4(t
$$
Generalising, we have
$$
\langle \Delta x_i(t)\Delta x_j(t) \rangle _{\theta_0}=\{ 2\bar D t+2\tau_r v_p^2[ t-\tau_1(t)]\}\delta_{ij} +\bigg[\frac{2\tau_rv_p^2}{3}  [\tau_1(t)-\tau_4(t)]+ \Delta D \  \tau_4(t) \bigg]M_{ij}(\theta_0)
$$
Therefore,
$$
\langle \Delta r^2(t) \rangle_{\theta_0}=\langle \Delta x^2(t) \rangle_{\theta_0}+\langle \Delta y^2(t) \rangle_{\theta_0}
\\ \langle \Delta r^2(t) \rangle_{\theta_0}=4(K_B T \ \bar\Gamma+ \tau_r v_p^2)t - 4\tau_r v_p^2 \tau_1(t)
\\ \text{Take } \bar D=  K_B T \ \bar\Gamma,
\\ \text{The MSD for the untrapped active asymmetric particle is given as}
\\ \langle \Delta r^2(t) \rangle_{\theta_0}=4\bar D t+4\tau_r v_p^2(t-2\tau_r(1-e^{-\frac{t}{2\tau_r}}))
$$



The time dependent displacement diffusion tensor for a fixed initial angle $\theta_0$ are
$$
\\D_{ij}(t,\theta_0)=\frac{\langle \Delta x_i(t)\Delta x_j(t) \rangle _{\theta_0}}{2t}
\\ \text{Asymmetric Brownian particle}
\\D_{ij}(t,\theta_0)=\bar D \delta_{ij}+ \frac{\Delta D}{2}\frac{\tau_4(t)}{t}M_{ij}(\theta_0)
\\\text{Asymmetric Active particle without harmonic trap}
\\D_{ij}(t,\theta_0)=[\bar D + \tau_r v_p^2-\frac{\tau_r v_p^2}{t}\tau_1(t)]\delta_{ij} +\bigg[\frac{2\tau_rv_p^2}{3}  [\tau_1(t)-\tau_4(t)]+ \Delta D \  \tau_4(t) \bigg]\frac{M_{ij}(\theta_0)}{2t}
$$
If we average $D_{ij}$ over all the initial angles $\theta_0$,
$$
\\ \text{Asymmetric Brownian particle}
\\D_{ij}(t)=\frac{1}{2\pi}\int_0^{2\pi}d\theta_0 D_{ij} (t,\theta_0) =\bar D \delta_{ij}
\\\text{Asymmetric Active particle without harmonic trap}
\\D_{ij}(t)=\frac{1}{2\pi}\int_0^{2\pi}d\theta_0 D_{ij} (t,\theta_0)=[\bar D + \tau_r v_p^2-\frac{\tau_r v_p^2}{t}\tau_1(t)]\delta_{ij}
$$
 For $t \gg \tau_r$, $D_{ij}(t)\sim[\bar D + \tau_r v_p^2]\delta_{ij}$, which means that the asymmetry is lost at long times and the system behave like a passive brownian particle but with an enhanced diffusion.

For $t \ll\tau_r$, $D_{ij}(t)\sim[\bar D + \frac{ v_p^2}{4}]\delta_{ij}$, $\langle \Delta r^2(t) \rangle_{\theta_0}=4\bar D t+v_p^2t^2$, which shows ballistic behaviour at short times.



 

**The correlation $\langle \Delta x(t_1)\Delta x(t_2) \rangle_{\theta_0}$**
$$
\langle \Delta x(t_1)\Delta x(t_2) \rangle_{\theta_0} =v_p^2\int_0^{t_1} dt_1\prime\int_0^{t_2} dt_2\prime \  \langle \hat n_x(t_1\prime) \hat n_x(t_2\prime) \rangle_{\theta_0}+\int_0^{t_1}dt_1\prime\int_0^{t_2} dt_2\prime \  \langle\xi_x(t_1\prime)\xi_x(t_2\prime)\rangle_{\theta_0}
\\\langle \Delta x(t_1)\Delta x(t_2) \rangle_{\theta_0} =v_p^2\int_0^{t_1} dt_1\prime\int_0^{t_2} dt_2\prime \ [ \frac{1}{2}e^{-D_r(t_1\prime+t_2\prime-2 \min(t_1\prime,t_2\prime))}+\frac{M_{xx}(\theta_0)}{2}e^{-D_r(t_1\prime+t_2\prime+2 \min(t_1\prime,t_2\prime))}] \\+ 2K_BT\int_0^{t_1}dt_1\prime\int_0^{t_2} dt_2\prime \  \langle\Gamma_{xx}(\theta (t_1\prime))\rangle_{\theta_0} \ \delta(t_1\prime-t_2\prime)
\\\langle \Delta x(t_1)\Delta x(t_2) \rangle_{\theta_0} =v_p^2\int_0^{t_2} dt_2\prime\int_{t_2\prime}^{t_2} dt_1\prime \  \frac{1}{2}e^{-D_r(t_1\prime-t_2\prime)}+v_p^2\int_0^{t_2} dt_2\prime\int_{t_2\prime}^{t_1} dt_1\prime \  \frac{1}{2}e^{-D_r(t_1\prime-t_2\prime)}\\+v_p^2\frac{M_{xx}(\theta_0)}{2}\int_0^{t_2} dt_2\prime\int_{t_2\prime}^{t_2} dt_1\prime \ e^{-D_r(t_1\prime+3t_2\prime)}+v_p^2\frac{M_{xx}(\theta_0)}{2}\int_0^{t_2} dt_2\prime\int_{t_2\prime}^{t_1} dt_1\prime \ e^{-D_r(t_1\prime+3t_2\prime)}\\+2K_BT\int_0^{t_1}dt_1\prime\int_0^{t_2} dt_2\prime \ [\bar\Gamma  + \frac{\Delta \Gamma}{2} \langle \cos 2 \theta(t_1\prime))\rangle_{\theta_0} ]  \delta(t_1\prime-t_2\prime)
\\\langle \Delta x(t_1)\Delta x(t_2) \rangle_{\theta_0} =v_p^2\tau_r \Bigg[ 2t_2- \tau_1(t_2) -2 \tau_r\Big( e^{\frac{-(t_1-t_2)}{2\tau_r}}-e^{\frac{-t_1}{2\tau_r}} \Big) \Bigg] \\+ \cos 2\theta_0 \tau_r v_p^2\Bigg[\frac{2 \tau_4(t_2)}{3}-\frac{ \tau_1(t_2)}{3}-e^{\frac{-t_1}{2\tau_r}}\tau_3(t_2)\Bigg]
\\+2 K_B T \ \bar\Gamma t_2+ K_B T \Delta \Gamma  \ \cos 2 \theta_0 \tau_4(t_2)
$$

The two time correlation for a fixed initial angle $\theta_0$,
$$
\text{Asymmetric brownian particle}
\\\text{Taking }t_1>t_2
\\ \langle \Delta x(t_1)\Delta x(t_2)\rangle_{\theta_0} =2\bar D t_2[1+\frac{\Delta \Gamma}{2 \bar \Gamma}\cos 2\theta_0 \ \tau_4(t_2)]
\\ \text{Asymmetric Active brownian particle}
\\ \langle \Delta x(t_1)\Delta x(t_2)\rangle_{\theta_0} =2\bar D t_2[1+\frac{\Delta \Gamma}{2 \bar \Gamma}\cos 2\theta_0 \ \tau_4(t_2)]+v_p^2\tau_r \Bigg[ 2t_2- \tau_1(t_2) -2 \tau_r\Big( e^{\frac{-(t_1-t_2)}{2\tau_r}}-e^{\frac{-t_1}{2\tau_r}} \Big) \Bigg] \\+ \cos 2\theta_0 \tau_r v_p^2\Bigg[\frac{2 \tau_4(t_2)}{3}-\frac{ \tau_1(t_2)}{3}-e^{\frac{-t_1}{2\tau_r}}\tau_3(t_2)\Bigg]
$$
Average over all the initial angles $\theta_0$, we have a non stationary correlation, 
$$
\text{Asymmetric brownian particle}\\ \langle \Delta x(t_1)\Delta x(t_2)\rangle=2\bar D \min(t_1,t_2)
\\ \text{Asymmetric Active brownian particle},
\\ \langle \Delta x(t_1)\Delta x(t_2)\rangle =2\bar D\min(t_1,t_2)+ v_p^2\tau_r\min(t_1,t_2)(2- \tau_1) -2 v_p^2 \tau_r^2\Big( e^{-D_r|t_1-t_2|}-e^{-D_rt_1} \Big)
$$

when $t_1,t_2 \rightarrow \infin$, $|t_1-t_2| \rightarrow \text{finite}$,  
$$
\langle \Delta x(t_1)\Delta x(t_2)\rangle =2\bar D t_2+ v_p^2\tau_r t_2(2+ t_1+\frac{t_1^2D_r}{2}) -2 v_p^2 \tau_r^2\Big( e^{\frac{-|t_1-t_2|}{2\tau_r}}- \Big[1-D_rt_1+\frac{(D_r t_1)^2}{2}\Big]\Big)
$$
Putting $t_1 =t, t_2 =0$,

$$\langle \Delta x(t)\Delta x(0)\rangle= 2 v_p^2 \tau_r^2\Big(  \Big[1-D_rt+\frac{(D_r t)^2}{2}\Big]-e^{-D_rt}\Big)$$ 

