# Pôr em ordem e contar os espaços

> Trilha Mirim 2 (4º e 5º anos) · Caminho 7 · Bloco 4 · Organizar em fila e nos intervalos. Nó da grade: Análise Combinatória › Contagem Direta e Contagem por Posição (ver `Classificacao_Fila_Intervalos.md`).

Este capítulo é sobre organizar itens numa linha e contar, com cuidado, o que existe entre eles. Numa fila de pessoas ou objetos, os espaços entre dois vizinhos são sempre um a menos que a quantidade de itens na fila, e cada espaço pode receber um grupo fixo de outros itens. E quando o pedido é manter grupos inteiros juntos dentro de uma fileira, a contagem de arranjos possíveis se resolve organizando primeiro os grupos entre si, e depois embaralhando cada grupo por dentro.

***Contar os espaços entre os itens de uma fila***

Numa fila com $n$ itens, o número de espaços entre vizinhos é sempre $n-1$, um a menos que o total de itens, porque o primeiro e o último item não têm vizinho de um dos lados. Quando cada um desses espaços recebe a mesma quantidade fixa de outros itens, o total geral se acha multiplicando essa quantidade pelo número de espaços, e depois somando o que já estava na fila.

**Exemplo 1:** Oito amigos ficam em fila para tirar uma foto. Entre cada dois amigos vizinhos, os fotógrafos colocam $2$ balões. **Quantos balões e amigos há ao todo na fila?**

[Inserir aqui a figura `fila_intervalos_estrutura.svg`.]

Com $8$ amigos na fila, o número de espaços entre vizinhos é

$8-1=7$

Cada um desses $7$ espaços recebe $2$ balões, então o total de balões é

$7\times2=14$

Somando os amigos e os balões,

$8+14=22$

há $22$ itens ao todo na fila. Conferimos contando de novo, $8$ amigos e $7$ espaços com $2$ balões cada, $7\times2=14$ balões, e $8+14=22$ no total.

[Inserir aqui a figura `fila_intervalos_resultado.svg`.]

**Guarde. Numa fila de $n$ itens, o número de espaços entre vizinhos é sempre $n-1$, nunca $n$. As pontas da fila não têm espaço para os dois lados, só um vizinho de cada.**

***Manter grupos juntos dentro de uma fileira***

Quando um pedido de organização exige que itens do mesmo tipo fiquem juntos dentro de uma fileira, o jeito mais simples de contar as maneiras possíveis é pensar em cada tipo como um bloco só. Primeiro contamos de quantas formas os blocos podem trocar de posição entre si, depois contamos, dentro de cada bloco, de quantas formas os itens daquele tipo podem trocar de lugar entre eles.

**Exemplo 2:** Pedro quer guardar $4$ bonés numa prateleira, em pé, lado a lado, $2$ bonés azuis e $2$ bonés vermelhos. Ele quer que os bonés da mesma cor fiquem sempre juntos. **De quantas maneiras diferentes ele pode fazer isso?**

[Inserir aqui a figura `prateleira_estrutura.svg`.]

Pensamos primeiro nos dois blocos de cor, o bloco azul e o bloco vermelho. Esses dois blocos podem ficar em $2$ ordens diferentes na prateleira, o azul antes do vermelho, ou o vermelho antes do azul.

Dentro do bloco azul, os $2$ bonés azuis podem trocar de posição entre si de $2$ maneiras. Dentro do bloco vermelho, os $2$ bonés vermelhos também podem trocar de posição entre si de $2$ maneiras.

$2\times2\times2=8$

Multiplicando as três escolhas independentes, a ordem dos blocos e a ordem dentro de cada bloco, chegamos a $8$ maneiras diferentes. Conferimos listando as possibilidades, começando pela ordem dos blocos e depois variando cada bloco por dentro, sem esquecer nenhuma combinação.

[Inserir aqui a figura `prateleira_resultado.svg`.]

**Guarde. Quando itens do mesmo tipo precisam ficar juntos numa fileira, trate cada tipo como um bloco só, conte de quantas formas os blocos podem trocar de ordem entre si, conte de quantas formas os itens trocam de lugar dentro de cada bloco, e multiplique todas essas contagens juntas.**

---

## Ilustrações

- `fila_intervalos_estrutura.svg` / `.png` — os $8$ amigos em fila, com os $2$ balões de cada um dos $7$ espaços entre eles.
- `fila_intervalos_resultado.svg` / `.png` — a mesma fila, usada para conferir a contagem de $7$ espaços vezes $2$ balões.
- `prateleira_estrutura.svg` / `.png` — os $4$ bonés do Exemplo $2$ misturados na prateleira, antes de serem organizados por cor.
- `prateleira_resultado.svg` / `.png` — uma das $8$ maneiras possíveis, com os $2$ bonés azuis juntos de um lado e os $2$ vermelhos juntos do outro.
