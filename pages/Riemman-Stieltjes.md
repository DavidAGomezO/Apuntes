# Definición de partición:
id:: 65e249b8-ed52-40b7-916e-f5f9bc261c47

#+BEGIN_QUOTE
Sea $[a,b]$ un intervalo dado. Se define $P$, una partición de $[a,b]$, como un conjunto finito de puntos $x_0, x_1, ..., x_n$ tales que $a = x_0 \leq x_1 \leq \dots \leq x_{n-1} \leq x_n = b$

Se define $\Delta x_i = x_{i-1} - x_i$ para todo $1 \leq i \leq n$
#+END_QUOTE
- # Definición de sumas e integrales superiores e inferiores
	- Tomando una función $f$ definida y acotada en $[a,b]$, para toda partición, se definen las sumas e integrales superiores e inferiores de la siguiente manera: ![SumIntDefs.pdf](../assets/AssetsPDF_1709403726826_0.pdf)
		- En el caso en que la integral inferior y la superior coincidan, se dice que $f$ es Riemman integrable en $[a,b]$, y en este caso, se omite la notación de superior e inferior y se escribe:
		  $$\int_a^b f(x)\,\mathrm{d}x$$
	- Tomando ahora $\alpha$, una función monótonamente creciente en $[a,b]$, se define, junto a una partición $P$, $\Delta \alpha_i = \alpha(x_i) - \alpha(x_{i-1})$
	  Tomando una función $f$ acotada en $[a,b]$, para toda partición se definen de manéra análoga las siguientes sumas e integrales: ![SumIntDefsStieltjes.pdf](../assets/AssetsPDF_1709491235439_0.pdf)
		- En el caso en que ambas integrales coincidan, se dice que $f$ es Riemman-Stieltjes integrable en $[a,b]$, y en de la misma manera que antes, se omite la notación de superior e interior y en cambio se escribe:
		  $$\int_a^bf\,\mathrm{d}\alpha$$
	- Para denotar que $f$ es Riemman integrable o Riemman-Stieltjes integrable en $[a,b]$, se escribe respectivamente:
	  $$f \in \mathscr{R}_{[a,b]} \qquad f \in \mathscr{R}(\alpha)_{[a,b]}$$
- Se dice que una [partición] ((65e249b8-ed52-40b7-916e-f5f9bc261c47)) $P^*$ es un refinamiento de una partición $P$ cuando $P \subseteq P^*$. Y se dice que $P^*$ es el refinamiento común de $P_1$ y $P_2$ cuando $P^* = P_1 \cup P_2$
-
- # Teorema 6.4 (Refinamientos y Sumas)
	- Si $P^*$ es un refinamiento de $P$, entonces:
	- $L(P,f,\alpha) \leq L(P^*,f,\alpha)$
	  logseq.order-list-type:: number
	  id:: 65e4c6f0-21f6-43f8-9071-1782e1e0799c
	- $U(P^*,f,\alpha) \leq L(P,f,\alpha)$
	  logseq.order-list-type:: number
	- ## Demostración: ![Demo6.4.pdf](../assets/AssetsPDF_1709493727214_0.pdf)
- # Teorema 6.5 (Desigualdad entre integrales superior e inferior)
	- ## ![Demo6.5.pdf](../assets/AssetsPDF_1709498735076_0.pdf)
- # Teorema 6.6 (Caracterización de ser integrable)
	- $f \in \mathscr(\alpha)_{[a,b]}$ si y solo si, para todo $\varepsilon > 0$, existe una partición $P$ de $[a,b]$ tal que
	  $U(P,f,\alpha) - L(P,f,\alpha) < \varepsilon$