Ficha de classificação · Bloco $6$ · Contar tirando os casos que não valem

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as três questões de referência do bloco: `2024/F1/Q8` (código `M2-24-F1-Q08`), `2023/F1/Q15` (código `M2-23-F1-Q15`) e `2025/F2/Q8` (código `M2-25-F2-Q08`).

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Contar um total completo e depois retirar o que uma regra exclui, ou descobrir por inventário o que ainda falta depois de uma distribuição. O bloco reúne três variações: (a) contar o total de um produto de escolhas e tirar categorias inteiras que deixaram de existir, (b) contar todas as combinações de um ou mais itens e tirar as que juntam dois itens proibidos ao mesmo tempo, e (c) achar exatamente o que sobra para o último grupo de uma distribuição, conferindo item por item quanto já foi usado.

**Nó principal (Apêndice D, grade oficial).** `Análise Combinatória › Princípio Multiplicativo da Contagem` (mesmo subnó proposto do Bloco $5$ deste Caminho). As três variações continuam sendo contagens que partem de um total ou de uma cota fixa, e chegam à resposta por eliminação do que não vale, em vez de contar direto só o que vale.

**Descritores secundários.**
- Total sem restrição menos categorias tiradas: quando um produto de escolhas perde categorias inteiras (uma linha, uma coluna, ou uma célula única), calcula-se o produto original e subtraem-se essas categorias, uma de cada vez.
- Combinações não vazias de $n$ itens: o total de combinações de $1$ ou mais itens, escolhidos livremente entre $n$ itens disponíveis, é sempre $2^n-1$, contando a combinação vazia fora.
- Combinações proibidas por dois itens fixos: para contar quantas combinações incluem dois itens específicos ao mesmo tempo, fixam-se esses dois itens como presentes e contam-se livremente as combinações dos itens restantes, $2^{n-2}$ combinações proibidas quando $n$ é o total de itens.
- Inventário item por item: quando o que se pede é descobrir o que sobra para o último grupo de uma distribuição, confere-se, tipo por tipo, quantas unidades já foram usadas pelos outros grupos, e o que falta para completar a cota total de cada tipo é o que sobra.

**Não é X (e por quê).**
- Não é o Bloco $5$ deste Caminho (Multiplicar as escolhas), mesmo quando a variação (a) usa um produto de duas categorias. A diferença é o ponto de partida, aqui categorias inteiras já deixaram de existir e precisam ser subtraídas do produto original, não é uma condição sobre pares de escolha que se aplica combinação por combinação.
- Não é o Bloco $2$ deste Caminho (Pareamento), mesmo quando a variação (c) envolve distribuir itens entre pessoas. A diferença é que aqui não existe formação de pares nem de conjuntos completos, existe uma cota fixa de cada tipo (sempre a mesma quantidade por tipo) e um inventário para achar o que sobra.
- Não é Raciocínio Lógico › Dedução com Pistas Numéricas (Bloco $1$ do Caminho $6$), porque a variação (c) não cruza pistas para descobrir um número escondido, ela confere diretamente quantas unidades de cada tipo já foram distribuídas, um inventário direto, não uma dedução por eliminação de possibilidades.
- Não é Operações Básicas como nó principal, mesmo quando a variação (b) usa potências de $2$ para contar combinações. O cálculo $2^n$ é só a ferramenta, o que classifica a questão é a contagem combinatória de combinações válidas, não o cálculo da potência em si.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 7** › **Bloco 6 · Contar tirando os casos que não valem** › capítulo de teoria "Contar tudo e tirar o proibido" (`Cap_Contar_Tirando_Proibido.md`).

---

***Notas específicas de cada questão de referência***

`2024/F1/Q8` (código `M2-24-F1-Q08`)
- **Motor aplicado:** variação (a), total sem restrição menos categorias tiradas. Uma fábrica produzia bolas em $3$ tamanhos e $3$ cores, $9$ tipos ao todo, e parou de produzir a bola verde pequena e as bolas amarelas de todos os tamanhos. O total fica $9-1-3=5$. Gabarito **B ($5$)** ✅, conferido contra a solução oficial (`sf1m2-2024.pdf`, questão $8$).
- **Não é X específico:** não é subtrair só $4$ tipos de uma vez sem separar as duas retiradas, a bola verde pequena e a linha inteira das amarelas são duas retiradas distintas, uma célula e uma categoria completa.

`2023/F1/Q15` (código `M2-23-F1-Q15`)
- **Motor aplicado:** variação (b), combinações proibidas por dois itens fixos. Irene tem $4$ ervas para o chá, usando $1$ ou mais ao mesmo tempo, mas nunca anis e hortelã juntas. O total sem restrição é $2^4-1=15$, e as combinações com anis e hortelã juntas são $2^{4-2}=4$. Subtraindo, $15-4=11$. Gabarito **E ($11$)** ✅, conferido contra a solução oficial (`sf1m2-2023.pdf`, questão $15$).
- **Não é X específico:** não é contar só as combinações com exatamente $2$, $3$ ou $4$ ervas separadamente e somar sem cuidado, o mais direto é usar o total de $2^n-1$ e tirar as combinações proibidas de uma vez.

`2025/F2/Q8` (código `M2-25-F2-Q08`)
- **Motor aplicado:** variação (c), inventário item por item. Dez figuras, duas de cada um de cinco tipos, foram distribuídas entre Ana, Beto, Carla, Daniel e Elisa, e a pergunta pede quais figuras sobraram para Elisa. Conferindo tipo por tipo, dois tipos já foram usados só uma vez cada, e são esses que sobram. Gabarito **A (estrela e coração)** ✅, conferido contra a solução oficial (`sf2m2-2025.pdf`, questão $8$).
- **Não é X específico:** não é uma questão de contagem combinatória com fórmula, é um inventário direto, cada tipo tem exatamente $2$ unidades ao todo, e o que sobra é o que ainda não completou essa cota depois de conferir as quatro primeiras pessoas.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Contar_Tirando_Proibido.md` seguem a classificação acima:
- Exercícios $1$ a $4$: variação (a), total sem restrição menos categorias tiradas, o exercício $4$ com duas categorias inteiras retiradas ao mesmo tempo.
- Exercícios $5$ a $7$: variação (b), combinações não vazias menos as que juntam dois itens proibidos.
- Exercícios $8$ a $10$: variação (c), inventário item por item para achar o que sobra, o exercício $9$ com seis tipos e seis pessoas em vez de cinco.
