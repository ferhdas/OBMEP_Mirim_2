# Medir o contorno na malha

> Trilha Mirim 2 (4º e 5º anos) · Caminho 4 · Bloco 3 · Medir o contorno na malha. Nó da grade: Geometria › Percepção Espacial no Plano › Perímetro e Contorno em Malha Quadriculada (subnó proposto, ver `Classificacao_Perimetro_Malha.md`).

Este capítulo é sobre medir a volta inteira de uma figura desenhada numa malha quadriculada. Duas linhas traçadas podem ocupar o mesmo espaço no papel e, mesmo assim, ter comprimentos diferentes: como decidir qual é mais comprida sem se deixar enganar pelo desenho? Quando uma figura é feita de vários quadradinhos grudados, como contar só os lados de fora, sem contar os lados escondidos por dentro? E existe algum atalho para medir o contorno de uma escada, sem contar degrau por degrau? Essas perguntas organizam o capítulo inteiro.

***O comprimento de um traçado é a soma dos seus trechinhos, não o espaço que ele ocupa***

Numa malha quadriculada, um traçado pode ir e voltar, subir e descer, ocupando pouco espaço no papel mesmo sendo bem comprido. Para medir o comprimento de um traçado, contamos cada trechinho reto de $1$ quadradinho que ele percorre, um por um, sem julgar pela aparência.

**Exemplo 1:** O caminho A é feito de $9$ trechinhos de $1$ cm, alternando entre andar para a direita e para baixo, numa malha quadriculada. O caminho B é feito de $7$ trechinhos de $1$ cm, andando em ziguezague mais apertado, na mesma malha. Ao olhar de longe, os dois caminhos parecem ocupar o mesmo pedaço da malha. **Qual dos dois caminhos é mais comprido?**

[Inserir aqui a figura `perim_tracado_estrutura.svg`.]

Não adianta comparar os dois caminhos só de olho, porque um ziguezague apertado pode parecer maior do que realmente é. O jeito seguro é contar os trechinhos de cada um.

$9 > 7$

O caminho A, com $9$ trechinhos de $1$ cm, é mais comprido do que o caminho B, com $7$ trechinhos de $1$ cm. Conferimos porque cada trechinho vale exatamente $1$ cm na malha, então basta comparar a quantidade de trechinhos contados.

[Inserir aqui a figura `perim_tracado_resultado.svg`.]

**Guarde. O tamanho que um traçado parece ter no papel não é uma medida confiável. A única forma segura de comparar dois traçados numa malha é contar os trechinhos de cada um, sem pular nenhum.**

***O perímetro de uma figura é a soma só dos lados de fora***

Quando vários quadradinhos ficam grudados uns nos outros, formando uma figura, alguns lados ficam escondidos por dentro, encostados no quadradinho vizinho, e outros ficam expostos, virados para fora. O ***perímetro*** de uma figura feita de quadradinhos é a soma só dos lados expostos, os que ficam na borda de fora. Um lado que dois quadradinhos compartilham nunca entra nessa soma, porque ele está escondido dentro da figura, não na borda.

**Exemplo 2:** Uma figura em formato de cruz é feita de $5$ quadradinhos iguais, de $1$ cm de lado: um quadradinho central e mais um grudado em cada um dos quatro lados dele. **Qual é o perímetro dessa figura em cruz?**

[Inserir aqui a figura `perim_cruz_estrutura.svg`.]

Cada quadradinho sozinho tem $4$ lados. Os $5$ quadradinhos juntos teriam, se estivessem separados, $5 \times 4 = 20$ lados ao todo. Só que, grudados em cruz, cada um dos $4$ quadradinhos das pontas encosta num lado do quadradinho central, e cada um desses encontros esconde $2$ lados por dentro da figura (um lado de cada quadradinho envolvido).

$4 \times 2 = 8$

São $4$ encontros, cada um escondendo $2$ lados, então $8$ lados ficam escondidos por dentro. Subtraindo esses lados escondidos do total de lados que os $5$ quadradinhos teriam separados, sobra o perímetro.

$20 - 8 = 12$

O perímetro da cruz é $12$ cm. Conferimos contando direto na borda da figura, lado por lado, ao redor de toda a cruz: também dá $12$.

[Inserir aqui a figura `perim_cruz_resultado.svg`.]

**Guarde. Contar todos os lados dos quadradinhos separados sempre exagera o perímetro, porque conta os lados escondidos também. Cada encontro entre dois quadradinhos esconde exatamente $2$ lados, um de cada quadradinho, e esses lados escondidos nunca entram na volta de fora.**

***O contorno de uma parte usa o mesmo tamanho de lado da figura toda***

Quando uma figura é feita de peças com todos os lados do mesmo tamanho, medir o contorno inteiro da figura revela esse tamanho de lado. Depois, para achar o contorno de só uma parte da figura, basta contar quantos lados de fora essa parte tem e multiplicar pelo mesmo tamanho de lado, sem precisar medir de novo.

**Exemplo 3:** Uma figura é feita de $2$ quadrados e $2$ triângulos, todos com lados do mesmo tamanho, grudados uns nos outros. O contorno da figura inteira, contando todos os lados de fora, tem $8$ lados ao todo, e mede $32$ cm nessa volta inteira. Dentro dessa figura, a região cinza (formada por $1$ quadrado e $1$ triângulo) tem $5$ lados de fora. **Qual é o contorno da região cinza?**

[Inserir aqui a figura `perim_partes_estrutura.svg`.]

Primeiro achamos quanto mede cada lado, dividindo o contorno inteiro pelo número de lados que ele tem.

$32 \div 8 = 4$

Cada lado da figura mede $4$ cm. Como a região cinza tem $5$ lados de fora, e todos os lados da figura têm esse mesmo tamanho, multiplicamos.

$5 \times 4 = 20$

O contorno da região cinza é $20$ cm. Conferimos vendo que os outros $3$ lados de fora, que não são da região cinza, também precisam medir $3 \times 4 = 12$ cm, e $20 + 12 = 32$ bate com o contorno da figura inteira.

[Inserir aqui a figura `perim_partes_resultado.svg`.]

**Guarde. Numa figura com todos os lados do mesmo tamanho, o contorno de qualquer parte se acha contando os lados de fora dessa parte e multiplicando pelo tamanho do lado, que é sempre o mesmo em toda a figura.**

***A escada que só desce tem um atalho no perímetro***

Uma figura em formato de escada, que só anda para um lado e para baixo, sem nunca voltar, é chamada de ***monótona***. Nessa escada, todos os trechinhos horizontais, somados, dão exatamente a largura da escada, e todos os trechinhos verticais, somados, dão exatamente a altura. Como a escada é contornada duas vezes, uma vez indo e outra voltando, o perímetro dela é sempre igual ao perímetro de um retângulo com a mesma largura e a mesma altura.

**Exemplo 4:** Uma escada com vários degraus está desenhada numa malha, sempre descendo para a direita, sem nenhum trecho voltando para trás. A largura total da escada é $9$ cm, e a altura total é $6$ cm. **Qual é o perímetro dessa escada?**

[Inserir aqui a figura `perim_escada_estrutura.svg`.]

Como a escada só desce e nunca volta, usamos o atalho do retângulo: o perímetro é o dobro da soma entre a largura e a altura.

$9 + 6 = 15$

$15 \times 2 = 30$

O perímetro da escada é $30$ cm. Conferimos imaginando a escada "esticada": se empurrarmos cada degrau para o canto, os trechinhos horizontais se juntam numa única largura de $9$ cm, contada duas vezes (embaixo e em cada degrau, ao todo), e os trechinhos verticais se juntam numa única altura de $6$ cm, também contada duas vezes, dando o mesmo $30$.

[Inserir aqui a figura `perim_escada_resultado.svg`.]

**Guarde. O atalho $2 \times (\text{largura} + \text{altura})$ só vale para escadas monótonas, que sempre andam no mesmo sentido, sem nenhum trecho voltando para trás. Numa escada assim, não é preciso medir degrau por degrau: a largura e a altura totais já bastam.**

Este capítulo reuniu quatro formas de medir contornos numa malha. Contar trechinhos para comparar traçados, sem se deixar enganar pela aparência. Somar só os lados de fora de uma figura feita de quadradinhos, descontando os lados escondidos nos encontros. Usar o tamanho do lado, descoberto pelo contorno da figura inteira, para achar o contorno de uma parte só. E usar o atalho do retângulo para medir de uma vez o perímetro de uma escada monótona. Em todos os casos, o cuidado é o mesmo: o perímetro se mede contando, nunca só olhando.

---

***Ilustrações***

| Arquivo | Onde entra | O que mostra |
|---|---|---|
| `perim_tracado_estrutura.svg` | Após o problema fechado dos caminhos A e B | Os dois traçados na malha, sem a contagem de trechinhos feita |
| `perim_tracado_resultado.svg` | Ao final da resolução do exemplo dos caminhos | Os dois traçados com os trechinhos numerados e o total de cada um em destaque |
| `perim_cruz_estrutura.svg` | Após o problema fechado da figura em cruz | A cruz de $5$ quadradinhos, sem nenhum lado marcado como escondido |
| `perim_cruz_resultado.svg` | Ao final da resolução do exemplo da cruz | A mesma cruz com os $8$ lados escondidos marcados por dentro e o perímetro $12$ em destaque na borda |
| `perim_partes_estrutura.svg` | Após o problema fechado dos $2$ quadrados e $2$ triângulos | A figura inteira, com os $8$ lados de fora contados e a região cinza demarcada, sem o tamanho do lado calculado |
| `perim_partes_resultado.svg` | Ao final da resolução do exemplo das partes | A mesma figura com o tamanho do lado ($4$ cm) e o contorno da região cinza ($20$ cm) em destaque |
| `perim_escada_estrutura.svg` | Após o problema fechado da escada | A escada monótona com a largura ($9$ cm) e a altura ($6$ cm) marcadas, sem o perímetro calculado |
| `perim_escada_resultado.svg` | Ao final da resolução do exemplo da escada | A mesma escada com o retângulo de comparação desenhado por trás e o perímetro $30$ em destaque |
