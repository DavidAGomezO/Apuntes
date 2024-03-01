# Instrucciones
	- Asignación
	  id:: 65dd5004-cc5a-44fa-8c54-981bedb8d190
	- Condicional
	  id:: 65dd5022-9299-4851-b9b8-2969a49afe51
	- Ciclo
	  id:: 65de3215-1bf2-4617-8d0a-7b0e930dc7a6
- # Operaciones "Nuevas"
	- Introducción de variables
	  id:: 65de3215-7ef7-498f-8660-a87c1206a15d
	- Concatenación
	  id:: 65de3215-b2c0-4e01-a775-cf8fda8733a0
	- Inicio y cierre de programas
	  id:: 65de3215-8aec-49b6-ab72-79339717c61a
- # Sintaxis
	- ## La sintaxis de las guardas
	  id:: 65dd5409-153b-473f-aab5-19b99a778e6b
	  collapsed:: true
		- La Guarda es un predicado, se denota con la letra $G$
		- La instrucción es un programa, se denota con la letra $S$
		- La forma en la que se relacionan sintácticamente es $G \to S$
	- ## ((65dd5004-cc5a-44fa-8c54-981bedb8d190))
	  collapsed:: true
		- Se usa el símbolo $:=$, toma dos variables
	- ## ((65dd5022-9299-4851-b9b8-2969a49afe51))
		- Actua sobre una cantidad finita de guardas, cada una con una respectiva instrucción:
		- ![CondicionalSintaxis.pdf](../assets/CondicionalSintaxis_1709061451148_0.pdf)
	- ## ((65de3215-1bf2-4617-8d0a-7b0e930dc7a6))
	  collapsed:: true
		- Actua sobre una cantidad finita de guardas, cada una con una respectiva instrucción:
		- ![CicloSintaxis.pdf](../assets/CicloSintaxis_1709061649744_0.pdf)
	- ## ((65de3215-7ef7-498f-8660-a87c1206a15d))
	  collapsed:: true
		- Se usa el símbolo $\texttt{var}$, toma una cantidad finita de variables.
	- ## ((65de3215-b2c0-4e01-a775-cf8fda8733a0))
	  collapsed:: true
		- Se usa el símbolo $\texttt{;}$, toma dos programas/ instrucciones.
	- ## ((65de3215-8aec-49b6-ab72-79339717c61a))
	  collapsed:: true
		- Se usan los símbolos $\texttt{[}\!\texttt{|}$ y $\texttt{|}\!\texttt{]}$, toma un programa completo.
- # Semántica
	- ## ((65dd5004-cc5a-44fa-8c54-981bedb8d190))
	  collapsed:: true
		- Toma la variable a la izquierda y le asigna el valor a la derecha.
		- Ejemplo:
			- Tomando cualquier valor mayor que o igual a $0$, asignandole este mismo valor sumado en uno, el resultado es mayor que o igual a $1$.
			- $\{x \geq 0\}\: x := x + 1\: \{x \geq 1\}$
	- ## ((65dd5022-9299-4851-b9b8-2969a49afe51))
	  collapsed:: true
		- Existe una guarda abierta.
		  logseq.order-list-type:: number
		- Se entra por alguna de las guardas abiertas y tras ejecutar la instrucción correspondiente, se pasa a la siguiente instrucción posterior al condicional.
		  logseq.order-list-type:: number
		- Ejemplo: ![SemanticaCondicional.pdf](../assets/AssetsPDF_1709064940288_0.pdf)
	- ## ((65de3215-1bf2-4617-8d0a-7b0e930dc7a6))
	  collapsed:: true
		- Si todas las guardas están cerradas, se pasa a la siguiente instrucción posterior al ciclo.
		  logseq.order-list-type:: number
		  id:: 65de4310-60f5-4f08-a4fb-dd48d6335035
		- Toma una de las guardas abiertas, ejecuta su respectiva instrucción y se evalúa la condición (1.)
		  logseq.order-list-type:: number
		- Ejemplo: ![SemanticaCiclo.pdf](../assets/AssetsPDF_1709065519916_0.pdf)
	- ## ((65de3215-7ef7-498f-8660-a87c1206a15d))
	  collapsed:: true
		- Debe usarse siempre antes de usar cualquier variable.
		- Su uso es el de presentar nombre y tipo de toda variable.
		- Ejemplos:
			- $\texttt{var} \,x:\texttt{int}$
			- $\texttt{var}\,x,y : \texttt{int}$
			- $\texttt{var}\, x: \texttt{type1}; \texttt{var}\, y:\texttt{type2}$
	- ## ((65de3215-b2c0-4e01-a775-cf8fda8733a0))
	  collapsed:: true
		- Se usa entre dos programas/ instrucciones.
		- Sirve de separador entre consecutivos.
		- Ejemplo: $\{P\}\: S_1\,;\,S_2\:\{Q\}$
	- ## ((65de3215-8aec-49b6-ab72-79339717c61a))
	  collapsed:: true
		- Se usa el primer símbolo siempre al inicio de un programa, mientras que el segundo se usa siempre al final de todo el programa.
	- ## Ejemplo: ![ProgramaEjemplo.pdf](../assets/AssetsPDF_1709067707909_0.pdf)