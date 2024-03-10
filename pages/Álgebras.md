# Definiciones:
	- ## Álgebra de funciones
		- Una familia $\mathscr{A}$ de funciones complejas definidas en un conjunto $E$ es llamada *álgebra* si para toda $f,g \in \mathscr{A} \land c \in \mathbb{C}$:
		  (La definición es análoga para considerar álgebras en $\mathbb{R}$)
			- $f+g \in \mathscr{A}$
			  logseq.order-list-type:: number
			- $f\,g \in \mathscr{A}$
			  logseq.order-list-type:: number
			- $c\,f\in\mathscr{A}$
			  logseq.order-list-type:: number
	- ## Álgebras cerradas uniformemente
	  id:: 65e90cd3-f8c5-4136-9c29-be8fe7eb1ec7
		- Un álgebra $\mathscr{A}$ tiene la propiedad de ser uniformemente cerrada cuando, para toda $\langle f_n \rangle$ con rango en $\mathscr{A}$ y con convergencia uniforme a $f$:
		  $$f\in\mathscr{A}$$
		- Sea
		  $$\mathscr{B} = \left\{f \in \mathscr{A} \middle|\left(\exists \langle f_n \rangle\,\middle|   \langle f_n \rangle [\mathbb{J}] \subseteq \mathscr{A}\,:\,\langle f_n \rangle \to f \text{ uniformemente}\right)\right\}$$
		  $\mathscr{B}$ es llamado la clausura o adherencia uniforme de $\mathscr{A}$
	- ## Familias que separan puntos
		- Sea $\mathscr{A}$ una familia de funciones en un conjunto $E$. Se dice que $\mathscr{A}$ separa puntos en $E$ cuando, para todo $x_1,x_2\in E$, existe una función $f\in\mathscr{A}$ tal que
		  $$f(x_1) \not= f(x_2)$$
	- ## Familias que no se anulan
		- Sea $\mathscr{A}$ una familia de funciones en un conjunto $E$. Se dice que $\mathscr{A}$ no se anula en $E$ cuando, para todo $x\in E$, existe $f\in\mathscr{A}$ tal que
		  $$f(x) \not= 0$$
- # Teorema 7.29
	- Sea $\mathscr{B}$ la clausura uniforme de una álgebra de funciónes acotadas. Entonces $\mathscr{B}$ es un álgebra cerrada.
	- Teoremas referenciados:
		- Teorema 2.27
		- Ejercicio 7.2
	- ## Demostración: ![Demo7.29.pdf](../assets/AssetsPDF_1709784034127_0.pdf)
- # Teorema 7.31
  id:: 65ecfc8f-9a3b-4ce6-aaba-4e989b2a9ef2
	- Sea $\mathscr{A}$ un álgebra de funciones definidas en un conjunto $E$. $\mathscr{A}$ separa puntos y no se anula en $E$. Dados dos puntos diferentes de $E$, $x_1,x_2$, y dos constantes $c_1,c_2$, existe una función $f\in\mathscr{A}$ tal que
	  $$f(x_1) = c_1 \quad \land \quad f(x_2) = c_2$$
- # Teorema 7.32
	- Sea $\mathscr{A}$ un álgebra de funciones reales continuas en un conjunto compacto $K$. \mathscr{A} separa puntos y no se anula en $K$. Entonces, la clausura uniforme de $\mathscr{A}$ consiste en todas las funciones reales continuas en $K$.
	- Teoremas referenciados:
		- Teorema 7.26 (Stone-Weierstrass)
		- ((65ecfc8f-9a3b-4ce6-aaba-4e989b2a9ef2))
	- ## Demostración: ![Demo7.32.pdf](../assets/AssetsPDF_1710029913047_0.pdf)