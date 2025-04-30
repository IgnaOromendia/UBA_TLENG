Determinar si es regular o no.

$L = \{a^nb^n | n \geq 0\}$

1. Dado $p \geq 0$

2. Elegimos una cadena $\alpha = a^pb^p$ ya que $\alpha \in L$ y $|\alpha| \geq p$

3. Me dan una descomposición $\alpha = xyz$ con $|xy| \leq p$ y $|y| \geq 1$.\
Podemos asegurar que $x = a^r$ con $r \geq 0$, $y = a^t$ con $t \geq 1$ y $z = a^{(p-r-t)}b^p$ ya que $|xy| \leq p$.

4. Elegimos un $i \geq 0$ tal que $xy^iz \notin L$\
Si elegimos $i = 0$ entonces $xy^0z = xz= a^ra^{(p-r-t)}b^p = a^{(p-t)}b^p$ y como $t \geq 1$ podemos asegurar que $p-t \neq p$ entonces pertence a $L$. Con lo cual $L$ no es regular.