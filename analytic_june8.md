Calculation of $\langle R_{0,i}(t)R_{2,j}(t)\rangle_{\xi,\theta}$
$$
\langle R_{0,i}(t)R_{2,j}(t)\rangle_{\xi,\theta}= \langle R_{0,i}(t)\int_0^tdt^\prime e^{-\kappa \bar \Gamma(t-t^\prime)}\sum_k M_{jk}(t^\prime) R_{1,k}(t^\prime)\rangle_{\xi,\theta}
\\=\int_0^tdt^\prime e^{-\kappa \bar \Gamma(t-t^\prime)}\bigg \langle \sum_k M_{jk}(t^\prime)\langle R_{0,i}(t)R_{1,k}(t^\prime)\rangle_{\xi} \bigg \rangle_{\theta}
\\=\bigg (\frac{K_BT}{\kappa}\bigg)e^{-2\kappa \bar \Gamma t}\int_0^tdt^\prime\int_0^{t^{\prime}}dt_2^\prime (e^{2\kappa \bar \Gamma t_2^\prime}-1)\bigg \langle \sum_k M_{jk}(t^\prime)M_{ki}(t_2^\prime)\bigg \rangle_{\theta}\\+ v_p^2 \int_0^tdt^\prime e^{-\kappa \bar \Gamma(t-t^\prime)}\int_0^{t^\prime}dt^{\prime\prime} e^{\kappa \bar \Gamma(t+t^\prime)}\int_0^{t}dt_1^{\prime}\int_0^{t^{\prime\prime}}dt_2^{\prime\prime}e^{\kappa \bar \Gamma(t_1^{\prime}+t_2^{\prime\prime})}\bigg \langle \sum_{k,l} M_{jk}(t^\prime)M_{kl}(t^{\prime\prime})\hat n_i(t_1^{\prime})\hat n_l(t_2^{\prime\prime})\bigg \rangle_{\theta}\\
$$
Along $x$ and $y$  direction, $i=j$. Also, considering for the case of $t^{\prime}> t^{\prime\prime}>t_1^{\prime}>t_2^{\prime}$, 

we have
$$
\sum_{k,l} \bigg \langle M_{ik}(t^\prime)M_{kl}(t^{\prime\prime})\hat n_i(t_1^{\prime})\hat n_l(t_2^{\prime\prime})\bigg \rangle_{\theta}=e^{-D_r(t_1^{\prime}-t_2^{\prime}+4t^{\prime}-4t^{\prime\prime})}
$$
Substituting,
$$
\langle x_{0}(t)x_{2}(t)\rangle_{\xi,\theta}=\bigg (\frac{K_BT}{\kappa}\bigg)e^{-2\kappa \bar \Gamma t}\int_0^tdt^\prime\int_0^{t^{\prime}}dt_2^\prime (e^{2\kappa \bar \Gamma t_2^\prime}-1)\bigg \langle \cos2(\theta(t\prime)-\theta(t_2\prime)) \bigg \rangle_{\theta}\\+ v_p^2 \int_0^tdt^\prime e^{(2\kappa \bar \Gamma-4D_r)t^\prime}\int_0^{t^\prime}dt^{\prime\prime} e^{4D_r t^{\prime\prime}}\int_0^{t}dt_1^{\prime}\int_0^{t^{\prime\prime}}dt_2^{\prime\prime}e^{(\kappa \bar \Gamma-D_r)t_1^\prime}e^{(\kappa \bar \Gamma+D_r)t_2^{\prime\prime}}\\
$$
Simplification of the $2^{nd}$ term of eqn. 3,
$$
v_p^2 \int_0^tdt^\prime e^{(2\kappa \bar \Gamma-4D_r)t^\prime}\int_0^{t^\prime}dt^{\prime\prime} e^{4D_r t^{\prime\prime}}\int_0^{t}dt_1^{\prime}\int_0^{t^{\prime\prime}}dt_2^{\prime\prime}e^{(\kappa \bar \Gamma-D_r)t_1^\prime}e^{(\kappa \bar \Gamma+D_r)t_2^{\prime\prime}}
\\=v_p^2 \int_0^tdt^\prime e^{(2\kappa \bar \Gamma-4D_r)t^\prime}\int_0^{t^\prime}dt^{\prime\prime} e^{4D_r t^{\prime\prime}} \bigg [\int_{t^{\prime \prime}}^{t}dt_1^{\prime}\int_0^{t^{\prime\prime}}dt_2^{\prime\prime}e^{(\kappa \bar \Gamma-D_r)t_1^\prime}e^{(\kappa \bar \Gamma+D_r)t_2^{\prime\prime}}\\+2\int_0^{t^{\prime\prime}}dt_1^{\prime}\int_0^{t_1^{\prime}}dt_2^{\prime\prime}e^{(\kappa \bar \Gamma-D_r)t_1^\prime}e^{(\kappa \bar \Gamma+D_r)t_2^{\prime\prime}} \bigg ]
\\=v_p^2 \int_0^tdt^\prime e^{(2\kappa \bar \Gamma-4D_r)t^\prime}\int_0^{t^\prime}dt^{\prime\prime} e^{4D_r t^{\prime\prime}} \bigg[\frac{e^{(\kappa \bar \Gamma-D_r)t}(e^{(\kappa \bar \Gamma+D_r)t^{\prime\prime}}-1)}{(\kappa \bar \Gamma)^2-D_r^2} +\frac{(2-e^{2\kappa \bar \Gamma t^{\prime\prime}}-e^{(\kappa \bar \Gamma-D_r)t^{\prime\prime}})}{(\kappa \bar \Gamma)^2-D_r^2}\\+\frac{(e^{2\kappa \bar \Gamma t^{\prime\prime}}-1)}{\kappa \bar \Gamma(\kappa \bar \Gamma+D_r)} \bigg ]
$$
1st term of eqn. 4,
$$
v_p^2 \int_0^tdt^\prime e^{(2\kappa \bar \Gamma-4D_r)t^\prime}\int_0^{t^\prime}dt^{\prime\prime} e^{4D_r t^{\prime\prime}} \bigg[\frac{e^{(\kappa \bar \Gamma-D_r)t}(e^{(\kappa \bar \Gamma+D_r)t^{\prime\prime}}-1)}{(\kappa \bar \Gamma)^2-D_r^2} \bigg ]
\\=\frac{v_p^2e^{(\kappa \bar \Gamma-D_r)t}}{(\kappa \bar \Gamma)^2-D_r^2}\int_0^tdt^\prime e^{(2\kappa \bar \Gamma-4D_r)t^\prime}\bigg[\frac{e^{(\kappa \bar \Gamma+5D_r)t^{\prime}}-1)}{(\kappa \bar \Gamma+5D_r)}-\frac{e^{4D_rt^{\prime}}-1)}{(4D_r)}\bigg]
\\=\frac{v_p^2e^{(\kappa \bar \Gamma-D_r)t}}{(\kappa \bar \Gamma)^2-D_r^2}\bigg [\frac{1}{(\kappa \bar \Gamma+5D_r)}\bigg(\frac{e^{(3\kappa \bar \Gamma+D_r)t}-1)}{(3\kappa \bar \Gamma+D_r)}-\frac{e^{(2\kappa \bar \Gamma-4D_r)t}-1)}{(2\kappa \bar \Gamma-4D_r)}\bigg)\\-\frac{1}{4D_r}\bigg(\frac{e^{2\kappa \bar \Gamma t}-1)}{2\kappa \bar \Gamma}-\frac{e^{(2\kappa \bar \Gamma-4D_r)t}-1)}{(2\kappa \bar \Gamma-4D_r)}\bigg)\bigg]
$$
$2^{nd}$ term of eqn. 4,
$$
\frac{v_p^2}{(\kappa \bar \Gamma)^2-D_r^2} \int_0^tdt^\prime e^{(2\kappa \bar \Gamma-4D_r)t^\prime}\int_0^{t^\prime}dt^{\prime\prime} e^{4D_r t^{\prime\prime}} (2-e^{2\kappa \bar \Gamma t^{\prime\prime}}-e^{(\kappa \bar \Gamma-D_r)t^{\prime\prime}})
\\=\frac{v_p^2}{(\kappa \bar \Gamma)^2-D_r^2} \int_0^tdt^\prime e^{(2\kappa \bar \Gamma-4D_r)t^\prime}\bigg[\frac{2(e^{4D_rt^\prime}-1)}{4D_r}-\frac{(e^{(2\kappa \bar \Gamma +4D_r)t^\prime}-1)}{(2\kappa \bar \Gamma +4D_r)}-\frac{(e^{(\kappa \bar \Gamma +3D_r)t^\prime}-1)}{(\kappa \bar \Gamma +3D_r)}\bigg]
\\=\frac{v_p^2}{(\kappa \bar \Gamma)^2-D_r^2}\bigg[\frac{1}{2D_r}\int_0^tdt^\prime( e^{2\kappa \bar \Gamma t^\prime}- e^{(2\kappa \bar \Gamma-4D_r)t^\prime})-\frac{1}{(2\kappa \bar \Gamma +4D_r)}\int_0^tdt^\prime( e^{4\kappa \bar \Gamma t^\prime}- e^{(2\kappa \bar \Gamma-4D_r)t^\prime})\\-\frac{1}{(\kappa \bar \Gamma +3D_r)}\int_0^tdt^\prime( e^{(3\kappa \bar \Gamma -D_r) t^\prime}- e^{(2\kappa \bar \Gamma-4D_r)t^\prime})\bigg]
\\=\frac{v_p^2}{(\kappa \bar \Gamma)^2-D_r^2}\bigg[\frac{1}{2D_r}\bigg(\frac{e^{2\kappa \bar \Gamma t}-1}{2\kappa \bar \Gamma}-\frac{e^{(2\kappa \bar \Gamma-4D_r)t}-1}{(2\kappa \bar \Gamma-4D_r)}\bigg)-\frac{1}{(2\kappa \bar \Gamma +4D_r)}\bigg(\frac{e^{4\kappa \bar \Gamma t}-1}{2\kappa \bar \Gamma}-\frac{e^{(2\kappa \bar \Gamma-4D_r)t}-1}{(2\kappa \bar \Gamma-4D_r)}\bigg)\\-\frac{1}{(\kappa \bar \Gamma +3D_r)}\bigg(\frac{e^{(3\kappa \bar \Gamma-D_r) t}-1}{(3\kappa \bar \Gamma-D_r)}-\frac{e^{(2\kappa \bar \Gamma-4D_r)t}-1}{(2\kappa \bar \Gamma-4D_r)}\bigg)\bigg]
$$
$3^{rd}$ term of eqn. 4,
$$
\frac{v_p^2}{\kappa \bar \Gamma(\kappa \bar \Gamma+D_r)} \int_0^tdt^\prime e^{(2\kappa \bar \Gamma-4D_r)t^\prime}\int_0^{t^\prime}dt^{\prime\prime} (e^{(2\kappa \bar \Gamma+4D_r )t^{\prime\prime}}-e^{4D_rt^{\prime\prime}})
\\=\frac{v_p^2}{\kappa \bar \Gamma(\kappa \bar \Gamma+D_r)} \int_0^tdt^\prime e^{(2\kappa \bar \Gamma-4D_r)t^\prime}\bigg[ \frac{e^{(2\kappa \bar \Gamma+4D_r )t^{\prime}}-1}{(2\kappa \bar \Gamma+4D_r )}-\frac{e^{4D_rt^\prime}-1}{4D_r}\bigg]
\\=\frac{v_p^2}{\kappa \bar \Gamma(\kappa \bar \Gamma+D_r)}\bigg[\frac{1}{(2\kappa \bar \Gamma+4D_r )}\int_0^tdt^\prime(e^{4\kappa \bar \Gamma t^\prime}-e^{(2\kappa \bar \Gamma-4D_r)t^\prime})-\frac{1}{4D_r}\int_0^tdt^\prime(e^{2\kappa \bar \Gamma t^\prime}-e^{(2\kappa \bar \Gamma-4D_r)t^\prime})\bigg]
\\=\frac{v_p^2}{\kappa \bar \Gamma(\kappa \bar \Gamma+D_r)}\bigg[\frac{1}{(2\kappa \bar \Gamma+4D_r )}\bigg(\frac{e^{4\kappa \bar \Gamma t}-1}{4\kappa \bar \Gamma}-\frac{e^{(2\kappa \bar \Gamma-4D_r)t}-1}{(2\kappa \bar \Gamma-4D_r)}\bigg)\\-\frac{1}{4D_r}\bigg(\frac{e^{2\kappa \bar \Gamma t}-1}{2\kappa \bar \Gamma}-\frac{e^{(2\kappa \bar \Gamma-4D_r)t}-1}{(2\kappa \bar \Gamma-4D_r)}\bigg)\bigg]
$$
The final expression for $\langle x_{0}(t)x_{2}(t)\rangle_{\xi,\theta}$ is
$$
\langle x_{0}(t)x_{2}(t)\rangle_{\xi,\theta} = \bigg(\frac{K_BT}{\kappa} \bigg)\bigg[ \frac{1-e^{-2\kappa \bar \Gamma t}}{2\kappa\bar \Gamma(2\kappa\bar \Gamma+4D_r)}-\frac{te^{-2\kappa \bar \Gamma t}}{4D_r}+\frac{2\kappa\bar \Gamma(1-e^{-4D_rt})}{4D_r} \bigg]\\
+\frac{v_p^2}{(\kappa \bar \Gamma)^2-D_r^2}\bigg [\frac{e^{(\kappa \bar \Gamma-D_r)t}}{(\kappa \bar \Gamma+5D_r)}\bigg(\frac{e^{(3\kappa \bar \Gamma+D_r)t}-1)}{(3\kappa \bar \Gamma+D_r)}-\frac{e^{(2\kappa \bar \Gamma-4D_r)t}-1)}{(2\kappa \bar \Gamma-4D_r)}\bigg)\\-\frac{e^{(\kappa \bar \Gamma-D_r)t}}{4D_r}\bigg(\frac{e^{2\kappa \bar \Gamma t}-1)}{2\kappa \bar \Gamma}-\frac{e^{(2\kappa \bar \Gamma-4D_r)t}-1)}{(2\kappa \bar \Gamma-4D_r)}\bigg)
\\+\frac{1}{2D_r}\bigg(\frac{e^{2\kappa \bar \Gamma t}-1}{2\kappa \bar \Gamma}-\frac{e^{(2\kappa \bar \Gamma-4D_r)t}-1}{(2\kappa \bar \Gamma-4D_r)}\bigg)-\frac{1}{(2\kappa \bar \Gamma +4D_r)}\bigg(\frac{e^{4\kappa \bar \Gamma t}-1}{2\kappa \bar \Gamma}-\frac{e^{(2\kappa \bar \Gamma-4D_r)t}-1}{(2\kappa \bar \Gamma-4D_r)}\bigg)\\-\frac{1}{(\kappa \bar \Gamma +3D_r)}\bigg(\frac{e^{(3\kappa \bar \Gamma-D_r) t}-1}{(3\kappa \bar \Gamma-D_r)}-\frac{e^{(2\kappa \bar \Gamma-4D_r)t}-1}{(2\kappa \bar \Gamma-4D_r)}\bigg)\bigg]
\\+\frac{v_p^2}{\kappa \bar \Gamma(\kappa \bar \Gamma+D_r)}\bigg[\frac{1}{(2\kappa \bar \Gamma+4D_r )}\bigg(\frac{e^{4\kappa \bar \Gamma t}-1}{4\kappa \bar \Gamma}-\frac{e^{(2\kappa \bar \Gamma-4D_r)t}-1}{(2\kappa \bar \Gamma-4D_r)}\bigg)\\-\frac{1}{4D_r}\bigg(\frac{e^{2\kappa \bar \Gamma t}-1}{2\kappa \bar \Gamma}-\frac{e^{(2\kappa \bar \Gamma-4D_r)t}-1}{(2\kappa \bar \Gamma-4D_r)}\bigg)\bigg]
$$
