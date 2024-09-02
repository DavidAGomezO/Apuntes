- Bajo la norma de $\mathbb{R}^2$, los complejos son un ![espacio métrico]([[Espacios Métricos]]). Sin embargo, el libro aporta algunas notaciones y definiciones específicas para este espacio.
- # Definiciones
	- ## Entorno
		- Un entorno, también llamado $a$-entorno, es simplemente una vecindad. En el caso del segundo nombre, se hace referencia al radio de dicha vecindad.
	- ## Frontera
		- Sea $S \subseteq \mathbb{C}$, se dice que un punto $z$ está en la frontera de $S$ cuando
		  $$\left(\forall\varepsilon\,\middle|\,\varepsilon>0\,:\,N_\varepsilon(z) \cap S \not= \varnothing \land N_\varepsilon \cap S^c \not= \varnothing\right)$$
		- En otras palabras, $z$ se encuentra en la frontera de $S$, cuando todas sus vecindades contienen puntos de $S$ y de su complemento.
	- ## Arco-Conexo
		- > En el libro esto se menciona como simplemente conexo, sin embargo, esta definición trae más especificaciones que la definición general de conexidad
		- Sea $S\subseteq\mathbb{C}$, se dice que $S$ es arco-conexo, cuando, para todo par de puntos $z_1,z_2\in S$, existe una colección finita de segmentos contenidos en $S$, los cuales conecten ambos puntos.
		- Otras fuentes cambian la colección de segmentos por curvas continuas, en este caso de un intervalo $[a,b]$ a $S$
- term
  : definition