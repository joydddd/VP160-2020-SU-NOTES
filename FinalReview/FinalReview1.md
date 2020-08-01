Meeting Recording:
https://umich.zoom.us/rec/share/yJFxEa-o1mlJQInStW7Vf4UmAZi8X6a80yQarPsJnkiQXx9FDoV-b6D_QFpS5e1H

# Lagrangian mechanics
A highly generalized dynamics
- generalized coordinates
- degree of freedom: f = 3N -m 
  - N: number of particles, m number of constraints
  - example: Average Energy of gas molecule: $\epsilon = \frac{f}{2} KT$
    - $CO_2, O_2, He$
## Hamilton's principle
the real trajectory extremizes Hamilton's action.
=> Fermat's principle (extremizes optical path)
**Lagrangian:** $L = K - U$ 
K: kinetic energy u: potential energy
**Hamilton's action**: $S = S[q] = \int_{T_A}^{T_B} L(q, \dot{q}, t) dt$
$$\frac{d}{dt}\left(\frac{\partial L}{\partial \dot{q}_i}\right)-\frac{\partial L}{\partial q_i}=0\quad  \text{for}\quad i=1,2,\cdots,f$$

# Momentum
moment - impulse
- $\vec{F} = m\frac{d\vec{v}}{dt} = \frac{d\vec{P}}{dt}$
- $\Delta \vec{P} = \int^{t_2}_{t_1} \vec{F} dt = \vec{J}$ (impulse)
- **law of conservation of momentum**: If the sum of all external forces on
the system is equal to zero then the total momentum of the system is constant.

Momentum vs. Work
- Momentum -- force accumulate w.r.t time, *resulting* in change of momentum (Has direction! because $\vec{F}$ has direction. i.e. x, y, z direction are independent)
    - based on Newton's second law
Work -- force accumulate w.r.t time, *resulting* in change of energy (must be considered only once for a whole system!)
    - based on energy conservation
## General Solution of Dynamic
see examples of collision
### General Solution from the *state of a system* point of view:
We only care about the initial situation and final situation, whatever happened in the process
- what is the system I'm studying? What are the external forces? What's the initial condition and what's the final condition?
- how does momentum (angular momentum) change in x, y, z direction (w.r.t the fixed axis) as a result of force accumulation on time? -- one equation for every degree of freedom
  - no need to know $\vec{F}(t)$, but how momentum "flow" through force from object exerting object to object force exert on. 
- how does energy change as a result of time? (Energy is conservative **altogether** added up -- only one equation, considering everything!)
  - no need to know $\vec{F}(t)$, but how energy "flow" through force from object exerting object to object force exert on. 

### General Solution from the *process of a motion* point of view:
We consider an instance during the process 
- Newton's second Law (x, y, z direction and rotation)
- position -> speed -> acceleration relationship

> Either solves the problem -- although one can be much more difficult than the other. You can also use a mixed method.
## Center of Mass
see examples 
## variable mass sys
An isolated system: conservation of momentum
before erupting gas of mass dm: mass m and speed v (lab FOR) P: mv
after: rocket: m - dm, v + dv, gas: dm, v - u P: (m-dm)(v+dv) + dm(v-u) = mv -udm +mdv
$ 0 = d(mv) = m dv +  udm $ 
-> $m \frac{dv}{dt} = - u \frac{dm}{dt}$ 