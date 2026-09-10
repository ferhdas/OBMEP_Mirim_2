Ficha de classificação · Bloco $5$ · Não tem como caber sem repetir

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as duas questões de referência do bloco: `2022/F2/Q12` e `2024/F1/Q15`.

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Garantir que uma repetição acontece, só de contar quantas "gavetas" existem e quantos "objetos" estão sendo distribuídos entre elas, sem precisar saber os detalhes de como a distribuição realmente acontece. O bloco cobre três variações: (a) o caso básico, com mais objetos do que gavetas, que garante que pelo menos uma gaveta recebe dois objetos, (b) o caso do "pior cenário", em que se pede o número mínimo de objetos para garantir não duas, mas um número maior de repetições numa mesma gaveta, e (c) o reconhecimento de uma "gaveta" escondida dentro de uma situação do dia a dia, que não parece, à primeira vista, um problema de gavetas e objetos.

**Nó principal (Apêndice D, grade oficial).** `Raciocínio Lógico › Problemas com Princípios de Existência / Princípio da Casa dos Pombos`. É o nó existente da grade que nomeia exatamente este raciocínio, sem precisar de subnó novo.

**Descritores secundários.**
- Contagem do pior cenário (variação a e b): a régua central do princípio da casa dos pombos é sempre imaginar o cenário mais "espalhado" possível, o que adia ao máximo a repetição, e então somar $1$ a esse cenário para forçá-la.
- Fórmula do mínimo generalizado (variação b): para garantir $k$ objetos numa mesma gaveta, com $n$ gavetas, o número mínimo de objetos é $(k - 1) \times n + 1$, generalizando o caso básico, em que $k = 2$.
- Identificação da gaveta escondida (variação c): parente do trabalho de classificação em si, reconhecer que "dias da semana", "meses do ano" ou "resultados possíveis de um sorteio" são, disfarçados, o papel das gavetas.

**Não é X (e por quê).**
- Não é Achar a Ordem (Bloco $1$ deste Caminho), porque não existe nenhuma posição relativa entre os objetos, só a contagem de quantos cabem em cada gaveta.
- Não é Associação por Pistas (Bloco $3$ deste Caminho), porque ali a quantidade de pessoas e de atributos é sempre igual, numa correspondência um para um, enquanto aqui existem sempre mais objetos do que gavetas, forçando a repetição.
- Não é uma questão de contagem combinatória (Caminho $7$), porque o princípio da casa dos pombos não conta **quantas** formas existem de algo acontecer, só garante **que** uma repetição acontece, sem calcular de quantos jeitos.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 5** › **Bloco 5 · Não tem como caber sem repetir** › capítulo de teoria "Não tem como caber sem repetir" (`Cap_Casa_Pombos.md`).

---

***Notas específicas de cada questão de referência***

`2022/F2/Q12`
- **Motor aplicado:** variação (a) ou (b), a depender de o enunciado pedir a garantia de uma repetição simples ou de um número maior de repetições numa mesma gaveta. 🖼️ (conferir a solução oficial antes de publicar).
- **Não é X específico:** não pede a probabilidade de a repetição acontecer, só o número mínimo que a garante com certeza.

`2024/F1/Q15`
- **Motor aplicado:** variação (c), reconhecimento de uma gaveta escondida numa situação do dia a dia.
- **Não é X específico:** não é uma questão de contagem combinatória, o que se pede é o menor número que força a repetição, não o total de formas de distribuir os objetos.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Casa_Pombos.md` seguem a classificação acima, variando o motor específico dentro do bloco:
- Exercícios $1$, $4$, $7$, $10$: variação (a), garantia básica de uma repetição.
- Exercícios $2$, $5$, $8$: variação (b), mínimo para garantir um número maior de repetições.
- Exercícios $3$, $6$, $9$: variação (c), reconhecimento de uma gaveta escondida.
