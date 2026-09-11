Ficha de classificação · Bloco $1$ · Descobrir os números que faltam

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as cinco questões de referência do bloco: `2019/Q9` (código `NA19-Q09`), `2020/Q10` (código `NA20-Q10`), `2020/Q14` (código `NA20-Q14`), `2025/F1/Q9` (código `M2-25-F1-Q09`) e `2024/F1/Q12` (código `M2-24-F1-Q12`).

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Descobrir um valor numérico escondido usando só as relações dadas entre os números, nunca uma medida ou uma figura para ler. O bloco reúne cinco variações do mesmo cuidado de "isolar a incógnita a partir das pistas": (a) achar um grupo pelo total que ele deveria somar, testando e descartando o agrupamento que não fecha com a segunda pista, (b) trocar uma quantidade por outra ao longo de uma cadeia de igualdades até reduzir tudo à mesma unidade, (c) buscar a única solução possível quando só o total final é dado, testando as contagens de cada categoria uma por uma, (d) preencher uma casa de uma grade numérica usando as somas de linhas e colunas como pistas cruzadas, e (e) descobrir quantas vezes uma pessoa participou de algo a partir de quantas vezes as outras participaram, contando como uma rede de ligações.

**Nó principal (Apêndice D, grade oficial).** `Raciocínio Lógico › Problemas com Restrições e Dedução › Dedução com Pistas Numéricas`. É o nó que melhor cobre o fio comum das cinco variações, isolar um número a partir de pistas sobre outros números, sem depender de leitura de figura. As variações (d) e (e) também encostam em nós vizinhos da mesma família: (d) em `Aritmética › Problemas com Restrições de Soma (Linhas e Colunas / Matrizes)`, e (e) em `Raciocínio Lógico › Problemas com Pontuação, Torneios e Máximos sob Restrições`. Mantemos o nó principal único porque, em todos os cinco casos, o que resolve a questão é a dedução a partir de pistas numéricas, e as somas de linha/coluna ou a contagem de partidas são só o formato da pista, não o motor.

**Descritores secundários.**
- Total conhecido menos parcelas conhecidas: a pista mestra de quase todo o bloco é que o todo e algumas partes já aparecem, e a parte que falta sai por subtração, variação já registrada noutros blocos da trilha, aqui aplicada a grupos de números (variação a) e a somas de linha/coluna (variação d).
- Teste e descarte de candidato: quando uma pista admite mais de um agrupamento possível, o segundo cuidado é testar cada candidato contra a próxima pista e descartar o que não fecha, nunca escolher o primeiro que parece razoável (variações a e d).
- Substituição em cadeia (parente do descritor "Duas pistas para duas quantidades" do Caminho $1$, mas aqui com três ou mais elos): cada igualdade troca uma coisa por outra até restar só a unidade de referência (variação b).
- Busca sistemática da solução única: quando o total é dado mas a divisão em categorias não, testa-se cada contagem possível de uma categoria, uma por vez, até sobrar exatamente uma que bate com o total (variação c).
- Contagem por participação (grau): cada pessoa "participa" um número de vezes, e quem participa o máximo possível já fica ligado a todo mundo, o que trava o resto da rede por eliminação (variação e).

**Não é X (e por quê).**
- Não é Geometria › Percepção Espacial, porque nenhuma das cinco variações depende de olhar, girar ou encaixar uma figura. A informação inteira já vem em números e frases, mesmo quando a questão original vem ilustrada com pesos ou animais desenhados.
- Não é Contagem e Combinatória como nó principal, porque a pergunta não é "de quantos jeitos", é "qual é o número escondido". A variação (e), sobre partidas de torneio, se aproxima da combinatória mas continua sendo dedução, porque o número de participações de cada um já está dado e cabe achar a rede que bate com todos eles, não contar todas as redes possíveis.
- Não é Álgebra › Sistemas de Equações, porque nenhuma variação pede montar e resolver equações com letras. A variação (b), de substituição em cadeia, e a variação (d), de somas em grade, se resolvem por troca direta de valores e por dedução passo a passo, sem escrever incógnita nenhuma.
- Não é Sequências e Padrões Numéricos (Caminho $8$), porque não há regularidade que se repete e se estende. Cada questão do bloco tem uma resposta única, fechada pelas pistas daquele caso específico, não uma regra que continua indefinidamente.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 6** › **Bloco 1 · Descobrir os números que faltam** › capítulo de teoria "Descobrir os números que faltam" (`Cap_Numeros_PorPistas.md`).

---

***Notas específicas de cada questão de referência***

`2019/Q9` (código `NA19-Q09`)
- **Motor aplicado:** variação (a), achar um grupo pelo total. Seis pesos de $1$ a $6$ gramas são separados em três gavetas, duas a duas. A primeira gaveta soma $9$ g e a segunda soma $8$ g. A pista $9$ g admite dois candidatos, $\{3,6\}$ e $\{4,5\}$. Testando $\{3,6\}$, sobram $\{1,2,4,5\}$, e nenhum par desses soma $8$. Testando $\{4,5\}$, sobram $\{1,2,3,6\}$, e $\{2,6\}$ soma $8$. Logo a primeira gaveta é $\{4,5\}$, a segunda é $\{2,6\}$, e a terceira, por sobra, é $\{1,3\}$. Gabarito **A ($1$ g e $3$ g)** ✅, conferido contra a solução oficial (`snA-2019.pdf`, questão $9$).
- **Não é X específico:** não basta achar o total da terceira gaveta por subtração ($21-9-8=4$ g), porque a pergunta pede **quais** pesos, não só a soma, e $4$ g também poderia vir de $\{1,3\}$ ou não vir de nenhum par disponível. É esse detalhe que torna a questão uma dedução, não uma subtração simples.

`2020/Q10` (código `NA20-Q10`)
- **Motor aplicado:** variação (b), substituição em cadeia. Na feira, um pato vale duas galinhas, um leitão mais três patos vale uma cabra, e dois patos mais duas galinhas valem um leitão. Convertendo tudo para patos, dois patos e duas galinhas dão $2+1=3$ patos (porque duas galinhas valem um pato), então um leitão vale $3$ patos. Substituindo na segunda igualdade, um leitão mais três patos é $3+3=6$ patos, e é isso que vale uma cabra. Gabarito **D ($6$)** ✅, conferido contra a solução oficial (`sf1na-2020.pdf`, questão $10$).
- **Não é X específico:** não é uma questão de razão nem de porcentagem, porque nenhuma comparação é proporcional a uma unidade externa (não se compara "quantos por cento"), é troca direta, uma coisa no lugar de outra, até sobrar só uma espécie de animal.

`2020/Q14` (código `NA20-Q14`)
- **Motor aplicado:** variação (c), busca da solução única. Joaninhas pequenas têm $5$ pintas e joaninhas grandes têm $6$, e o total de pintas na festa é $43$. Supor $0$, $1$ ou $2$ joaninhas grandes deixa um resto que não é múltiplo de $5$ ($43$, $37$ e $31$), então é impossível. Com $3$ grandes, sobra $43-18=25=5\times5$, que fecha com $5$ pequenas. Com $4$ ou mais grandes, o resto também não seria múltiplo de $5$, e $8$ ou mais grandes já passariam de $43$ pintas sozinhas. Logo há $3$ grandes e $5$ pequenas, $8$ joaninhas ao todo. Gabarito **C ($8$)** ✅, conferido contra a solução oficial (`sf1na-2020.pdf`, questão $14$).
- **Não é X específico:** não dá para montar uma conta direta de divisão, porque o total mistura duas espécies com pintas diferentes. É a busca ordenada, testando cada contagem possível de uma espécie, que fecha a questão.

`2025/F1/Q9` (código `M2-25-F1-Q09`)
- **Motor aplicado:** variação (d), grade numérica com somas de linha e coluna. Um quadriculado $3\times3$ recebe os números de $1$ a $9$, sem repetir. A soma da primeira linha é $6$, a segunda é $22$, a primeira coluna é $20$ e a segunda é $14$. A soma mínima possível de três números diferentes é $1+2+3=6$, então a primeira linha só pode ser $\{1,2,3\}$. Testando as colunas, a única distribuição que fecha as quatro somas dadas deixa $4$ na casa cinza (linha $3$, coluna $3$). Gabarito **A ($4$)** ✅, conferido contra a solução oficial (`sf1m2-2025.pdf`, questão $9$).
- **Não é X específico:** não é Percepção Espacial no Plano, porque a grade não pede reconhecer forma nem posição visual, pede achar que números cabem em cada casa a partir das somas. A "casa cinza" é só o rótulo da posição a descobrir, não uma pista geométrica.

`2024/F1/Q12` (código `M2-24-F1-Q12`)
- **Motor aplicado:** variação (e), contagem de participações. Cinco jogadores disputam um torneio em que cada dupla joga no máximo uma vez. O $1º$ jogador jogou uma vez, o $3º$ jogou duas, o $4º$ jogou três e o $5º$ jogou quatro. Como o $5º$ jogou com todo mundo, a única partida do $1º$ jogador já é contra o $5º$, então o $1º$ não jogou com o $4º$. Como o $4º$ jogou três vezes e uma delas não pode ser com o $1º$, as outras duas partidas do $4º$ têm de ser com o $2º$, o $3º$ e o $5º$ à exceção de uma, o que fecha o $2º$ jogador em duas partidas. Gabarito **B (duas)** ✅, conferido contra a solução oficial (`sf1m2-2024.pdf`, questão $12$).
- **Não é X específico:** não é contagem combinatória do tipo "de quantos jeitos", porque a rede de partidas já está determinada pelas pistas, cabe reconstruí-la, não contar quantas redes diferentes seriam possíveis.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Numeros_PorPistas.md` seguem a classificação acima, dois exercícios para cada variação, na mesma ordem do capítulo de teoria:
- Exercícios $1$ e $2$: variação (a), achar um grupo pelo total, o segundo já exigindo testar e descartar um candidato.
- Exercícios $3$ e $4$: variação (b), substituição em cadeia, o quarto com um elo a mais que o terceiro.
- Exercícios $5$ e $6$: variação (c), busca da solução única a partir de um total misto.
- Exercícios $7$ e $8$: variação (d), grade numérica $3\times3$ com somas de linha e coluna.
- Exercícios $9$ e $10$: variação (e), contagem de participações numa rede de partidas.
