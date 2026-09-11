Ficha de classificação · Bloco $3$ · Deduzir as faces de dados e cubos

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as cinco questões de referência do bloco: `2020/Q13` (código `NA20-Q13`), `2022/F2/Q14` (código `M2-22-F2-Q14`), `2023/F2/Q8` (código `M2-23-F2-Q08`), `2024/F1/Q4` (código `M2-24-F1-Q04`) e `2025/F2/Q9` (código `M2-25-F2-Q09`).

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Descobrir um número que está numa face de um cubo ou de um dado sem poder olhar diretamente para ela, usando só uma regra sobre as faces opostas ou sobre o total de vários lançamentos. O bloco reúne quatro variações: (a) usar a regra de que todo par de faces opostas soma sempre o mesmo valor para achar uma face escondida ou para descartar uma soma impossível nos outros pares, (b) quando um cubo só usa poucos valores diferentes, cada um repetido em mais de uma face, achar o menor ou o maior total possível para as seis faces, (c) girar o cubo e acompanhar, giro a giro, quais letras ou números ficam em faces opostas, e (d) quando o mesmo dado é lançado várias vezes e só o total final é dado, descobrir qual face apareceu com certeza em pelo menos um dos lançamentos.

**Nó principal (Apêndice D, grade oficial).** `Raciocínio Lógico › Problemas com Visualização Espacial`. É o nó que mais se aproxima das quatro variações, porque em todas elas a resposta depende de imaginar a face escondida de um sólido a partir de regras e vistas parciais, não de calcular algo já visível. A variação (d) também encosta em `Raciocínio Lógico › Problemas com Restrições e Dedução › Dedução com Pistas Numéricas`, do Bloco $1$ deste mesmo Caminho, porque o raciocínio de testar as poucas somas possíveis é o mesmo, só que aplicado às faces de um dado em vez de a grupos de números soltos.

**Descritores secundários.**
- Par oposto de soma fixa: num dado comum a soma de duas faces opostas é sempre $7$, e essa regra também pode aparecer inventada com outro valor fixo, sempre do mesmo jeito, cada face tem uma única oposta e a soma das duas nunca muda.
- Cota mínima ou máxima por composição de poucos valores: quando só um conjunto pequeno de números pode aparecer nas faces, cada um usado ao menos uma vez, o menor total possível vem de completar as faces que faltam com o menor valor disponível, e o maior total possível vem de completar com o maior valor disponível, respeitando sempre a obrigação de usar cada valor ao menos uma vez.
- Pareamento por eliminação num giro: um cubo com seis rótulos diferentes forma exatamente três pares de faces opostas, e descobrir dois desses pares por meio de giros observados deixa só uma dupla de rótulos para o terceiro par, que fecha por eliminação.
- Decomposição de um total em parcelas limitadas: quando vários lançamentos de dado somam um total conhecido, cabe testar quais combinações de valores entre $1$ e $6$ chegam a esse total, e um valor que aparece em todas as combinações possíveis é o único que pode ser afirmado com certeza.

**Não é X (e por quê).**
- Não é Geometria › Percepção Espacial no Plano (Caminho $4$), porque nenhuma das variações lida com figuras achatadas, contorno ou composição de peças planas. O cubo aqui é sempre um sólido, e o que se pede é uma face dele, não uma forma no papel.
- Não é o Bloco $3$ da unidade de Grandezas, Medidas e Sólidos, que trata de planificação, vistas ortogonais e decomposição de sólidos por volume. Aqui a pergunta nunca é "que sólido é esse" ou "quantos cubinhos cabem", é sempre "que número ou letra está numa face que eu não vejo".
- Não é o Bloco $1$ deste Caminho como classificação principal, mesmo quando o raciocínio da variação (d) lembra o de testar candidatos por total. A diferença é o objeto, aqui as parcelas vêm sempre de faces de um mesmo dado, limitadas a $1$–$6$, e a resposta é sempre sobre uma face, não sobre um grupo de números soltos.
- Não é Contagem e Combinatória, porque a variação (b) não pede quantas composições diferentes existem, pede só o menor ou o maior total possível dentro das composições permitidas.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 6** › **Bloco 3 · Deduzir as faces de dados e cubos** › capítulo de teoria "O que está na face escondida" (`Cap_Faces_Dados_Cubos.md`).

---

***Notas específicas de cada questão de referência***

`2020/Q13` (código `NA20-Q13`)
- **Motor aplicado:** variação (a), par oposto de soma fixa usado para descartar uma soma impossível. Samuel numerou as seis faces de $1$ a $6$, e um par de faces opostas soma $3$, o que só pode ser $\{1,2\}$. As outras quatro faces são $3$, $4$, $5$ e $6$, e testando todos os pares possíveis entre elas, as somas alcançáveis são $7$, $8$, $9$, $10$ e $11$, nunca $6$. Gabarito **A ($6$)** ✅, conferido contra a solução oficial (`sf1na-2020.pdf`, questão $13$).
- **Não é X específico:** não é suficiente achar só uma soma possível e concluir que as outras são impossíveis, é preciso testar todos os pareamentos válidos dos quatro números restantes antes de afirmar que uma soma nunca aparece.

`2022/F2/Q14` (código `M2-22-F2-Q14`)
- **Motor aplicado:** variação (b), cota mínima por composição de poucos valores. O cubo de Patrícia só tem os números $1$, $2$ e $4$ nas faces, cada um usado ao menos uma vez, e ela vê as faces $1$, $1$ e $4$. Como o $2$ ainda não apareceu, ao menos uma das três faces escondidas tem que ser $2$. O menor total possível usa o $2$ obrigatório e completa as outras duas faces escondidas com o menor valor disponível, o $1$, chegando a $1+1+4+2+1+1=10$. Gabarito **B (a soma é no mínimo $10$)** ✅, conferido contra a solução oficial (`sf2m2-2022.pdf`, questão $14$).
- **Não é X específico:** não dá para afirmar a soma exata das seis faces, porque as três faces escondidas podem variar entre si, respeitando só a obrigação de ter ao menos um $2$. O que se pode afirmar com certeza é apenas o limite mínimo.

`2023/F2/Q8` (código `M2-23-F2-Q08`)
- **Motor aplicado:** variação (a), par oposto de soma fixa usado para achar a face escondida. Num dado comum, a soma de faces opostas é sempre $7$. As faces visíveis mostram $4$ e $2$, cujas opostas são $3$ e $5$. Sobra o par $\{1,6\}$ para as faces de cima e de baixo, e como a face de cima não tem número par, ela só pode ser $1$. Gabarito **A ($1$)** ✅, conferido contra a solução oficial (`sf2m2-2023.pdf`, questão $8$).
- **Não é X específico:** não é preciso descobrir a face de baixo nem a posição de nenhuma outra face, só isolar o par que sobra depois de eliminar os dois pares já identificados pelas faces visíveis.

`2024/F1/Q4` (código `M2-24-F1-Q04`)
- **Motor aplicado:** variação (d), decomposição de um total em parcelas limitadas. André jogou um dado três vezes e a soma das faces de cima foi $17$. O máximo possível em três lançamentos é $18$, e a única forma de somar $17$ com três valores entre $1$ e $6$ é $6+6+5$, em qualquer ordem. Como o $5$ aparece em toda decomposição válida, ele com certeza foi uma das faces sorteadas. Gabarito **E ($5$)** ✅, conferido contra a solução oficial (`sf1m2-2024.pdf`, questão $4$).
- **Não é X específico:** não é uma pergunta sobre qual foi a ordem das jogadas, é sobre qual face aparece em toda decomposição possível do total, mesmo sem saber a ordem exata dos três lançamentos.

`2025/F2/Q9` (código `M2-25-F2-Q09`)
- **Motor aplicado:** variação (c), pareamento por eliminação num giro. O cubo de Martina tem as letras A a F, uma em cada face. No primeiro giro, ela vê que C e D ficam em faces opostas. No segundo giro, vê que A e E ficam em faces opostas. Como um cubo só tem três pares de faces opostas, e dois já foram descobertos, o terceiro par tem que ser formado pelas duas letras que sobraram, F e B. Gabarito **B** ✅, conferido contra a solução oficial (`sf2m2-2025.pdf`, questão $9$).
- **Não é X específico:** não é necessário reconstruir o cubo inteiro nem imaginar a posição de cada face durante os giros, o pareamento final sai só de eliminar os dois pares já vistos e juntar quem sobrou.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Faces_Dados_Cubos.md` seguem a classificação acima:
- Exercícios $1$, $2$, $3$ e $4$: variação (a), par oposto de soma fixa, tanto para achar a face escondida quanto para descartar uma soma impossível.
- Exercícios $5$ e $6$: variação (b), cota mínima ou máxima por composição de poucos valores.
- Exercícios $7$ e $8$: variação (c), pareamento por eliminação num giro do cubo.
- Exercícios $9$ e $10$: variação (d), decomposição de um total de vários lançamentos.
