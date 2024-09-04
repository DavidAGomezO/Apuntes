- Sean $f$ una función compleja, $u$ y $v$ funciones reales tales que $f(x + iy) = u(x,y) + iv(x,y)$ y 
  $z_0 = x_0 + iy_0$ un punto en el dominio de $f$ donde esta es diferenciable.
- Por el primer teorema de la sección de ![límites]([[Límites (VACO)]]), se tiene que
  $$\text{Re}(f'(z_0)) = \lim_{z\to z_0} \text{Re}\left[\frac{f(z) - f(z_0)}{z-z_0}\right]$$
  $$\text{Im}(f'(z_0)) = \lim_{z\to z_0} \text{Im}\left[\frac{f(z) - f(z_0)}{z-z_0}\right]$$
- Dado que estos límites existen, el resultado es el mismo para cualquier acercamiento de $z$ a $z_0$. En particular para los acercamientos $(t,y_0)$ y $(x_0,t)$. Expresando el cociente del límite con funciones $u$ y $v$, y las componentes de los números usados, queda de la siguiente manera:
  $$\frac{u(x,y) - u(x_0,y_0) + i(v(x,y) - v(x_0,y_0))}{x-x_0 + i(y-y_0)}$$
	- El límite para el primer acercamiento es
	  $$\text{Re}(f'(z_0)) = u_x(x_0,y_0)$$
	  $$\text{Im}(f'(z_0)) = v_x(x_0,y_0)$$
	- El límite para el segundo acercamiento es
	  $$\text{Re}(f'(z_0)) = v_y(x_0,y_0)$$
	  $$\text{Im}(f'(z_0)) = -u_y(x_0,y_0)$$
- De estas ecuaciones se tiene lo siguiente: Si la función $f$ es diferenciable en $z_0$, entonces,
  $$
  \begin{aligned}
  u_x(x_0,y_0) &= v_y(x_0,y_0)\\
  v_y(x_0,y_0) &= -u_y(x_0,y_0)
  \end{aligned}
  $$
- De forma equivalente, si en el punto $z_0$, no se tienen estas igualdades, entonces $f$ no es diferenciable en $z_0$.