# O que está na face escondida

> Trilha Mirim 2 (4º e 5º anos) · Caminho 6 · Bloco 3 · Deduzir as faces de dados e cubos. Nó da grade: Raciocínio Lógico › Problemas com Visualização Espacial (ver `Classificacao_Faces_Dados_Cubos.md`).

Este capítulo é sobre descobrir o número de uma face de um cubo sem olhar para ela. Um cubo tem seis faces, e elas formam três pares de faces opostas, cada face de costas para exatamente uma outra. Às vezes existe uma regra fixa sobre a soma de cada par oposto, e essa regra sozinha já entrega a face escondida. Às vezes o cubo só usa poucos números diferentes, repetidos várias vezes, e cabe descobrir o menor ou o maior total possível para as seis faces juntas. Às vezes o cubo gira sobre a mesa, e seguir letra por letra em cada giro revela quem fica de costas para quem. E às vezes o dado é jogado várias vezes seguidas, e só o total final é dado, mesmo assim, dá para garantir que uma face em especial apareceu. Essas quatro perguntas sobre faces escondidas organizam o capítulo.

***A soma de um par oposto nunca muda***

Num dado comum, a soma dos números em duas faces opostas é sempre $7$, $1$ fica de costas para $6$, $2$ para $5$, e $3$ para $4$. Essa regra vale para o dado inteiro, então basta saber uma face para descobrir a face oposta a ela, sem nunca precisar virar o dado. Quando o dado usa outra regra fixa, a mesma ideia funciona, só muda o número que a soma sempre dá.

**Exemplo 1:** Num dado comum, a soma dos números em faces opostas é sempre $7$. A face de cima está coberta por um adesivo, mas sabemos que ela é maior que $3$. As faces visíveis mostram $1$ e $4$. **Quantos pontos há na face de cima?**

[Inserir aqui a figura `dado_regra_fixa_estrutura.svg`.]

A face oposta ao $1$ tem $6$ pontos, porque $1+6=7$. A face oposta ao $4$ tem $3$ pontos, porque $4+3=7$. Já usamos os números $1$, $6$, $4$ e $3$, então sobram $2$ e $5$ para as faces de cima e de baixo, que também formam um par oposto.

$2 \quad\quad 5$

Como a face de cima precisa ser maior que $3$, ela só pode ser o $5$.

$5$

Conferimos separando os três pares opostos completos, $1$ e $6$, $4$ e $3$, $5$ e $2$, cada par somando exatamente $7$.

[Inserir aqui a figura `dado_regra_fixa_resultado.svg`.]

**Guarde. Quando a soma de um par oposto é fixa, cada face visível já revela sua oposta na hora. As faces que sobram formam o último par, e uma pista extra, como "maior que" ou "número ímpar", escolhe qual delas é a face escondida.**

***Testar todos os pares que restam, antes de descartar uma soma***

A mesma regra de par oposto fixo também serve para o contrário, descobrir qual soma **nunca** aparece nos outros pares de um cubo. Para isso, não basta olhar um único pareamento possível, é preciso testar todos os jeitos de formar pares com os números que sobraram.

**Exemplo 2:** Beto numerou de $1$ a $6$ as faces de um cubo. Ele percebeu que um par de faces opostas soma $11$. **Ao somar os dois outros pares de faces opostas, qual desses números ele com certeza NÃO pode ter achado, $3$, $8$, $5$ ou $6$?**

A soma $11$ só pode vir de um par entre $1$ e $6$, o par $\{5,6\}$, porque nenhum outro par de números diferentes nesse intervalo chega a $11$. Sobram os números $1$, $2$, $3$ e $4$ para formar os outros dois pares opostos.

O maior par possível entre esses quatro números é $3+4=7$. Como nenhum par desses quatro números passa de $7$, nenhuma soma de $8$ ou mais pode aparecer.

$3+4=7$

Entre as opções dadas, $8$ é o único número maior que $7$, então $8$ é a soma que Beto com certeza não achou.

**Guarde. Para garantir que uma soma nunca aparece, ache primeiro o maior valor possível entre os números que restaram. Qualquer soma maior que esse valor máximo está automaticamente descartada, sem precisar testar par por par.**

***Poucos valores, muitas repetições: o menor e o maior total possíveis***

Quando um cubo usa só um punhado de números diferentes, cada um aparecendo em pelo menos uma face, várias combinações de faces continuam sendo possíveis mesmo depois de ver algumas delas. Nesses casos, a pergunta não é "qual é a soma", porque ela pode variar, é "qual é o menor total possível" ou "qual é o maior total possível", respeitando sempre a regra de que cada número precisa aparecer ao menos uma vez.

**Exemplo 3:** Um cubo tem só os números $2$, $3$ e $5$ pintados em suas faces, cada um aparecendo em pelo menos uma face. Olhando o cubo de um jeito, aparecem as faces $2$, $5$ e $5$. **Qual é o menor total possível para a soma dos números das seis faces desse cubo?**

[Inserir aqui a figura `cubo_valores_limitados_estrutura.svg`.]

Vimos três faces, $2$, $5$ e $5$, e ainda restam três faces escondidas. Como o número $3$ ainda não apareceu em nenhuma face vista, pelo menos uma das três faces escondidas precisa ser $3$, para que o $3$ apareça no cubo pelo menos uma vez.

Para o total ficar o menor possível, as outras duas faces escondidas devem usar o menor valor disponível, que é o $2$. Assim, as três faces escondidas ficam sendo $3$, $2$ e $2$.

$2+5+5+3+2+2=19$

O menor total possível é $19$. Conferimos contando as seis faces completas, duas com $2$, uma com $3$ e três com $5$, e somando de novo, $2+2+3+5+5+5=19$.

[Inserir aqui a figura `cubo_valores_limitados_resultado.svg`.]

**Guarde. Quando um cubo repete poucos valores diferentes, o número que ainda não apareceu tem que estar em alguma das faces escondidas. Para o menor total, complete o resto das faces escondidas com o menor valor permitido, e para o maior total, complete com o maior valor permitido.**

***Girar o cubo e seguir quem fica de costas para quem***

Um cubo com seis rótulos diferentes, letras ou desenhos, forma exatamente três pares de faces opostas. Cada vez que o cubo gira sobre a mesa e mostra duas faces opostas ao mesmo tempo, um desses três pares fica descoberto. Depois de descobrir dois pares, o terceiro fecha sozinho, com os dois rótulos que sobraram.

**Exemplo 4:** O cubo de Sofia tem as letras P, Q, R, S, T e U, uma em cada face. Ela girou o cubo sobre a mesa duas vezes. No primeiro giro, ela percebeu que as letras P e Q ficaram em faces opostas. No segundo giro, percebeu que R e S ficaram em faces opostas. **Qual letra está na face oposta a U?**

[Inserir aqui a figura `cubo_giros_estrutura.svg`.]

O primeiro giro revela um par de faces opostas, P e Q. O segundo giro revela outro par, R e S. Um cubo só tem três pares de faces opostas ao todo, e dois já foram descobertos.

Sobram só as letras T e U, que ainda não apareceram em nenhum dos dois pares. Como só existe mais um par para fechar, T e U formam esse terceiro par.

$T$

A face oposta a U tem a letra T. Conferimos contando os três pares completos, P com Q, R com S, e T com U, seis letras diferentes, cada uma numa face só.

[Inserir aqui a figura `cubo_giros_resultado.svg`.]

**Guarde. Um cubo com seis rótulos diferentes sempre forma três pares opostos. Descobrindo dois desses pares por giros observados, o terceiro par fecha por eliminação, com as duas letras que ainda não apareceram em nenhum par.**

***Quando o total de vários lançamentos denuncia uma face obrigatória***

Jogando o mesmo dado várias vezes seguidas e somando as faces de cima, o total pode ter mais de um jeito de se formar. Mas às vezes todos os jeitos possíveis de chegar naquele total têm uma face em comum, e essa face apareceu com certeza em algum dos lançamentos, mesmo sem saber em qual.

**Exemplo 5:** Marina jogou um dado comum $3$ vezes seguidas e somou os pontos das faces que ficaram viradas para cima, chegando a um total de $16$. **Qual das faces com certeza apareceu virada para cima em pelo menos uma das três jogadas?**

O maior total possível em três lançamentos é $6+6+6=18$. Para chegar a $16$, faltam $2$ pontos em relação a esse máximo.

Testamos os jeitos de somar $16$ com três números entre $1$ e $6$. Sem nenhum $6$, o maior total possível seria $5+5+5=15$, que já é menor que $16$, então pelo menos um dos três lançamentos tem que ter mostrado a face $6$.

$5+5+5=15$

Com um $6$ na jogada, sobram $10$ pontos para as outras duas, que só podem ser $6+4$ ou $5+5$. Testando as duas possibilidades, $6+6+4=16$ e $6+5+5=16$, e as duas realmente somam $16$.

$6+6+4=16 \quad\quad 6+5+5=16$

Nas duas possibilidades, a face $6$ aparece, em uma delas duas vezes e na outra uma vez. Por isso, a face $6$ apareceu com certeza em pelo menos uma das três jogadas.

**Guarde. Para saber se uma face apareceu com certeza em vários lançamentos, comece pelo maior total possível sem usar aquela face. Se esse total sem ela já fica menor que o total dado, ela precisa ter aparecido, não importa como os outros lançamentos se organizaram.**

---

## Ilustrações

- `dado_regra_fixa_estrutura.svg` / `.png` — um dado com duas faces visíveis mostrando $1$ e $4$ pontos, e a face de cima coberta com um "?" em laranja.
- `dado_regra_fixa_resultado.svg` / `.png` — o mesmo dado com a face de cima revelada, mostrando $5$ pontos em verde, e as três faces opostas indicadas por setas curtas ligando $1$–$6$, $4$–$3$ e $5$–$2$.
- `cubo_valores_limitados_estrutura.svg` / `.png` — um cubo com três faces visíveis marcadas $2$, $5$ e $5$, e as três faces escondidas em cinza com "?".
- `cubo_valores_limitados_resultado.svg` / `.png` — o mesmo cubo com as três faces escondidas reveladas em verde, $3$, $2$ e $2$, e a soma total em destaque.
- `cubo_giros_estrutura.svg` / `.png` — dois desenhos lado a lado mostrando o cubo de Sofia em dois giros diferentes, o primeiro com P e Q em faces opostas visíveis, o segundo com R e S.
- `cubo_giros_resultado.svg` / `.png` — um terceiro desenho do cubo mostrando o par T e U em faces opostas, com T em verde na face oposta a U.
