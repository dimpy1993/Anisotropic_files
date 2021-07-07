Calculation of $\langle R_{0,i}(t_1)R_{1,j}(t_2) \rangle _{\xi,\theta}$
$$
\langle R_{0,i}(t_1)R_{1,j}(t_2) \rangle _{\xi} = \langle R_{0,i}(t_1)\int_0^{t_2}dt_2^\prime e^{-\kappa \bar \Gamma (t_2-t_2^\prime)} \sum_kM_{jk}(t_2^\prime)R_{0,k}(t_2^\prime) \rangle _{\xi}
\\=\int_0^{t_2}dt_2^\prime e^{-\kappa \bar \Gamma (t_2-t_2^\prime)} \sum_kM_{jk}(t_2^\prime)\langle R_{0,i}(t_1)R_{0,k}(t_2^\prime) \rangle _{\xi}
\\=\int_0^{t_2}dt_2^\prime e^{-\kappa \bar \Gamma (t_2-t_2^\prime)} \sum_kM_{jk}(t_2^\prime)\bigg[ \bigg(\frac{K_B T}{\kappa}\bigg)\delta_{ik} \bigg( e^{-\kappa \bar \Gamma(t_1-t_2^\prime)}-e^{-\kappa \bar \Gamma(t_1+t_2^\prime)}\bigg)+ K_BT \Delta \Gamma e^{-\kappa \bar \Gamma(t_1+t_2^\prime)} \\\int_0^{min(t_1,t_2^\prime)}dt_1^\prime  e^{2\kappa \bar \Gamma t_1^\prime}M_{ik}(t_1^\prime)+v_p^2 e^{-\kappa \bar \Gamma(t_1+t_2^\prime)} \int_0^{t_1} dt_1^\prime\int_0^{t_2^\prime} dt^{\prime\prime}e^{\kappa \bar \Gamma(t_1^\prime+t^{\prime\prime})}\langle \hat n_i(t_1^\prime)n_k(t^{\prime\prime}) \rangle_{\xi} \bigg]
\\=\bigg(\frac{K_B T}{\kappa}\bigg)e^{-\kappa \bar \Gamma (t_1+t_2)}\int_0^{t_2}dt_2^\prime e^{-\kappa \bar \Gamma t_2^\prime}M_{ji}(t_2^\prime)  \bigg( e^{-\kappa \bar \Gamma t_2^\prime}-e^{-\kappa \bar \Gamma t_2^\prime}\bigg)+ K_BT \Delta \Gamma e^{-\kappa \bar \Gamma(t_1+t_2)} \\\int_0^{t_2}dt_2^\prime \int_0^{min(t_1,t_2^\prime)}dt_1^\prime  e^{2\kappa \bar \Gamma t_1^\prime}\sum_kM_{jk}(t_2^\prime)M_{ik}(t_1^\prime)+\\
v_p^2e^{-\kappa \bar \Gamma (t_1+t_2)}\int_0^{t_2}dt_2^\prime \int_0^{t_1}dt_1^\prime \int_0^{t_2^\prime}dt^{\prime\prime}e^{\kappa \bar \Gamma(t_1^\prime+t^{\prime\prime})} \sum_kM_{jk}(t_2^\prime)\hat n_i(t_1^\prime)n_k(t^{\prime\prime})
$$

$$
\langle R_{0,i}(t_1)R_{1,j}(t_2) \rangle _{\xi,\theta_0} =\bigg(\frac{K_B T}{\kappa}\bigg)e^{-\kappa \bar \Gamma (t_1+t_2)}\int_0^{t_2}dt_2^\prime e^{-\kappa \bar \Gamma t_2^\prime}\langle M_{ji} \rangle_{\theta_0} (t_2^\prime)  \bigg( e^{-\kappa \bar \Gamma t_2^\prime}-e^{-\kappa \bar \Gamma t_2^\prime}\bigg)+ \\K_BT \Delta \Gamma e^{-\kappa \bar \Gamma(t_1+t_2)} \int_0^{t_2}dt_2^\prime \int_0^{min(t_1,t_2^\prime)}dt_1^\prime  e^{2\kappa \bar \Gamma t_1^\prime}\sum_k\langle M_{jk}(t_2^\prime)M_{ik}(t_1^\prime)\rangle_{\theta_0}+\\
v_p^2e^{-\kappa \bar \Gamma (t_1+t_2)}\int_0^{t_2}dt_2^\prime \int_0^{t_1}dt_1^\prime \int_0^{t_2^\prime}dt^{\prime\prime}e^{\kappa \bar \Gamma(t_1^\prime+t^{\prime\prime})} \sum_k \bigg\langle M_{jk}(t_2^\prime)\hat n_i(t_1^\prime)n_k(t^{\prime\prime}) \bigg \rangle_{\theta_0}
$$
Along the $x$ and $y$ direction, $i=j$. Also, Considering $t_2^\prime>t_1^\prime>t^{\prime\prime}$

we have
$$
\sum_k \bigg\langle M_{jk}(t_2^\prime)\hat n_i(t_1^\prime)n_k(t^{\prime\prime}) \bigg \rangle_{\theta_0} = e^{-D_r(4t_2^\prime-3t_1^\prime-t^{\prime\prime})}
$$

$$
\langle x_0(t_1) x_1(t_2)\rangle_{\xi,\theta_0} = \bigg(\frac{K_BT}{\kappa} \bigg)\cos \theta_0 e^{-\kappa \bar \Gamma t_1} \bigg(\frac{e^{(\kappa \bar \Gamma-4D_r) t_2} -e^{-\kappa \bar \Gamma t_2} }{2\kappa \bar \Gamma-4D_r}-\frac{e^{-\kappa \bar \Gamma t_2} -e^{-(\kappa \bar \Gamma+4D_r) t_2}}{4D_r} \bigg)+\\ \bigg(\frac{K_BT}{\kappa} \bigg)\bigg(\frac{\Delta \Gamma}{2\bar \Gamma}\bigg)e^{-\kappa \bar \Gamma t_1}\bigg[\frac{e^{\kappa \bar \Gamma t_2} -e^{-\kappa \bar \Gamma t_2}}{2\kappa \bar \Gamma+4D_r}-\bigg( \frac{2\kappa \bar \Gamma}{4D_r}\bigg)\frac{e^{-\kappa \bar \Gamma t_2} -e^{-(\kappa \bar \Gamma+4D_r) t_2}}{\kappa \bar \Gamma+4D_r}  \bigg]+\\
v_p^2e^{-\kappa \bar \Gamma (t_1+t_2)}\int_0^{t_2}dt_2^\prime e^{-4D_rt_2^\prime}\int_0^{t_1}dt_1^\prime e^{(\kappa \bar \Gamma +3D_r)t_1^\prime} \int_0^{t_2^\prime}dt^{\prime\prime}e^{(\kappa \bar \Gamma +D_r)t^{\prime\prime}}
$$

Simplification of the $3^{rd}$ term of eqn. 4,
$$
v_p^2e^{-\kappa \bar \Gamma (t_1+t_2)}\int_0^{t_2}dt_2^\prime e^{-4D_rt_2^\prime}\int_0^{t_1}dt_1^\prime e^{(\kappa \bar \Gamma +3D_r)t_1^\prime} \int_0^{t_2^\prime}dt^{\prime\prime}e^{(\kappa \bar \Gamma +D_r)t^{\prime\prime}}\\=
v_p^2e^{-\kappa \bar \Gamma (t_1+t_2)}\int_0^{t_2}dt_2^\prime e^{-4D_rt_2^\prime}
\bigg[2\int_0^{t_2^\prime}dt_1^\prime e^{(\kappa \bar \Gamma +3D_r)t_1^\prime}\int_0^{t_1^\prime}dt^{\prime\prime}e^{(\kappa \bar \Gamma +D_r)t^{\prime\prime}}+\\\int_{t_2^\prime}^{t_1}dt_1^\prime e^{(\kappa \bar \Gamma +3D_r)t_1^\prime} \int_0^{t_2^\prime}dt^{\prime\prime}e^{(\kappa \bar \Gamma +D_r)t^{\prime\prime}}\bigg]
\\=v_p^2e^{-\kappa \bar \Gamma (t_1+t_2)}\int_0^{t_2}dt_2^\prime e^{-4D_rt_2^\prime}
\bigg[ \frac{2}{\kappa \bar \Gamma +D_r}\bigg(\frac{e^{(2\kappa \bar \Gamma +4D_r)t_2^\prime}-1}{(2\kappa \bar \Gamma +4D_r)}-\frac{e^{(\kappa \bar \Gamma +3D_r)t_2^\prime}-1}{(\kappa \bar \Gamma +3D_r)}\bigg)+\\\frac{(e^{(\kappa \bar \Gamma +3D_r)t_1}-e^{(\kappa \bar \Gamma +3D_r)t_2^\prime})(e^{(\kappa \bar \Gamma +D_r)t_2^\prime}-1)}{(\kappa \bar \Gamma +D_r)(\kappa \bar \Gamma +3D_r)} \bigg]
\\=v_p^2e^{-\kappa \bar \Gamma (t_1+t_2)}\int_0^{t_2}dt_2^\prime 
\bigg[ \frac{2}{\kappa \bar \Gamma +D_r}\bigg(\frac{e^{(2\kappa \bar \Gamma +4D_r)t_2^\prime}-e^{-4D_rt_2^\prime}}{2\kappa \bar \Gamma }-\frac{e^{(\kappa \bar \Gamma -D_r)t_2^\prime}-e^{-4D_rt_2^\prime}}{(\kappa \bar \Gamma +3D_r)}\bigg)+\\\frac{(e^{(\kappa \bar \Gamma +3D_r)t_1}-e^{(\kappa \bar \Gamma +3D_r)t_2^\prime})(e^{(\kappa \bar \Gamma -3D_r)t_2^\prime}-e^{-4D_rt_2^\prime})}{(\kappa \bar \Gamma +D_r)(\kappa \bar \Gamma +3D_r)} \bigg]
$$

$$
\\=v_p^2e^{-\kappa \bar \Gamma (t_1+t_2)}\bigg[ \frac{2}{2\kappa \bar \Gamma(\kappa \bar \Gamma +D_r)}\bigg(\frac{e^{(2\kappa \bar \Gamma +4D_r)t_2}-1}{(2\kappa \bar \Gamma +4D_r)}-\frac{1-e^{-4D_rt_2}}{4D_r}\bigg)\\-\frac{2}{(\kappa \bar \Gamma +D_r)(\kappa \bar \Gamma +3D_r)}\bigg(\frac{e^{(\kappa \bar \Gamma -D_r)t_2}-1}{(\kappa \bar \Gamma -D_r)}-\frac{1-e^{-4D_rt_2}}{4D_r} \bigg)+\\\int_0^{t_2}dt_2^\prime \frac{e^{(\kappa \bar \Gamma +3D_r)t_1}(e^{(\kappa \bar \Gamma -3D_r)t_2^\prime}-e^{-4D_rt_2^\prime})-(e^{2\kappa \bar \Gamma t_2^\prime}-e^{(\kappa \bar \Gamma -D_r)t_2^\prime})}{(\kappa \bar \Gamma +D_r)(\kappa \bar \Gamma +3D_r)} \bigg]
\\=v_p^2e^{-\kappa \bar \Gamma (t_1+t_2)}\bigg[ \frac{2}{2\kappa \bar \Gamma(\kappa \bar \Gamma +D_r)}\bigg(\frac{e^{(2\kappa \bar \Gamma +4D_r)t_2}-1}{(2\kappa \bar \Gamma +4D_r)}-\frac{1-e^{-4D_rt_2}}{4D_r}\bigg)\\-\frac{2}{(\kappa \bar \Gamma +D_r)(\kappa \bar \Gamma +3D_r)}\bigg(\frac{e^{(\kappa \bar \Gamma -D_r)t_2}-1}{(\kappa \bar \Gamma -D_r)}-\frac{1-e^{-4D_rt_2}}{4D_r} \bigg)+\\
\frac{1}{(\kappa \bar \Gamma +D_r)(\kappa \bar \Gamma +3D_r)}\bigg\{e^{(\kappa \bar \Gamma +3D_r)t_1} \bigg(\frac{e^{(\kappa \bar \Gamma -3D_r)t_2}-1}{(\kappa \bar \Gamma -3D_r)}-\frac{1-e^{-4D_rt_2}}{4D_r} \bigg)-\\\bigg(\frac{e^{2\kappa \bar \Gamma t_2}-1}{2\kappa \bar \Gamma}-\frac{e^{(\kappa \bar \Gamma -D_r)t_2}-1}{(\kappa \bar \Gamma -D_r)}\bigg)
\bigg\}
$$
The final expression for $\langle x_0(t_1) x_1(t_2)\rangle_{\xi,\theta_0}$ is 
$$
\langle x_0(t_1) x_1(t_2)\rangle_{\xi,\theta_0} = \bigg(\frac{K_BT}{\kappa} \bigg)\cos \theta_0 e^{-\kappa \bar \Gamma t_1} \bigg(\frac{e^{(\kappa \bar \Gamma-4D_r) t_2} -e^{-\kappa \bar \Gamma t_2} }{2\kappa \bar \Gamma-4D_r}-\frac{e^{-\kappa \bar \Gamma t_2} -e^{-(\kappa \bar \Gamma+4D_r) t_2}}{4D_r} \bigg)+\\ \bigg(\frac{K_BT}{\kappa} \bigg)\bigg(\frac{\Delta \Gamma}{2\bar \Gamma}\bigg)e^{-\kappa \bar \Gamma t_1}\bigg[\frac{e^{\kappa \bar \Gamma t_2} -e^{-\kappa \bar \Gamma t_2}}{2\kappa \bar \Gamma+4D_r}-\bigg( \frac{2\kappa \bar \Gamma}{4D_r}\bigg)\frac{e^{-\kappa \bar \Gamma t_2} -e^{-(\kappa \bar \Gamma+4D_r) t_2}}{\kappa \bar \Gamma+4D_r}  \bigg]+\\
v_p^2e^{-\kappa \bar \Gamma (t_1+t_2)}\bigg[ \frac{2}{2\kappa \bar \Gamma(\kappa \bar \Gamma +D_r)}\bigg(\frac{e^{(2\kappa \bar \Gamma +4D_r)t_2}-1}{(2\kappa \bar \Gamma +4D_r)}-\frac{1-e^{-4D_rt_2}}{4D_r}\bigg)\\-\frac{2}{(\kappa \bar \Gamma +D_r)(\kappa \bar \Gamma +3D_r)}\bigg(\frac{e^{(\kappa \bar \Gamma -D_r)t_2}-1}{(\kappa \bar \Gamma -D_r)}-\frac{1-e^{-4D_rt_2}}{4D_r} \bigg)+\\
\frac{1}{(\kappa \bar \Gamma +D_r)(\kappa \bar \Gamma +3D_r)}\bigg\{e^{(\kappa \bar \Gamma +3D_r)t_1} \bigg(\frac{e^{(\kappa \bar \Gamma -3D_r)t_2}-1}{(\kappa \bar \Gamma -3D_r)}-\frac{1-e^{-4D_rt_2}}{4D_r} \bigg)-\\\bigg(\frac{e^{2\kappa \bar \Gamma t_2}-1}{2\kappa \bar \Gamma}-\frac{e^{(\kappa \bar \Gamma -D_r)t_2}-1}{(\kappa \bar \Gamma -D_r)}\bigg)
\bigg\}
$$
