## Non-inertia FOR
1. Chose a FOR for the system
2. Free body diagram
3. Add fictitious forces
Consider fictitious forces one by one. 
- d'Alembert force (translation acceleration)
  - $-m\vec{a_{O'}}$
- Euler force (angular acceleration)
  -  $-m\frac{d\vec{\omega}}{dt}\times \vec{r'}$
- Coriolis force  (地转偏向力)
  - $-2m(\vec{\omega}\times \vec{v'})$
- centrifugal force （离心力）
  - $-m\vec{\omega}\times (\vec{\omega} \times \vec{r'})$
> NOTE: $\vec{a_{O'}}$, $\vec{\omega}$ is acceleration and angular velocity of the non-inertia FOR w.r.t any inertia FOR. $\vec{r'}$ and $\vec{v'}$ are the partical described in the non-inertia FOR.

--------------------------------
Gravity on earth is similar to d'Alembert forces. We may consider d'Alembert force as a kind of gravitational field. e.g. In a falling box, d'Alembert force $ma_{O'}$ points upwards <=> a upwards gravitational field. The box FOR <=> inertia FOR with $g-a_{o'}$ gravitational field. 


## Work and Energy
only discussed under a fixed FOR, usually lab FOR. 
- König's theorem (if you want to deal with kinetic energy under different FOR)
### Work
Basis formulas: $dW = \vec{F}\cdot d\vec{x}$, $W = \int_{\Gamma_{AB}}{\vec{F}\cdot d\vec{x}}$
- -> W = $\vec{F} \cdot \vec{x}$ if $\vec{F}$ is const
- -> $P = \frac{dW}{dt} = \vec{F}\cdot \vec{v}$
### Kinetic energy: translation and rotational
- $E_k = \frac{1}{2}mv^2$
### potential energy: 
  - gravitational
  - elastic
  - electric
  - etc. 

Generally speaking, energy transforms by forces doing work. In dynamics, mechanical energy is conservative unless some of them become heat, through dynamical friction for example. Always have a big picture of where the energy goes to, through which force and when. 