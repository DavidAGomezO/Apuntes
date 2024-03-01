- La terna de Hoare es una forma de expresar un programa a modo de proposición lógica, tiene la forma $\{P\} S \{Q\}$
- $\{P\}$ es la precondición del programa, esto es, suposiciones sobre las variables nombradas y si es pertinente, propiedades y teoremas útiles para entender mayormente la demostración del programa.
- $S$ es el programa en sí. En este se encuentra, con la sintaxis de los [[Comandos Guardados]] , una serie de instrucciones.
- $\{Q\}$ es la postcondición del programa, esto es, los resultados esperados tras aplicar $S$ tomando en cuenta $\{P\}$.
- Textualmente en el libro 
  #+BEGIN_QUOTE
  Toda ejecución de $S$ finaliza en un estado que satisface $Q$ cuando es aplicado a un estado que satisface $P$.
  #+END_QUOTE
- ## Relación entre programas
- De forma general, el estado $P$, bajo las instrucciones de $S$, resultan en $Q$, como dice la definición. Una mejor forma de verlo es con $wp$ mencionada en el libro como una función que toma un programa y una postcondición y devuelve la precondición más debil. Con eso, lo que se busca demostrar es que $$P \Rightarrow wp(S,Q)$$
- ![Propiedades.pdf](../assets/Propiedades_1709002193602_0.pdf)