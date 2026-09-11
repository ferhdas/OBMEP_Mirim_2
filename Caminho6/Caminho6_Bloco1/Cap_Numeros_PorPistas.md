# Descobrir os números que faltam

> Trilha Mirim 2 (4º e 5º anos) · Caminho 6 · Bloco 1 · Descobrir os números que faltam. Nó da grade: Raciocínio Lógico › Problemas com Restrições e Dedução › Dedução com Pistas Numéricas (ver `Classificacao_Numeros_PorPistas.md`).

Este capítulo é sobre achar um número que ninguém disse, usando só as pistas que sobraram. Se eu te contar quanto somam duas partes de um grupo e quanto soma o grupo inteiro, dá para achar a terceira parte sem ver nem uma delas. Se eu trocar uma coisa por outra várias vezes seguidas, dá para descobrir quanto vale a primeira coisa só andando pela cadeia de trocas. E se eu te disser só o total final de uma mistura, dá até para descobrir os dois números que foram somados, testando as poucas contagens possíveis até sobrar uma só que funciona. Cinco jeitos diferentes de fazer a mesma coisa, achar o que falta a partir do que já se sabe, organizam este capítulo.

***O que sobra é o total menos o que já se sabe***

Quando um grupo inteiro é dividido em partes e sabemos o total e algumas das partes, a parte que falta sai por subtração. Esse é o primeiro passo, mas em muitas questões ele não é suficiente, porque a pergunta não quer só um número, quer saber **quais** elementos formam essa parte. Aí não basta subtrair, é preciso testar os agrupamentos possíveis e descartar os que não combinam com as outras pistas.

**Exemplo 1:** Seis fichas numeradas de $1$ a $6$ são separadas em pares e guardadas em três potes. As fichas do pote Estrela somam $9$. As fichas do pote Lua somam $4$. **Quais fichas estão no pote Sol?**

[Inserir aqui a figura `fichas_potes_estrutura.svg`.]

A soma $9$ pode vir de dois pares diferentes entre $1$ e $6$: $3+6$ ou $4+5$. Testamos o primeiro. Se o pote Estrela fosse $\{3,6\}$, sobrariam as fichas $1$, $2$, $4$ e $5$ para os outros dois potes, e nenhum par entre elas soma $4$ ($1+2=3$, $1+4=5$, $1+5=6$, $2+4=6$, $2+5=7$, $4+5=9$). Esse candidato não fecha, então descartamos.

Testamos o segundo candidato. Se o pote Estrela é $\{4,5\}$, sobram as fichas $1$, $2$, $3$ e $6$. Entre elas, $1+3=4$, que é exatamente a soma do pote Lua. Esse candidato fecha.

Assim, o pote Estrela é $\{4,5\}$, o pote Lua é $\{1,3\}$, e o pote Sol fica com o que sobrou.

$\{2,6\}$

O pote Sol tem as fichas $2$ e $6$. Conferimos juntando tudo, $4+5=9$, $1+3=4$, e $2+6=8$, e as seis fichas de $1$ a $6$ aparecem uma única vez.

[Inserir aqui a figura `fichas_potes_resultado.svg`.]

**Guarde. Quando uma pista de total admite mais de um agrupamento possível, não escolha o primeiro que parecer razoável. Teste cada candidato contra a próxima pista, e só fique com o que fecha certinho. O agrupamento que sobra sai por eliminação dos números que ainda não foram usados.**

***Trocar uma coisa pela outra até sobrar só uma espécie***

Às vezes um problema dá o valor de uma coisa em função de outra, e o valor dessa outra em função de uma terceira, formando uma cadeia. Uma ***cadeia de trocas*** é essa sequência de igualdades, cada uma trocando um item por uma quantidade de outro item, até que tudo possa ser reescrito na mesma unidade. O caminho é sempre o mesmo, substituir uma igualdade dentro da outra, de trás para a frente, até restar só a unidade que a pergunta pede.

**Exemplo 2:** Na quitanda da Dona Marta, uma melancia vale o mesmo que $3$ laranjas. Uma caixa de morangos vale o mesmo que $2$ melancias e $1$ laranja. Uma cesta de frutas vale o mesmo que $1$ caixa de morangos e $2$ melancias. **Se Pedro vender uma cesta de frutas, quantas laranjas ele pode comprar com esse dinheiro?**

Começamos pela troca mais simples. Uma melancia vale $3$ laranjas.

Agora trocamos a caixa de morangos. Ela vale $2$ melancias e $1$ laranja, e cada melancia já vale $3$ laranjas, então $2$ melancias valem $6$ laranjas. Somando a laranja avulsa,

$6+1=7$

a caixa de morangos vale $7$ laranjas.

Por fim trocamos a cesta de frutas. Ela vale $1$ caixa de morangos, que já sabemos valer $7$ laranjas, mais $2$ melancias, que valem $6$ laranjas. Juntando as duas partes,

$7+6=13$

Pedro pode comprar $13$ laranjas com o dinheiro de uma cesta de frutas. Conferimos voltando pelas três igualdades originais, cada uma delas continua batendo quando trocamos tudo por laranjas.

**Guarde. Numa cadeia de trocas, resolva de dentro para fora, começando pela igualdade mais simples, a que já está escrita direto na unidade final. Cada troca seguinte usa o resultado da anterior, até sobrar só a unidade que a pergunta pede.**

***Quando só o total é dado, testamos até achar a única solução***

Nem sempre as pistas dizem quantos elementos há de cada tipo. Às vezes só o total combinado aparece, e cabe descobrir a divisão entre os tipos testando as poucas contagens possíveis, uma de cada vez, até sobrar uma única que funciona.

Imagine uma coleção com dois tipos de peça, cada tipo valendo um número de pontos diferente, e um total de pontos já somado. Para cada quantidade possível de peças do tipo mais raro, o resto dos pontos precisa se dividir certinho pelo valor do tipo mais comum, sem sobra nem falta. A maioria das quantidades testadas não fecha, e só uma sobra no final.

**Exemplo 3:** Figurinhas comuns valem $3$ pontos cada, e figurinhas raras valem $7$ pontos cada. Ana juntou figurinhas comuns e raras que somam, ao todo, $29$ pontos. **Quantas figurinhas ela tem, contando as comuns e as raras juntas?**

Testamos quantas figurinhas raras Ana pode ter, começando do zero. Sem nenhuma rara, sobrariam $29$ pontos para dividir por $3$, e $29$ não é múltiplo de $3$. Com $1$ rara, sobram $29-7=22$ pontos, e $22$ também não é múltiplo de $3$. Com $2$ raras, sobram $29-14=15$ pontos, e $15$ dividido por $3$ dá exatamente $5$.

$15 \div 3 = 5$

Com $3$ ou mais raras, o total de pontos das raras já passaria de $21$, deixando só $8$ pontos ou menos para as comuns, e nenhuma dessas contagens fecha sem sobra.

Então Ana tem $2$ figurinhas raras e $5$ comuns, $7$ figurinhas ao todo. Conferimos, $2\times7+5\times3=14+15=29$, que é o total dado.

**Guarde. Quando o problema só dá o total e o valor de cada tipo, teste a contagem do tipo mais raro a partir do zero, uma de cada vez. Descarte toda contagem cujo resto não se divide certinho pelo valor do outro tipo, e pare de testar assim que o total de um único tipo já ultrapassar o total inteiro.**

***Uma grade se resolve casa por casa, usando as somas cruzadas***

Numa grade numérica, cada linha e cada coluna funciona como uma pista independente sobre os números que ela contém. Quando a soma de uma linha ou coluna é muito baixa ou muito alta para o conjunto de números disponível, ela só pode ser formada por um grupo específico, e esse grupo trava as demais casas por eliminação.

**Exemplo 4:** Um quadriculado $3\times3$ deve ser preenchido com os números de $1$ a $9$, sem repetir nenhum. A soma dos números da primeira linha é $6$. A soma da segunda linha é $24$. A soma da primeira coluna é $12$. A soma da segunda coluna é $15$. **Qual número fica na casa cinza, na terceira linha e na terceira coluna?**

[Inserir aqui a figura `grade_numerica_estrutura.svg`.]

A menor soma possível de três números diferentes entre $1$ e $9$ é $1+2+3=6$, que é exatamente a soma da primeira linha. Não existe outro jeito de somar $6$ com três números diferentes nesse intervalo, então a primeira linha usa exatamente $1$, $2$ e $3$.

A maior soma possível dos números que sobraram é $7+8+9=24$, que é exatamente a soma da segunda linha. Pelo mesmo motivo, a segunda linha usa exatamente $7$, $8$ e $9$, e a terceira linha fica com o que sobrou, $4$, $5$ e $6$.

Agora usamos as colunas para descobrir a ordem dentro de cada linha. A primeira coluna tem um número de cada linha, e soma $12$. Testando, $1+7+4=12$ fecha certinho. A segunda coluna soma $15$, e testando entre os números que restaram em cada linha, $2+8+5=15$ também fecha.

$1+7+4=12 \quad\quad 2+8+5=15$

O que sobra em cada linha vai para a terceira coluna, o $3$ da primeira linha, o $9$ da segunda e o $6$ da terceira.

$3 \quad\quad 9 \quad\quad 6$

A casa cinza é o número $6$. Conferimos somando a terceira coluna inteira, $3+9+6=18$, que é o total geral, $45$, menos as duas colunas já dadas, $45-12-15=18$.

[Inserir aqui a figura `grade_numerica_resultado.svg`.]

**Guarde. Numa grade com números que não se repetem, comece pela linha ou coluna com a soma mais extrema, a mais baixa ou a mais alta possível para aquele intervalo de números. Ela costuma ter um único grupo de números capaz de formar aquela soma, e isso trava o resto da grade, casa por casa.**

***Contar quantas vezes cada um jogou, ligando as pistas como uma rede***

Num torneio em que cada dupla de participantes joga no máximo uma vez, dizer quantas vezes uma pessoa jogou é o mesmo que dizer com quantas outras pessoas ela jogou. Quem jogou o número máximo de vezes jogou com todo mundo, e essa informação sozinha já resolve boa parte das outras pistas.

**Exemplo 5:** Cinco amigos, Ana, Beto, Carla, Duda e Elis, jogaram xadrez entre si num torneio, cada dupla no máximo uma vez. Ana jogou $2$ vezes. Carla jogou $4$ vezes. Duda jogou $1$ vez. Elis jogou $3$ vezes. **Quantas vezes jogou Beto?**

[Inserir aqui a figura `torneio_partidas_estrutura.svg`.]

Carla jogou $4$ vezes, o máximo possível entre cinco pessoas, então ela jogou com todo mundo, com Ana, Beto, Duda e Elis.

Duda jogou só $1$ vez, e essa vez já é a partida contra Carla, porque Carla jogou com todo mundo. Então Duda não jogou com mais ninguém além de Carla.

Elis jogou $3$ vezes. Uma delas já é contra Carla. Como Duda não joga com mais ninguém, a partida de Elis contra Duda não existe, então as outras duas partidas de Elis são contra Ana e contra Beto.

Ana jogou $2$ vezes. Uma é contra Carla, e a outra, pelo que vimos, é contra Elis. Isso já fecha as duas partidas de Ana, então Ana não jogou contra Beto.

Beto, então, jogou contra Carla e contra Elis, e não jogou contra Ana nem contra Duda.

$1+1=2$

Beto jogou $2$ vezes. Conferimos juntando todas as partidas encontradas, Carla com todo mundo, Duda só com Carla, Elis com Carla, Ana e Beto, Ana com Carla e Elis, e Beto com Carla e Elis, e cada pista bate com a contagem dada no início.

[Inserir aqui a figura `torneio_partidas_resultado.svg`.]

**Guarde. Num torneio de partidas únicas entre duplas, comece por quem jogou o número máximo possível, porque essa pessoa jogou com todo mundo. Cada pessoa que jogou pouco já gasta suas partidas contra quem jogou muito, e o que sobra para as demais pistas fica cada vez mais restrito.**

---

## Ilustrações

- `fichas_potes_estrutura.svg` / `.png` — três potes (Estrela, Lua, Sol) com as seis fichas numeradas espalhadas ao lado, sem nenhuma dentro dos potes ainda, e as somas $9$ e $4$ escritas sobre os potes Estrela e Lua. O pote Sol aparece com um "?" em laranja.
- `fichas_potes_resultado.svg` / `.png` — os três potes preenchidos, Estrela com $4$ e $5$, Lua com $1$ e $3$, Sol com $2$ e $6$, cada ficha numerada dentro do seu pote e a soma de cada pote em destaque.
- `grade_numerica_estrutura.svg` / `.png` — o quadriculado $3\times3$ vazio, com as somas $6$ e $24$ ao lado das duas primeiras linhas e as somas $12$ e $15$ acima das duas primeiras colunas, e a casa da terceira linha e terceira coluna pintada de cinza com um "?" em laranja.
- `grade_numerica_resultado.svg` / `.png` — o mesmo quadriculado preenchido com $1,2,3$ na primeira linha, $7,8,9$ na segunda e $4,5,6$ na terceira, e a casa cinza destacada com o número $6$ em verde.
- `torneio_partidas_estrutura.svg` / `.png` — cinco pontos nomeados Ana, Beto, Carla, Duda e Elis dispostos em círculo, sem nenhuma linha de partida desenhada ainda, e o número de partidas de cada um escrito ao lado do seu nome, com o de Beto em laranja e "?".
- `torneio_partidas_resultado.svg` / `.png` — os mesmos cinco pontos com as linhas de partida desenhadas (Carla ligada a todos, Duda só a Carla, Elis a Carla, Ana e Beto, Ana só a Carla e Elis), e o número final de partidas de Beto em verde.
