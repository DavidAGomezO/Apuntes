- Una serie de potencias es el límite de una sucesión de sumas parciales de forma polinómica. Es decir, funciones de la forma
  $$f(x) = \lim_{n\to\infty}\sum_{k=0}^n c_k\,(x-a)^k$$
- Si bien, esto aplica para valores de $x\in\mathbb{C}$, la sección se restringe a tomar valores en $\mathbb{R}$, haciendo referencia al teorema 3.39.
- # Teorema 8.1
	- Suponga que la serie
	  $$\sum_{n=0}^\infty c_n\,x^n$$
	  converge para $|x|<R$. Se define
	  $$f=\sum_{n=0}^\infty c_n\,x^n \qquad (|x|<R)$$
	  Entonces, para todo $\varepsilon>0$, la serie converge uniformemente en $[-R + \varepsilon, R - \varepsilon]$. $f$ es continua y diferenciable en $(-R,R)$ y
	  $$f'(x) = \sum_{n=1}^\infty n\,c_n\,x^{n-1}$$