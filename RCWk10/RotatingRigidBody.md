# Rotation of Rigid Body
> Last week we discussed tensor of inertia and how to find principle axis. We told you that non-principle axis are very difficult to handle. Today we'll show you what we can get given principle axis. All the following discussions are based on **principle axis through center of mass**. 

## Kinetic Energy
- Kinetic of energy of rotating rigid body w.r.t to center of gravity
  - $K_{rot} = \frac{1}{2}I_{cm}\omega^2$
  - The axis is a principle axis passing centre of mass
> Recall our discussion that kinetic energy under different FOR is different. What if center of mass start to move, i.e. the rigid body had transitional movement?
- Konig's theorem (proof in additional material)
  - $K_{total} = K_c + \sum_{i=1}^n K_{ic}$
  - Total kinetic energy of a particle system = $\frac{1}{2}\sum m v_c^2$ + total kinetic energy w.r.t to center of gravity FOR. 
  - Konig's theorem holds even if the center of gravity FOR is non-inertia FOR. 
- Rigid body with transitional velocity and rotation 
  - $K_{total} = K_c + K_{rot}$

## Dynamics of Rotation
Assuming the rotation happens along a principle axis with fixed direction
- $\vec{F} = m\vec{a}$ -> $\vec{\tau} = I\vec{\omega}$
- $\delta W = F dx$ -> $\delta W = dK_{rot} = \tau d\theta$
- $P = F \cdot v$ -> $P = \tau \omega$
- $\tau_{ext} = I \frac{d\omega}{dt}$
- If $\tau_{ext} = 0$ -> $L = I\omega = const$