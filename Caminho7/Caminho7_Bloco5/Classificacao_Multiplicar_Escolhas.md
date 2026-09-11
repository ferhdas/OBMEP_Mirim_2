Ficha de classificação · Bloco $5$ · Multiplicar as escolhas

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as quatro questões de referência do bloco: `2025/F1/Q5` (código `M2-25-F1-Q05`), `2024/F1/Q14` (código `M2-24-F1-Q14`), `2024/F2/Q8` (código `M2-24-F2-Q08`) e `2023/F1/Q9` (código `M2-23-F1-Q09`).

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Contar combinações formadas por duas ou mais escolhas independentes, multiplicando as quantidades de cada categoria, e ajustando o produto quando a pergunta exige. O bloco reúne quatro variações: (a) multiplicar diretamente duas quantidades de escolhas independentes, (b) multiplicar e depois subtrair as combinações que uma condição extra proíbe, (c) contar quantos resultados diferentes uma operação entre escolhas pode produzir, reconhecendo que escolhas diferentes às vezes dão o mesmo resultado, e (d) calcular, por uma regra de "pelo menos um de cada tipo", a própria quantidade de escolhas de uma categoria antes de multiplicar.

**Nó principal (Apêndice D, grade oficial).** `Análise Combinatória › Princípio Multiplicativo da Contagem` (subnó proposto, já referenciado nos blocos anteriores deste Caminho). É o nó que define diretamente a ideia central do bloco, que escolhas independentes se combinam por multiplicação, não por soma.

**Descritores secundários.**
- Produto de escolhas independentes: quando a escolha de uma categoria não muda as opções disponíveis da outra, o total de combinações é o produto das quantidades de cada categoria.
- Produto total menos casos proibidos: quando uma condição exclui algumas combinações do produto, calcula-se primeiro o produto sem restrição, e só depois se subtraem as combinações proibidas, nunca contando direto as combinações válidas sem esse passo intermediário.
- Resultado repetido entre escolhas diferentes: ao listar os resultados de uma operação (como uma multiplicação) entre pares de escolhas, resultados iguais vindos de pares diferentes contam como um só, especialmente quando um dos valores envolvidos é $0$.
- Quantidade de escolhas calculada por uma regra: quando o número de opções de uma categoria não vem pronto, mas depende de uma condição do tipo "pelo menos um de cada tipo em cada grupo", esse número se calcula separadamente antes de entrar na multiplicação final.

**Não é X (e por quê).**
- Não é o Bloco $6$ deste Caminho (Contar tirando os casos que não valem), mesmo quando a variação (b) subtrai combinações proibidas de um produto. A diferença é que aqui a subtração vem depois de um produto de duas categorias independentes, e no Bloco $6$ o ponto de partida costuma ser um total já fixo, não necessariamente um produto de duas escolhas.
- Não é Sistema de Numeração ou Operações Básicas como nó principal, mesmo quando a variação (c) envolve multiplicar algarismos de um número. O foco da questão é contar quantos resultados diferentes existem, uma contagem combinatória, não uma propriedade do sistema decimal.
- Não é o Bloco $2$ deste Caminho (Pareamento), porque ali as quantidades de duas categorias se combinam por um mínimo ou por uma diferença, não por um produto de escolhas livres.
- Não é o Bloco $4$ deste Caminho (Organizar em fila e nos intervalos), mesmo quando a variação (d) usa uma regra de "pelo menos um de cada tipo". Aqui não existe fileira nem posição, só uma divisão de itens iguais em dois grupos, cuja contagem entra como fator de um produto maior.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 7** › **Bloco 5 · Multiplicar as escolhas** › capítulo de teoria "Cada escolha multiplica" (`Cap_Multiplicar_Escolhas.md`).

---

***Notas específicas de cada questão de referência***

`2025/F1/Q5` (código `M2-25-F1-Q05`)
- **Motor aplicado:** variação (a), produto de escolhas independentes. Numa garagem de $14$ vagas, $3$ já ocupadas, sobram $11$ vagas livres, e cada vaga aceita o carro de frente ou de ré, $2$ jeitos. Multiplicando, $11\times2=22$. Gabarito **E ($22$)** ✅🖼️, conferido contra a solução oficial (`sf1m2-2025.pdf`, questão $5$).
- **Não é X específico:** não é somar as $11$ vagas com as $2$ orientações ($11+2=13$), as duas escolhas são independentes e por isso se multiplicam.

`2024/F1/Q14` (código `M2-24-F1-Q14`)
- **Motor aplicado:** variação (d), quantidade de escolhas calculada por uma regra. Janaína tem $2$ vasos, $4$ rosas e $3$ margaridas, e quer pelo menos uma flor de cada tipo em cada vaso. As rosas podem se dividir de $3$ jeitos ($4-1=3$), as margaridas de $2$ jeitos ($3-1=2$), e multiplicando, $3\times2=6$. Gabarito **B ($6$)** ✅, conferido contra a solução oficial (`sf1m2-2024.pdf`, questão $14$).
- **Não é X específico:** não é contar todas as divisões possíveis das rosas e das margaridas sem a restrição, a condição "pelo menos uma de cada tipo em cada vaso" já reduz as divisões possíveis antes mesmo de multiplicar.

`2024/F2/Q8` (código `M2-24-F2-Q08`)
- **Motor aplicado:** variação (b), produto total menos casos proibidos. Juliano tem $4$ camisetas e $3$ bermudas, e quer se vestir com peças de cores diferentes. O produto total é $4\times3=12$, e duas combinações de mesma cor são proibidas (branca com branca, azul com azul), restando $12-2=10$. Gabarito **C ($10$)** ✅, conferido contra a solução oficial (`sf2m2-2024.pdf`, questão $8$).
- **Não é X específico:** não é contar direto as combinações de cores diferentes sem passar pelo produto total, esse caminho é mais sujeito a esquecer alguma combinação.

`2023/F1/Q9` (código `M2-23-F1-Q09`)
- **Motor aplicado:** variação (c), resultado repetido entre escolhas diferentes. Janaína escolhe dois algarismos do número $1023$ (algarismos $1$, $0$, $2$, $3$) e multiplica. Os seis produtos possíveis são $0$, $2$, $3$, $0$, $0$ e $6$, e como o algarismo $0$ aparece nas escolhas, várias multiplicações repetem o resultado $0$. Descontando as repetições, sobram $4$ resultados diferentes, $0$, $2$, $3$ e $6$. Gabarito **D ($4$)** ✅, conferido contra a solução oficial (`sf1m2-2023.pdf`, questão $9$).
- **Não é X específico:** não é contar quantos pares de algarismos existem (isso daria $6$), é contar quantos valores diferentes os produtos desses pares produzem, e o $0$ colapsa três pares num só resultado.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Multiplicar_Escolhas.md` seguem a classificação acima:
- Exercícios $1$ a $3$: variação (a), produto de escolhas independentes, o exercício $3$ com três categorias em vez de duas.
- Exercícios $4$ e $5$: variação (b), produto total menos casos proibidos.
- Exercícios $6$ e $7$: variação (c), resultados diferentes de um produto de algarismos, o exercício $7$ incluindo o algarismo $0$ entre as escolhas.
- Exercícios $8$ a $10$: variação (d), quantidade de escolhas calculada pela regra "pelo menos um de cada tipo em cada grupo".
