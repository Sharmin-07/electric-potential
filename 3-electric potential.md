Long Version- 

Electric potential at a point can be defined in two equivalent ways: as the negative of the work done by the electrostatic force in bringing a unit positive charge from infinity to that point, or as the work done by an external agent in moving a unit positive charge from that point to infinity quasi-statically. Let’s proceed with the former definition.
Consider a point charge q. To find the electric potential at a point in space, at position $\vec{r}$ in space with respect to q, imagine bringing a unit positive charge from infinity to this point. In case of a unit positive charge, the force vector $\vec{F}$ is equal to the electric field $\vec{E}$ . Since work is defined as the dot product of force and displacement, and the distance between the source charge and the test charge keeps changing as the charge moves inward, this work has to be calculated using an integral. 

W = $\int_{\infty}^{r} \vec{F} \cdot d\vec{R}$ = $\int_{\infty}^{r} \vec{E} \cdot d\vec{R}$

The electric field due to the (point) charge q would be $\frac{kq}{R^2} \hat{R}$ , R being the magnitude of the position vector joining the unit charges and the source charge, pointing radially outwards. The dot product simply becomes the product of magnitudes of the electric field and displacement vectors, since both have a common direction. Therefore, the electric potential($V_r$) is calculated as- 

$V_r$ = $-\int_{\infty}^{r} \vec{E} \cdot d\vec{R}$ = $-\int_{\infty}^{r} \frac{kq}{R^2} \cdot dR$ = $(V_r +c) - (V_\infty + c)$ = $V_r - V_\infty$

This is a definite integral. While evaluating this definite integral, the integration constant c disappears. At first, this makes the constant feel irrelevant—almost like a formality. But what if this “irrelevance” is exactly where something interesting is hiding?

In electrostatics, we usually take potential at infinity to be zero, while real-world circuits use Earth as their reference. Initially, this seemed inconsistent. Shouldn’t a physical quantity have a single, well-defined zero point?

The key realization is that electric potential does not have an absolute value. Only differences in potential ($\Delta V$) matter physically. The choice of zero is arbitrary, and as long as all measurements share the same reference, the underlying physics remains the same. To see this more concretely, consider Earth as a charged sphere with charge $Q_e$ and radius $R_e$. If we choose Earth as the reference and set its potential to zero, then the potential at infinity becomes  $-k\frac{Q_e}{R_e}$. The values change, but the work done in bringing a unit charge from infinity to Earth, i.e., the potential difference, remains exactly the same.

What initially looked like an inconsistency turned out to be a choice. Mathematics allows this flexibility, and physics makes use of it. We take the potential at infinity to be zero for global, theoretical purposes, and the potential at Earth to be zero for local, practical purposes. The change isn’t in the set-up or in the concept, it’s in our perspective.


Short Version-

Electric potential is relative, not absolute; it is defined only relative to a chosen reference point. Potential difference ($\Delta V$) is calculated using using a definite integral, which naturally eliminates any integration constant. As the integration constant is arbitrary, the potential at a point is also arbitrary. This means the zero of potential is arbitrary and can be chosen for convenience. In electrostatics, infinity is taken as the reference for globbal and theoretical purposes, while for practical and local purposes, Earth is chosen to have zero electric potential. The numerical values change, but the physics does not—because only potential differences have physical meaning, not the absolute potential at a point.







