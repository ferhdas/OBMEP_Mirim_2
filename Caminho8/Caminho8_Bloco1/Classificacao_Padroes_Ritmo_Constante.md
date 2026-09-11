Ficha de classificação · Bloco $1$ · Padrões que crescem em ritmo constante

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as cinco questões de referência do bloco: `2022/F1/Q3` (código `M2-22-F1-Q03`), `2022/F2/Q1` (código `M2-22-F2-Q01`), `2019/Q8` (código `NA19-Q08`), `2025/F1/Q8` (código `M2-25-F1-Q08`) e `2023/F2/Q4` (código `M2-23-F2-Q04`).

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Descobrir a regra de crescimento de uma sequência que soma sempre a mesma quantidade a cada passo (uma regra do tipo $a\cdot n+b$), a partir de dois termos conhecidos, e usar essa regra para calcular outro termo pedido, seja ele um termo distante, seja um termo escondido que não dá para desenhar ou contar diretamente.

**Nó principal (Apêndice D, grade oficial).** `Raciocínio Lógico › Sequências e Padrões Numéricos`. Propõe-se o subnó nomeado **Regra Linear de Crescimento ($a\cdot n+b$)**, porque a grade oficial não distingue, dentro desse nó, entre crescimento em ritmo constante (o caso deste bloco) e crescimento que acelera (números figurados, tratado no Bloco $2$ deste Caminho).

**Descritores secundários.**
- Diferença constante entre termos vizinhos: numa sequência que cresce em ritmo constante, a diferença entre dois termos vizinhos quaisquer é sempre a mesma, e essa diferença é o "passo" da regra.
- Extrapolação por multiplicação do passo: para achar um termo a $k$ passos de um termo conhecido, multiplica-se o passo fixo por $k$ e soma-se ao termo conhecido, sem precisar desenhar ou contar os termos intermediários.
- Passo descoberto por termos não vizinhos: quando os dois termos conhecidos não são vizinhos, o passo fixo se descobre dividindo a diferença total entre eles pelo número de passos que os separam.
- Regra lida na estrutura da figura: além de descobrir o passo por comparação numérica, muitas vezes a regra pode ser deduzida diretamente olhando por que a figura cresce daquele jeito (o que se repete, o que é compartilhado entre termos vizinhos), o que serve como conferência independente do valor numérico.

**Não é X (e por quê).**
- Não é Números Figurados (Bloco $2$ deste Caminho), porque ali o salto entre termos vizinhos aumenta a cada passo (a diferença não é constante), enquanto aqui o salto é sempre o mesmo, do início ao fim da sequência.
- Não é Achar pela Posição (Bloco $3$ deste Caminho), porque ali a pergunta é sobre qual elemento cai numa posição específica dentro de um ciclo ou de uma grade, enquanto aqui a pergunta é sobre o valor de uma grandeza (comprimento, quantidade de peças, número de pontas) que cresce junto com a posição.
- Não é Contagem por Princípio Multiplicativo (Caminho $7$), mesmo quando a figura é montada com peças que se repetem, porque aqui não se trata de multiplicar escolhas independentes, e sim de somar um valor fixo repetidamente a partir de uma regra descoberta por comparação de termos.
- Não é Medida com Padrão resolvida por conta direta (Caminho $3$), porque ali o objetivo é achar uma dimensão a partir de um total dado (uma divisão ou subtração isolada), enquanto aqui o objetivo é caracterizar como uma sequência inteira cresce, para poder prever qualquer termo dela.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 8** › **Bloco 1 · Padrões que crescem em ritmo constante** › capítulo de teoria "Achar a regra que soma sempre o mesmo" (`Cap_Padroes_Ritmo_Constante.md`).

---

***Notas específicas de cada questão de referência***

`2022/F1/Q3` (código `M2-22-F1-Q03`)
- **Motor aplicado:** carrinhos de brinquedo são encaixados um atrás do outro. Um carrinho sozinho mede $70$ centímetros, e dois carrinhos encaixados medem $80$ centímetros, um aumento de $10$ centímetros por carrinho a mais. Para $5$ carrinhos encaixados, são $4$ carrinhos a mais que o primeiro, então o comprimento total é $70+4\times10=110$ centímetros. Gabarito **B ($110$)** ✅, conferido contra a solução oficial (`sf1m2-2022.pdf`, questão $3$).
- **Não é X específico:** não é uma questão de medir um carrinho isolado, é sobre descobrir quanto cada encaixe novo acrescenta ao comprimento total e estender essa regra a um número maior de carrinhos.

`2022/F2/Q1` (código `M2-22-F2-Q01`)
- **Motor aplicado:** estrelas são montadas com dois polígonos iguais sobrepostos e girados. Um triângulo tem $3$ pontas, dois triângulos formam uma estrela de $6$ pontas. Um quadrado tem $4$ lados, dois quadrados formam uma estrela de $8$ pontas. Dois pentágonos, com $5$ lados cada, formam uma estrela de $2\times5=10$ pontas. Gabarito **C ($10$)** ✅, conferido contra a solução oficial (`sf2m2-2022.pdf`, questão $1$).
- **Não é X específico:** não é uma questão de contar pontas numa única figura desenhada, porque o pentágono não vem desenhado como estrela pronta, é preciso aplicar a regra (dobro do número de lados) descoberta nos dois casos anteriores.

`2019/Q8` (código `NA19-Q08`)
- **Motor aplicado:** mesas quadradas da cantina são encostadas em fila. Uma mesa sozinha tem $4$ cadeiras (uma por lado). Duas mesas encostadas têm $6$ cadeiras, porque o lado que encosta na vizinha perde a cadeira. Numa fila de $10$ mesas, cabem $10$ cadeiras de um lado comprido, $10$ do outro lado comprido, e $2$ nas pontas, totalizando $10+10+2=22$. Gabarito **B ($22$)** ✅, conferido contra a solução oficial (`snA-2019.pdf`, questão $8$).
- **Não é X específico:** não é uma questão de contar cadeiras numa mesa só, é sobre entender por que cada mesa a mais na fila libera exatamente $2$ lugares novos, e estender essa regra a uma fila bem mais longa.

`2025/F1/Q8` (código `M2-25-F1-Q08`)
- **Motor aplicado:** uma faixa é formada por "casinhas" de palitos de $3$ centímetros, cada casinha com $6$ centímetros de largura na base, numa faixa de $30$ centímetros de comprimento total, o que dá $30\div6=5$ casinhas. A primeira casinha sozinha usa $11$ palitos, e cada casinha a mais compartilha $1$ palito com a vizinha, somando $10$ palitos novos por casinha. Para $5$ casinhas, $11+4\times10=51$ palitos. Gabarito **D ($51$)** ✅🖼️, conferido contra a solução oficial (`sf1m2-2025.pdf`, questão $8$: a faixa tem $5$ casinhas, não $10$, uma contagem que precisou ser corrigida na ficha-mestra, mas a resposta $51$ já estava certa).
- **Não é X específico:** não é uma questão de contar palitos numa figura pequena e pronta, é sobre descobrir quanto cada casinha nova acrescenta (o palito compartilhado é o detalhe que muda a conta) e aplicar essa regra ao total de casinhas da faixa.

`2023/F2/Q4` (código `M2-23-F2-Q04`)
- **Motor aplicado:** tabuleiros com as duas diagonais pintadas crescem de $3\times3$ ($5$ quadradinhos pretos) para $5\times5$ ($9$ quadradinhos) para $7\times7$ ($13$ quadradinhos), um aumento de $4$ quadradinhos a cada vez que o tamanho aumenta $2$. O quarto tabuleiro, coberto por um pano, é $9\times9$, então tem $13+4=17$ quadradinhos pretos. Gabarito **C ($17$)** ✅🖼️, conferido contra a solução oficial (`sf2m2-2023.pdf`, questão $4$: confirma os tamanhos $3\times3$, $5\times5$, $7\times7$ e $9\times9$ coberto).
- **Não é X específico:** não é uma questão de contar quadradinhos numa figura visível, o quarto tabuleiro está coberto, então a única saída é confiar na regra descoberta com os três tabuleiros visíveis e aplicá-la sem poder conferir contando.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Padroes_Ritmo_Constante.md` seguem a classificação acima:
- Exercícios $1$ e $2$: regra descoberta por dois termos vizinhos, num contexto de comprimento que cresce por encaixe (variação do Exemplo $1$/`2022/F1/Q3`).
- Exercícios $3$ e $4$: regra do tipo "dobro do número de lados/elementos", num contexto de figuras com pontas ou elementos que se repetem (variação do Exemplo $2$/`2022/F2/Q1`).
- Exercícios $5$ e $6$: regra descoberta por dois termos vizinhos, num contexto de fila com elementos nas pontas e no meio (variação do Exemplo $3$/`2019/Q8`).
- Exercícios $7$ e $8$: regra aplicada a um termo escondido ou grande demais para desenhar, num contexto de grade ou painel (variação do Exemplo $4$/`2023/F2/Q4`).
- Exercícios $9$ e $10$: passo descoberto a partir de dois termos não vizinhos, dividindo a diferença total pelo número de passos entre eles (variação do Exemplo $5$/`2025/F1/Q8`).
