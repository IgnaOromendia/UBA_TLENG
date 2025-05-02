Determinar si es regular o no.

$L = \{w \in \{a,b\}^* \text{ tal que } |w|_a \neq |w|_b \}$

1. Dado $p \geq 0$

2. Elegimos una cadena $\alpha = a^{p+j}b^p$ para que $\alpha \in L$ y $|\alpha| \geq p$

3. Me dan una descomposición $\alpha = xyz$ con $|xy| \leq p$ y $|y| \geq 1$.\
Podemos asegurar que\
$x = a^r$ con $r \geq 0$\
$y = a ^t$ con $t \geq 1$\
$z = a^{2p-r-t}b^p$ ya que $|xy| \leq p$.

4. Elegimos un $i \geq 0$ tal que $xy^iz \notin L$.\
Si elegimos $i = j - t - r$ entonces $|w|_a = |w|_b$ y no pertenece a $L$.
