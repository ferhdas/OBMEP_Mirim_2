# Pintar para igualar ou dobrar

> Trilha Mirim 2 (4º e 5º anos) · Caminho 7 · Bloco 3 · Pintar ou virar para criar uma relação. Nó da grade: Análise Combinatória › Contagem Direta e Contagem por Posição (ver `Classificacao_Pintar_Virar_Relacao.md`).

Este capítulo é sobre mudar a cor de alguns quadradinhos até que duas contagens fiquem numa relação pedida, iguais, ou uma o dobro da outra. Às vezes o quadradinho só pode virar numa direção, de branco para preto, e nunca volta. Às vezes ele pode virar para qualquer um dos dois lados, porque é branco de um lado e preto do outro, e a pergunta é quantas viradas transformam um desenho inteiro noutro. Nos três casos, o caminho é o mesmo, montar uma conta que descreve a relação pedida e resolver essa conta para achar quantos quadradinhos mudam.

***Pintar para igualar duas contagens***

Quando um painel tem quadradinhos pretos e brancos em quantidades diferentes, e a pergunta pede para pintar alguns brancos de preto até as duas quantidades ficarem iguais, cada quadradinho pintado soma um preto e tira um branco ao mesmo tempo. Isso faz a diferença entre as duas contagens diminuir de dois em dois a cada quadradinho pintado.

**Exemplo 1:** Um painel tem $16$ quadradinhos, $5$ pretos e $11$ brancos. **Quantos quadradinhos brancos devem ser pintados de preto para que a quantidade de pretos fique igual à de brancos?**

[Inserir aqui a figura `painel_igualar_estrutura.svg`.]

Chamamos de $x$ a quantidade de quadradinhos brancos que serão pintados de preto. Depois de pintar, a quantidade de pretos fica $5+x$, e a quantidade de brancos fica $11-x$. Para as duas ficarem iguais,

$5+x=11-x$

Juntando os dois $x$ do mesmo lado,

$2x=11-5=6$

e dividindo por $2$,

$x=3$

Devem ser pintados $3$ quadradinhos brancos. Conferimos substituindo, a quantidade de pretos fica $5+3=8$, e a de brancos fica $11-3=8$, as duas iguais.

[Inserir aqui a figura `painel_igualar_resultado.svg`.]

**Guarde. Cada quadradinho pintado de branco para preto soma um numa contagem e tira um da outra ao mesmo tempo, então a diferença entre as duas contagens sempre diminui de dois em dois. Para achar quantos pintar até igualar, divida a diferença inicial por $2$.**

***Pintar para criar uma relação de dobro***

A mesma ideia de pintar branco para preto também serve para relações diferentes de igualdade, como "o dobro de". A montagem da conta muda, mas o caminho continua o mesmo, escrever a relação pedida com $x$ representando quantos quadradinhos foram pintados, e resolver.

**Exemplo 2:** Um colar tem $12$ contas, $3$ pretas e $9$ brancas. **Quantas contas brancas devem ser pintadas de preto para que o número de contas pretas fique igual ao dobro do número de contas brancas?**

[Inserir aqui a figura `colar_dobro_estrutura.svg`.]

Chamando de $x$ a quantidade de contas brancas pintadas, a quantidade de pretas fica $3+x$, e a de brancas fica $9-x$. A relação pedida é que as pretas sejam o dobro das brancas,

$3+x=2\times(9-x)$

Abrindo o lado direito,

$3+x=18-2x$

Juntando os $x$,

$3x=18-3=15$

e dividindo por $3$,

$x=5$

Devem ser pintadas $5$ contas brancas. Conferimos substituindo, as pretas ficam $3+5=8$, as brancas ficam $9-5=4$, e $8$ é mesmo o dobro de $4$.

[Inserir aqui a figura `colar_dobro_resultado.svg`.]

**Guarde. Quando a relação pedida não é igualdade simples, escreva a equação exatamente como a relação é descrita, "pretas igual ao dobro de brancas" vira pretas $=2\times$ brancas, com $x$ pintado somando de um lado e subtraindo do outro. Resolver a equação dá direto quantos quadradinhos pintar.**

***Virar quadradinhos para transformar um desenho no outro***

Alguns quadradinhos são brancos de um lado e pretos do outro, e podem ser virados para qualquer um dos dois lados, quantas vezes for preciso. Quando a pergunta mostra um desenho "antes" e um desenho "depois", o número de viradas necessárias é simplesmente a quantidade de casas em que a cor muda de um desenho para o outro, comparando casa por casa.

**Exemplo 3:** As duas figuras abaixo, com $4$ linhas e $4$ colunas, são feitas de quadradinhos brancos de um lado e pretos do outro. **Quantos quadradinhos precisam ser virados para transformar a primeira figura na segunda?**

[Inserir aqui a figura `virar_estrutura.svg`.]

Comparamos as duas figuras casa por casa. Nas casas onde a cor já é a mesma nas duas figuras, nenhuma virada é necessária. Nas casas onde a cor muda, uma virada é necessária.

Para organizar a contagem, separamos em dois grupos. Primeiro, as casas que são pretas na primeira figura mas deveriam ficar brancas na segunda, fora do quadrado preto central, $6$ casas nesse caso.

Depois, as casas que são brancas na primeira figura mas deveriam ficar pretas na segunda, dentro do quadrado preto central, $2$ casas nesse caso.

$6+2=8$

Ao todo, $8$ quadradinhos precisam ser virados. Conferimos casa por casa, comparando as duas figuras uma última vez, e contando de novo cada casa que muda de cor.

[Inserir aqui a figura `virar_resultado.svg`.]

**Guarde. Para contar quantas viradas transformam um desenho no outro, compare casa por casa, e não confunda "casas pretas na primeira figura" com "casas que precisam virar". Só as casas em que a cor realmente muda entre as duas figuras contam, separadas em dois grupos, as que eram pretas e viram brancas, e as que eram brancas e viram pretas.**

---

## Ilustrações

- `painel_igualar_estrutura.svg` / `.png` — os $16$ quadradinhos do Exemplo $1$, $5$ pretos e $11$ brancos, espalhados sem destaque.
- `painel_igualar_resultado.svg` / `.png` — o mesmo painel, com $3$ quadradinhos brancos destacados em verde, os que precisam ser pintados de preto.
- `colar_dobro_estrutura.svg` / `.png` — as $12$ contas do Exemplo $2$, $3$ pretas e $9$ brancas, numa fileira, sem destaque.
- `colar_dobro_resultado.svg` / `.png` — o mesmo colar, com $5$ contas brancas destacadas em verde, as que precisam ser pintadas de preto.
- `virar_estrutura.svg` / `.png` — as duas figuras $4\times4$ do Exemplo $3$, "Antes" e "Depois", lado a lado, sem destaque.
- `virar_resultado.svg` / `.png` — as mesmas duas figuras, com as $8$ casas que mudam de cor destacadas em verde nas duas figuras.
