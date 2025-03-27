### Definiciones

#### Cadenas

$\Sigma^n$ dentoa todas las cadenas de longiutd $n$

$\Sigma^* = \bigcup_{n\geq0} \Sigma^n$

$\Sigma^+ = \bigcup_{n\geq1} \Sigma^n$

Longitud
- $|\lambda| = 0$
- $|x.\alpha| = 1 + |\alpha|$

Apariciones
- $|\lambda|_x = 0$
- $|y.\alpha|_x = |\alpha|_x$       si $y\neq x$
- $|y.\alpha|_x = 1 + |\alpha|_x$   si $y = x$

Reversa
- $\lambda^r = \lambda$
- $(x.\alpha)^r = \alpha^r.x$

#### Lenguajes

$L_1\cup L_2 = \{\alpha\in\Sigma^* : \alpha \in L_1 \lor \alpha\in L_2\} $

$L_1\cap L_2 = \{\alpha\in\Sigma^* : \alpha \in L_1 \land \alpha\in L_2\} $

$L^r = \{\alpha^r : \alpha\in L\} $

$L_1.L_2 = \{\alpha.\beta : \alpha \in L_1 \land \beta\in L_2\} $

$L^n = L.L^{n-1}$ si n > 0\
$L^n = \Lambda$ si n = 0

$L^* = \bigcup_{n\geq0} L^n$

$L^+ = \bigcup_{n\geq1} L^n$