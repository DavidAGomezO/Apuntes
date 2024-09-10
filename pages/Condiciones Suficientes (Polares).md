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
- Si $u$ y $v$ cumplen las [[Ecuaciones de Cauchy-Riemann]], entonces:
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
- Estas ecuaciones son llamadas ecuaciones de Cauchy-Riemman polares (C-R polares).
- # Teorema 1: Las ecuaciones son equivalentes
	- Si una función $f$ cumple con las ecuaciones C-R polares, entonces, cumple con las ecuaciones de Cauchy-Riemman.
	- Demostración: ![Demo.pdf](..\assets\VACO_050924_1.pdf)
- # Teorema 2: Condiciones suficientes en polares
	- Si una función $f(z) = u(r,\theta) + iv(r,\theta)$, cumple con las ecuaciones C-R polares en un punto 
	  $z_0 = r_0\,e^{i\theta_0}$, y sus derivadas son continuas en una vecindad de $z_0$. Entonces $f$ es diferenciable en $z_0$.
	- ## Lema: derivada en términos de $u_r,v_r$
		- Si una función $f(z) = u(x,y) + iv(x,y)$ es diferenciable en un punto $z_0$, entonces su derivada en $z_0$ se puede escribir como $e^{-i\theta_0}(u_r(r_0,\theta_0) + iv_r(r_0,\theta_0))$
		- Demostración: ![DemoLema.pdf](../assets/AssetsPDF_1725599589782_0.pdf)
	- Demostración: Dado que $f$ cumple con las ecuaciones C-R polares, entonces cumple con las ecuaciones normales. Tomando las igualdades del lema en sentido contrario se obtiene una expresión para la derivada en $z_0$.