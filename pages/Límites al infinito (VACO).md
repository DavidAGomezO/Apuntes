- El concepto de infinito en el plano complejo, se refiere a puntos los cuales están en un conjunto no acotado. Esto se puede definir explícitamente con el siguiente conjunto:
  $$\left\{z\in\mathbb{C}\middle| \left(\forall \varepsilon\,\middle|\, \varepsilon > 0 : |z| > \frac{1}{\varepsilon}\right)\right\}$$
- Los puntos en este conjunto son denotados con $\infty$.
- # Definición de límite al infinito
	- ## Limites cuando el resultado tiende a infinito
		- La expresión
		  $$\lim_{z\to z_0} f(z) = \infty$$
		  es definida, de la misma forma que los límites usuales, exepto por la última parte. Es decir, dado $\varepsilon>0$, existe $\delta>0$ tal que, para todo $z\in\text{dom}f$
		  $$0<|z-z_0|<\delta \Rightarrow |f(z)| > \frac{1}{\varepsilon}$$
		- Nótese que, esta última expresión es equivalente a
		  $$0<|z-z_0|<\delta \Rightarrow \frac{1}{|f(z)|} < \varepsilon$$
		  Con lo que, estos límites se pueden calcular mostrando que
		  $$\lim_{z\to z_0} \frac{1}{f(z)} = 0$$
		  Claro está, siempre que la operación tenga sentido.
	- ## Limites cuando la variable tiende a infinito
		- La expresión
		  $$\lim_{z\to \infty} f(z) = w_0$$
		  es definida