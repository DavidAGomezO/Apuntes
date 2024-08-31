- Para $n\in\mathbb{N}$, las potencias de un número complejo $z = re^{i\theta}$, están dadas por la expresión
  $$z^n = r^n e^{in\theta}$$
  Cosa que se puede demostrar fácilmente por inducción usando el hecho de que $z^{n+1} = z\,z^n$.
- De esta definición, también se puede expandir a los enteros con la ecuación 
  $$z^{-n} = (z^{-1})^n$$
  Tomando todo lo anterior, se puede demostrar que $(z^{-1})^n = (z^n)^{-1}$ usando la ecuación
  $$(\cos(\theta) \pm i\sin(\theta))^n = \cos(n\theta) \pm i\sin(n\theta)$$
- Para definir raices n-ésimas, se realiza el mismo proceso que en $\mathbb{R}$. Haciendo referencia a un complejo $z_0$, sus raices serán las soluciones a la ecuación
  $$z^n = z_0$$
- Antes de entrar en detalles, un ejemplo para las raices n-ésimas de la unidad: ![RaizUnidad.pdf](../assets/AssetsPDF_1725126252848_0.pdf)
- Con este ejemplo, es más facil ver que, para un número complejo $z_0 = re^{i\theta_0}$, su raíz n-ésima es el conjunto
  $$\left\{\sqrt{r}\exp\left(i\frac{\theta_0 + 2k\pi}{n}\right)\middle| 0 \geq k < n \land k \in \mathbb{Z}\right\}$$