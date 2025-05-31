In this code, we aim to solve the Friedmann Equation for 4 types of Universes: an Universe compounded solely of matter (both baryonic and Dark), one made solely by radiation, one made solely
by Dark Energy, and finally, an Universe that mirrors ours, with the same content distribution. We disregard curvature contributions for all four analysis.

The Friedmann Equation states that the scale factor a, which parameterizes the Universe expansion, has its evolution dependent on the Universe components:

$$H^2 = \left(\frac{\dot{a}}{a}\right)^2 = \frac{8 \pi G}{3} \rho(t) - \frac{\kappa}{R_0^2 a^2}$$\

where $\rho(t)$ represents the total energy density of the Universe and $G$ is the Newtonian Constant of Gravitation. For this equation, and for the following analysis, we adopt the usage of natural units ($c = \hbar = 1$). The second term relates to the geometry of our Universe: $\kappa > 0$ represents an elliptical geometry, $\kappa = 0$ an Euclidean geometry, and $\kappa < 0$ an hyperbolic geometry. Finally, $R_0$ is the curvature radius for the Universe. According to recent estimates, cosmological evidence points that our Universe is very close to flat, as considered in the $\Lambda CDM$ model. Hence, from now on, we take $\kappa = 0$.

Using the Friedman Equation and computing the second derivative of the scale factor:\

$$\dot{a} = H a \Rightarrow \ddot{a} = \dot{a} H + a \frac{d H}{dt}$$\

But:\

$$H  = \sqrt{\frac{8 \pi G}{3} \rho(t)} \Rightarrow \frac{d H}{d t} = \frac{1}{2} H \frac{\dot{\rho}}{\rho}$$\

$$\ddot{a} = \dot{a} H + a \frac{H}{2} \frac{\dot{\rho}}{\rho}$$\

$$\ddot{a} = \frac{\dot{a}^2}{a} + \frac{\dot{a}}{2} \frac{\dot{\rho}}{\rho}$$ \
    
where we have used $\dot{a} = H a$ in the last step. Therefore, in order to determine $a(t)$ we must also determine how the energy density evolves with time.

The time evolution of $\rho$ can be determined under some simplifying assumptions. We begin by considering the first law of Thermodynamics:\

$$dQ = dU + dW$$\

where $dQ$ is the heat that enters or exits a specific region in space, $dU$ is the energy variation in this determined region, and $dW$ is the work made inside this area. If we consider this volume to be expanding, we can write:\

$$dW = P dV \Rightarrow dQ = dU + P dV$$\

where $P$ is the system's external pressure, and $dV$ represents the change in volume.

If our Universe is homogeneous, then there is no relevant flow of heat into any region in space. Therefore $dQ = 0$, and the expansion is an adiabatic process. Consequently, the expansion does not increase entropy, which would be expected if we assume that the total entropy in our Universe is constant (entropy density, however, still changes due to the expansion).

Therefore:\

$$dU + P dV = 0$$\

If we choose our system to be a sphere of radius $R(0) = 1$, that changes with time as $R(t) = R(0) a(t) = a(t)$, its volume will be:\

$$V = \frac{4}{3} \pi a(t)^3 \Rightarrow dV = 4 \pi a(t)^2 \frac{da(t)}{dt}$$\

Choosing the energy density of this area to be $\rho$, the total internal energy $U$ inside this sphere is:\

$$U = \frac{4}{3} \pi a(t)^3 \rho \Rightarrow dU = 4 \pi a(t)^2 \frac{d a(t)}{dt} \rho + \frac{4}{3} \pi a(t)^3 \frac{d \rho}{dt}$$\

Finally, substituting in the previous equations:\


$$4 \pi a(t)^2 \dot{a} (P + \rho) + \frac{4}{3} \pi a(t)^3 \dot{\rho} = 0$$\

$$\dot{\rho} + 3 \frac{\dot{a}}{a} (P + \rho) = 0$$/

This is the Fluid Equation, and it defines how the Universe's energy density and pressure changes with time. Combining Fluid Equation with Friedmann Equation, we obtain:

$$\frac{\ddot{a}}{a} = \frac{-4 \pi G}{3} (\rho + 3P)$$\ 

which determines how the Universe acceleration evolves with time.

From this equation, it is possible to see that, if both energy density ($\rho$) and pressure ($P$) are positive, then Universe expansion should be slowing down. However, from observations of galaxy velocities, we know this is not true. The expansion rate is actually increasing with time. Today, the main theory to explain this acceleration phenomenon is \textit{Dark Energy} . In the $\Lambda CDM$ model, Dark Energy is a cosmological constant $\Lambda$, related to an intrinsic vacuum energy. Analysis of anisotropies present in the Cosmic Microwave Background (CMB) predict that almost 68$\%$ of our Universe is made of Dark Energy.

The $\Lambda CDM$ model considers that our Universe is made of 31$\%$ of matter (both baryonic and dark), 68$\%$ of Dark Energy (as mentioned previously), and the rest of radiation. However, this scenario was not always true. Right after the Big Bang, the Universe was dominated by radiation. 

In order to understand how the densities of each component and scale factor evolved during these times, we must first determine how the pressure is related to the energy density. For a non-relativistic and ideal gas  we can use the perfect gas law:\

$$P V = N k T \Rightarrow P = \frac{N}{V} k T$$\

where $k$ is Boltzmann's constant, $T$ the gas temperature and $N/V = n$ the particle density. But, from the kinetic theory:\

$$3 k T = m \langle v^2 \rangle $$\

being $\langle v^2 \rangle$ the root mean square thermal velocity of the particles and $m$ their mass.  
Since for non-relativistic particles $v \ll 1$, we have $k T \simeq 0$ and therefore:\

$$P \simeq 0 \mbox{ (non-relativistic gas)}$$\

In the case of a gas of photons, its energy density is given by:\

$$\rho = n \langle E \rangle = n p \mbox{ and } 3 k T = p$$

where $p$ is the average 3-momentum of the particles. Therefore:\

$$\rho = 3 (n k T)  = 3 P$$\

$$\Rightarrow P = \frac{1}{3} \rho \mbox{ (relativistic gas)}$$\

Lastly, for Dark Energy we assume:\

$$P = -\rho \mbox{ (Dark Energy)}$$\

All the above gases can be parameterized as:\

$$P = w \rho$$\

where $ w = 0,1/3,-1$ for matter, radiation and Dark Energy, respectively.


Using the above results, we can finally integrate the Fluid Equation:\

$$\rho(t) = \int \Dot{\rho} dt = \int -3 \frac{\Dot{a}}{a} (P + \rho) dt$$\

Then, using the pressure, we obtain:\

$$\rho(t) = \int - 3 \frac{\Dot{a}}{a} \rho (1 + w) dt$$\

Therefore:\

$$\int \frac{1}{\rho} \frac{d \rho}{dt} dt = \int \frac{-3 (1 + w)}{a} \frac{d a}{dt} dt$$\

$$\log \left(\frac{\rho}{\rho_0}\right) = -3 (1+w) \log\left(\frac{a}{a_0}\right)$$\

Using logarithms properties:\

$$\log \left( \frac{\rho}{\rho_0} \right) = \log \left( \frac{a}{a_0} \right)^{-3 (1+w)}$$\

$$\rightarrow \rho = \rho_0 \left( \frac{a_0}{a} \right)^{3 (1+w)}$$\

Hence:
\begin{eqnarray}
    \rho_M & =&  \rho_{M,0} \left(\frac{a_0}{a}\right)^{3} \mbox{ (matter)} \nonumber\\
    \rho_R & = & \rho_{R,0} \left(\frac{a_0}{a}\right)^{4}  \mbox{ (radiation) } \nonumber\\
    \rho_{DE} & = & \rho_{DE,0} \mbox{ (Dark Energy)}
\end{eqnarray}

Through this, we can see that radiation density decreases faster than matter density, and that dark energy density is constant.
The difference between the expressions for radiation and matter densities can be explained through redshift. As the Universe expands, the wavelength of radiation increases by a factor $a$. But the energy of a wave is given by:
\begin{equation}
    E = \frac{2 \pi}{\lambda}
\end{equation}
where $\lambda$ is its wavelength. Therefore, as the wavelength increases by a factor $a$, the energy decreases by the same factor $a$. So, radiation energy density decreases by the variation of the total volume of the Universe, but also by the redshift it suffers in this process.

Today, the measured energy densities, for radiation, baryonic matter, Dark Matter, and Dark Energy are, respectively \cite{planckmeasurements}:
\begin{eqnarray}
    \rho_R & \approx & 4.64 \times 10^{-34} \mbox{GeV}^4 \nonumber\\
    \rho_{BM} & \approx & 4.20 \times 10^{-31} \mbox{GeV}^4 \nonumber\\
    \rho_{DM} & \approx & 2.25 \times 10^{-30} \mbox{GeV}^4 \nonumber \\
    \rho_{DE} & = & 5.83 \times 10^{-30} \mbox{GeV}^4
\end{eqnarray}

Employing these values and knowing how each density changes with $a$, we are able to estimate the initial energy densities $\rho_0$, and analyse how $\rho_{TOTAL}$ changed with time.
The result is that, for the approximate first 50 thousand years after the Big Bang, the Universe was dominated by radiation \cite{planckmeasurements}. Afterwards, we arrive at a point where matter and radiation had the same density, known as the matter-radiation equality. Following this moment, we enter an era where the dominant component of the Universe was matter. Lastly, when the Universe was approximately 8 billion years old, dark energy density became bigger than matter density.
