Determinar si es regular o no.

$L = \{w \in \{a,b\}^* \text{ tal que } |w|_a \neq |w|_b \}$

1. Dado $p \geq 0$

2. Elegimos una cadena $\alpha = w$ para que $\alpha \in L$ y $|\alpha| \geq p$

3. Me dan una descomposición $\alpha = xyz$ con $|xy| \leq p$ y $|y| \geq 1$.\
Podemos asegurar que\
$x \in \{a,b\}^*$ con $|x| = r, r \geq 0$\
$y \in \{a,b\}^*$ con $|y| = t, t \geq 1$\
$z \in \{a,b\}^*$ con $|z| = p - r - t$\
ya que $|xy| \leq p$.

4. Elegimos un $i \geq 0$ tal que $xy^iz \notin L$. A menos que $|y|_a$ o $|y|_b$ sean 0 $\nexists i / |xy^iz|_a = |xy^iz|_b$

Por lo tanto $L$ es un lenguaje regular.