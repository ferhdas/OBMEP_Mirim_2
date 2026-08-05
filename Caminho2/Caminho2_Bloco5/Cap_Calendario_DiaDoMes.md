# Calendário e dia do mês

> Trilha Mirim 2 (4º e 5º anos) · Caminho 2 · Bloco 5 · Calendário e dia do mês. Nó da grade: Aritmética › Grandezas e Medidas › Medidas de tempo › Dias da semana por resto da divisão por $7$ (mesmo subnó do Bloco 3, agora aplicado à leitura do calendário do mês).

Este capítulo é sobre o calendário pendurado na parede. Sabendo o dia da semana de uma data, como descobrimos o dia da semana de outra data do mesmo mês? E, se quisermos saber quando vem o próximo sábado, ou conferir se um grupo de datas cai mesmo todo no mesmo dia da semana, como fazemos essa conta sem contar quadradinho por quadradinho?

***A grade do mês tem sete colunas***

Um calendário de mês é organizado em linhas e colunas, e cada coluna representa um dia da semana, sempre na mesma ordem. Isso quer dizer que datas que ficam na mesma coluna, em linhas diferentes, caem no mesmo dia da semana. Andar uma linha inteira para baixo é o mesmo que andar $7$ dias, e $7$ dias completam uma volta na roda da semana sem mudar o dia. Essa é a mesma roda de $7$ posições do Bloco $3$, só que agora vista dentro da grade do calendário.

[Inserir aqui a figura `cal_mes_grade.svg`.]

***Duas datas do mesmo mês, uma única conta***

Quando sabemos o dia da semana de uma data e queremos o dia da semana de outra data do mesmo mês, a conta tem dois passos. Primeiro achamos a diferença entre os dois números do mês, subtraindo o menor do maior. Depois dividimos essa diferença por $7$ e olhamos só para o resto, exatamente como fizemos no Bloco $3$ para "daqui a quantos dias". O resto é quantos passos andamos na roda da semana a partir do dia que já conhecemos.

Tomemos o caso de um mês qualquer.

⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯
*O dia $3$ de um certo mês caiu numa segunda-feira.* **Em que dia da semana cai o dia $24$ desse mesmo mês?**
⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯

[Inserir aqui a figura `cal_ex_a_estrutura.svg`.]

Primeiro achamos a diferença entre os dois dias do mês.

$$24 - 3 = 21$$

Agora dividimos essa diferença por $7$.

$$21 \div 7 = 3 \text{, resto } 0$$

O resto é $0$, o que significa que $21$ dias são exatamente $3$ semanas inteiras, sem sobra nenhuma. Andar um número exato de semanas não muda o dia da semana, então o dia $24$ cai no mesmo dia que o dia $3$. Conferimos contando de $7$ em $7$ a partir do dia $3$: $10$, $17$, $24$, todos numa segunda-feira. O dia $24$ desse mês também cai numa segunda-feira.

[Inserir aqui a figura `cal_ex_a_resultado.svg`.]

***Achar a próxima vez que um dia da semana aparece***

Às vezes a pergunta é ao contrário: sabendo o dia da semana de hoje, em que dia do mês cai o próximo sábado, ou a próxima quarta-feira? Para isso contamos quantos passos faltam, na roda da semana, do dia de hoje até o dia da semana procurado, e somamos esse número ao dia do mês em que estamos.

Veja o caso de alguém marcando uma consulta.

⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯
*Hoje é dia $5$ de um mês, uma quarta-feira.* **Qual é o próximo dia do mês que cai num sábado?**
⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯

[Inserir aqui a figura `cal_ex_b_estrutura.svg`.]

Imagine que você está olhando para a roda da semana com o dedo em cima de quarta-feira. Para chegar a sábado você precisa dar $3$ passos para a frente: quinta, sexta, sábado. Esses $3$ passos valem $3$ dias no calendário. Some esses $3$ dias ao dia $5$, que é onde você está agora.

$$5 + 3 = 8$$

O próximo sábado cai no dia $8$ do mês. Conferimos contando os dias um por um a partir do dia $5$: dia $6$ é quinta, dia $7$ é sexta, dia $8$ é sábado. Bate certo.

[Inserir aqui a figura `cal_ex_b_resultado.svg`.]

***Quando hoje já é o dia procurado***

Um cuidado importante aparece quando o dia de hoje já é o mesmo dia da semana que estamos procurando. Se hoje já é sábado e a pergunta é "qual o próximo sábado", a resposta não pode ser hoje mesmo, porque "próximo" sempre aponta para a frente. Nesse caso os $3$ passos da conta acima viram $0$ pela subtração direta, mas como não podemos ficar parados, completamos uma volta inteira e usamos $7$ passos em vez de $0$.

**Guarde.** Quando a diferença entre o dia de hoje e o dia procurado der resto $0$, o próximo dia procurado não é hoje, e sim $7$ dias à frente.

***Comparando várias datas candidatas***

Outro tipo de pergunta dá uma lista de datas que deveriam cair todas no mesmo dia da semana e pede para achar a que não bate com as outras. A ideia é a mesma: datas separadas por um múltiplo de $7$ caem sempre no mesmo dia, então a data candidata que não está a um múltiplo de $7$ de distância das demais é a que foge da regra.

Este capítulo reuniu três formas de usar a mesma ideia da roda de $7$ dias dentro do calendário do mês. Achar o dia da semana de uma segunda data, sabendo a primeira. Achar o dia do mês da próxima vez que um certo dia da semana aparece, com o cuidado do resto $0$. E comparar datas candidatas para achar a que não pertence ao grupo.

---

***Ilustrações***

| Arquivo | Onde entra | O que mostra |
|---|---|---|
| `cal_mes_grade.svg` | Logo após a explicação das sete colunas | Uma grade de calendário com as sete colunas de dias da semana em destaque e uma coluna inteira realçada |
| `cal_ex_a_estrutura.svg` | Após o problema fechado do dia $3$ e do dia $24$ | As duas datas do mês na grade, uma conhecida (dia $3$ = segunda) e outra em aberto (dia $24$ = ?) |
| `cal_ex_a_resultado.svg` | Ao final da resolução do exemplo A | A conta $24 - 3 = 21$ e $21 \div 7$, com o resto $0$ e a contagem de $7$ em $7$ (dia $3$, $10$, $17$, $24$) em destaque |
| `cal_ex_b_estrutura.svg` | Após o problema fechado do dia $5$ e do próximo sábado | O dia $5$ marcado como quarta-feira, com a pergunta sobre o próximo sábado em aberto, sem resposta |
| `cal_ex_b_resultado.svg` | Ao final da resolução do exemplo B | Os $3$ passos contados na roda da semana e a soma $5 + 3 = 8$ em destaque |
