- Existen varias formas de clasificar las funciones que representan la complejidad de un algoritmo.
- # *O* grande
	- Esta clasificación toma una función y denota el conjunto de todas las funciones que asintóticamente son menores que esta.
	- Más formalmente, sean $f$ y $g$ funciones de valor entero. Se dice que:
		- $\displaystyle g \in O(f) \equiv \left(\exists c \,|\,c\in \mathbb{R}-\{0\} \,:\, \lim_{n\to\infty} \frac{g(n)}{f(n)} = c\right)$
		  logseq.order-list-type:: number