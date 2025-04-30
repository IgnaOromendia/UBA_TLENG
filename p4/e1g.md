Determinar si es regular o no.

$L = \{w \in \{a,b\}^* \text{ tal que } |w|_a < |w|_b \}$

1. Dado $p \geq 0$

2. Elegimos una cadena $\alpha = w$ para que $\alpha \in L$ y $|\alpha| \geq p$

3. Me dan una descomposición $\alpha = xyz$ con $|xy| \leq p$ y $|y| \geq 1$.\
Podemos asegurar que\
$x \in \{a,b\}^*$ con $|x| = r, r \geq 0$\
$y \in \{a,b\}^*$ con $|y| = t, t \geq 1$\
$z \in \{a,b\}^*$ con $|z| = p - r - t$\
ya que $|xy| \leq p$.

4. Elegimos un $i \geq 0$ tal que $xy^iz \notin L$. Vamos a separarlo en casos:\
Si $|y|_a > |y|_b$ podemos elegir $i \geq |xz|_b + |y|_b$ para que $xy^iz \notin L$\
Si $|y|_a < |y|_b$ entonces $\nexists i/xy^iz \notin L$

Por lo tanto $L$ es un lenguaje regular.