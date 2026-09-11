# Achar a regra que soma sempre o mesmo

> Trilha Mirim 2 (4º e 5º anos) · Caminho 8 · Bloco 1 · Padrões que crescem em ritmo constante. Nó da grade: Sequências e Padrões (ver `Classificacao_Padroes_Ritmo_Constante.md`).

Este capítulo é sobre sequências que crescem sempre no mesmo ritmo. De um termo para o próximo, alguma quantidade aumenta sempre pela mesma quantia, um número fixo de centímetros, de cadeiras, de peças ou de pontas. Descobrindo esse aumento fixo a partir de dois termos conhecidos, dá para prever qualquer outro termo da sequência, mesmo um termo bem distante, ou até um termo que está escondido e não dá para desenhar.

***Descobrir quanto cada passo soma***

O primeiro passo é sempre o mesmo, comparar dois termos vizinhos da sequência e descobrir de quanto ela cresceu de um para o outro. Esse valor, o aumento fixo a cada passo, vale para toda a sequência, do começo ao fim.

**Exemplo 1:** Um trenzinho de brinquedo é montado encaixando vagões iguais, um atrás do outro. Com $1$ vagão, o trenzinho mede $15$ centímetros. Com $2$ vagões encaixados, ele passa a medir $26$ centímetros. **Quanto vai medir o trenzinho com $6$ vagões encaixados?**

[Inserir aqui a figura `trem_1vagao.svg`.]

[Inserir aqui a figura `trem_2vagoes.svg`.]

De $1$ para $2$ vagões, o comprimento aumentou de $15$ para $26$ centímetros, um aumento de $26-15=11$ centímetros. Esse é o comprimento que cada vagão a mais acrescenta ao trenzinho.

Para chegar a $6$ vagões, partindo de $1$ vagão, é preciso encaixar mais $5$ vagões. Cada um deles soma $11$ centímetros, então o aumento total é $5\times11=55$ centímetros.

$15+55=70$

O trenzinho com $6$ vagões mede $70$ centímetros. Conferimos contando passo a passo, $15$, depois $26$, depois $37$, $48$, $59$ e $70$, sempre somando $11$.

[Inserir aqui a figura `trem_6vagoes_resultado.svg`.]

**Guarde. Numa sequência que cresce em ritmo constante, basta comparar dois termos vizinhos para descobrir quanto cada passo soma. Depois, para chegar a qualquer outro termo, multiplica-se esse aumento fixo pelo número de passos que faltam, e soma-se ao termo de partida.**

**Exemplo 2:** Ana forma flores encaixando dois polígonos iguais, um girado em relação ao outro, de modo que as pontas dos dois apareçam ao redor da flor. Com $2$ triângulos, a flor tem $6$ pontas. Com $2$ quadrados, a flor tem $8$ pontas. **Quantas pontas tem a flor formada com $2$ pentágonos?**

[Inserir aqui a figura `flor_triangulo.svg`.]

[Inserir aqui a figura `flor_quadrado.svg`.]

Do triângulo (com $3$ lados) para o quadrado (com $4$ lados), o número de pontas foi de $6$ para $8$, um aumento de $2$ pontas. Isso acontece porque cada polígono contribui com uma ponta para cada lado que tem, e os dois polígonos juntos formam o dobro de pontas do número de lados.

O pentágono tem $5$ lados, um lado a mais que o quadrado. Seguindo o mesmo ritmo, a flor de pentágonos tem $2$ pontas a mais que a flor de quadrados.

$8+2=10$

A flor de $2$ pentágonos tem $10$ pontas. Conferimos direto pela regra, o dobro do número de lados do polígono, $2\times5=10$.

[Inserir aqui a figura `flor_pentagono_estrutura.svg`.]

[Inserir aqui a figura `flor_pentagono_resultado.svg`.]

**Guarde. Quando cada polígono a mais soma sempre o mesmo tanto de lado (aqui, um lado a mais a cada figura), o número de pontas da flor também cresce em ritmo constante, dois a dois, porque cada lado novo do polígono vira uma ponta nova na flor.**

**Exemplo 3:** Numa festa, mesas quadradas iguais são encostadas lado a lado, formando uma fila. Uma cadeira cabe em cada lado livre de mesa. Com $1$ mesa sozinha, cabem $4$ cadeiras. Com $2$ mesas encostadas, cabem $6$ cadeiras. **Quantas cadeiras cabem numa fila de $12$ mesas encostadas?**

[Inserir aqui a figura `mesas_1mesa.svg`.]

[Inserir aqui a figura `mesas_2mesas.svg`.]

De $1$ para $2$ mesas, o número de cadeiras foi de $4$ para $6$, um aumento de $2$ cadeiras. Isso faz sentido, encostar uma mesa a mais sempre libera $2$ lados novos para cadeiras, um de cada lado comprido da fila, porque o lado que encosta na mesa vizinha perde a cadeira.

Para chegar a $12$ mesas, partindo de $1$ mesa, são $11$ mesas a mais, cada uma somando $2$ cadeiras.

$4+11\times2=4+22=26$

Cabem $26$ cadeiras numa fila de $12$ mesas. Conferimos de outro jeito, contando $1$ cadeira em cada um dos $12$ lados de cima, mais $1$ em cada um dos $12$ lados de baixo, mais $1$ cadeira em cada ponta da fila, $12+12+2=26$.

[Inserir aqui a figura `mesas_12mesas_resultado.svg`.]

**Guarde. O mesmo padrão pode ser lido de dois jeitos, comparando dois termos vizinhos e multiplicando o aumento fixo pelo número de passos, ou entendendo diretamente por que a regra funciona, olhando a estrutura da figura. Os dois caminhos sempre concordam.**

***Estender a regra até um termo que não dá para ver***

Às vezes o termo pedido é grande demais para desenhar, ou está escondido. Nesses casos, a única saída é confiar na regra descoberta com os termos visíveis e aplicá-la sem desenhar o termo pedido.

**Exemplo 4:** Um painel quadriculado tem as duas diagonais coloridas. Um painel $3\times3$ tem $5$ quadradinhos coloridos, um painel $5\times5$ tem $9$ quadradinhos coloridos, e um painel $7\times7$ tem $13$ quadradinhos coloridos. Um painel $9\times9$ está coberto por um pano. **Quantos quadradinhos coloridos tem o painel $9\times9$ coberto?**

[Inserir aqui a figura `painel_3x3.svg`.]

[Inserir aqui a figura `painel_5x5.svg`.]

[Inserir aqui a figura `painel_7x7.svg`.]

Cada vez que o tamanho do painel aumenta $2$ (de $3\times3$ para $5\times5$, de $5\times5$ para $7\times7$), o número de quadradinhos coloridos aumenta sempre $4$ (de $5$ para $9$, de $9$ para $13$). Esse aumento fixo se repete mesmo sem ver o próximo painel.

Do painel $7\times7$ para o painel $9\times9$, o tamanho aumenta mais $2$, então o número de quadradinhos coloridos aumenta mais $4$.

$13+4=17$

O painel $9\times9$ coberto tem $17$ quadradinhos coloridos, mesmo sem poder contá-los diretamente. Conferimos entendendo por que a regra vale, cada diagonal de um painel $n\times n$ (com $n$ ímpar) tem $n$ quadradinhos, e as duas diagonais se cruzam em $1$ quadradinho central, contado duas vezes, então o total é $2n-1$. Para $n=9$, $2\times9-1=17$.

[Inserir aqui a figura `painel_9x9_resultado.svg`.]

**Guarde. Um termo escondido ou grande demais para desenhar se resolve do mesmo jeito que qualquer outro termo da sequência, aplicando o aumento fixo o número de vezes necessário. Não é preciso ver o termo para calculá-lo.**

**Exemplo 5:** Uma cerca é feita de seções iguais, encaixadas lado a lado, cada seção com $2$ estacas verticais e $2$ travessas horizontais, e seções vizinhas compartilham a estaca do meio. Uma cerca com $1$ seção usa $4$ peças. Uma cerca com $3$ seções usa $10$ peças. **Quantas peças usa uma cerca com $9$ seções?**

[Inserir aqui a figura `cerca_1secao.svg`.]

[Inserir aqui a figura `cerca_3secoes.svg`.]

Aqui os dois termos dados não são vizinhos, faltam $2$ seções entre eles. De $1$ para $3$ seções, o número de peças foi de $4$ para $10$, um aumento total de $6$ peças em $2$ passos. Dividindo, cada seção a mais soma $6\div2=3$ peças.

Para chegar a $9$ seções, partindo de $1$ seção, são $8$ seções a mais, cada uma somando $3$ peças.

$4+8\times3=4+24=28$

Uma cerca com $9$ seções usa $28$ peças. Conferimos entendendo a estrutura, cada seção nova soma $1$ estaca e $2$ travessas ($3$ peças novas), porque a outra estaca já estava contada na seção vizinha, e a primeira seção sozinha soma as $4$ peças iniciais ($2$ estacas e $2$ travessas).

[Inserir aqui a figura `cerca_9secoes_resultado.svg`.]

**Guarde. Quando os dois termos conhecidos não são vizinhos, o aumento fixo por passo se descobre dividindo o aumento total pelo número de passos entre eles. O resultado é o mesmo aumento fixo que vale para a sequência inteira.**

---

## Ilustrações

- `trem_1vagao.svg` / `.png` — trenzinho com $1$ vagão, $15$ centímetros, do Exemplo $1$.
- `trem_2vagoes.svg` / `.png` — trenzinho com $2$ vagões, $26$ centímetros, do Exemplo $1$.
- `trem_6vagoes_resultado.svg` / `.png` — trenzinho com $6$ vagões, $70$ centímetros, resultado do Exemplo $1$.
- `flor_triangulo.svg` / `.png` — flor de $2$ triângulos, $6$ pontas, do Exemplo $2$.
- `flor_quadrado.svg` / `.png` — flor de $2$ quadrados, $8$ pontas, do Exemplo $2$.
- `flor_pentagono_estrutura.svg` / `.png` — flor de $2$ pentágonos, com o número de pontas oculto, do Exemplo $2$.
- `flor_pentagono_resultado.svg` / `.png` — flor de $2$ pentágonos, $10$ pontas, resultado do Exemplo $2$.
- `mesas_1mesa.svg` / `.png` — $1$ mesa, $4$ cadeiras, do Exemplo $3$.
- `mesas_2mesas.svg` / `.png` — $2$ mesas encostadas, $6$ cadeiras, do Exemplo $3$.
- `mesas_12mesas_resultado.svg` / `.png` — fila de $12$ mesas, $26$ cadeiras, resultado do Exemplo $3$.
- `painel_3x3.svg` / `.png` — painel $3\times3$, $5$ quadradinhos coloridos, do Exemplo $4$.
- `painel_5x5.svg` / `.png` — painel $5\times5$, $9$ quadradinhos coloridos, do Exemplo $4$.
- `painel_7x7.svg` / `.png` — painel $7\times7$, $13$ quadradinhos coloridos, do Exemplo $4$.
- `painel_9x9_resultado.svg` / `.png` — painel $9\times9$ coberto, $17$ quadradinhos coloridos, resultado do Exemplo $4$.
- `cerca_1secao.svg` / `.png` — cerca com $1$ seção, $4$ peças, do Exemplo $5$.
- `cerca_3secoes.svg` / `.png` — cerca com $3$ seções, $10$ peças, do Exemplo $5$.
- `cerca_9secoes_resultado.svg` / `.png` — cerca com $9$ seções, $28$ peças, resultado do Exemplo $5$.
