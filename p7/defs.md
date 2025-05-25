### Definiciones

Dado un programa $P$, para cada $n\in \N$ se define como $\Psi^{(n)}_P: \N^n \rightarrow \N$ como la **función computada por** $P$ con $n$ entradas

$\text{Dom}(\Psi_P^{(n)}) = \{(x_1,\dots,x_n) | \Psi_P^{(n)}(x_1,\dots,x_n) \downarrow\} $

$\Psi$ es total cuando su dominio es $\N$

#### Minimización acotada

$f(z) = \min_{x\leq z}P(x)$

#### Esitencial acotado

$f(z) = (\exists x)_{x\leq z}P(x)$

#### Para todo acotado

$f(z) = (\forall x)_{x\leq z}P(x)$

### Codificación

$z = \langle x,y \rangle = 2^x (2y + 1) - 1$

$l(z) = \min_{x\leq z}((\exists y)_{y\leq z} z = \langle x,y \rangle)$

$r(z) = \min_{y\leq z}((\exists x)_{x\leq z} z = \langle x,y \rangle)$

$[a_1,\dots,a_n] = \prod^n_{i=1} p_i^{a_i}$

Definimos $\Phi^{(n)}_e : \N^n \rightarrow \N$ como la función computad apor el programam de número $e$. Si $P = e$, entonces $\Psi^{(n)}_P = \Phi^{(n)}_e$.

### Configuración instantánea

El predicado $\text{STEP}^{(n)}(e,t,x_1,\dots,x_n):\N^{n+2} \rightarrow \N$ devuelve 1 si el programa de número $e$ con entrada $x_1,\dots,x_n$ termina su ejecución tras $t$ o menos pasos, y si no 0.

La función $\text{SNAP}^{(n)}(e,t,x_1,\dots,x_n):\N^{n+2} \rightarrow \N$ codifica la configuración instantánea del programa de número $e$ con entrada $x_1,\dots,x_n$ en tiempo $t$.

$r(\text{SNAP}^{(1)}(x,t,z))[0] =$ Y (variable de salida del progama $x$ en tiempo $t$ y entrada $z$)