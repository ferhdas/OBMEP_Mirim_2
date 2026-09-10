Ficha de classificação · Bloco $1$ · Achar a ordem

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as cinco questões de referência do bloco: `2018/Q17`, `2024/F1/Q10`, `2025/F2/Q4`, `2023/F2/Q15` e `2023/F1/Q8`.

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Reconstrução de uma ordem completa a partir de pistas parciais, sem nenhuma medida numérica direta. O bloco cobre três variações: (a) montar uma fila inteira a partir de pistas de posição relativa (na frente de, atrás de, entre), (b) montar um ranking encadeando comparações par a par por transitividade (se A é maior que B e B é maior que C, então A é maior que C), e (c) fechar uma ordem parcialmente dada usando uma pista negativa (o que **não** é verdade) para eliminar a única posição que sobra.

**Nó principal (Apêndice D, grade oficial).** `Raciocínio Lógico › Problemas com Restrições e Dedução › Grupos e Posicionamento com Pistas`. É o nó existente da grade que cobre pistas de posição e ordenação por dedução, sem precisar de subnó novo.

**Descritores secundários.**
- Transitividade de comparação (variação b): encadear "maior que" ou "mais rápido que" de pista em pista até cobrir todos os itens, o mesmo raciocínio que sustenta ordenar números ou grandezas sem medi-las diretamente.
- Eliminação por pista negativa (variação c): parente do descritor "achar a parte que falta de um total", já validado na trilha, aqui aplicado a uma posição em vez de uma quantidade.
- Unicidade da solução: em todas as variações, o conjunto de pistas precisa fechar numa única ordem possível, nunca em mais de uma, e o exercício deve dar pistas suficientes para isso.

**Não é X (e por quê).**
- Não é Casa dos Pombos (Bloco $5$ deste Caminho), porque aqui nenhuma pista força uma repetição por falta de espaço, cada posição da fila ou do ranking é ocupada por exatamente uma pessoa.
- Não é Associação por Pistas (Bloco $3$ deste Caminho), porque ali o desafio é casar pessoas com atributos diferentes (quem tem o quê), enquanto aqui todos os elementos são do mesmo tipo (pessoas numa fila, corredores numa corrida) e o que se busca é só a posição relativa entre eles.
- Não é Operações com Números Naturais, porque nenhuma das três variações soma, subtrai ou multiplica um valor. O raciocínio é comparar e ordenar, não calcular.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 5** › **Bloco 1 · Achar a ordem** › capítulo de teoria "Achar a ordem" (`Cap_Ordenar_Comparar.md`).

---

***Notas específicas de cada questão de referência***

`2018/Q17`
- **Motor aplicado:** variação (a) ou (b), a depender da leitura exata do enunciado (montagem de fila ou de ranking por pistas). 🖼️ (conferir a solução oficial antes de publicar).
- **Não é X específico:** não envolve conta aritmética, o valor pedido é uma posição ou uma identidade, não uma quantidade.

`2024/F1/Q10`
- **Motor aplicado:** variação (b), ranking por comparação par a par. Conferir se as pistas comparam grandezas (altura, idade, velocidade) ou posições diretas.
- **Não é X específico:** não é comparação de dois cenários (Caminho $6$), porque não há um "antes" e um "depois" a comparar, só uma cadeia de comparações entre itens diferentes.

`2025/F2/Q4`
- **Motor aplicado:** variação (a) ou (c), fila por pistas relativas com possível pista negativa a fechar a posição final.
- **Não é X específico:** não é um problema de contagem, o número de pessoas é dado, o que falta é só a ordem entre elas.

`2023/F2/Q15`
- **Motor aplicado:** variação (b), transitividade de comparação entre grandezas.
- **Não é X específico:** não pede o valor numérico de nenhuma grandeza, só a posição relativa no ranking.

`2023/F1/Q8`
- **Motor aplicado:** variação (c), eliminação por pista negativa fechando a última posição em aberto. Ver a nota do §$3$ do protocolo sobre "balança/equilíbrio": quando o foco é ordenar por transitividade em vez de calcular peso, a questão vai para este bloco.
- **Não é X específico:** não é Grandezas e Medidas (balança para achar peso), porque o foco é a ordem entre os itens, não o valor de cada um.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Ordenar_Comparar.md` seguem a classificação acima, variando o motor específico dentro do bloco:
- Exercícios $1$, $4$, $7$, $10$: variação (a), fila por pistas de posição relativa.
- Exercícios $2$, $5$, $8$: variação (b), ranking por comparação par a par (transitividade).
- Exercícios $3$, $6$, $9$: variação (c), ordem por eliminação com pista negativa.
