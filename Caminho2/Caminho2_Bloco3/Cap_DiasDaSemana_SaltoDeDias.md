> Trilha Mirim 2 (4º e 5º anos) · Caminho 4 · Tempo, Calendário e Dias da Semana · Bloco 3 · Dias da semana por salto de dias. Nó da grade: Aritmética › Grandezas e Medidas › Medidas de tempo › Dias da semana por resto da divisão por 7 (subnó proposto, ver ficha de classificação em anexo).

# Dias da semana por salto de dias

## 1) Este capítulo responde a uma pergunta que aparece o tempo todo

Este capítulo é sobre descobrir que dia da semana vai cair depois de um certo número de dias. A pergunta aparece de formas parecidas, sempre com a mesma ideia por trás. Se hoje é um certo dia, que dia da semana será daqui a N dias? Se um evento começou num dia certo, em que dia da semana cai outro dia marcado no calendário? A resposta das duas perguntas usa o mesmo truque, que é andar em roda pelos sete dias da semana e aproveitar o que sobra depois de completar semanas inteiras.

## 2) A semana anda em roda de sete dias

Os dias da semana sempre aparecem na mesma ordem, domingo, segunda-feira, terça-feira, quarta-feira, quinta-feira, sexta-feira e sábado, e depois do sábado a contagem volta para o domingo. Chamamos isso de ***ciclo da semana***, uma roda de sete posições que se repete sem parar. Contar dias para a frente é dar passos nessa roda, sempre na mesma direção.

[Inserir aqui a figura `dias_semana_ciclo.svg`.]

Tomemos o caso mais simples, quando o número de dias é pequeno e cabe contar um por um.

⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯
*Hoje é quarta-feira.* **Que dia da semana será daqui a 4 dias?**
⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯

[Inserir aqui a figura `dias_ex_a_estrutura.svg`.]

Como 4 é um número pequeno, contamos um dia de cada vez a partir de quarta-feira. Um dia depois é quinta-feira, dois dias depois é sexta-feira, três dias depois é sábado e quatro dias depois é domingo. Conferimos contando de novo, agora nos dedos, e chegamos ao mesmo lugar. Daqui a 4 dias será domingo.

[Inserir aqui a figura `dias_ex_a_resultado.svg`.]

## 3) O dia de hoje não é um dos dias que passam

Aqui mora um erro fácil de cometer. Quando o problema diz "daqui a 4 dias", hoje não entra na contagem, só os dias que ainda vão passar. Contar quarta-feira como o primeiro dia da lista, em vez de começar a contar a partir de quinta-feira, dá uma resposta adiantada em um dia inteiro. Vale o mesmo cuidado quando o problema fala de duração, como "um passeio de 5 dias, contando o dia de início". Nesse caso o último dia não é 5 dias depois do começo, é 4 dias depois, porque o próprio dia de início já é o primeiro dos 5.

**Guarde.** Ao contar dias para a frente, comece a contar a partir de amanhã, nunca a partir de hoje.

## 4) O resto da divisão por 7 encurta a conta

Contar um dia de cada vez funciona bem para números pequenos, mas fica cansativo quando o número de dias é grande. A roda da semana tem só sete posições, então cada volta completa de 7 dias termina exatamente no mesmo dia da semana em que começou. Isso quer dizer que só o que sobra depois de tirar as voltas completas é que realmente muda o dia da semana. Para achar esse pedaço que sobra, dividimos o número de dias por 7 e olhamos só para o resto, que é sempre um número de 0 a 6. Esse resto é quantos passos damos na roda a partir de hoje.

Veja o caso de uma viagem mais longa.

⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯
*Hoje é sexta-feira.* **Que dia da semana será daqui a 23 dias?**
⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯

[Inserir aqui a figura `dias_ex_b_estrutura.svg`.]

Imagine que você tem só os dedos das mãos para contar, e 23 dias não cabem neles de uma vez. Em vez de contar um por um, dividimos 23 por 7.

23 ÷ 7 = 3, resto 2

Três voltas completas na roda da semana não mudam nada, porque terminam de novo numa sexta-feira. Sobram só 2 dias para andar. Contamos então 2 dias a partir de sexta-feira, e chegamos em domingo. Conferimos de outro jeito, somando 7 três vezes a partir de sexta e depois mais 2, o que também fecha em domingo.

[Inserir aqui a figura `dias_ex_b_resultado.svg`.]

## 5) Quando o problema dá duas datas, fazemos duas contas

Até aqui, o problema sempre dizia direto quantos dias iam se passar. Às vezes, porém, o problema dá dois dias marcados num calendário e pede o dia da semana de um deles, sabendo o dia da semana do outro. Nesse caso, a primeira conta é achar quantos dias separam as duas datas, subtraindo a menor da maior. Só depois de ter esse número é que aplicamos o mesmo atalho do resto da divisão por 7.

⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯
*O dia 5 de um mês caiu numa quinta-feira.* **Em que dia da semana cai o dia 23 desse mesmo mês?**
⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯

[Inserir aqui a figura `dias_ex_c_estrutura.svg`.]

Primeiro achamos a distância entre os dois dias do mês, subtraindo 5 de 23.

23 − 5 = 18

Entre o dia 5 e o dia 23 se passam 18 dias. Agora usamos o atalho de sempre, dividindo 18 por 7.

18 ÷ 7 = 2, resto 4

Sobram 4 dias para andar na roda a partir de quinta-feira, que é o dia do dia 5. Contando 4 dias depois de quinta-feira chegamos a segunda-feira. Conferimos olhando o total, três voltas completas de 7 não fariam sentido aqui porque só temos 18 dias, e duas voltas completas mais 4 dias soltos dá exatamente 18, o que confere com a nossa conta. O dia 23 cai numa segunda-feira.

[Inserir aqui a figura `dias_ex_c_resultado.svg`.]

Um caso particular vale a pena guardar. Quando a diferença entre as duas datas é um múltiplo de 7, como 7, 14 ou 21 dias, o resto da divisão é 0, e isso quer dizer que a segunda data cai exatamente no mesmo dia da semana que a primeira, sem precisar andar nenhum passo a mais na roda.

## 6) As duas ideias juntas resolvem qualquer problema deste tipo

A pergunta do começo do capítulo sempre se resolve do mesmo jeito. Primeiro descobrimos quantos dias realmente vão se passar, o que às vezes já vem pronto no problema e às vezes precisa de uma subtração entre duas datas. Depois dividimos esse número por 7 e usamos só o resto, que conta quantos passos damos na roda da semana a partir do dia conhecido. Antes de fechar a resposta, vale conferir duas coisas. O dia de hoje, ou o dia já marcado no calendário, ficou de fora da contagem dos dias que passam? E o resto usado está mesmo entre 0 e 6, e não o número de dias inteiro sem dividir? Respondendo essas duas perguntas, qualquer problema de salto de dias na semana fica mais fácil de organizar.

---

## Ilustrações

| Arquivo | Onde entra | O que mostra |
|---|---|---|
| `dias_semana_ciclo.svg` | Seção 2, logo após a definição do ciclo da semana | Os sete dias da semana dispostos em roda, com setas mostrando a ordem e a volta de sábado para domingo |
| `dias_ex_a_estrutura.svg` | Seção 2, logo após o problema fechado de quarta-feira + 4 dias | O dia de hoje (quarta-feira) e a pergunta sobre 4 dias depois, sem a resposta |
| `dias_ex_a_resultado.svg` | Seção 2, ao final da resolução | A contagem dia a dia de quarta até domingo, com domingo em destaque |
| `dias_ex_b_estrutura.svg` | Seção 4, logo após o problema fechado de sexta-feira + 23 dias | O dia de hoje (sexta-feira) e a pergunta sobre 23 dias depois, sem a resposta |
| `dias_ex_b_resultado.svg` | Seção 4, ao final da resolução | A divisão 23 ÷ 7, o resto 2 e o resultado final em destaque |
| `dias_ex_c_estrutura.svg` | Seção 5, logo após o problema fechado do dia 5 e do dia 23 | Os dois dias marcados no mês, com o segundo ainda sem resposta |
| `dias_ex_c_resultado.svg` | Seção 5, ao final da resolução | A subtração 23 − 5, a divisão por 7 e o resultado final em destaque |
