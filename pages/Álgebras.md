# Definición:
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
- # Teorema 7.29
	- Sea $\mathscr{B}$ la clausura uniforme de una álgebra de funciónes acotadas. Entonces $\mathscr{B}$ es un álgebra cerrada.
	- Teoremas referenciados:
		- Teorema 2.27
		- Ejercicio 7.2
	- ## Demostración: ![Demo7.29.pdf](../assets/AssetsPDF_1709784034127_0.pdf)