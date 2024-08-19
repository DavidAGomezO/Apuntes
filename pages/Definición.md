- Como se vio en [[Análisis]], los complejos se definen en $\mathbb{R}^2$. Sea $z\in\mathbb{C}$, $z$ es entonces una pareja de números reales $(x,y)$, los cuales serán llamados parte real y parte imaginaria respectivamente, denotadas como
  $$\text{Re}\,z = x \quad \text{y} \quad \text{Im}\,z = y$$
  La igualdad se define de la misma forma que en $\mathbb{R}^2$.
- # Suma y Producto
- Sean $z_1,z_2\in\mathbb{C}$ con $z_1 = (x_1,y_1),\,z_2=(x_2,y_2)$. La suma y producto de estos se define como:
  $$\begin{aligned}
  z_1 + z_2 &= (x_1,y_1) + (x_2,y_2) &&= (x_1 + x_2, y_1 + y_2)\\
  z_1\cdot z_2 &= (x_1,y_1)\cdot (x_2,y_2) &&= (x_1\,x_2 - y_1\,y_2 , x_1\,y_2 + x_2\,y_1 )
  \end{aligned}$$
- Al restringir estas operaciones a números complejos con parte imaginaria nula, se obtienen las operaciones usuales en $\mathbb{R}$. Así, los complejos son una extensión de los reales.
- Definiendo el número imaginario $i$ como la pareja $(0,1)$. el complejo $z=(x,y)$ se puede escribir como
  collapsed:: true
  $$z = x + iy$$
	- Nótese que $i^2 = -1$
- Por último, la suma y el producto se comportan de tal forma que los complejos son un cuerpo.
	- Los elementos neutros por lo mencionado antes son los mismos que en $\mathbb{R}$, es decir
	  $0 = (0,0)$ para la suma, y $1 = (1,0)$ para el producto.
	- Dado $z=x+iy$, el inverso aditivo de $z$ es el complejo $-x - iy$. Si $z\not=0$, su inverso multiplicativo es el complejo $\dfrac{x}{x^2+ y^2} - \dfrac{iy}{x^2+y^2}$
- # Geometría en $\mathbb{C}$
- Dado que los complejos están definidos con $\mathbb{R}^2$, la visualización de estos se puede lograr usando un plano cartesiano.  El módulo de un número complejo se define de igual forma que en la métrica usual para $\mathbb{R}^2$. Dado $z = x + iy$, entonces $|z| = \sqrt{x^2 + y^2}$
- ## Conjugado
	- Muchas veces es de utilidad trabajar el complejo $z=x+iy$ junto a lo que sería su reflexión en el eje real, es decir, el complejo $x-iy$. Este número es llamado el *conjugado* de $z$, y es denotado por $\overline{z}$.
	- El conjugado distribuye sobre la suma y el producto.
- ## Forma Polar
	- Al igual que para $\mathbb{R}^2$, cada pareja cartesiana tiene una única pareja polar asignada, lo mismo sucede con los complejos. Esto se ve con la representación exponencial, sin embargo, el libro presenta la expresión cartesiana usando los parámetros polares. Sea $z\in\mathbb{C}$, $z$ puede ser representado de la siguiente manera:
	  $$z = r(\cos(\theta) + i\sin(\theta))$$
	  Donde $r=|z|$ y $\theta$ es una representación del ángulo formado entre el eje real y el vector representante de $z$.
	- ### Argumento de un número complejo
		- Sea $z\in\mathbb{C}$, con $z = r(\cos(\theta) + i\sin(\theta))$, con $\theta \in (-\pi,\pi]$. El argumento de $z$, es un conjunto denotado y definido de la siguiente manera:
		  $$\text{arg}\,z = \{\theta + 2k\pi | k \in \mathbb{Z}\}$$
		- El *argumento principal* de $z$, denotado por $\text{Arg}\,z$, es el único elemento de $\text{arg} z \cap (-\pi, \pi]$
		- Una propiedad de los arumentos de los números complejos es que el argumento de un producto es la suma de los argumentos de sus factores, con la convención de que la suma de conjuntos es la suma de sus elementos.