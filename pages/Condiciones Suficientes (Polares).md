- En este caso, se quiere ver el resultado anterior para la descomposición de una función dada una entrada en coordenadas polares. Para esto se debe tomar como punto de referencia $z_0 \not= 0$. Se va a tomar 
  $z = x + iy = r e^{i\theta}$
- Dado que las coordenadas cartesianas se pueden dar en función de las coordenadas polares, se puede obtener una relación entre las derivadas mediante la regla de la cadena para funciones de varias variables. Tomando la función $f(x+iy) = u(x,y) + iv(x,y)$:
  $$
  \begin{aligned}
  \frac{\partial u}{\partial r} = \frac{\partial u}{\partial x}\frac{\partial x}{\partial r} + \frac{\partial u}{\partial y}\frac{\partial y}{\partial r}\\
  \frac{\partial u}{\partial \theta} = \frac{\partial u}{\partial x}\frac{\partial x}{\partial \theta} + \frac{\partial u}{\partial y}\frac{\partial y}{\partial \theta}
  \end{aligned}
  $$
  De forma más compacta:
  $$
  \begin{aligned}
  u_r &= u_x\,x_r + u_y\,x_r= u_x\,\cos(\theta) + u_y\,\sin(\theta)\\
  u_\theta &=u_x\,x_\theta + u_y\,x_\theta= -u_x\,r\sin(\theta) + u_y\,r\cos(\theta) 
  \end{aligned}
  $$
  Y de forma análoga para $v$.
- Si $u$ y $v$ cumplen las [[Ecuaciones de Cauchy-Riemman]], entonces:
  $$
  \begin{aligned}
  v_r &= -u_y\,\cos(\theta) + u_x\,\sin(\theta) = -[-u_x\,\sin(\theta) + u_y\,\cos(\theta)]\\
  v_\theta &= u_y\,r\sin(\theta) + u_x\,r\cos(\theta) = u_x\,r\cos(\theta) + u_y\,r\sin(\theta)
  \end{aligned}
  $$
- Con todas las igualdades juntas, se tiene entonces que:
  $$
  \begin{aligned}
  u_r &= \frac{1}{r}v_\theta\\[10pt]
  -v_r &= \frac{1}{r}u_\theta
  \end{aligned}
  $$
- # Teorema 1: Las ecuaciones son equivalentes
	- Si una función $f$ cumple con las ecuaciones obtenidas anteriormente, entonces, cumple con las ecuaciones de Cauchy-Riemman.
	- Demostración: ![Demo.pdf](..\assets\VACO_050924_1.pdf)