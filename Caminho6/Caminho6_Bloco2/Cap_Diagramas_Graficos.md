# Ler e montar a informação

> Trilha Mirim 2 (4º e 5º anos) · Caminho 6 · Bloco 2 · Diagramas e gráficos. Nó da grade: Raciocínio Lógico › Problemas com Conjuntos e Diagramas de Venn (ver `Classificacao_Diagramas_Graficos.md`).

Este capítulo é sobre ler uma informação que já vem organizada numa figura, em vez de escrita direto numa frase. Quando três formas se cruzam num desenho, cada número mora numa combinação diferente delas, e a pergunta pede só uma dessas combinações. Quando um grupo de pessoas responde a duas perguntas de sim ou não, dá para descobrir quantas responderam sim às duas ao mesmo tempo, mesmo sem ver a lista de nomes. Quando os dados vêm numa tabela, um gráfico de barras só está certo se cada barra tiver a altura exata do valor que ela representa. E quando um gráfico mostra horários que se cruzam, dá para descobrir quantos compromissos cabem sem conflito escolhendo sempre o que termina mais cedo. Três jeitos de olhar para uma figura com atenção organizam este capítulo.

***Um número pode morar em mais de uma região ao mesmo tempo***

Quando três formas se cruzam num desenho, um círculo, um retângulo e um triângulo, por exemplo, cada uma das regiões que aparecem no desenho junta um conjunto diferente de condições. Um número pode estar dentro de só uma forma, dentro de duas ao mesmo tempo, ou dentro das três. Para achar quem pertence a uma combinação específica, o caminho mais seguro é ler cada forma separadamente, listar quem está dentro dela, e só depois cruzar as listas.

**Exemplo 1:** No desenho abaixo, um quadrado, um círculo e um losango se cruzam, e cada número de $1$ a $7$ está escrito dentro de uma combinação diferente dessas três formas. **Qual é a soma dos números que estão dentro do quadrado e dentro do círculo, mas fora do losango?**

[Inserir aqui a figura `venn_estrutura.svg`.]

Primeiro listamos quem está dentro do quadrado, $1$, $4$, $5$ e $7$. Depois listamos quem está dentro do círculo, $2$, $4$, $6$ e $7$. Cruzando as duas listas, quem está dentro das duas formas ao mesmo tempo é $4$ e $7$.

Agora tiramos dessa lista quem também está dentro do losango. O losango tem $3$, $5$, $6$ e $7$, e o $7$ está nessa lista. Então o $7$ sai, porque a pergunta pede fora do losango, e sobra só o $4$.

$4$

A soma pedida é só o número $4$. Conferimos guardando as três regras ao mesmo tempo, o $4$ está no quadrado, está no círculo, e não aparece na lista do losango.

[Inserir aqui a figura `venn_resultado.svg`.]

**Guarde. Numa figura com formas que se cruzam, liste separadamente quem está dentro de cada forma antes de cruzar as listas. Uma região "dentro disto e daquilo, mas fora daquilo outro" só se acha eliminando, por último, quem também aparece na forma proibida.**

***Quem respondeu duas perguntas de sim ao mesmo tempo***

Às vezes a informação não vem desenhada, vem contada em uma frase, quantas pessoas responderam sim a cada uma de duas perguntas, e quantas não responderam sim a nenhuma das duas. Mesmo sem ver a lista de nomes, dá para descobrir quantas pessoas responderam sim às duas perguntas ao mesmo tempo.

O primeiro passo é achar quantas pessoas responderam sim a pelo menos uma das perguntas, que é o total menos quem não respondeu sim a nenhuma. Depois, como cada pessoa que respondeu sim às duas foi contada duas vezes, uma em cada pergunta, a soma das duas respostas menos esse total dá exatamente quem respondeu sim às duas ao mesmo tempo.

**Exemplo 2:** Numa excursão com $40$ crianças, $30$ delas levantaram a mão quando perguntadas quem gosta de futebol, e $25$ levantaram a mão quando perguntadas quem gosta de natação. Só $2$ crianças não levantaram a mão em nenhuma das duas perguntas. **Quantas crianças gostam de natação, mas não gostam de futebol?**

Primeiro achamos quantas crianças levantaram a mão pelo menos uma vez, o total menos quem não levantou a mão nenhuma vez.

$40-2=38$

Agora achamos quantas levantaram a mão nas duas perguntas ao mesmo tempo. A soma das duas respostas é $30+25=55$, e cada criança que gosta das duas coisas foi contada duas vezes nessa soma. A diferença entre essa soma e o total de quem levantou a mão pelo menos uma vez é exatamente quem gosta das duas.

$55-38=17$

Dezessete crianças gostam de futebol e de natação ao mesmo tempo. Como $25$ crianças ao todo gostam de natação, e $17$ delas também gostam de futebol, as que gostam só de natação são

$25-17=8$

Oito crianças gostam de natação, mas não de futebol. Conferimos somando todos os grupos, $13$ que gostam só de futebol ($30-17$), $17$ que gostam das duas, $8$ que gostam só de natação, e $2$ que não gostam de nenhuma, e $13+17+8+2=40$, o total da excursão.

**Guarde. Quando duas perguntas de sim ou não têm respostas que se sobrepõem, quem respondeu sim às duas ao mesmo tempo sai da soma das duas respostas menos quem respondeu sim a pelo menos uma. E quem respondeu sim só a uma delas sai do total daquela pergunta menos quem respondeu sim às duas.**

***Um gráfico de barras só está certo se a altura contar a verdade***

Um gráfico de barras representa cada valor por uma altura. Para reconhecer o gráfico certo entre vários parecidos, não basta olhar qual barra é a mais alta ou a mais baixa de relance, é preciso conferir se cada barra tem a altura exata do valor que ela deveria representar, na ordem certa.

**Exemplo 3:** Beatriz anotou quantos livros leu por mês, $6$ em março, $2$ em abril e $5$ em maio. **Qual dos dois gráficos abaixo representa certinho essa leitura, na ordem março, abril e maio?**

[Inserir aqui a figura `grafico_tabela_estrutura.svg`.]

No Gráfico $1$, as barras têm altura $6$, $2$ e $5$, nessa ordem, exatamente os números que Beatriz anotou. No Gráfico $2$, a primeira e a segunda barra estão trocadas, $2$ e depois $6$, o que representaria abril com mais livros que março, o contrário do que aconteceu.

O Gráfico $1$ é o correto.

[Inserir aqui a figura `grafico_tabela_resultado.svg`.]

**Guarde. Para conferir um gráfico de barras, não compare só qual barra parece maior. Confira, uma por uma, se a altura de cada barra bate com o valor certo, na posição certa.**

***Quando só a proporção é dada, comparamos as alturas entre si***

Nem sempre um gráfico vem acompanhado de números exatos. Às vezes o enunciado só diz como as quantidades se comparam entre si, "o dobro de", "o triplo de", e cabe transformar essas relações numa proporção entre as alturas das barras antes de procurar o gráfico certo.

**Exemplo 4:** Numa horta, a quantidade de pés de tomate é o dobro da quantidade de pés de pimentão, e também é o triplo da quantidade de pés de alface. **Qual dos dois gráficos abaixo pode representar essa horta, na ordem tomate, pimentão e alface?**

[Inserir aqui a figura `grafico_razao_estrutura.svg`.]

Escolhemos um número fácil de trabalhar para o tomate, $6$, porque $6$ é múltiplo de $2$ e de $3$ ao mesmo tempo. Se o tomate vale $6$, o pimentão, que é a metade do tomate, vale $3$, e a alface, que é a terça parte do tomate, vale $2$.

$6 \quad\quad 3 \quad\quad 2$

No Gráfico $1$, as barras têm essa proporção exata, $6$, $3$ e $2$. No Gráfico $2$, a barra do pimentão e a da alface têm a mesma altura, $3$ e $3$, o que não respeita a regra de que o tomate deveria ser o triplo da alface, e não do pimentão.

O Gráfico $1$ é o que pode representar a horta.

[Inserir aqui a figura `grafico_razao_resultado.svg`.]

**Guarde. Quando o enunciado só dá relações de dobro, triplo ou metade, escolha um número fácil para a maior quantidade e calcule as outras a partir dele. Depois confira se as duas relações valem ao mesmo tempo, não só uma delas.**

***O compromisso que termina mais cedo abre espaço para o próximo***

Num gráfico com vários horários que se cruzam, o objetivo costuma ser achar quantos compromissos cabem inteiros, do início ao fim, sem que dois deles aconteçam ao mesmo tempo. A estratégia que sempre funciona é escolher, a cada passo, o compromisso que termina mais cedo entre os que ainda cabem depois do último escolhido, nunca o que começa mais cedo nem o mais curto.

**Exemplo 5:** O gráfico abaixo mostra o horário de cinco atividades num acampamento, da natação à uma da tarde. **Qual é o maior número de atividades inteiras que dá para participar, sem que duas delas aconteçam ao mesmo tempo?**

[Inserir aqui a figura `horarios_estrutura.svg`.]

Começamos pela atividade que termina mais cedo entre todas, a Natação, das $8$h às $10$h. Depois dela, olhamos só as atividades que começam às $10$h ou depois, e escolhemos, entre elas, a que termina mais cedo, o Vôlei, das $10$h às $11$h.

Continuando, olhamos as atividades que começam às $11$h ou depois, e escolhemos a que termina mais cedo entre elas, o Judô, das $11$h às $13$h. Depois do Judô, só sobra o Surfe, das $12$h às $14$h, que começa antes das $13$h e por isso não cabe.

$1+1+1=3$

Três atividades cabem sem conflito, Natação, Vôlei e Judô, uma emendada exatamente onde a anterior termina. Conferimos testando as outras combinações possíveis, qualquer uma que inclua a Ginástica ou o Surfe esbarra em pelo menos uma das três já escolhidas, então três é mesmo o máximo.

[Inserir aqui a figura `horarios_resultado.svg`.]

**Guarde. Para caber o maior número de compromissos sem conflito, escolha sempre o que termina mais cedo entre os que ainda restam depois do último escolhido. Escolher pelo que começa mais cedo ou pelo mais curto pode parecer natural, mas nem sempre dá o maior número possível de compromissos.**

---

## Ilustrações

- `venn_estrutura.svg` / `.png` — quadrado, círculo e losango se cruzando, com os sete números de $1$ a $7$ distribuídos pelas regiões, cada forma numa cor.
- `venn_resultado.svg` / `.png` — a mesma figura com a região "dentro do quadrado e do círculo, fora do losango" destacada em verde, mostrando só o número $4$.
- `grafico_tabela_estrutura.svg` / `.png` — dois pequenos gráficos de barras lado a lado, Gráfico $1$ e Gráfico $2$, cada um com três barras para março, abril e maio, sem indicação de qual é o certo.
- `grafico_tabela_resultado.svg` / `.png` — os mesmos dois gráficos, com o Gráfico $1$ destacado em verde como o correto e o Gráfico $2$ marcado em vermelho.
- `grafico_razao_estrutura.svg` / `.png` — dois pequenos gráficos de barras lado a lado, cada um com três barras para tomate, pimentão e alface, sem números escritos.
- `grafico_razao_resultado.svg` / `.png` — os mesmos dois gráficos, com o Gráfico $1$ destacado em verde e as alturas $6$, $3$ e $2$ indicadas.
- `horarios_estrutura.svg` / `.png` — uma linha do tempo das $8$h às $14$h com cinco barras horizontais representando Natação, Ginástica, Vôlei, Judô e Surfe, mostrando onde cada uma começa e termina.
- `horarios_resultado.svg` / `.png` — a mesma linha do tempo com Natação, Vôlei e Judô destacadas em verde e Ginástica e Surfe esmaecidas, por não caberem sem conflito.
