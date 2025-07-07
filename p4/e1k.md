Determinar si es regular o no.

$L = \{w \in \{a,b\}^* \text{ tal que para todo prefijo } \gamma \text{ de } w, ||\gamma|_a - |\gamma|_b | \leq 1\}$

Tiene autonmata con lo cual es regular.

4 estados
- Dif_0 (inicial)
- Dif_1
- Dif_-1
- Trampa

Todos finales menos Trampa.

Estando en Dif_0 
- -a-> Dif_1 
- -b-> Dif_-1

Estando en Dif_1
- -a-> Trampa 
- -b-> Dif_0

Estando en Dif_-1
- -a-> Dif_0
- -b-> Trampa

Estando en trampa no podemos salir.
