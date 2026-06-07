# 2N49R1M3-predativo-e-deterministico
Provando numeros primos de maneira inovadora e eficiente.

2N49R1M3-alimentado-por-1NV4S1V0
Script feito por um construtor civil com auxílio da IA ​​Gemini

Em um momento da minha vida eu fiz uma questão sobre os números primos e desde então utilizo a IA no Google Colab pra tentar coletar primos com base em heurísticas que estou tentando criar.

Propriedade Intelectual e Registro
O presente ecossistema computacional encontra-se devidamente registrado junto ao Instituto Nacional da Propriedade Industrial (INPI):

Patente de Invenção (PI) : BR 10 2026 004136 0
Registro de Programa de Computador (RPC) : 512026001601-0
Objeto : Proteção do código-fonte e direitos autorais do software 2N49R1M3

# P = +- ∆ A Fórmula que poucos enxergam.

# Relação Formal entre $\Delta$ e a Fatoração de $N$

Um semiprimo $N$ é definido como o produto de dois números primos $p$ e $q$, ou seja, $N = p \times q$. A diferença interna $\Delta$ é definida como o valor absoluto da diferença entre esses fatores, $\Delta = |q - p|$. Assumindo, sem perda de generalidade, que $q > p$, temos:

$$\Delta = q - p$$

Podemos expressar $q$ em termos de $p$ e $\Delta$:

$$q = p + \Delta$$

Substituindo esta expressão de $q$ na definição de $N$:

$$N = p \times (p + \Delta)$$

$$N = p^2 + p\Delta$$

Rearranjando os termos, obtemos uma equação quadrática na variável $p$:

$$p^2 + p\Delta - N = 0$$

Esta equação quadrática pode ser resolvida para $p$ usando a fórmula quadrática, onde $a = 1$, $b = \Delta$, e $c = -N$:

$$p = \frac{-\Delta \pm \sqrt{\Delta^2 - 4(1)(-N)}}{2(1)}$$

$$p = \frac{-\Delta \pm \sqrt{\Delta^2 + 4N}}{2}$$

Para que $p$ seja um inteiro e um fator primo de $N$, a expressão dentro da raiz quadrada $(\Delta^2 + 4N)$ deve ser um quadrado perfeito. Além disso, o valor de $p$ resultante deve ser positivo. Se essas condições forem satisfeitas, um dos valores resultantes da fórmula quadrática será $p$. Uma vez que $p$ é conhecido, $q$ pode ser facilmente encontrado usando $q = p + \Delta$.
