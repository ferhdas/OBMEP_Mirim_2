# Quebrar e remontar figuras

> Trilha Mirim 2 (4º e 5º anos) · Caminho 4 · Bloco 2 · Quebrar e remontar figuras. Nó da grade: Geometria › Percepção Espacial no Plano › Recorte, Ladrilhamento e Decomposição de Área (subnó proposto, ver `Classificacao_Figuras_RecortarLadrilhar.md`).

Este capítulo é sobre cortar uma figura em pedaços menores e sobre cobrir uma malha com peças iguais. Quando uma folha é recortada em quadradinhos do mesmo tamanho, quantos quadradinhos ela rende? Quando uma malha é coberta por peças iguais de cores diferentes, como descobrir quantas peças têm a cor que ninguém contou? E quando um desenho maior é dividido em regiões, como achar a área de uma região só de olhar para as outras? As três perguntas têm a mesma resposta de fundo: a área de uma figura é sempre a soma das áreas dos pedaços que a formam.

***Recortar uma folha em quadradinhos iguais mostra quantos cabem***

Uma folha desenhada numa malha quadriculada pode ser recortada em quadradinhos, todos do mesmo tamanho de um quadradinho de referência. O número de quadradinhos que saem da folha inteira é o número de linhas de quadradinhos multiplicado pelo número de colunas, o mesmo raciocínio de contar grupos iguais em fileiras.

**Exemplo 1:** Uma folha retangular, desenhada numa malha quadriculada, mede $6$ quadradinhos de largura por $4$ quadradinhos de altura. Um quadradinho bem no meio da folha está destacado como referência de tamanho. **Se a folha inteira for recortada em quadradinhos desse mesmo tamanho, quantos quadradinhos saem ao todo?**

[Inserir aqui a figura `ladr_folha_estrutura.svg`.]

A folha tem $6$ quadradinhos numa fileira e $4$ fileiras empilhadas, uma em cima da outra. Para contar o total, multiplicamos a largura pela altura, do mesmo jeito que contamos objetos organizados em fileiras iguais.

$6 \times 4 = 24$

Saem $24$ quadradinhos dessa folha. Conferimos contando fileira por fileira: $6 + 6 + 6 + 6 = 24$, as quatro fileiras de $6$, batendo com a multiplicação.

[Inserir aqui a figura `ladr_folha_resultado.svg`.]

**Guarde. Contar quadradinhos numa malha é sempre multiplicar largura por altura, não é preciso contar quadradinho por quadradinho um a um. Esse número já é a área da folha, medida na unidade do quadradinho de referência.**

***Ladrilhar sem sobrepor: cada peça ocupa sempre o mesmo tanto de espaço***

Uma malha pode ser coberta inteira por peças iguais, encostadas sem sobrepor e sem deixar buraco. Se cada peça ocupa sempre o mesmo número de quadradinhos, o número total de peças é a área da malha dividida pela área de uma peça. Quando algumas peças já têm cor e cabe descobrir quantas faltam de outra cor, o caminho é contar as coloridas conhecidas, achar quantas peças existem ao todo, e subtrair.

**Exemplo 2:** Um retângulo de $8$ por $6$ quadradinhos é coberto, sem sobrepor e sem deixar buraco, por peças iguais, cada uma formada por $4$ quadradinhos grudados. Nesse ladrilhamento, $5$ peças são verdes e $4$ peças são amarelas, e todas as demais são vermelhas. **Quantas peças vermelhas há nesse ladrilhamento?**

[Inserir aqui a figura `ladr_peca4_estrutura.svg`.]

Primeiro achamos a área do retângulo inteiro.

$8 \times 6 = 48$

O retângulo tem $48$ quadradinhos. Como cada peça cobre $4$ quadradinhos, dividimos a área total pela área de uma peça para achar quantas peças existem ao todo.

$48 \div 4 = 12$

Há $12$ peças ao todo. Dessas, $5$ são verdes e $4$ são amarelas, então $5 + 4 = 9$ peças já têm cor conhecida. As vermelhas são as que sobram.

$12 - 9 = 3$

Há $3$ peças vermelhas. Conferimos somando as três cores: $5 + 4 + 3 = 12$, batendo com o total de peças.

[Inserir aqui a figura `ladr_peca4_resultado.svg`.]

**Guarde. Antes de contar uma cor que falta, ache sempre o total de peças dividindo a área da malha pela área de uma peça só. Só depois disso a subtração das cores conhecidas faz sentido, porque ela precisa de um total certo para partir.**

Um cuidado a mais aparece quando o ladrilhamento já está quase pronto e falta encaixar só uma peça, numa vaga com formato e posição fixos. Nesse caso, não vale girar nem virar as peças candidatas: a peça certa é a que já chega no papel do jeito exato que a vaga pede, sem nenhum giro.

**Exemplo 3:** Uma malha está quase toda coberta por peças em formato de L, todas do mesmo tamanho, encaixadas sem sobrepor. Falta cobrir uma vaga, também em formato de L, virada com o degrau para a direita e para baixo. Ao lado da malha há quatro peças soltas, todas em formato de L, mas cada uma virada para um lado diferente. **Sem girar nem virar nenhuma peça, qual delas encaixa exatamente na vaga?**

[Inserir aqui a figura `ladr_pecaL_estrutura.svg`.]

Comparamos a vaga com cada peça solta, sem girar nenhuma delas na cabeça. A vaga tem o degrau apontando para a direita e para baixo. A peça A tem o degrau para a esquerda e para baixo, a peça B tem o degrau para a direita e para cima, e a peça C tem o degrau espelhado, para a esquerda e para cima. Só a peça D tem o degrau exatamente para a direita e para baixo, igual à vaga.

A peça D é a que encaixa. As outras três têm o formato de L, mas na orientação errada, e o enunciado proíbe girar ou virar qualquer uma delas para consertar isso.

[Inserir aqui a figura `ladr_pecaL_resultado.svg`.]

**Guarde. Duas peças do mesmo formato só encaixam no mesmo lugar se estiverem viradas para o mesmo lado. Reconhecer o formato não basta: é preciso reconhecer também a direção exata em que ele está virado.**

***A área de uma parte se descobre pela área das outras partes***

Uma figura grande pode ser dividida em regiões de cores diferentes. Se conhecemos a área da figura inteira e a área de quase todas as regiões, a área da região que falta é a diferença entre o total e a soma das áreas conhecidas.

**Exemplo 4:** Um quadrado grande, desenhado numa malha, tem $36$ quadradinhos de área. Dentro dele, a região azul tem $15$ quadradinhos, a região amarela tem $8$ quadradinhos, e a região preta tem $1$ quadradinho. O resto do quadrado é ocupado por dois retângulos rosa, do mesmo tamanho. **Qual é a área de cada retângulo rosa?**

[Inserir aqui a figura `ladr_areas_estrutura.svg`.]

Somamos as áreas já conhecidas: azul, amarela e preta.

$15 + 8 + 1 = 24$

Essas três regiões ocupam $24$ quadradinhos do quadrado de $36$. O que sobra para os dois retângulos rosa, juntos, é a diferença.

$36 - 24 = 12$

Os dois retângulos rosa juntos têm $12$ quadradinhos, e como são do mesmo tamanho, cada um tem metade disso.

$12 \div 2 = 6$

Cada retângulo rosa tem $6$ quadradinhos de área. Conferimos somando as quatro áreas: $15 + 8 + 1 + 6 + 6 = 36$, o total do quadrado grande.

[Inserir aqui a figura `ladr_areas_resultado.svg`.]

**Guarde. A área que falta nunca se mede direto: ela se calcula subtraindo, do total da figura inteira, a soma de todas as áreas que já são conhecidas. Quando a área que falta está dividida em partes iguais, o último passo é repartir essa diferença entre elas.**

Este capítulo reuniu três formas de trabalhar com áreas feitas de pedaços. Contar quantos quadradinhos saem de uma folha recortada, multiplicando largura por altura. Achar quantas peças de uma cor faltam num ladrilhamento, dividindo a área total pela área de uma peça e subtraindo as cores já conhecidas — e, quando falta encaixar uma última peça, reconhecer não só o formato dela, mas também a direção exata em que está virada. E achar a área de uma região que falta, subtraindo do total a soma das áreas já conhecidas. Nos três casos, a área da figura inteira é sempre a soma das áreas de todos os seus pedaços.

---

***Ilustrações***

| Arquivo | Onde entra | O que mostra |
|---|---|---|
| `ladr_folha_estrutura.svg` | Após o problema fechado da folha retangular | A folha de $6$ por $4$ quadradinhos, com um quadradinho central destacado como referência, sem o total calculado |
| `ladr_folha_resultado.svg` | Ao final da resolução do exemplo da folha | A mesma folha com as $4$ fileiras de $6$ quadradinhos marcadas e o total $24$ em destaque |
| `ladr_peca4_estrutura.svg` | Após o problema fechado do retângulo $8\times 6$ | O retângulo coberto por peças de $4$ quadradinhos, com as verdes e amarelas identificadas e as vermelhas sem contar |
| `ladr_peca4_resultado.svg` | Ao final da resolução do exemplo das peças de $4$ | O mesmo retângulo com as $3$ peças vermelhas destacadas e a conta $12-9=3$ em evidência |
| `ladr_pecaL_estrutura.svg` | Após o problema fechado da vaga em L | A malha quase coberta, a vaga em L em aberto, e as quatro peças soltas A, B, C, D, cada uma virada para um lado |
| `ladr_pecaL_resultado.svg` | Ao final da resolução do exemplo da peça em L | A malha com a peça D encaixada na vaga, e as peças A, B e C marcadas como erradas por estarem viradas para o lado errado |
| `ladr_areas_estrutura.svg` | Após o problema fechado do quadrado de $36$ | O quadrado grande com as regiões azul ($15$), amarela ($8$) e preta ($1$) marcadas, e os dois retângulos rosa em aberto |
| `ladr_areas_resultado.svg` | Ao final da resolução do exemplo das áreas | O mesmo quadrado com os dois retângulos rosa marcados com $6$ cada, e a soma final $36$ em destaque |
