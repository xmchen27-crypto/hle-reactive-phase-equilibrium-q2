# Solution

The vessel is adiabatic and does only pressure-volume work at constant pressure, so total enthalpy, not temperature, is conserved. Adiabatic relaxation need not be isentropic.
At fixed composition, $s=-g_T$ and $h=g+Ts$. Put $b=x_0+x_1$ and $t=x_1$, so that $(x_A,x_0,x_1)=(1-b,b-t,t)$. Define
$$
w(b,t)=W_{A0}(1-b)(b-t)+W_{A1}(1-b)t+W_{01}(b-t)t.




$$

The molar enthalpy and entropy are
$$
h=C(T-T_r)+\Delta h\,t+w(b,t),




$$

$$
s=C\ln(T/T_r)+\Delta s\,t-R[(1-b)\ln(1-b)+(b-t)\ln(b-t)+t\ln t].




$$

Thus $H_i=1478.400000\ \mathrm J$ and $S_i=3.655618776543\ \mathrm{J\,K^{-1}}$ for the initial sample. The enthalpy of mixing in the initially homogeneous liquid must be included.
At fixed $T$ and $b$, reaction equilibrium requires $g_t=0$:
$$
\Delta h-T\Delta s+RT\ln\frac{t}{b-t}
+(W_{A1}-W_{A0})(1-b)+W_{01}(b-2t)=0.




$$

The ideal-solution ratio alone is therefore insufficient. The reaction composition generally differs between coexisting phases. Define the reaction-equilibrated molar Gibbs energy
$$
\bar g(T,b)=\min_{0\leq t\leq b}g(T,b,t).




$$

For the final temperature found below, $g_{tt}=RT[1/t+1/(b-t)]-2W_{01}>0$ throughout the interior, so the reaction-equilibrium composition is unique at each $b$.
By the envelope theorem, $\bar g_b=g_b$ evaluated at $g_t=0$, where
$$
g_b=RT\ln\frac{b-t}{1-b}
+W_{A0}(1-2b+t)-W_{A1}t+W_{01}t.




$$

Two coexisting phases $\alpha$ and $\beta$, labeled by $b_\alpha<b_\beta$, must satisfy $g_t^\alpha=g_t^\beta=0$ and
$$
g_b^\alpha=g_b^\beta=\mu,\qquad
g^\alpha-b_\alpha\mu=g^\beta-b_\beta\mu.




$$

These are the common-tangent conditions after reaction equilibration, equivalent to equality of the chemical potentials of the conserved components. The phase fraction and enthalpy balance are
$$
\lambda_\beta=\frac{z-b_\alpha}{b_\beta-b_\alpha},\qquad
(1-\lambda_\beta)h^\alpha+\lambda_\beta h^\beta=H_i/n.




$$

Solving these equations jointly, rather than imposing coexistence at the initial temperature, gives
$$
T_f=321.6505979463\ \mathrm K,




$$

$$
(x_A^\alpha,x_0^\alpha,x_1^\alpha)
=(0.909852968333,0.015775813455,0.074371218212),




$$

$$
(x_A^\beta,x_0^\beta,x_1^\beta)
=(0.062596522187,0.439476982685,0.497926495128).




$$

Consequently,
$$
\lambda_{\mathrm{rich}}=\lambda_\beta=0.0824460747992.




$$

Global stability must still be checked. At $T_f$, the tangent line is $\ell(b)=c+\mu b$, where
$$
c=-256.3557856105\ \mathrm{J\,mol^{-1}},\qquad
\mu=-1373.5457176979\ \mathrm{J\,mol^{-1}}.




$$

Minimizing $g(T_f,b,t)-\ell(b)$ over the composition simplex gives zero at the two reported phase compositions and nonnegative values everywhere else. In a one-dimensional check after minimizing over $t$, the stationary points are at $b=0.090147031667$, $0.530195544549$, and $0.937403477813$. The first and last are zero-gap minima; the middle is a maximum with gap $273.154369956\ \mathrm{J\,mol^{-1}}$. The limiting gaps at $b=0$ and $b=1$ are positive, about $195.3075$ and $135.6527\ \mathrm{J\,mol^{-1}}$, respectively. Thus the line supports the entire reaction-equilibrated Gibbs curve. No additional liquid phase lowers the equilibrium Gibbs energy at this temperature.
This supporting line also establishes the relevant fixed-enthalpy entropy maximum. For any trial composition and temperature $T'>0$,
$$
h(T',\mathbf x)-T_f s(T',\mathbf x)
=g(T_f,\mathbf x)+C\left[T'-T_f-T_f\ln(T'/T_f)\right]
\geq c+\mu b,




$$

because $u-1-\ln u\geq0$. Summing over any trial phases at the prescribed total enthalpy and composition gives
$$
S\leq\frac{H_i-n(c+\mu z)}{T_f}.




$$

The reported two-phase state attains equality. It is therefore a global entropy maximum under the actual adiabatic constraints, not just an isothermal stationary solution. The two contact compositions, the common temperature, and the lever rule fix the equilibrium state.
For comparison, enforcing homogeneity gives a stationary state at $T=319.1622123158\ \mathrm K$ and $x_1=0.130654631457$. Its reaction-equilibrated composition curvature is positive, approximately $5460.04\ \mathrm{J\,mol^{-1}}$, but its entropy is only $5.976538163766\ \mathrm{J\,K^{-1}}$. It is not the global maximum.
For the stable two-phase state,
$$
S_f=n[(1-\lambda_\beta)s^\alpha+\lambda_\beta s^\beta]
=6.076541168962\ \mathrm{J\,K^{-1}},




$$

$$
\Delta S=2.420922392419\ \mathrm{J\,K^{-1}}.




$$

The required rounded answer is
$$
\boxed{(321.65,\ 0.0824,\ 2.421)}.




$$
