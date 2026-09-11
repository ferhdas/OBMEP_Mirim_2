Ficha de classificação · Bloco $2$ · Pareamento: pés, mãos e conjuntos

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as cinco questões de referência do bloco: `2020/Q9` (código `NA20-Q09`), `2022/F2/Q3` (código `M2-22-F2-Q03`), `2023/F1/Q3` (código `M2-23-F1-Q03`), `2024/F2/Q4` (código `M2-24-F2-Q04`) e `2024/F1/Q2` (código `M2-24-F1-Q02`).

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Juntar itens em pares ou em conjuntos completos, e descobrir o que sobra quando o pareamento não fecha de forma exata. O bloco reúne quatro variações: (a) formar pares entre itens que precisam ter o mesmo atributo, como o número de um par de meias, (b) formar pares entre dois lados que se completam, esquerdo com direito, achando o menor número de "donos" possível a partir do excesso de um dos lados, (c) descobrir qual mão foi usada num carimbo pela posição do dedão, contando por orientação, e (d) montar conjuntos completos com uma peça de cada tipo, limitados pelo tipo mais escasso.

**Nó principal (Apêndice D, grade oficial).** `Análise Combinatória › Contagem Direta e Contagem por Posição` (mesmo subnó proposto do Bloco $1$ deste Caminho). As quatro variações continuam sendo formas de contar com cuidado, aqui aplicadas especificamente ao pareamento de itens complementares e à montagem de conjuntos limitados pela peça mais rara.

**Descritores secundários.**
- Pareamento por atributo igual: um par só se forma entre dois itens que compartilham o mesmo valor de um atributo (o mesmo número, por exemplo). Um item cujo atributo não se repete fica de fora, mesmo com outros itens sobrando no monte.
- Pareamento por lados complementares: quando o par precisa de um item de cada lado (esquerdo e direito), o número de pares completos é o menor entre as duas contagens, e o excesso do lado maior é o que sobra sem par.
- Menor número de "donos" a partir do excesso: quando cada dono contribui no máximo um item de cada lado, o menor número de donos possível é sempre igual à contagem do lado que mais aparece, não à soma dos dois lados.
- Contagem por posição do dedão: a posição do dedão num carimbo de mão (à direita = mão esquerda, à esquerda = mão direita) transforma uma pergunta sobre "qual mão" numa contagem direta de posição, desde que a regra de correspondência seja aplicada com cuidado.
- Total menos a parte conhecida, aplicado a mãos: quando o total de carimbos e o total de crianças (todas com pelo menos uma mão carimbada) são dados, quem esqueceu a segunda mão sai subtraindo, primeiro, o total de crianças da soma total de carimbos, depois o resultado do total de crianças de novo, parente do descritor "total menos o que já se sabe" do Bloco $1$ do Caminho $6$.
- Cota pelo tipo mais escasso: montar um conjunto com uma peça de cada tipo diferente limita o número de conjuntos completos à quantidade do tipo mais escasso, mesmo com sobra generosa dos outros tipos.

**Não é X (e por quê).**
- Não é Raciocínio Lógico › Dedução com Pistas Numéricas (Bloco $1$ do Caminho $6$), porque nenhuma das quatro variações pede descobrir um número escondido a partir de pistas cruzadas. A resposta sai de contar e comparar quantidades já visíveis.
- Não é o Bloco $1$ deste mesmo Caminho, porque ali a contagem é sobre um único tipo de item de cada vez (uma figura, um símbolo, um algarismo). Aqui a contagem sempre envolve comparar duas ou mais categorias entre si, para formar pares ou conjuntos.
- Não é Grandezas e Medidas, mesmo quando a variação (a) usa números de calçado. O número aqui é só um rótulo de identificação, não uma medida a calcular ou converter.
- Não é Contagem e Combinatória (Bloco $5$ deste Caminho, "cada escolha multiplica"), porque nenhuma variação multiplica opções independentes. O pareamento e a montagem de conjuntos aqui são sempre limitados pelo lado ou pelo tipo mais escasso, uma restrição de mínimo, não uma multiplicação de possibilidades.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 7** › **Bloco 2 · Pareamento: pés, mãos e conjuntos** › capítulo de teoria "Juntar aos pares" (`Cap_Pareamento_Pes_Maos_Conjuntos.md`).

---

***Notas específicas de cada questão de referência***

`2020/Q9` (código `NA20-Q09`)
- **Motor aplicado:** variação (a), pareamento por atributo igual. Os sapatos de uma loja estão misturados, cada um marcado com um número, e Alice forma pares entre sapatos do mesmo número, um pé direito com um pé esquerdo. Contando quantas vezes cada número aparece, dá para formar $5$ pares completos. Gabarito **B ($5$)** ✅, conferido contra a solução oficial (`sf1na-2020.pdf`, questão $9$).
- **Não é X específico:** não é uma questão de combinar todos os sapatos possíveis entre si, é contar, número por número, quantos pares fecham exatamente.

`2022/F2/Q3` (código `M2-22-F2-Q03`)
- **Motor aplicado:** variação (c) seguida de (b) invertida, contagem por posição e depois total menos a parte conhecida. Algumas crianças carimbaram a mão esquerda numa cartolina, e a pergunta pede quantas esqueceram de carimbar a direita. Das $9$ figuras carimbadas, $3$ têm a posição de mão direita, então $6$ são de mão esquerda, ou seja, $6$ crianças participaram. Dessas $6$, $3$ também carimbaram a direita, e $6-3=3$ esqueceram. Gabarito **C ($3$)** ✅, conferido contra a solução oficial (`sf2m2-2022.pdf`, questão $3$).
- **Não é X específico:** não dá para responder só com o total de carimbos, é preciso separar as duas mãos pela posição do dedão antes de calcular quem esqueceu a segunda.

`2023/F1/Q3` (código `M2-23-F1-Q03`)
- **Motor aplicado:** variação (c), contagem por posição do dedão. Marília carimbou as mãos, formando $9$ figuras dispostas em círculo, e a pergunta pede quantas vezes ela carimbou a mão esquerda. Só $3$ das $9$ figuras têm a posição de mão esquerda. Gabarito **C ($3$)** ✅, conferido contra a solução oficial (`sf1m2-2023.pdf`, questão $3$).
- **Não é X específico:** não é uma questão sobre quantas mãos ao todo, é sobre uma orientação específica entre as duas possíveis, e a disposição em círculo não muda a contagem por posição do dedão.

`2024/F2/Q4` (código `M2-24-F2-Q04`)
- **Motor aplicado:** variação (b), menor número de "donos" a partir do excesso. Alunos retiraram os chinelos para a natação, e a pergunta pede o menor número de alunos possível. Formando pares entre os chinelos esquerdos e direitos mostrados na figura, sobram $4$ chinelos direitos sem par, cada um exigindo um aluno a mais. Gabarito **C ($5$)** ✅🖼️, conferido contra a solução oficial (`sf2m2-2024.pdf`, questão $4$: corrige a tentativa "B (4)" registrada em versões anteriores da ficha-mestra).
- **Não é X específico:** não é somar todos os chinelos e dividir por $2$, porque nem todo chinelo tem um par, o menor número de alunos é sempre igual à contagem do lado que mais aparece.

`2024/F1/Q2` (código `M2-24-F1-Q02`)
- **Motor aplicado:** variação (d), cota pelo tipo mais escasso. A figura mostra $7$ lápis, $6$ apontadores e $5$ borrachas, e a pergunta pede quantos conjuntos de $1$ lápis, $1$ borracha e $1$ apontador dá para montar. A borracha é o tipo mais escasso, com só $5$ unidades, e por isso $5$ é a resposta. Gabarito **D ($5$)** ✅🖼️, conferido contra a solução oficial (`sf1m2-2024.pdf`, questão $2$).
- **Não é X específico:** não é uma questão de contar todos os objetos juntos, é achar o tipo mais escasso entre os três, porque ele é quem limita quantos conjuntos completos existem.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Pareamento_Pes_Maos_Conjuntos.md` seguem a classificação acima:
- Exercícios $1$ e $2$: variação (a), pareamento por atributo igual, contando pares de meias pelo número.
- Exercícios $3$ e $4$: variação (b), pareamento por lados complementares, achando o menor número de "donos".
- Exercícios $5$ e $6$: variação (c), contagem por posição do dedão num carimbo de mão.
- Exercícios $7$ e $8$: variação (c) seguida de total menos a parte conhecida, como em `2022/F2/Q3`.
- Exercícios $9$ e $10$: variação (d), cota pelo tipo mais escasso ao montar conjuntos completos.
