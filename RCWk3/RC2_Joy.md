# VP160 RC2 3D Kinetics 
topics: 2D polar coordinates; quick review and problems on 3D kinetics
## $\dot{\mathbf{v}}$ vs. $\dot{v}$
acceleration vs. speed change rate (will discuss later in nature coordinates
## 3D Motion in Cartesian Coordinates
* $\vec{r} = x\hat{n_x} + y\hat{n_y} + z\hat{n_z}$
* $\vec{v} = \dot{x}\hat{n_x} + \dot{y}\hat{n_y} + \dot{z}\hat{n_z}$
* $\vec{a} = \ddot{x}\hat{n_x} + \ddot{y}\hat{n_y} + \ddot{z}\hat{n_z}$
## 3D Cylindrical Coordinates
* $$\left(\begin{matrix} \dot{\hat{n_\rho}}\\\\\dot{\hat{n_\varphi}}\\\\\dot{\hat{n_z}} \end{matrix}\right) = \left(\begin{matrix} \dot{\varphi}\hat{n_\varphi}\\\\-\dot{\varphi}\hat{n_\rho}\\\\0 \end{matrix}\right)$$
* $\vec{r} = \rho\hat{n_\rho} + z\hat{n_z}$
* $\vec{v} = \dot{\rho}\hat{n_\rho} + \rho\dot{\varphi}\hat{n_\varphi}+\dot{z}\hat{n_z}$
* $\vec{a} = (\ddot{\rho} - \rho\dot{\varphi}^2) \hat{n_\rho} + (\rho \ddot{\varphi } + 2\dot{\rho}\dot{\varphi}) \hat{n_\varphi} + \ddot{z}\hat{n_z}$
## 3D Spherical Coordinates
*  $$\left(\begin{matrix} \dot{\hat{n_r}}\\\\\dot{\hat{n_\varphi}}\\\\\dot{\hat{n_\theta}} \end{matrix}\right) = \left(\begin{matrix} \dot{\theta} \hat{n_\theta}+\dot{\varphi} sin \theta \hat{n_\varphi}\\\\-\dot{\varphi} \sin \theta \hat{n_r}-\dot{\varphi} cos \theta \hat{n_\theta}\\\\-\dot{\theta} \hat{n_r}+\dot{\varphi} cos \theta \hat{n_\varphi}\end{matrix}\right)$$
* $\vec{r} = r\hat{n_r}$
* $\vec{v} = \dot{r}\hat{n_r}+r\dot{\theta}\hat{n_\theta}+r\dot{\varphi}\sin\theta\hat{n_\varphi}$
* $\vec{a} = \ddot{r}\hat{n_r}+\dot{r}\dot{\hat{n_r}}+\dot{r}\dot{\theta}\hat{n_\theta}+r\ddot{\theta}\hat{n_\theta}+r\dot{\theta}\dot{\hat{n_\theta}}+\dot{r}\dot{\varphi}sin\theta\hat{n_\varphi}+r\ddot{\varphi}sin\theta\hat{n_\varphi}+r\dot{\varphi}\dot{\theta}cos\theta\hat{n_\varphi}+r\dot{\varphi}sin\theta\dot{\hat{n_\varphi}}$
## Polar Coordinates
> **transverse**: along $n_\varphi$
> 
> **radial**: along $n_\rho$
*  change r while keeping $\varphi$ constant. $ds = dr$
* change $\varphi$ while keeping r constant $ds = rd\varphi$
* change both at the same time $(ds)^2 = (dr)^2 + (d\varphi)^2$
 $$(\frac{ds}{dt})^2 = (\frac{dr}{dt})^2 = (\frac{d\varphi}{dt})^2$$ 
 = magnitude of $\vec{v} = \dot{r}\hat{n_r} + \rho \dot{\varphi}\hat{n_\varphi}$


## Nature Coordinates
* established based on the trajectory (rely on the trajectory, cannot describe the trajectory, but the motion along the trajectory)
  * $\hat{n_\tau}\times \hat{n_n} = \hat{n_b}$ normal, tangential, normal, binormal (normal vector of the plane the trajectory is in locally)
* Acceleration under nature coordinates
  * $a_t$: **tangential** component. 'speed change rate' $\dot{v} = a_t$
  * $a_n$: **normal** component. contributes to 'turning'
* **Curvature**: 'local radius' 
  * physic way of finding curvature: $R = \frac{v^2}{a_n}$