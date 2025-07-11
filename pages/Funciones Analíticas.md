# Def. función analítica
	- Sean $f$ una función compleja y $A$ un subconjunto abierto de $\mathbb{C}$. $f$ es llamada *analítica* en $A$, cuando existe su derivada en todos los puntos de $A$.
		- Sea $B$ un subconjunto no abierto de $\mathbb{C}$. $f$ es llamada *analítica* en $B$ cuando existe un abierto $X$  tal que $B\subseteq X$ y $f$ es analítica en $X$.
		- Sea $z_0\in\mathbb{C}$. $f$ es llamada *analítica* en $z_0$ cuando existe una vecindad de $z_0$ en la que $f$ sea analítica.
- # Def. función entera
	- Sea $f$ una función compleja. $f$ es llamada *entera* cuando es analítica en todo punto de $\mathbb{C}$.
- # Teorema
	- Sean $f$ y $g$ funciones analíticas en un subconjunto $A$ de $\mathbb{C}$. Entonces
	  1. $f+g$
	  2. $f*g$
	  3. $\displaystyle\frac{f}{g}$
	  4. $f \circ g$
	  Son funciones analíticas
	- ## Demostración:
		- Esto es consecuencia inmediata de los resultados de las derivadas para estas mismas combinaciones.
- # Teorema
	- Sea $f$ una función analítica en un dominio $D$, tal que, para todo $z\in D$, $f'(z) = 0$. Entonces, existe $z_0\in\mathbb{C}$ tal que, para todo $z\in D$, $f(z)=z_0$.
	- ## Demostración:
		- Dado que $f$ es analítica en $D$ y $u,v$ son las funciones de su parte real e imaginario respectivamente, entonces $f'(x+iy) = u_x(x,y) + i\,v_x(x,y) = 0$. Por otra parte, al ser $f$ analítica, cumple con las [[Ecuaciones de Cauchy-Riemann]], con lo que $v_y(x,y) - i\,u_y(x,y) = 0$. Así, para todo $z\in D$,
		  $$u_x=u_y=v_x=v_y=0$$
		  Y por resultados del cáclulo en varias variables, esto es, $u,v$ son constantes en $\{(x,y)\,|\,x+iy\in D\}$. Con lo que $f$ resulta ser constante en $D$.