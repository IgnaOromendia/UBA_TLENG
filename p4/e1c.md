Determinar si es regular o no.

$L = \{a^mb^na^{m+n} | m,n \geq 1\}$

1. Dado $p \geq 0$

2. Elegimos una cadena $\alpha = a^pb^pa^{2p}$ ya que $\alpha \in L$ y $|\alpha| \geq p$

3. Me dan una descomposición $\alpha = xyz$ con $|xy| \leq p$ y $|y| \geq 1$.\
Podemos asegurar que $x = a^r$ con $r \geq 0$, $y = a^t$ con $t \geq 1$ y $z = a^{(p-r-t)}b^pa^{2p}$ ya que $|xy| \leq p$.

4. Elegimos un $i \geq 0$ tal que $xy^iz \notin L$\
Si elegimos $i = 0$ entonces $xy^0z = xz= a^ra^{(p-r-t)}b^pa^{2p} = a^{(p-t)}b^pa^{2p}$ y como $t \geq 1$ podemos asegurar que $p-t \neq p$ entonces $(p-t) + p \neq 2p$ y por lo tanto no pertence a $L$. Con lo cual $L$ no es regular.