Ficha de classificação · Bloco $7$ · Contar configurações válidas

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as duas questões de referência do bloco: `2022/F1/Q7` (código `M2-22-F1-Q07`) e `2019/Q13` (código `NA19-Q13`).

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Contar, entre várias possibilidades, quantas respeitam uma regra dada, seja uma condição de paridade sobre um valor único, seja uma condição de preenchimento válido num quadriculado inteiro. O bloco reúne duas variações: (a) contar quantos valores possíveis têm a paridade necessária para vencer uma disputa de par ou ímpar, e (b) contar quantos preenchimentos completos de um quadriculado respeitam a regra de não repetir números em nenhuma linha nem coluna, a partir de uma casa já dada.

**Nó principal (Apêndice D, grade oficial).** `Análise Combinatória › Princípio Multiplicativo da Contagem` (mesmo subnó proposto dos demais blocos deste Caminho). Embora a contagem final das duas variações não seja um produto direto de fatores, ela nasce do mesmo cuidado combinatório, enumerar sistematicamente as possibilidades válidas, testando e eliminando o que não respeita a regra.

**Descritores secundários.**
- Contagem por paridade complementar: numa disputa em que a soma de dois valores precisa ter uma paridade específica, a quantidade de valores que servem para o segundo participante depende só de quantos valores, dentro do intervalo possível, têm a paridade necessária, não do valor específico mostrado pelo primeiro participante.
- Intervalo simétrico de paridade: quando o intervalo de valores possíveis é simétrico entre pares e ímpares (como $0$ a $5$, com $3$ de cada), a contagem de valores vencedores é sempre a mesma, não importa a paridade escolhida nem o valor mostrado primeiro. Essa simetria se perde em intervalos maiores ou assimétricos (como $0$ a $10$).
- Preenchimento válido por eliminação sistemática: num quadriculado com a regra de números diferentes em cada linha e coluna, contar os preenchimentos válidos a partir de uma casa dada exige testar as possibilidades linha por linha, eliminando a cada passo as escolhas que já entram em conflito com o que foi fixado.
- Invariância da contagem num quadriculado $3\times3$: para um quadriculado $3\times3$ preenchido com três símbolos diferentes, respeitando linhas e colunas, a quantidade de preenchimentos válidos a partir de uma única casa dada é sempre $4$, não importa qual casa nem qual valor foi fixado.

**Não é X (e por quê).**
- Não é Raciocínio Lógico › Problemas com Restrição de Quantidade em Linhas e Colunas (Bloco $1$ do Caminho $6$), mesmo quando a variação (b) usa um quadriculado com regra de linhas e colunas. A diferença é a pergunta, lá o quadriculado tem números que precisam ser descobertos a partir de somas dadas, e aqui a pergunta é quantos preenchimentos completos diferentes existem, uma contagem combinatória, não uma dedução de valores.
- Não é o Bloco $5$ deste Caminho (Multiplicar as escolhas), porque as duas variações não se resolvem por um produto direto de contagens independentes, elas exigem enumerar e testar possibilidades que interagem entre si (a paridade de uma soma, ou o preenchimento simultâneo de várias casas).
- Não é Probabilidade, mesmo quando a variação (a) envolve uma disputa com vencedor e perdedor. A pergunta não é sobre a chance de vencer, é sobre contar quantos valores diferentes garantem a vitória.
- Não é o Bloco $6$ deste Caminho (Contar tirando os casos que não valem), porque aqui não existe um total maior do qual se subtraem casos proibidos, existe uma contagem direta e sistemática das configurações que já nascem válidas.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 7** › **Bloco 7 · Contar configurações válidas** › capítulo de teoria "Quantos jeitos respeitam a regra" (`Cap_Configuracoes_Validas.md`).

---

***Notas específicas de cada questão de referência***

`2022/F1/Q7` (código `M2-22-F1-Q07`)
- **Motor aplicado:** variação (a), contagem por paridade complementar. Isabel e Paula brincam de par ou ímpar, cada uma mostrando uma mão. Paula escolheu par e mostrou $4$ dedos, um número par, então Isabel só ganha se mostrar um número ímpar. Entre os valores possíveis de uma mão, $0$ a $5$, os ímpares são $1$, $3$ e $5$. Gabarito **C ($3$)** ✅, conferido contra a solução oficial (`sf1m2-2022.pdf`, questão $7$).
- **Não é X específico:** não é uma questão de probabilidade sobre a chance de Isabel ganhar, é uma contagem de quantos valores diferentes de dedos garantem a vitória dela.

`2019/Q13` (código `NA19-Q13`)
- **Motor aplicado:** variação (b), preenchimento válido por eliminação sistemática. Janaína preenche um quadriculado $3\times3$ com os números $1$, $2$ e $3$, sem repetir em nenhuma linha nem coluna, com a casa da primeira linha e primeira coluna já preenchida com $1$. Testando as possibilidades linha por linha, existem $4$ preenchimentos válidos. Gabarito **C ($4$)** ✅, conferido contra a solução oficial (`snA-2019.pdf`, questão $13$).
- **Não é X específico:** não é uma questão de descobrir um número escondido a partir de somas ou pistas numéricas, todas as regras já estão dadas (números diferentes por linha e coluna), e o que se conta são os preenchimentos completos que respeitam essas regras.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Configuracoes_Validas.md` seguem a classificação acima:
- Exercícios $1$ a $3$: variação (a), contagem por paridade complementar, com uma mão só (intervalo simétrico, resposta sempre $3$).
- Exercícios $4$ e $5$: variação (a), contagem por paridade complementar, com as duas mãos (intervalo assimétrico, resposta $5$ ou $6$).
- Exercícios $6$ a $10$: variação (b), preenchimento válido de um quadriculado $3\times3$, com a casa dada em posições diferentes, sempre confirmando a invariância da resposta $4$.
