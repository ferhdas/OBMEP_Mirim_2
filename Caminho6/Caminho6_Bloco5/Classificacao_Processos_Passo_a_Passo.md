Ficha de classificação · Bloco $5$ · Processos passo a passo

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as cinco questões de referência do bloco: `2024/F1/Q7` (código `M2-24-F1-Q07`), `2025/F2/Q15` (código `M2-25-F2-Q15`), `2019/Q14` (código `NA19-Q14`), `2025/F1/Q13` (código `M2-25-F1-Q13`) e `2025/F2/Q12` (código `M2-25-F2-Q12`).

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Acompanhar um processo que muda passo a passo segundo uma regra fixa, e descobrir algo sobre ele sem precisar ver cada passo escrito por extenso. O bloco reúne quatro variações: (a) percorrer uma regra de movimento determinística até uma posição final, (b) repetir uma transformação enquanto ela for possível, até o processo estabilizar, (c) reconstruir de trás para frente o que precisa ter acontecido num processo com "reset" e "afastamento", a partir só do resultado final, e (d) reconhecer o que não muda enquanto o processo acontece, uma paridade que se mantém ou uma ordem que nunca se embaralha.

**Nó principal (Apêndice D, grade oficial).** `Raciocínio Lógico › Problemas com Regras de Transformação e Algoritmos`. É o nó que cobre diretamente as quatro variações, porque em todas elas existe uma regra fixa que se aplica repetidas vezes, e a resposta depende de simular ou de reconstruir essa aplicação, não de calcular um valor direto.

**Descritores secundários.**
- Percurso por trechos retos e viradas: um processo de movimento guiado por uma regra fixa de virada se acompanha melhor trecho reto por trecho reto, marcando cada virada no momento exato em que ela acontece, nunca tentando prever o caminho inteiro de uma vez.
- Transformação até estabilizar: quando uma regra pode ser aplicada repetidas vezes enquanto certas condições existirem, o processo sempre termina no mesmo estado final, desde que a regra seja sempre aplicada enquanto for possível, não importa a ordem dos passos intermediários quando só uma transformação está disponível de cada vez.
- Reconstrução por contagem de passos consecutivos: quando uma regra "reseta" um valor para um estado conhecido e outra o afasta dele por uma quantidade fixa, o valor final revela quantos passos consecutivos de afastamento aconteceram por último, e isso obriga o passo imediatamente anterior a ter sido um reset.
- Paridade como invariante: quando um total fixo é dividido em duas partes, e se pergunta pela diferença entre elas, a paridade dessa diferença é sempre a mesma, não importa como a divisão seja feita, porque ela depende só da paridade do total.
- Ordem preservada como invariante: quando itens só podem ser retirados pelas duas pontas de uma fila, o que sobra é sempre um pedaço contínuo da sequência original, na mesma ordem, nunca uma sequência com os itens certos fora de ordem.

**Não é X (e por quê).**
- Não é o Bloco $1$ deste Caminho, porque ali as pistas chegam prontas e cabe combiná-las para achar um número escondido. Aqui existe sempre um processo que muda ao longo de vários passos, e a resposta depende de acompanhar essa mudança, não de cruzar pistas estáticas.
- Não é o Bloco $4$ deste Caminho, mesmo quando a variação (d) usa um colar com contas retiradas pelas pontas, parecido com o Bloco $4$. A diferença é a pergunta, no Bloco $4$ o objetivo é achar o menor número de retiradas, e aqui o objetivo é reconhecer quais sequências finais são possíveis, o invariante da ordem preservada, não uma otimização.
- Não é Geometria › Percepção Espacial no Plano (Caminho $4$), mesmo quando a variação (a) usa um labirinto desenhado. O que resolve a questão é seguir a regra de movimento passo a passo, não reconhecer uma forma ou compor peças.
- Não é Sequências, Padrões e Regularidades (Caminho $8$), porque o processo não segue um padrão que se estende infinitamente, ele tem um começo e um fim claros, e a pergunta é sobre um estado específico do processo, não sobre uma regra de crescimento.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 6** › **Bloco 5 · Processos passo a passo** › capítulo de teoria "Seguir, inverter e o que não muda" (`Cap_Processos_Passo_a_Passo.md`).

---

***Notas específicas de cada questão de referência***

`2025/F1/Q13` (código `M2-25-F1-Q13`)
- **Motor aplicado:** variação (a), percurso por trechos retos e viradas. Roberto anda reto por um labirinto e vira à direita sempre que encontra uma parede, começando na entrada indicada. Percorrendo o labirinto trecho por trecho, o trajeto termina no ponto A, uma das cinco saídas possíveis marcadas na figura. Gabarito **A** ✅, conferido contra a solução oficial (`sf1m2-2025.pdf`, questão $13$).
- **Não é X específico:** não dá para adivinhar a saída olhando só o formato geral do labirinto, é preciso seguir o trajeto real, corredor por corredor, cada virada exatamente onde a parede aparece.

`2025/F2/Q15` (código `M2-25-F2-Q15`)
- **Motor aplicado:** variação (b), transformação até estabilizar. Um mágico transforma $4$ chapéus numa varinha, e $4$ varinhas num chapéu, sempre que uma das duas transformações é possível. Começando com $3$ chapéus e $7$ varinhas, a sequência de transformações forçadas é $3$ chapéus e $7$ varinhas, depois $4$ chapéus e $3$ varinhas, depois $0$ chapéus e $4$ varinhas, depois $1$ chapéu e $0$ varinhas, onde o processo estabiliza. Gabarito **A ($1$ chapéu)** ✅, conferido contra a solução oficial (`sf2m2-2025.pdf`, questão $15$).
- **Não é X específico:** não é preciso testar ordens diferentes de transformação, porque em cada etapa só uma das duas transformações está disponível, o processo é determinístico do início ao fim.

`2019/Q14` (código `NA19-Q14`)
- **Motor aplicado:** variação (d), paridade como invariante. Paulo usa os números $5$, $6$, $7$, $8$ e $9$, cada um uma vez, soma três deles e subtrai a soma dos outros dois. Como a soma total, $35$, é ímpar, a diferença $2S-35$ é sempre ímpar, o que descarta de cara as opções pares. Testando os números, o valor $11$ é alcançável. Gabarito **D ($11$)** ✅, conferido contra a solução oficial (`snA-2019.pdf`, questão $14$).
- **Não é X específico:** não é uma questão de tentar todas as combinações possíveis de agrupamento, a paridade da soma total já elimina metade das alternativas antes de qualquer teste.

`2025/F2/Q12` (código `M2-25-F2-Q12`)
- **Motor aplicado:** variação (d), ordem preservada como invariante. Um colar tem $8$ miçangas presas ao cordão numa ordem fixa, e Milena remove $4$ delas pelas pontas. O que sobra é sempre um pedaço contínuo da sequência original, e a única alternativa que não corresponde a nenhum pedaço contínuo válido é a que troca a ordem de duas miçangas vizinhas. Gabarito **E** ✅, conferido contra a solução oficial (`sf2m2-2025.pdf`, questão $12$).
- **Não é X específico:** não é uma questão sobre quais tipos de miçanga sobram, é sobre se a ordem entre as miçangas que sobram é uma ordem que realmente aparece em algum trecho contínuo do colar original.

`2024/F1/Q7` (código `M2-24-F1-Q07`)
- **Motor aplicado:** variação (c), reconstrução por contagem de passos consecutivos. O nariz de Pinóquio mede $3$ cm em repouso, cresce $5$ cm a cada mentira e volta a $3$ cm a cada verdade. Depois de $5$ falas, o nariz mede $18$ cm, e $18-3=15$, que dividido por $5$ dá $3$. As últimas $3$ falas formaram uma sequência de mentiras, o que obriga a fala imediatamente anterior a essa sequência, a segunda, a ter sido verdade. Gabarito **B (a segunda)** ✅, conferido contra a solução oficial (`sf1m2-2024.pdf`, questão $7$).
- **Não é X específico:** não dá para afirmar nada com certeza sobre a primeira fala, porque ela fica fora da sequência final de mentiras e não afeta o raciocínio que prova a segunda fala verdadeira.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Processos_Passo_a_Passo.md` seguem a classificação acima:
- Exercícios $1$ e $2$: variação (a), percurso por trechos retos e viradas.
- Exercícios $3$ e $4$: variação (b), transformação até estabilizar.
- Exercícios $5$ e $6$: variação (c), reconstrução por contagem de passos consecutivos.
- Exercícios $7$ e $8$: variação (d), paridade como invariante.
- Exercícios $9$ e $10$: variação (d), ordem preservada como invariante.
