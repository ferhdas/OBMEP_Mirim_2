# Vistas do sólido

> Trilha Mirim 2 (4º e 5º anos) · Caminho 3 · Bloco 6 · Vistas do sólido. Nó da grade: Geometria › Sólidos Geométricos › Vistas Ortogonais de Montagens de Cubos (nó irmão de Planificação do Cubo, aberto no Bloco 5).

Este capítulo é sobre fotografar uma montagem de cubinhos de três jeitos diferentes. Se giramos ao redor de uma montagem de cubos e tiramos uma foto de frente, uma foto de lado e uma foto de cima, o que aparece em cada foto? E será que dá para montar a peça de novo só olhando essas três fotos?

***Três fotos da mesma montagem***

Uma montagem de cubinhos pode ser fotografada de três posições diferentes, sempre olhando bem reto para ela, sem inclinar a câmera. A ***vista de frente*** é a foto tirada bem na frente da montagem. A ***vista de lado*** é a foto tirada de um dos lados. A ***vista de cima*** é a foto tirada de cima, olhando para baixo, como se estivéssemos olhando pela janela de um avião.

Cada uma dessas três fotos mostra só um pedaço da informação sobre a montagem. Nenhuma delas sozinha conta a história inteira, mas as três juntas costumam contar.

[Inserir aqui a figura `vista_tres_fotos.svg`.]

***A vista de cima é o mapa da base***

A vista de cima mostra, para cada posição da base da montagem, se existe uma coluna de cubinhos ali ou não. Ela funciona como um mapa visto de cima, parecido com a planta baixa de uma casa. Esse mapa é o mais informativo dos três porque mostra todas as posições da base de uma vez, sem nenhuma escondida atrás da outra.

Só que o mapa simples, sem número nenhum escrito, só diz se tem cubo ali ou não tem. Ele sozinho não diz quantos cubinhos estão empilhados em cada posição. Por isso, muitas questões desenham a vista de cima com um número escrito em cada posição da base, contando a altura daquela coluna.

Tomemos o caso de uma montagem com quatro posições diferentes na base.

⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯
*A figura mostra uma montagem feita de cubinhos empilhados em quatro posições da base.* **Qual é a vista de cima dessa montagem, com o número de cubinhos de cada posição?**
⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯

[Inserir aqui a figura `vista_ex_a_estrutura.svg`.]

Para descobrir os números, olhamos cada uma das quatro posições da base e contamos quantos cubinhos estão empilhados ali, sem olhar para as outras posições. A pilha de trás, à esquerda, tem $3$ cubinhos. A de trás, à direita, tem $2$. A da frente, à esquerda, tem $1$. A da frente, à direita, tem $2$.

Juntando os quatro números no mapa, cada um na posição certa, e somando para conferir o total de cubinhos da montagem:

$$3+2+1+2 = 8$$

A montagem tem $8$ cubinhos ao todo, e cada número do mapa mostra a altura daquela posição da base. Conferimos contando os cubinhos da figura pilha por pilha, e as quatro alturas batem com os números escritos no mapa.

[Inserir aqui a figura `vista_ex_a_resultado.svg`.]

***A vista de frente e a de lado contam altura, não profundidade***

A vista de frente e a vista de lado também contam alturas, mas de um jeito diferente do mapa de cima. A vista de frente junta todas as pilhas que estão na mesma coluna, não importa se estão mais perto ou mais longe de quem fotografa, e mostra só a mais alta delas. A vista de lado faz parecido, só que junta as pilhas que estão na mesma fileira de profundidade.

Isso quer dizer que a vista de frente e a vista de lado escondem a posição exata de cada pilha. As duas contam a altura, mas não contam se aquela altura pertence à fileira da frente ou à de trás.

Um exemplo simples ajuda a enxergar isso. Numa coluna com uma pilha de $3$ cubinhos atrás e uma pilha de $2$ cubinhos na frente, a foto de frente dessa coluna mostra altura $3$, porque a pilha de trás é mais alta e aparece por cima da pilha da frente. Só o mapa de cima mostra que ali existem duas pilhas diferentes, uma de $3$ e outra de $2$, cada uma na sua posição.

[Inserir aqui a figura `vista_frente_lado_estrutura.svg`.]

***Juntando as três fotos para montar de novo***

Até aqui vimos cada foto sozinha. Mas o mais comum nas questões de prova é o contrário: a questão já dá as três fotos prontas e pede para descobrir qual montagem, entre várias desenhadas, é a dona daquelas fotos.

Imaginemos as três fotos de uma montagem, sem ver a montagem inteira ainda.

⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯
*Uma prova mostra a vista de frente, a vista de lado e a vista de cima de uma montagem, sem mostrar a montagem inteira.* **Entre três montagens candidatas, qual delas é a certa?**
⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯

[Inserir aqui a figura `vista_ex_b_estrutura.svg`.]

O jeito mais seguro de resolver é testar candidato por candidato, sem chutar. Para cada um, imagine as três fotos que ele daria e compare com as fotos que a questão trouxe.

O candidato $1$ dá vista de frente $3$ e $2$, vista de lado $2$ e $3$, e vista de cima com as quatro posições ocupadas. Bate com as três fotos dadas.

O candidato $2$ tem duas pilhas de $3$ na mesma coluna, uma na frente e outra atrás, então a vista de frente dele mostraria $3$ e $3$, não $3$ e $2$. Esse candidato sai.

O candidato $3$ deixou uma posição da base vazia onde devia ter cubinho, então a vista de cima dele mostraria uma posição a menos do que as quatro que a questão garante. Esse candidato também sai.

Sobra só o candidato $1$, e ele é a montagem certa.

[Inserir aqui a figura `vista_ex_b_resultado.svg`.]

***O cubinho escondido não some, só não aparece de frente***

Um cuidado importante aparece quando duas pilhas ficam na mesma coluna, uma atrás da outra, com exatamente a mesma altura. Nesse caso, a pilha de trás fica completamente escondida atrás da pilha da frente numa foto de frente, porque as duas ocupam o mesmo espaço na foto.

Isso não quer dizer que a pilha escondida deixou de existir. Ela existe e entra na conta quando somamos o total de cubinhos da montagem. Só não aparece numa foto tirada de frente. A vista de cima, porém, mostra as duas posições separadas, porque no mapa cada posição da base tem seu próprio quadradinho, não importa a altura da pilha.

Pegue como exemplo uma montagem com um cubinho escondido atrás de outro igual.

⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯
*A figura mostra uma montagem em que duas pilhas da mesma coluna têm a mesma altura, uma na frente e outra atrás.* **Qual é a vista de cima dessa montagem?**
⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯

[Inserir aqui a figura `vista_ex_c_estrutura.svg`.]

Imagine que você tira uma foto bem na frente dessa montagem. As duas pilhas da coluna da esquerda, por terem a mesma altura, aparecem juntas nessa foto, como se fossem uma pilha só. Mas no mapa de cima cada uma mora na sua posição, então marcamos como ocupadas as duas posições da coluna da esquerda, a de trás e a da frente, e também a posição da frente da coluna da direita. A posição de trás da coluna da direita fica vazia, porque ali não existe cubo nenhum.

[Inserir aqui a figura `vista_ex_c_resultado.svg`.]

**Guarde.** Antes de contar quantos cubinhos tem uma montagem só pela vista de frente, conferimos a vista de cima. Duas pilhas da mesma altura, uma atrás da outra, sempre viram uma só sombra na foto de frente.

***As três fotos podem não bastar sozinhas***

Combinar as três fotos costuma ser suficiente para descobrir a montagem certa, mas nem sempre é assim. Às vezes duas montagens bem diferentes por dentro dão exatamente as mesmas três fotos, e não tem como escolher entre uma e outra só olhando de fora.

[Inserir aqui a figura `vista_ambiguidade.svg`.]

Toda questão de prova, porém, sempre dá um jeito de decidir. Ou a questão já mostra a montagem inteira e só pede a vista de cima, ou dá candidatos prontos e pede para escolher entre eles, como no exemplo anterior. O cuidado é nunca supor uma altura que as três fotos não garantem.

Este capítulo reuniu três jeitos de fotografar a mesma montagem de cubinhos, de frente, de lado e de cima. A vista de cima funciona como um mapa da base e é a mais informativa sobre onde tem cubo, mas só conta a altura se vier com números escritos. As vistas de frente e de lado contam a altura de cada fileira, mas escondem a posição exata em profundidade. E um cuidado continua valendo sempre. O cubinho que fica escondido atrás de outro igual numa foto de frente aparece certinho no mapa de cima.

---

***Ilustrações***

| Arquivo | Onde entra | O que mostra |
|---|---|---|
| `vista_tres_fotos.svg` | Logo após a explicação das três fotos | Uma montagem de cubinhos com três setas apontando para a foto de frente, a de lado e a de cima já resolvidas |
| `vista_ex_a_estrutura.svg` | Após o problema fechado do exemplo da vista de cima | A montagem de quatro posições, com o mapa de cima em branco, esperando os números |
| `vista_ex_a_resultado.svg` | Ao final da resolução do exemplo da vista de cima | O mapa de cima preenchido com os quatro números e o total $3+2+1+2=8$ em destaque |
| `vista_frente_lado_estrutura.svg` | Após a explicação de que frente e lado escondem a profundidade | A montagem de duas colunas com a vista de frente e a vista de lado resolvidas ao lado |
| `vista_ex_b_estrutura.svg` | Após o problema fechado de reconstruir a montagem pelas três fotos | As três fotos dadas (frente, lado, cima), sem mostrar a montagem |
| `vista_ex_b_resultado.svg` | Ao final da resolução do exemplo de reconstrução | Os três candidatos numerados, com o candidato certo marcado com visto verde e os outros dois com X vermelho e o motivo da eliminação |
| `vista_ex_c_estrutura.svg` | Após o problema fechado do cubinho escondido | A montagem com o cubinho escondido destacado em laranja e o mapa de cima em branco |
| `vista_ex_c_resultado.svg` | Ao final da resolução do exemplo do cubinho escondido | O mapa de cima com as três posições ocupadas marcadas, incluindo a posição do cubinho escondido |
| `vista_ambiguidade.svg` | Após a explicação de que as três fotos às vezes não bastam | Duas montagens diferentes, P e Q, que dão exatamente as mesmas três fotos |
