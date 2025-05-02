Determinar si es regular o no.

$L = \{w \in \{a,b\}^* \text{ tal que } w = w^r \}$

1. Dado $p \geq 0$

2. Elegimos una cadena $\alpha = a^pba^p $ para que $\alpha \in L$ y $|\alpha| \geq p$

3. Me dan una descomposición $\alpha = xyz$ con $|xy| \leq p$ y $|y| \geq 1$.\
Podemos asegurar que\
$x = a^r$ con $r \geq 0$\
$y = a ^t$ con $t \geq 1$\
$z = a^{p-r-t}ba^p$ ya que $|xy| \leq p$.

4. Elegimos un $i \geq 0$ tal que $xy^iz \notin L$. Con $i = 0$ tenemos que la cantidad de $a$ antes de $b$ es menor a $p$ y la cantidad de $a$ después de $b$ es $p$, con lo cual no pertenece al lenguaje y no es regular