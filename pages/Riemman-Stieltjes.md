- Definición de partición:
  
  #+BEGIN_QUOTE
  Sea $[a,b]$ un intervalo dado. Se define $P$, una partición de $[a,b]$, como un conjunto finito de puntos $x_0, x_1, ..., x_n$ tales que $a = x_0 \leq x_1 \leq \dots \leq x_{n-1} \leq x_n = b$
  
  Se define $\Delta x_i = x_{i-1} - x_i$ para todo $1 \leq i \leq n$
  #+END_QUOTE
- Tomando una función $f$ definida y acotada en $[a,b]$, para toda partición, se definen las sumas e integrales superiores e inferiores de la siguiente manera: ![SumIntDefs.pdf](../assets/AssetsPDF_1709403726826_0.pdf)
	- En el caso en que la integral inferior y la superior coincidan, se dice que $f$ es Riemman integrable en $[a,b]$, y en este caso, se omite la notación de superior e inferior y se escribe:
	  $$\int_a^b f(x)\,\mathrm{d}x$$
- Tomando ahora $\alpha$, una función monótonamente creciente en $[a,b]$, se define, junto a una partición $P$, $\Delta \alpha_i = \alpha(x_i) - \alpha(x_{i-1})$
  Tomando una función $f$ acotada en $[a,b]$, para toda partición se definen de manéra análoga las siguientes sumas e integrales: ![SumIntDefsStieltjes.pdf](../assets/AssetsPDF_1709491235439_0.pdf)