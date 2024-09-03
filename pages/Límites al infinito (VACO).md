- El concepto de infinito en el plano complejo, se refiere a puntos los cuales están en un conjunto no acotado. Esto se puede definir explícitamente con el siguiente conjunto:
  $$\left\{z\in\mathbb{C}\middle| \left(\forall \varepsilon\,\middle|\, \varepsilon > 0 : |z| > \frac{1}{\varepsilon}\right)\right\}$$
- Los puntos en este conjunto son denotados con $\infty$.
- # Definición de límite al infinito
	- ## Límites cuando el resultado tiende a infinito
		- La expresión
		  $$\lim_{z\to z_0} f(z) = \infty$$
		  es definida, de la misma forma que los límites usuales, exepto por la consecuencia a $f$. Es decir, dado $\varepsilon>0$, existe $\delta>0$ tal que, para todo $z\in\text{dom}f$
		  $$0<|z-z_0|<\delta \Rightarrow |f(z)| > \frac{1}{\varepsilon}$$
		- Nótese que, esta última expresión es equivalente a
		  $$0<|z-z_0|<\delta \Rightarrow \frac{1}{|f(z)|} < \varepsilon$$
		  Con lo que, estos límites se pueden calcular mostrando que
		  $$\lim_{z\to z_0} \frac{1}{f(z)} = 0$$
		  Y viceversa. Claro está, siempre que la operación tenga sentido.
	- ## Límites cuando la variable tiende a infinito
		- La expresión
		  $$\lim_{z\to \infty} f(z) = w_0$$
		  es definida, de la misma forma, exepto por la condición de $z$. Es decir, dado $\varepsilon>0$, existe $\delta>0$ tal que, para todo $z\in\text{dom}f$
		  $$|z|>\frac{1}{\delta} \Rightarrow |f(z) - w_0| < \varepsilon$$
		- Nótese que, esta última expresión es equivalente a
		  $$\frac{1}{|z|}<\delta \Rightarrow |f(z) - w_0| < \varepsilon$$
		- Entonces estos límites se pueden calcular mostrando que
		  $$\lim_{z\to 0} f\left(\frac{1}{z}\right) = w_0$$
		  y viceversa. Claro está, siempre que tenga sentido la operación.
	- ## Límites cuando la variable y el resultado tienen a infinito
		- La expresión
		  $$\lim_{z\to \infty} f(z) = \infty$$
		  Se define igual que antes, y ahora cambian tanto la condición a $z$ como la consecuencia en $f$. Es decir, dado $\varepsilon>0$, existe $\delta>0$ tal que, para todo $z\in\text{dom}f$
		  $$|z|>\frac{1}{\delta} \Rightarrow |f(z)| > \frac{1}{\varepsilon}$$
		- Nótese que esta expresión es equivalente a
		  $$\frac{1}{|z|} < \delta \Rightarrow \frac{1}{|f(z)|} < \varepsilon$$
		- Entonces, estos límites se pueden calcular mostrando que
		  $$\lim_{z\to 0} \frac{1}{f\left(\frac{1}{z}\right)} = 0$$
		  y viceversa. Claro está, siempre que la operación tenga sentido.
-