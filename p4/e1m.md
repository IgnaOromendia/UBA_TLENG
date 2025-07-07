$L = \{w \in \{a,b\}^* \text{ tal que para todo prefijo } \gamma \text{ de } w, |\gamma|_a \geq |\gamma|_b  \}$

1. Dado $p \geq 0$

2. Elegimos una cadena $\alpha = a^pb^p$ para que $\alpha \in L$ y $|\alpha| \geq p$

3. Me dan una descomposición $\alpha = xyz$ con $|xy| \leq p$ y $|y| \geq 1$.\
Podemos asegurar que\
$x = a^r$ con $r \geq 0$\
$y = a ^t$ con $t \geq 1$\
$z = a^{p-r-t}b^p$ ya que $|xy| \leq p$.

4. Elegimos un $i \geq 0$ tal que $xy^iz \notin L$. Basta elegir $i = 0$ para que $|xz|_a < |xz|_b$ ya que $t \geq 1$. Con lo cual este lenguaje no es regular.