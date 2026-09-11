Ficha de classificação · Bloco $2$ · Números figurados

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as duas questões de referência do bloco: `2018/Q10` (código `NA18-Q10`) e `2022/F2/Q8` (código `M2-22-F2-Q08`).

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Reconhecer que uma sequência vem de organizar objetos numa figura que cresce (um quadrado, ou uma pilha em camadas triangulares), descobrir a regra que dá a quantidade de objetos a partir da posição na sequência, e usá-la para calcular um termo mais distante, mesmo sabendo que o salto entre termos vizinhos não é sempre o mesmo, ele também cresce.

**Nó principal (Apêndice D, grade oficial).** `Aritmética › Quadrados Perfeitos`. Propõe-se o subnó nomeado **Números Figurados (Quadrados e Triangulares)**, ampliando esse nó, porque a grade oficial não tem nó separado para números triangulares ou tetraédricos, e a tradição da matemática recreativa trata quadrados perfeitos e números triangulares como a mesma família, "números figurados", organizada pela forma geométrica que os objetos formam.

**Descritores secundários.**
- Quadrado perfeito por posição: numa sequência de figuras quadradas, a figura de número $n$ sempre tem $n\times n$ objetos, o que permite calcular qualquer termo direto pela posição, sem somar salto por salto.
- Número triangular como tamanho de camada: numa pilha empilhada em camadas triangulares, o tamanho da camada de número $n$ é o número triangular $1+2+\dots+n$, que também cresce a cada posição.
- Pilha como soma acumulada: o total de uma pilha depois de $n$ camadas é a soma dos $n$ primeiros números triangulares, um crescimento que acelera duas vezes, porque tanto o tamanho de cada camada quanto o total acumulado crescem cada vez mais rápido.
- Salto crescente entre termos vizinhos: ao contrário de uma sequência de ritmo constante, aqui o salto entre um termo e o próximo aumenta a cada passo, o que é justamente o sinal de que a sequência vem de uma figura que cresce em duas dimensões (quadrado) ou em camadas acumuladas (pilha triangular).

**Não é X (e por quê).**
- Não é o Bloco $1$ deste Caminho (Padrões que crescem em ritmo constante), porque ali o salto entre termos vizinhos é sempre o mesmo, e aqui o salto cresce a cada passo, sinal de uma figura que se expande em mais de uma direção ou que acumula camadas.
- Não é Multiplicação simples de dois números dados (Caminho $1$), porque a regra ($n\times n$, ou a soma dos triangulares até $n$) precisa ser descoberta a partir do padrão da sequência, não vem pronta no enunciado.
- Não é Contagem por Princípio Multiplicativo (Caminho $7$), porque aqui não se trata de multiplicar escolhas independentes, e sim de reconhecer a fórmula de crescimento de uma figura geométrica específica (quadrado ou pilha triangular) e aplicá-la a uma posição pedida.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 8** › **Bloco 2 · Números figurados** › capítulo de teoria "Quando o crescimento acelera" (`Cap_Numeros_Figurados.md`).

---

***Notas específicas de cada questão de referência***

`2018/Q10` (código `NA18-Q10`)
- **Motor aplicado:** uma sequência de figuras triangulares subdivididas mostra $1$, $4$, $9$ e $16$ triângulos pequenos nas quatro primeiras figuras. Reconhecendo os quadrados perfeitos ($1\times1$, $2\times2$, $3\times3$, $4\times4$), a $5$ª figura tem $5\times5=25$ triângulos pequenos. Gabarito **C ($25$)** ✅, conferido contra a solução oficial (`sf1na-2018.pdf`, questão $10$).
- **Não é X específico:** não é uma questão de contar triângulos numa figura só, é sobre reconhecer que a contagem de cada figura da sequência é sempre um quadrado perfeito e aplicar essa regra à quinta figura.

`2022/F2/Q8` (código `M2-22-F2-Q08`)
- **Motor aplicado:** pilhas de cubinhos crescem em camadas, a $1$ª pilha tem $1$ cubinho, a $2$ª tem $4$, a $3$ª tem $10$, a $4$ª tem $20$. Cada camada nova tem o tamanho de um número triangular ($1$, $3$, $6$, $10$), então a $5$ª camada tem $1+2+3+4+5=15$ cubinhos novos, e a $5$ª pilha tem $20+15=35$ cubinhos ao todo. Gabarito **A ($35$)** ✅, conferido contra a solução oficial (`sf2m2-2022.pdf`, questão $8$).
- **Não é X específico:** não é uma questão de somar um valor fixo repetidamente, o tamanho de cada camada nova também cresce, por isso o total da pilha acelera duas vezes, e não dá para usar a regra do Bloco $1$ (ritmo constante) aqui.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Numeros_Figurados.md` seguem a classificação acima:
- Exercícios $1$ a $5$: reconhecer uma sequência de quadrados perfeitos em contextos diferentes (selos, azulejos, sementes, blocos, mosaico) e calcular um termo mais distante, sempre pela regra $n\times n$.
- Exercícios $6$ a $10$: reconhecer uma pilha que cresce em camadas triangulares em contextos diferentes (queijos, copos, caixas, sacos de areia, potes de tinta) e calcular o total depois de um número maior de camadas, somando os números triangulares correspondentes.
