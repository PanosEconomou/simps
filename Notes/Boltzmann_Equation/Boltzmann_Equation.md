# Boltzmann Equation

We consider the universe as two perfect fluids, one baryonic and one dark matter, in curved space with the following line element.
$$
ds^2 = dt^2-a(t)^2\left[\frac{1}{1-\kappa r^2}dr^2 + r^2d\theta^2 +r^2 \sin^2\theta\, d\phi^2\right],
$$
Where $a(t)$ is the scale factor, and $\kappa = 0$ denotes the curvature. In this case we are considering flat space. Using Einstein’s Field Equations we can predict the time evolution of the metric. More specifically, we can derive the Friedmann Equaions that tell us how $a(t)$ evolves. To so we need to specify the energy-momentum tensor $T^\mu_\nu$, which for a perfect fluid we define like so:
$$
T^\mu_\nu = \text{diag}\left(\rho,-p,-p,-p\right),
$$
where $\rho$ is the energy density of the fluids, and $p$ is the pressure. The interactions between the particles of the fluids give rize to different equations of state that relate $\rho$ and $p$. We want to track the evolution of the probability density $f$ of each of the species comprising our liquids. To do this, we use the Boltzmann Equation which is given by
$$
\mathcal{L}f_\chi=\mathcal{C}f_\chi
$$
where $f_\chi$ is the distribution over the phase space of species $\chi$, $\mathcal{L}$ is the Liouville operator, and $\mathcal{C}$ is the collision operator.

The Liouville operator is simply the total derivative with respect to an affine parameter of the system. In phase space that parameter can be time $t$. In particular this is given by
$$
\mathcal{L}f_\chi = \frac{df_\chi}{dt}=\frac{\partial f_\chi}{\partial t} + \left[f_\chi,H\right]=\frac{\part f_\chi}{\part t} - H\frac{p^2}{E}\frac{\part f_\chi}{\part E}
$$
Where we are using the poisson bracket. In the last part we have used the fact that the fluid particles move along the geodesics of the space we have described. Here $H$ is the hubble constant.



We can define multiple quantities using the distribution of the species over the phase space. Perhaps the most useful one for now is the energy density $\rho$ as a function of the temperature $T$ of the fluid. This is given by averaging the energy over the momenta for a particular location. Note that for an isotropic universe the distribution function $f_\chi$ does not depend on the position
$$
\rho_\chi(T) = \frac{g}{(2\pi)^3}\int d^3\vec{p}\ E\left(||\vec{p}||\right)\,f_\chi\left(||\vec{p}||,T\right).
$$
Other nice quantities are number density, given by:
$$
n_\chi(T) = \frac{g}{(2\pi)^3}\int d^3\vec{p}\ \,f_\chi\left(||\vec{p}||,T\right).
$$
Notice that all of these are functions of temperature, but in the evolution of the universe, Temperature is a function of time. Using these definitions we can derive dynamical equations by integrating the Boltzmann Equation on time