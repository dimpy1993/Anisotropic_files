Calculation of $\langle R_{1,i}(t)R_{1,j}(t) \rangle$
$$
\langle R_{1,i}(t)R_{1,j}(t) \rangle = \int_0^tdt^\prime\int_0^tdt^{\prime\prime}e^{-\kappa \bar\Gamma(t-t^\prime)}e^{-\kappa \bar\Gamma(t-t^{\prime\prime})} \langle \sum_{k,l}M_{ik}(t^\prime)M_{jl}(t^{\prime\prime})\langle R_{0,k}(t^{\prime
})R_{0,l}(t^{\prime\prime})\rangle_{\xi}\rangle_{\theta}
\\=2K_BT\int_0^tdt^\prime\int_0^tdt^{\prime\prime}e^{-\kappa \bar\Gamma(t-t^\prime)}e^{-\kappa \bar\Gamma(t-t^{\prime\prime})}\langle \sum_{k,l}M_{ik}(t^\prime)M_{jl}(t^{\prime\prime})\int_0^{t^\prime}dt_1^\prime\int_0^{t^{\prime\prime}}dt_2^{\prime}e^{-\kappa \bar\Gamma(t^\prime-t_1^\prime)}e^{-\kappa \bar\Gamma(t^{\prime\prime}-t_2^{\prime})}\\ \bigg[\bar \Gamma \delta _{kl}+\frac{\Delta \Gamma}{2} M_{kl}(t_1^{\prime}) \bigg]\delta(t_1^{\prime}-t_2^{\prime})  \rangle_{\theta} +v_p^2 e^{-2\kappa \bar \Gamma t}\int_0^tdt^\prime\int_0^tdt^{\prime\prime}e^{\kappa \bar\Gamma(t^\prime+t^{\prime\prime})}\bigg\langle \sum_{k,l}M_{ik}(t^\prime)M_{jl}(t^{\prime\prime})\\\int_0^{t^\prime}dt_1^\prime\int_0^{t^{\prime\prime}}dt_2^{\prime}e^{-\kappa \bar\Gamma(t^\prime-t_1^\prime)}e^{-\kappa \bar\Gamma(t^{\prime\prime}-t_2^{\prime})} \hat n_k(t_1^\prime)\hat n_l(t_2^\prime) \bigg \rangle_{\theta}
$$
Ignoring the term proportional to $\Delta \Gamma$, we have
$$
\langle R_{1,i}(t)R_{1,j}(t) \rangle =2K_BT \bar \Gamma e^{-2\kappa \bar\Gamma t} \int_0^tdt^\prime\int_0^tdt^{\prime\prime}\int_0^{min(t^\prime,t^{\prime\prime})}dt_1^{\prime}e^{2\kappa \bar\Gamma t_1^\prime}\langle \sum_{k,l}M_{ik}(t^\prime)M_{jl}(t^{\prime\prime})\delta_{kl} \rangle_{\theta} \\+v_p^2 e^{-2\kappa \bar \Gamma t}\int_0^tdt^\prime\int_0^tdt^{\prime\prime}\int_0^{t^\prime}dt_1^\prime\int_0^{t^{\prime\prime}}dt_2^{\prime}e^{\kappa \bar\Gamma(t_1^\prime+t_2^{\prime})}\bigg\langle \sum_{k,l}M_{ik}(t^\prime)M_{jl}(t^{\prime\prime})\hat n_k(t_1^\prime)\hat n_l(t_2^\prime) \bigg \rangle_{\theta}
$$
Along $x$ and $y$ direction, $i=j$. Considering the case for $t^\prime>t^{\prime\prime}>t_1^\prime>t_2^\prime$,
$$
\langle\sum_{k,l}M_{ik}(t^\prime)M_{ik}(t^{\prime\prime}) \rangle_{\theta}=\langle \cos 2 [\theta(t^\prime)-\theta(t^{\prime\prime})] \rangle_{\theta_0}=e^{-4D_r(t^\prime-t^{\prime\prime})}
\\\bigg\langle \sum_{k,l}M_{ik}(t^\prime)M_{jl}(t^{\prime\prime})\hat n_k(t_1^\prime)\hat n_l(t_2^\prime) \bigg \rangle_{\theta}=e^{-D_r(4t^\prime-4t^{\prime\prime}+t_1^\prime-t_2^\prime)}
$$
Substituting we have,
$$
\langle x_{1}(t)x_{1}(t) \rangle =2K_BT \bar \Gamma e^{-2\kappa \bar\Gamma t} \int_0^tdt^\prime\int_0^tdt^{\prime\prime}\int_0^{t^{\prime\prime}}dt_1^{\prime}e^{2\kappa \bar\Gamma t_1^\prime}e^{-4D_r(t^\prime-t^{\prime\prime})}+\\
v_p^2 e^{-2\kappa \bar \Gamma t}\int_0^tdt^\prime\int_0^tdt^{\prime\prime}\int_0^{t^\prime}dt_1^\prime\int_0^{t^{\prime\prime}}dt_2^{\prime}e^{\kappa \bar\Gamma(t_1^\prime+t_2^{\prime})}e^{-D_r(4t^\prime-4t^{\prime\prime}+t_1^\prime-t_2^\prime)}
$$
Evaluation of first term:
$$
2K_BT \bar \Gamma e^{-2\kappa \bar\Gamma t} \int_0^tdt^\prime\int_0^tdt^{\prime\prime}\int_0^{t^{\prime\prime}}dt_1^{\prime}e^{2\kappa \bar\Gamma t_1^\prime}e^{-4D_r(t^\prime-t^{\prime\prime})}\\=
2K_BT \bar \Gamma e^{-2\kappa \bar\Gamma t} \int_0^tdt^\prime\int_0^tdt^{\prime\prime}
e^{-4D_r(t^\prime-t^{\prime\prime})}\frac{e^{2\kappa \bar\Gamma t^{\prime\prime}}-1}{2\kappa \bar\Gamma}\\
=\frac{K_BT }{\kappa}e^{-2\kappa \bar\Gamma t} \int_0^tdt^\prime e^{-4D_rt^\prime}\int_0^tdt^{\prime\prime} \bigg(e^{(2\kappa \bar \Gamma+4D_r)t^{\prime\prime}}- e^{4D_rt^{\prime\prime}}\bigg)
\\=\frac{K_BT }{\kappa}e^{-2\kappa \bar\Gamma t} \times2 \int_0^tdt^\prime e^{-4D_rt^\prime}\int_0^{t^\prime}dt^{\prime\prime}\bigg(e^{(2\kappa \bar \Gamma+4D_r)t^{\prime\prime}}- e^{4D_rt^{\prime\prime}}\bigg)
\\=\frac{2K_BT }{\kappa}e^{-2\kappa \bar\Gamma t}\int_0^tdt^\prime e^{-4D_rt^\prime}\bigg(\frac{e^{(2\kappa \bar \Gamma+4D_r)t^{\prime}}-1}{(2\kappa \bar \Gamma+4D_r)}- \frac{e^{4D_rt^{\prime}}-1}{4D_r}\bigg)
\\=\frac{2K_BT }{\kappa}e^{-2\kappa \bar\Gamma t}\int_0^tdt^\prime \bigg(\frac{e^{2\kappa \bar \Gamma t^{\prime}}-e^{-4D_rt^\prime}}{(2\kappa \bar \Gamma+4D_r)}- \frac{1-e^{-4D_rt^{\prime}}}{4D_r}\bigg)
\\=\frac{2K_BT }{\kappa}e^{-2\kappa \bar\Gamma t}\bigg(\frac{e^{2\kappa \bar \Gamma t}-1}{2\kappa \bar \Gamma(2\kappa \bar \Gamma+4D_r)}- \frac{1-e^{-4D_rt}}{4D_r(2\kappa \bar \Gamma+4D_r)}-\frac{t}{4D_r}+\frac{1-e^{-4D_rt}}{16D_r^2}\bigg)
\\=\frac{K_BT }{\kappa}\bigg(\frac{1-e^{-2\kappa \bar \Gamma t}}{\kappa \bar \Gamma(2\kappa \bar \Gamma+4D_r)}+\kappa \bar \Gamma \frac{e^{-2\kappa \bar \Gamma t}-e^{-(2\kappa \bar \Gamma+4D_r)t}}{4D_r^2(2\kappa \bar \Gamma+4D_r)}-\frac{te^{-2\kappa \bar\Gamma t}}{2D_r}\bigg)
$$
Evaluation of the $2^{nd}$ term:
$$
v_p^2 e^{-2\kappa \bar \Gamma t}\int_0^tdt^\prime\int_0^tdt^{\prime\prime}\int_0^{t^\prime}dt_1^\prime\int_0^{t^{\prime\prime}}dt_2^{\prime}e^{\kappa \bar\Gamma(t_1^\prime+t_2^{\prime})}e^{-D_r(4t^\prime-4t^{\prime\prime}+t_1^\prime-t_2^\prime)}
\\=v_p^2 e^{-2\kappa \bar \Gamma t}\int_0^tdt^\prime\int_0^tdt^{\prime\prime} e^{-4D_r(t^\prime-t^{\prime\prime})} \bigg( 2\int_0^{t^{\prime\prime}}dt_1^\prime\int_0^{t^{\prime}}dt_2^{\prime}+\int_{t^{\prime\prime}}^{t^\prime}dt_1^\prime\int_0^{t^{\prime\prime}}dt_2^{\prime}\bigg)e^{(\kappa \bar\Gamma -D_r)t_1^\prime}e^{(\kappa \bar\Gamma +D_r)t_2^\prime}
\\=2v_p^2 e^{-2\kappa \bar \Gamma t}\int_0^tdt^\prime\int_0^tdt^{\prime\prime} e^{-4D_r(t^\prime-t^{\prime\prime})}\int_0^{t^{\prime\prime}}dt_1^\prime e^{(\kappa \bar\Gamma -D_r)t_1^\prime}\int_0^{t^{\prime}}dt_2^{\prime}e^{(\kappa \bar\Gamma +D_r)t_2^\prime}+\\v_p^2 e^{-2\kappa \bar \Gamma t}\int_0^tdt^\prime\int_0^tdt^{\prime\prime} e^{-4D_r(t^\prime-t^{\prime\prime})}\int_{t^{\prime\prime}}^{t^{\prime}} dt_1^\prime e^{(\kappa \bar\Gamma -D_r)t_1^\prime}\int_0^{t^{\prime\prime}}dt_2^{\prime}e^{(\kappa \bar\Gamma +D_r)t_2^\prime}
\\=2v_p^2 e^{-2\kappa \bar \Gamma t}\int_0^tdt^\prime\int_0^tdt^{\prime\prime} e^{-4D_r(t^\prime-t^{\prime\prime})}\bigg( \frac{e^{(\kappa \bar\Gamma -D_r)t^{\prime\prime}}-1}{(\kappa \bar\Gamma -D_r)}\bigg)\bigg(\frac{e^{(\kappa \bar\Gamma +D_r)t^{\prime}}-1}{(\kappa \bar\Gamma +D_r)} \bigg)+
\\v_p^2 e^{-2\kappa \bar \Gamma t}\int_0^tdt^\prime\int_0^tdt^{\prime\prime} e^{-4D_r(t^\prime-t^{\prime\prime})}\bigg( \frac{e^{(\kappa \bar\Gamma -D_r)t^{\prime}}-e^{(\kappa \bar\Gamma -D_r)t^{\prime\prime}}}{(\kappa \bar\Gamma -D_r)}\bigg)\bigg(\frac{e^{(\kappa \bar\Gamma +D_r)t^{\prime\prime}}-1}{(\kappa \bar\Gamma +D_r)} \bigg)
\\=\frac{2v_p^2 e^{-2\kappa \bar \Gamma t}}{(\kappa \bar\Gamma)^2 -D_r^2}\int_0^tdt^\prime\int_0^tdt^{\prime\prime}(e^{(\kappa \bar\Gamma +3D_r)t^{\prime\prime}}-e^{4D_rt^{\prime\prime}})(e^{(\kappa \bar\Gamma -3D_r)t^{\prime}}-e^{-4D_rt^{\prime}})+\\
\frac{v_p^2 e^{-2\kappa \bar \Gamma t}}{(\kappa \bar\Gamma)^2 -D_r^2}\int_0^tdt^\prime\int_0^tdt^{\prime\prime}\bigg(e^{(\kappa \bar\Gamma +5D_r)t^{\prime\prime}}-e^{4D_rt^{\prime\prime}}\bigg)e^{(\kappa \bar\Gamma -5D_r)t^{\prime}}-\bigg(e^{(2\kappa \bar\Gamma +4D_r)t^{\prime\prime}}-e^{(\kappa \bar\Gamma +3D_r)t^{\prime\prime}}\bigg)e^{-4D_rt^{\prime}}
$$
 Solving the $1^{st}$ term of equation. 6,
$$
\frac{2v_p^2 e^{-2\kappa \bar \Gamma t}}{(\kappa \bar\Gamma)^2 -D_r^2}\int_0^tdt^\prime\int_0^tdt^{\prime\prime}(e^{(\kappa \bar\Gamma +3D_r)t^{\prime\prime}}-e^{4D_rt^{\prime\prime}})(e^{(\kappa \bar\Gamma -3D_r)t^{\prime}}-e^{-4D_rt^{\prime}})
\\=\frac{4v_p^2 e^{-2\kappa \bar \Gamma t}}{(\kappa \bar\Gamma)^2 -D_r^2}\int_0^tdt^\prime (e^{(\kappa \bar\Gamma -3D_r)t^{\prime}}-e^{-4D_rt^{\prime}})\int_0^{t^\prime}dt^{\prime\prime}(e^{(\kappa \bar\Gamma +3D_r)t^{\prime\prime}}-e^{4D_rt^{\prime\prime}})
\\=\frac{4v_p^2 e^{-2\kappa \bar \Gamma t}}{(\kappa \bar\Gamma)^2 -D_r^2}\int_0^tdt^\prime (e^{(\kappa \bar\Gamma -3D_r)t^{\prime}}-e^{-4D_rt^{\prime}})
\bigg(\frac{e^{(\kappa \bar\Gamma +3D_r)t^{\prime}}-1}{(\kappa \bar\Gamma +3D_r)}-\frac{e^{4D_rt^{\prime}}-1}{4D_r} \bigg)
\\=\frac{4v_p^2 e^{-2\kappa \bar \Gamma t}}{(\kappa \bar\Gamma)^2 -D_r^2}\bigg[\frac{1}{(\kappa \bar\Gamma +3D_r)}\bigg(\int_0^tdt^\prime (e^{2\kappa \bar\Gamma t^{\prime}}-e^{(\kappa \bar\Gamma -3D_r)t^{\prime}}-e^{(\kappa \bar\Gamma -D_r)t^{\prime}}-e^{-4D_r t^{\prime}}) \bigg) \\-\frac{1}{4D_r}\bigg(\int_0^tdt^\prime (e^{(\kappa \bar\Gamma -3D_r)t^{\prime}})-e^{(\kappa \bar\Gamma +D_r)t^{\prime}}+1-e^{-4D_rt^\prime}) \bigg) \bigg]
\\=\frac{4v_p^2 e^{-2\kappa \bar \Gamma t}}{(\kappa \bar\Gamma)^2 -D_r^2}\bigg[\frac{1}{(\kappa \bar\Gamma +3D_r)}\bigg(\frac{e^{2\kappa \bar\Gamma t}-1}{2\kappa \bar\Gamma}-\frac{e^{(\kappa \bar\Gamma -3D_r)t}-1}{(\kappa \bar\Gamma -3D_r)}-\frac{e^{(\kappa \bar\Gamma -D_r)t}-1}{(\kappa \bar\Gamma -D_r)}-\frac{1-e^{-4D_r }}{4D_r} \bigg)\\-\frac{1}{4D_r}\bigg(\frac{e^{(\kappa \bar\Gamma -3D_r)t}-1}{(\kappa \bar\Gamma -3D_r)}-\frac{e^{(\kappa \bar\Gamma +D_r)t}-1}{(\kappa \bar\Gamma +D_r)}+t-\frac{1-e^{-4D_rt}}{4D_r}\bigg) \bigg]
$$
Solving the $2^{nd}$ term of equation. 6,
$$
\frac{v_p^2 e^{-2\kappa \bar \Gamma t}}{(\kappa \bar\Gamma)^2 -D_r^2}\int_0^tdt^\prime\int_0^tdt^{\prime\prime}\bigg(e^{(\kappa \bar\Gamma +5D_r)t^{\prime\prime}}-e^{4D_rt^{\prime\prime}}\bigg)e^{(\kappa \bar\Gamma -5D_r)t^{\prime}}-\bigg(e^{(2\kappa \bar\Gamma +4D_r)t^{\prime\prime}}-e^{(\kappa \bar\Gamma +3D_r)t^{\prime\prime}}\bigg)e^{-4D_rt^{\prime}}
\\=\frac{2v_p^2 e^{-2\kappa \bar \Gamma t}}{(\kappa \bar\Gamma)^2 -D_r^2}\bigg[\int_0^tdt^\prime e^{(\kappa \bar\Gamma -5D_r)t^{\prime}}\int_0^{t^\prime}dt^{\prime\prime}\bigg(e^{(\kappa \bar\Gamma +5D_r)t^{\prime\prime}}-e^{4D_rt^{\prime\prime}}\bigg)-\\\int_0^tdt^\prime e^{-4D_rt^{\prime}}\int_0^{t^\prime}dt^{\prime\prime}\bigg(e^{(2\kappa \bar\Gamma +4D_r)t^{\prime\prime}}-e^{(\kappa \bar\Gamma +3D_r)t^{\prime\prime}}\bigg)\bigg]
\\=\frac{2v_p^2 e^{-2\kappa \bar \Gamma t}}{(\kappa \bar\Gamma)^2 -D_r^2}\bigg[\int_0^tdt^\prime e^{(\kappa \bar\Gamma -5D_r)t^{\prime}}\bigg(\frac{e^{(\kappa \bar\Gamma +5D_r)t^{\prime}}-1}{(\kappa \bar\Gamma +5D_r)}-\frac{e^{4D_rt^{\prime}}-1}{4D_r}\bigg)-\\\int_0^tdt^\prime e^{-4D_rt^{\prime}}\bigg(\frac{e^{(2\kappa \bar\Gamma +4D_r)t^{\prime}}-1}{(2\kappa \bar\Gamma +4D_r)}-\frac{e^{(\kappa \bar\Gamma +3D_r)t^{\prime}}-1}{(\kappa \bar\Gamma +3D_r)} \bigg)\bigg]
\\=\frac{2v_p^2 e^{-2\kappa \bar \Gamma t}}{(\kappa \bar\Gamma)^2 -D_r^2}\bigg[
\frac{1}{(\kappa \bar\Gamma +5D_r)}\int_0^tdt^\prime\bigg( e^{2\kappa \bar\Gamma t^{\prime}}- e^{(\kappa \bar\Gamma -5D_r)t^{\prime}}\bigg) -\frac{1}{4D_r} \int_0^tdt^\prime\bigg( e^{(\kappa \bar\Gamma -D_r)t^{\prime}}-e^{(\kappa \bar\Gamma -5D_r)t^{\prime}}\bigg) \\-\frac{1}{(2\kappa \bar\Gamma +4D_r)} \int_0^tdt^\prime\bigg( e^{2\kappa \bar\Gamma t^{\prime}}- e^{-4D_r t^{\prime}}\bigg) +\frac{1}{(\kappa \bar\Gamma +3D_r)} \int_0^tdt^\prime\bigg(e^{(\kappa \bar\Gamma-D_r) t^{\prime}}- e^{-4D_r t^{\prime}}\bigg) \bigg]
\\=\frac{2v_p^2 e^{-2\kappa \bar \Gamma t}}{(\kappa \bar\Gamma)^2 -D_r^2}\bigg[
\frac{1}{(\kappa \bar\Gamma +5D_r)} \bigg(\frac{e^{2\kappa \bar\Gamma t}-1}{2\kappa \bar\Gamma}-\frac{e^{(\kappa \bar\Gamma -5D_r)t}-1}{(\kappa \bar\Gamma -5D_r)} \bigg)-\frac{1}{4D_r}\bigg(\frac{e^{(\kappa \bar\Gamma -D_r)t}-1}{(\kappa \bar\Gamma -D_r)}-\frac{e^{(\kappa \bar\Gamma -5D_r)t}-1}{(\kappa \bar\Gamma -5D_r)}\bigg)\\ -\frac{1}{(2\kappa \bar\Gamma +4D_r)}\bigg(\frac{ e^{2\kappa \bar\Gamma t}-1}{2\kappa \bar\Gamma}-\frac{1-e^{-4D_r t}}{4D_r}\bigg)+\frac{1}{(\kappa \bar\Gamma +3D_r)}\bigg(\frac{e^{(\kappa \bar\Gamma-D_r) t}}{(\kappa \bar\Gamma-D_r)}-\frac{1-e^{-4D_r t}}{4D_r}\bigg)\bigg]
$$
The final expression is 
$$
\langle x_{1}(t)x_{1}(t) \rangle =\frac{K_BT }{\kappa}\bigg(\frac{1-e^{-2\kappa \bar \Gamma t}}{\kappa \bar \Gamma(2\kappa \bar \Gamma+4D_r)}+\kappa \bar \Gamma \frac{e^{-2\kappa \bar \Gamma t}-e^{-(2\kappa \bar \Gamma+4D_r)t}}{4D_r^2(2\kappa \bar \Gamma+4D_r)}-\frac{te^{-2\kappa \bar\Gamma t}}{2D_r}\bigg)+\\\frac{4v_p^2 e^{-2\kappa \bar \Gamma t}}{(\kappa \bar\Gamma)^2 -D_r^2}\bigg[\frac{1}{(\kappa \bar\Gamma +3D_r)}\bigg(\frac{e^{2\kappa \bar\Gamma t}-1}{2\kappa \bar\Gamma}-\frac{e^{(\kappa \bar\Gamma -3D_r)t}-1}{(\kappa \bar\Gamma -3D_r)}-\frac{e^{(\kappa \bar\Gamma -D_r)t}-1}{(\kappa \bar\Gamma -D_r)}-\frac{1-e^{-4D_r }}{4D_r} \bigg)\\-\frac{1}{4D_r}\bigg(\frac{e^{(\kappa \bar\Gamma -3D_r)t}-1}{(\kappa \bar\Gamma -3D_r)}-\frac{e^{(\kappa \bar\Gamma +D_r)t}-1}{(\kappa \bar\Gamma +D_r)}+t-\frac{1-e^{-4D_rt}}{4D_r}\bigg) \bigg]+\\
\frac{2v_p^2 e^{-2\kappa \bar \Gamma t}}{(\kappa \bar\Gamma)^2 -D_r^2}\bigg[
\frac{1}{(\kappa \bar\Gamma +5D_r)} \bigg(\frac{e^{2\kappa \bar\Gamma t}-1}{2\kappa \bar\Gamma}-\frac{e^{(\kappa \bar\Gamma -5D_r)t}-1}{(\kappa \bar\Gamma -5D_r)} \bigg)-\frac{1}{4D_r}\bigg(\frac{e^{(\kappa \bar\Gamma -D_r)t}-1}{(\kappa \bar\Gamma -D_r)}-\frac{e^{(\kappa \bar\Gamma -5D_r)t}-1}{(\kappa \bar\Gamma -5D_r)}\bigg)\\ -\frac{1}{(2\kappa \bar\Gamma +4D_r)}\bigg(\frac{ e^{2\kappa \bar\Gamma t}-1}{2\kappa \bar\Gamma}-\frac{1-e^{-4D_r t}}{4D_r}\bigg)+\frac{1}{(\kappa \bar\Gamma +3D_r)}\bigg(\frac{e^{(\kappa \bar\Gamma-D_r) t}}{(\kappa \bar\Gamma-D_r)}-\frac{1-e^{-4D_r t}}{4D_r}\bigg)\bigg]
$$
