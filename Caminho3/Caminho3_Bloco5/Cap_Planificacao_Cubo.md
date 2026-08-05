# Planificação do cubo

> Trilha Mirim 2 (4º e 5º anos) · Caminho 3 · Bloco 5 · Planificação do cubo. Nó da grade: Geometria › Sólidos Geométricos › Planificação e Faces Opostas do Cubo (subnó proposto, ver `Classificacao_Planificacao_Cubo.md`).

Este capítulo é sobre um molde de papel que vira um cubo quando dobramos. Se recortamos esse molde e o dobramos, que formato ele precisa ter para fechar certinho, sem sobrar quadrado nem faltar parede? Depois de montado, quais faces do cubo ficam uma de costas para a outra? E um desenho que estava apontando para cima no papel, ele continua apontando para cima depois que o cubo está pronto? Essas três perguntas são o assunto inteiro do capítulo.

***O molde de papel que vira cubo***

Um cubo tem seis faces quadradas, todas do mesmo tamanho. Se cortarmos as arestas certas e abrirmos o cubo até ele ficar totalmente plano, sobra um desenho feito de seis quadrados grudados uns nos outros. Esse desenho chama-se ***planificação***. Cada quadrado da planificação vira uma face do cubo, e as linhas onde os quadrados se tocam são exatamente as linhas onde vamos dobrar.

O caminho inverso também funciona. Se já temos os seis quadrados desenhados no papel, do jeito certo, e dobramos nas linhas entre eles, o resultado é um cubo fechado.

[Inserir aqui a figura `planif_molde_dobra.svg`.]

***Nem todo molde de seis quadrados fecha um cubo***

Seis quadrados grudados nem sempre formam uma planificação de cubo. Se o formato for errado, ao dobrar sobra papel encavalado numa face e falta papel em outra. Para reconhecer um molde que fecha, vale a pena olhar para alguns exemplos e comparar.

Veja o caso de quatro moldes desenhados lado a lado.

⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯
*Quatro moldes, cada um com seis quadrados.* **Qual deles, dobrado, fecha um cubo sem sobrar nem faltar face?**
⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯

[Inserir aqui a figura `planif_formatos_estrutura.svg`.]

Olhamos molde por molde. O Molde $1$ é uma cruz, um quadrado central com um em cada lado e mais dois embaixo. Dobrando essa cruz nas linhas certas, as quatro pontas viram as quatro paredes e as duas pontas que sobram viram o chão e o teto. Fecha certinho. O Molde $3$ também fecha, embora pareça uma fileira torta. O Molde $2$ é uma fileira reta de seis quadrados. Dobrando um atrás do outro, ela dá a volta e o sétimo lado (que não existe) faria falta, então dois quadrados acabam encostando um no outro e o cubo fica sem chão nem teto. O Molde $4$ é um bloco de duas linhas com três quadrados cada. Ao dobrar, uma face acaba encavalando em cima da outra, e o cubo fica sem uma das paredes.

[Inserir aqui a figura `planif_formatos_resultado.svg`.]

O Molde $1$ e o Molde $3$ fecham o cubo. O Molde $2$ e o Molde $4$ não fecham.

**Guarde.** Para saber se um molde fecha, é mais seguro imaginar a dobra quadrado por quadrado do que só olhar de longe. Um molde reto demais (como uma fileira de seis) ou empilhado demais (como um bloco de duas linhas) costuma ser o que não fecha.

***Como achar as faces que ficam opostas***

Depois que um molde fecha em cubo, cada face tem uma ***face oposta***, a que fica do lado de trás, impossível de ver ao mesmo tempo que ela. Existe um jeito rápido de descobrir esses pares direto no papel, sem imaginar a dobra inteira.

Quando várias casas do molde estão grudadas em linha reta, seguidas, as faces opostas são sempre as que ficam a duas casas de distância uma da outra, pulando exatamente uma casa no meio. Numa fileira reta de três quadrados grudados, os dois das pontas são opostos. Numa fileira reta de quatro, o primeiro é oposto ao terceiro, e o segundo é oposto ao quarto.

Tomemos o caso de um molde em cruz, com uma cor em cada face.

⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯
*O molde abaixo tem seis cores, uma por face, e vai virar um cubo.* **Qual cor fica oposta ao amarelo?**
⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯

[Inserir aqui a figura `planif_pares_estrutura.svg`.]

Imagine que você separa o molde em duas fileiras retas que se cruzam. Uma fileira sobe e desce, com quatro quadrados. A outra atravessa de lado a lado, com três quadrados, e o quadrado do meio dela é o mesmo que já está na fileira vertical.

Primeiro olhamos a fileira de três, a que atravessa de lado a lado. O amarelo está numa ponta dela, então a face oposta ao amarelo é a outra ponta da mesma fileira, pulando o quadrado do meio.

$$\text{amarelo (ponta)} \rightarrow \text{pula uma casa} \rightarrow \text{roxo (outra ponta)}$$

A cor oposta ao amarelo é o roxo. Conferimos olhando a fileira vertical de quatro quadrados, que não tem nada a ver com o amarelo: nela, o primeiro quadrado com o terceiro formam um par oposto, e o segundo com o quarto formam outro par oposto, sempre pulando uma casa. Os três pares da planificação inteira são o azul com o laranja, o verde com o marinho, e o amarelo com o roxo.

[Inserir aqui a figura `planif_pares_resultado.svg`.]

**Guarde.** Numa fileira reta de quadrados grudados, sempre pule uma casa para achar o par oposto. Isso vale tanto numa planificação em cruz quanto numa planificação em fileira torta, porque a regra olha só para a fileira reta, não para o formato inteiro do molde.

***Uma face pode virar de lado ao dobrar***

Até aqui descobrimos quais faces ficam opostas. Falta um cuidado a mais: um desenho pintado numa face pode mudar de direção quando o cubo é montado, porque a face inteira gira ao dobrar.

Pegue como exemplo uma seta pintada numa das faces do molde, apontando para a casa vizinha.

⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯
*Uma seta está pintada numa das faces do molde, apontando para a casa da esquerda, ainda no papel.* **Depois de dobrado o cubo, para onde a seta aponta?**
⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯

[Inserir aqui a figura `planif_giro_estrutura.svg`.]

No papel, a face amarela é vizinha da casa que vai virar uma das paredes do cubo, e a seta aponta reto para ela. Quando dobramos o molde, a face amarela não fica mais deitada, ela se levanta e vira uma parede do cubo. A casa vizinha, que estava do lado, agora está lá em cima, formando o teto.

A seta continua pintada do mesmo jeito na face amarela, ela não se apaga nem se redesenha. Mas como a face inteira girou para ficar de pé, a seta girou junto. Ela deixa de apontar para o lado e passa a apontar na diagonal, para cima, na direção da face que virou teto.

[Inserir aqui a figura `planif_giro_resultado.svg`.]

A seta muda de direção porque a face inteira gira ao dobrar, e a seta gira junto com ela.

**Guarde.** Um desenho não muda de lugar dentro da própria face, ele continua no mesmo cantinho onde foi pintado. O que muda é a posição da face inteira depois de montado o cubo, e por isso o desenho parece ter virado de direção.

Este capítulo reuniu quatro ideias sobre a planificação do cubo. O molde de seis quadrados que vira cubo ao dobrar. O jeito de reconhecer, comparando alguns exemplos, se um molde fecha ou não. A regra de pular uma casa numa fileira reta para achar as faces opostas. E o cuidado de que uma face inteira gira ao dobrar, levando junto qualquer desenho pintado nela.

---

***Ilustrações***

| Arquivo | Onde entra | O que mostra |
|---|---|---|
| `planif_molde_dobra.svg` | Logo após a definição de planificação | Um molde plano colorido, uma seta de "dobra" e o cubo montado com as mesmas cores nas três faces visíveis |
| `planif_formatos_estrutura.svg` | Após o problema fechado dos quatro moldes | Quatro moldes de seis quadrados lado a lado, sem indicação de qual fecha ou não |
| `planif_formatos_resultado.svg` | Ao final da resolução do exemplo dos quatro moldes | Os mesmos quatro moldes com visto ou X, e uma frase curta dizendo por que cada um fecha ou não fecha |
| `planif_pares_estrutura.svg` | Após o problema fechado do molde colorido | O molde em cruz com as seis cores, sem nenhum par marcado |
| `planif_pares_resultado.svg` | Ao final da resolução do exemplo do molde colorido | O mesmo molde com os três pares de faces opostas ligados por linhas tracejadas, o par amarelo-roxo em destaque |
| `planif_giro_estrutura.svg` | Após o problema fechado da seta | O molde com uma face amarela em destaque e uma seta apontando para a casa vizinha, ainda no papel |
| `planif_giro_resultado.svg` | Ao final da resolução do exemplo da seta | O cubo montado, com a mesma face amarela mostrando a seta já apontando na diagonal |
