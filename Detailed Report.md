Detailed report on the Analysis of asymmetric particle in 2 D:

Brainstorming thoughts:

* Both brownian particle and the active matter undergo both rotational and translational diffusion. The only difference being that in case of active particle there will propulsion of the particle along the direction of the symmetry axis due to the gradient created at the interface leading to self phoresis.
* The shape asymmetry leads to a different transport properties along the symmetry axis. The rotational and translational diffusivity in this case will be characterise by a mobility matrix. 

* Brownian motion of an isolated ellipsoidal particle in 2-d have dissipative coupling of translational motion  to rotational motion due to their anisotropy, there will be crossover from short time anisotropy to long time isotropy. In the lab frame, the probability distribution of the position is non-Gaussian.

* Since the particle is ellipsoidal, there is going to be a longer and shorter axis. If $\gamma_a$ is the friction coefficient along the longer axis (motion parallel to the long axis) and $\gamma_b$ along the shorter axis(motion perpendicular to the axis).$\gamma_a$ is smaller than $\gamma_b$, Along the axis parallel , the surface area which is interacting with solvent molecules is small as compare to the one is perpendicular, hence $\gamma_a>\gamma_b$, i.e. $D_a>D_b$ . If rotation is not allowed, there will be independent diffusion along the two axis.

* When rotation is allowed, the system will undergo rotational diffusion with diffusion coefficient $D_r$ . There is a rotational diffusion time, $\tau_r = \frac{1}{2D_r}$ .Average over the trajectory for a fixed initial angle $\theta_0$,the particle will undergo anisotropic diffusion with the time $\tau_r$, and crossing over to an isotropic diffusion for $t \gg \tau_r$. 

* As we already know, the particle with a given initial angle will diffuse more rapidly along the longer axis.  For $\theta_0=0$,at $ t\ll \tau_r$ ,$D_{xx}= \frac{\langle [\Delta  x(t)]^2\rangle_{0}}{2t}= D_a$ and $D_{yy}= \frac{\langle [\Delta  y(t)]^2\rangle_{0}}{2t}= \frac{\langle [\Delta  x(t)]^2\rangle_{\frac{\pi}{2}}}{2t}=D_b$ and for $t \gg \tau_r$, isotropic diffusion $D_{xx} =D_{yy}= \bar D = (D_a +D_b)$. The reason being after long time $t \gg \tau_r$ ,the memory of the initial angle is lost, when we average over all the trajectories, the diffusion along the x and y axis will be the same and hence isotropic diffusion.

* MSD of the body frame and lab frame average over all trajectory with different initial angle are all diffusive. They are all diffusive with $\langle [\Delta \tilde x(t)]\rangle =2 D_a t,\langle [\Delta \tilde y(t)]\rangle =2 D_b t$ $\{$ Body Frame $\}$ and  $\langle [\Delta  x(t)]\rangle =\langle [\Delta  y(t)]\rangle =(D_a+D_b) t$ in the Lab Frame.

* The random noise contribution from translational and rotational dynamics is given by $\xi_r$ and $\xi_{\theta}$, where $\xi_{\theta}$ is Gaussian at all times however $\xi_r$ will be Gaussian only for a fixed angle $\theta(t)$. The PDF for the body frame displacement is Gaussian at all times since $\xi_r$ is Gaussian within this domain.

* In the lab frame, due to the coupling of the translational and rotational diffusion, the PDF is no longer Gaussian. 

* However, for a fixed initial angle $\theta_0$, at short times and very large times,$t \rightarrow \infin $ , the distribution is Gaussian. At very large times, $\Delta x(t)$ will be the sum of the displacement from $ \sim \frac{t}{\tau_r}$ independent steps, and by central limit theorem, the PDF is Gaussian. The non Gaussian parameter will be maximum at times of order  $t =t_r$. The non Gaussian parameter are the given by fourth and higher order cummulants .

* Non Gaussian Parameter(NGP) effect dependence:

  * Ensemble average of $\theta$, (NGP) is maximum at t=0 and vanishes as $t \rightarrow \infin $. How?

  At $t \rightarrow 0$, during the displacement the orientation will not change. Those $\Delta x$ with the same $\theta_0$ follows Gaussian statistics. However, averaging Gaussian PDF with different $\theta_0$ over $[0,2\pi]$ yields non Gaussian PDF.

  * Larger $\frac{D_a}{D_b}$ leads to larger deviation of Gaussian nature. [Anisotropy leads to NGP]

#### Active Brownian motion of an asymmetric rigid particle

* Studying the case of active brownian particle when the asymmetric force and the particle orientation are in line. In case of an isolated rod, both the longitudinal and transverse diffusion coefficients are enhanced and they will assume the same value at different times. 
* The model consist of an active brownian particle self propelled along the long axis and undergoing brownian motion in 2 D.
* In the cases which will be studied further, we will specifically consider the case for a fixed initial angle $\theta(t)$, as the translational noise will be Gaussian only for this case. The self propulsion do not induced torque so the system will undergo free orientation and hence angular displacement still obey Gaussian statistics.
* As already discuss above, even for a fixed initial angle $\theta$, at order of times $\sim \frac{t}{\tau_r}$ , the system will show non Gaussian nature due to its asymmetry  inducing a dissipative coupling of translational to rotational motion.
* In the absence of the external torque $\tau$ and force $F$, the mean square angular displacement is linear in $t$.

$$
\langle [\Delta \theta(t)]^2 \rangle =2 D_r t\\ \langle [\Delta r(t)]^2 \rangle =[2 D t+4\tau_rv_p^2[1-2\tau_r(1-e^{-\frac{t}{2\tau_r}})] \frac{\tau_1}{t}]\delta_{ij}
$$

* Averaging over all the initial angle $\theta_0$, time dependent diffusion tensor is given by
  $$
  D_{ij}(t) =D+\tau_r v_p^2-\tau_r v_p^2\frac{\tau_1}{t}
  $$
  which shows that the system is no longer diffusion due to its time dependence.

* when $t\gg \tau_r$, directional memory lose and the system behaves like a spherical brownian particle with an enhanced diffusion coefficient,$D_{ij}(t) \rightarrow (D+\tau_r v_p^2)\delta_{ij}$

* when $t \ll \tau_r$, the MSD,$ \langle [\Delta r(t)]^2 \rangle \sim2 D t+v_p^2t^2$, indicating ballistic behaviour at short times.

#### Persistence in Brownian motion of an ellipsoidal particle in two dimensions

