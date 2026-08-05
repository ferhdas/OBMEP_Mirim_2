# Decompor o sólido em cubinhos

> Trilha Mirim 2 (4º e 5º anos) · Caminho 3 · Bloco 7 · Decompor o sólido em cubinhos. Nó da grade: Geometria › Sólidos Geométricos › Decomposição e Volume por Cubos Unitários (subnó proposto, irmão de Planificação do Cubo, do Bloco $5$, e de Vistas do Sólido, do Bloco $6$).

Este capítulo é todo sobre contar cubinhos. Quantos cubinhos cabem dentro de um bloco maior? Quando cortamos esse bloco em pedaços menores, quantos cubinhos cada pedaço leva? Quando colamos vários cubinhos, quantas faces ficam grudadas por dentro, uma escondida na outra? E se pintarmos um cubo grande por fora e depois cortarmos ele em cubinhos, quantas faces pintadas cada cubinho carrega, dependendo de onde ele morava?

***Um sólido é um monte de cubinhos colados***

Um ***cubinho unitário*** é o cubo mais simples que existe, do tamanho de um dado pequeno, e usamos ele como unidade de medida para sólidos maiores. Quando um bloco maior é feito de vários cubinhos iguais colados uns aos outros, sem buracos por dentro, o ***volume*** desse bloco é a quantidade de cubinhos que o formam. Contar o volume de um bloco assim é contar quantos cubinhos cabem dentro dele.

A forma mais fácil de contar é por camadas. Contamos quantos cubinhos tem numa só camada do fundo e depois multiplicamos pelo número de camadas empilhadas, porque cada camada de cima repete a mesma quantidade da camada de baixo.

[Inserir aqui a figura `decomp_volume_cubinhos.svg`.]

No bloco da figura, cada camada do fundo tem $6$ cubinhos e há $2$ camadas empilhadas uma sobre a outra, então o bloco inteiro tem

$$6 \times 2 = 12 \text{ cubinhos}$$

***Repartir o sólido em pedaços do mesmo tamanho***

Às vezes um bloco grande precisa ser repartido em pedaços menores, todos exatamente do mesmo tamanho. ***Decompor*** um sólido é cortar ele em ***peças***, e quando a divisão é em partes iguais, cada peça carrega a mesma quantidade de cubinhos que as outras. Contar o total é só o primeiro passo. O passo seguinte é dividir esse total pelo número de peças que queremos.

Veja o caso do bloco de sabonete de Marina.

⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯
*Marina tem um bloco maciço de sabonete artesanal, feito de cubinhos de cheiro colados uns aos outros. O bloco tem $2$ cubinhos de largura, $3$ de profundidade e $4$ de altura, e ela vai cortar esse bloco em $3$ pedaços exatamente do mesmo tamanho.* **Quantos cubinhos de sabonete cada pedaço vai ter?**
⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯

[Inserir aqui a figura `decomp_peca_estrutura.svg`.]

Primeiro contamos o total de cubinhos do bloco inteiro, multiplicando as três medidas.

$$2 \times 3 \times 4 = 24$$

O bloco de Marina tem $24$ cubinhos ao todo. Agora dividimos esse total pelas $3$ peças que ela quer cortar.

$$24 \div 3 = 8$$

Cada pedaço vai ter $8$ cubinhos de sabonete. Conferimos multiplicando de volta, $3$ pedaços de $8$ cubinhos formam $3 \times 8 = 24$ cubinhos, o mesmo total do bloco inteiro.

[Inserir aqui a figura `decomp_peca_resultado.svg`.]

***O que decide se uma peça serve é o tamanho, não a forma***

Um cuidado importante: as $3$ peças do sabonete de Marina não precisam ter o mesmo formato entre si, só a mesma quantidade de cubinhos. Uma peça esticada como uma barra e uma peça mais compacta como um cubo menor podem ter os mesmos $8$ cubinhos, e as duas servem, porque o que decide é o volume, não o desenho da peça.

[Inserir aqui a figura `decomp_peca_candidatas.svg`.]

Na figura, as peças $P$ e $R$ têm formatos bem diferentes um do outro, mas as duas têm $8$ cubinhos, então as duas poderiam ser um dos pedaços de Marina. Já as peças $Q$ e $S$ têm outro número de cubinhos e não servem, mesmo tendo um tamanho parecido numa olhada rápida.

**Guarde.** Para saber se uma peça pode ser um dos pedaços, contamos os cubinhos dela e comparamos com o número certo. O formato da peça não entra nessa conta.

***Quantos pontos de cola prendem os cubinhos***

Quando colamos cubinhos uns nos outros, cada lugar onde uma face inteira de um cubinho encosta na face inteira de outro cubinho é um ***ponto de cola***. Para contar quantos pontos de cola uma peça tem, olhamos cubinho por cubinho e contamos os vizinhos colados de cada um, sem contar duas vezes o mesmo encontro.

Tomemos o caso das peças de EVA de Diego.

⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯
*Diego cola cubinhos de EVA colorido para montar duas peças, cada uma com $4$ cubinhos. A peça $X$ forma uma fileira reta, um cubinho atrás do outro. A peça $Y$ forma um quadrado achatado, com $2$ cubinhos de largura e $2$ de profundidade, numa só camada.* **Qual das duas peças, $X$ ou $Y$, tem mais pontos de cola?**
⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯

[Inserir aqui a figura `decomp_cola_estrutura.svg`.]

Olhe primeiro para a peça $X$. Como os $4$ cubinhos estão em fila, cada um só encosta no vizinho da frente e no de trás, e os pontos de cola ficam um entre cada dois cubinhos vizinhos da fileira.

$$X: 3 \text{ pontos de cola}$$

Agora olhe para a peça $Y$. No quadrado achatado, cada cubinho encosta em dois vizinhos dentro da mesma camada, um do lado e um de cima ou de baixo, e são $4$ encontros ao todo dentro do quadrado.

$$Y: 4 \text{ pontos de cola}$$

A peça $Y$ tem mais cola que a peça $X$, mesmo as duas tendo a mesma quantidade de cubinhos. Isso acontece porque a peça $Y$ é mais compacta, então seus cubinhos encostam uns nos outros de mais jeitos.

[Inserir aqui a figura `decomp_cola_resultado.svg`.]

***Encostar na quina não é a mesma coisa que colar***

Um erro comum é contar como cola um encontro que só toca numa quina ou numa aresta, sem as duas faces inteiras se encostando de verdade. Dois cubinhos que se tocam só na pontinha, na diagonal, não têm nenhum ponto de cola entre eles, porque nenhuma face inteira de um encosta numa face inteira do outro.

[Inserir aqui a figura `decomp_cola_nao_conta.svg`.]

**Guarde.** Só conta como ponto de cola quando duas faces inteiras se encostam de verdade. Encostar só numa quina ou numa aresta não é cola.

***O cubo pintado por fora***

Existe um tipo de sólido bem conhecido nas provas de matemática, o cubo grande pintado por fora e depois cortado em cubinhos menores. Cada cubinho desse corte carrega uma quantidade de faces pintadas que depende de uma única coisa, a posição que ele ocupava dentro do cubo grande antes do corte.

Um ***cubinho de canto*** fica numa quina do cubo grande e tem $3$ faces pintadas, porque três lados dele davam para fora ao mesmo tempo. Um ***cubinho de aresta*** fica no meio de uma aresta do cubo grande, sem estar numa quina, e tem $2$ faces pintadas. Um ***cubinho de face*** fica no meio de uma face do cubo grande, sem tocar nenhuma aresta, e tem só $1$ face pintada. E um ***cubinho do centro*** fica bem escondido no meio do cubo grande, sem encostar em nenhuma face de fora, e não tem nenhuma face pintada.

[Inserir aqui a figura `decomp_pintado_categorias.svg`.]

Com essas quatro posições em mente, já dá para descobrir quantos cubinhos de cada tipo aparecem num corte de verdade.

Imaginemos um cubo de madeira pintado numa marcenaria.

⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯
*Uma marcenaria pinta de laranja um cubo de madeira maciço com $3$ cubinhos de aresta, feito de cubinhos de $1$ cm colados uns aos outros. Depois de pintado, o marceneiro corta esse cubo grande em $27$ cubinhos iguais.* **Quantos desses $27$ cubinhos ficam com exatamente $2$ faces pintadas de laranja?**
⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯

[Inserir aqui a figura `decomp_pintado_estrutura.svg`.]

Os cubinhos com $2$ faces pintadas são os cubinhos de aresta, os que ficam no meio de uma aresta do cubo grande sem estar numa quina. Um cubo tem $12$ arestas, e como o cubo grande tem $3$ cubinhos por aresta, sobra exatamente $1$ cubinho no meio de cada aresta depois de tirar os dois cantos das pontas.

$$12 \text{ arestas} \times 1 \text{ cubinho no meio de cada} = 12$$

Então $12$ cubinhos ficam com exatamente $2$ faces pintadas de laranja. Conferimos contando os outros grupos também: $8$ cantos com $3$ faces cada, $6$ centros de face com $1$ face cada, e só $1$ cubinho bem no meio sem nenhuma face pintada. Somando os quatro grupos,

$$8 + 12 + 6 + 1 = 27$$

a soma bate com os $27$ cubinhos do corte inteiro, então a contagem está certa.

[Inserir aqui a figura `decomp_pintado_resultado.svg`.]

Este capítulo reuniu quatro jeitos de contar cubinhos dentro de um sólido. Contar o total de cubinhos que formam um bloco maior. Dividir esse total entre peças menores do mesmo tamanho, sem se importar com o formato de cada peça. Contar os pontos de cola que prendem os cubinhos de uma peça, faces inteiras encostando em faces inteiras. E, no cubo pintado por fora, descobrir quantas faces pintadas cada cubinho carrega, só de saber se ele mora numa quina, numa aresta, numa face ou bem no centro escondido.

---

***Ilustrações***

| Arquivo | Onde entra | O que mostra |
|---|---|---|
| `decomp_volume_cubinhos.svg` | Após a explicação de contar por camadas | Um bloco de $3 \times 2 \times 2$ cubinhos, com a camada do fundo e o empilhamento marcados, e o total $12$ em destaque |
| `decomp_peca_estrutura.svg` | Após o problema fechado do bloco de sabonete de Marina | O bloco de $2 \times 3 \times 4$ cubinhos, com as medidas indicadas e o corte em $3$ pedaços ainda em aberto |
| `decomp_peca_resultado.svg` | Ao final da resolução do exemplo do sabonete | O bloco dividido em $3$ fatias coloridas, com a conta $24 \div 3 = 8$ em destaque |
| `decomp_peca_candidatas.svg` | Após a explicação de que o formato não importa | Quatro peças candidatas ($P$, $Q$, $R$, $S$), cada uma com sua contagem de cubinhos, marcadas com visto ou X conforme têm ou não os $8$ cubinhos certos |
| `decomp_cola_estrutura.svg` | Após o problema fechado das peças de EVA de Diego | As peças $X$ (fileira reta) e $Y$ (quadrado achatado), cada uma com $4$ cubinhos, sem os pontos de cola marcados |
| `decomp_cola_resultado.svg` | Ao final da resolução do exemplo de Diego | As mesmas peças $X$ e $Y$ com os pontos de cola marcados e contados, mostrando que $Y$ tem mais |
| `decomp_cola_nao_conta.svg` | Após o aviso sobre encostar na quina | Dois cubinhos tocando só na quina, marcados com X, ao lado de dois cubinhos com a face inteira encostada, marcados com visto |
| `decomp_pintado_categorias.svg` | Após a definição das quatro posições do cubo pintado | Quatro cubinhos de exemplo, um de cada posição (canto, aresta, face, centro), com as faces pintadas destacadas |
| `decomp_pintado_estrutura.svg` | Após o problema fechado do cubo da marcenaria | O cubo grande de $3$ cubinhos de aresta, inteiro e pintado de laranja, antes do corte |
| `decomp_pintado_resultado.svg` | Ao final da resolução do exemplo da marcenaria | A contagem dos $27$ cubinhos por posição, com o grupo das arestas ($12$) em destaque |
