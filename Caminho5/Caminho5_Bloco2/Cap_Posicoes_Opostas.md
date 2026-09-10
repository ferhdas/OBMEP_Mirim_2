# Opostos e frente a frente

> Trilha Mirim 2 · Caminho 5 · Bloco 2 · Opostos e frente a frente. Nó da grade: Raciocínio Lógico › Problemas com Restrições e Dedução › Posições Opostas e de Correspondência (subnó proposto, ver `Classificacao_Posicoes_Opostas.md`).

Este capítulo é sobre lugares numerados que se correspondem. Numa roda-gigante ou numa mesa redonda, qual cadeira fica exatamente do lado oposto de outra? Numa mesa comprida, com gente sentada dos dois lados, quem fica de frente para quem? E se a gente já souber quais dois lugares são opostos, dá para descobrir quantos lugares a mesa tem ao todo? As três perguntas se resolvem com a mesma ideia: contar quantos lugares cabem numa volta inteira, ou em meia volta.

***O lugar oposto está a meio caminho ao redor***

Numa roda ou mesa circular com lugares numerados em sequência, dois lugares são opostos quando estão exatamente do lado contrário um do outro, a mesma distância do centro. Para achar o lugar oposto a um lugar dado, soma-se metade do total de lugares ao número desse lugar. Quando essa soma passa do total, ela volta a contar desde o número $1$, porque os lugares formam um círculo fechado.

**Exemplo 1:** Uma roda-gigante tem $8$ cadeiras, numeradas de $1$ a $8$ em sequência, ao redor de todo o círculo. **Qual cadeira fica oposta à cadeira $3$?**

[Inserir aqui a figura `pos_roda_estrutura.svg`.]

Primeiro, achamos quantas cadeiras cabem em meia volta. Como a roda tem $8$ cadeiras ao todo, meia volta corresponde à metade desse total.

$8 \div 2 = 4$

Em seguida, somamos essas $4$ cadeiras ao número da cadeira $3$, para andar meia volta a partir dela.

$3 + 4 = 7$

A cadeira oposta à cadeira $3$ é a cadeira $7$. Conferimos contando ao redor da roda, nos dois sentidos, a partir da cadeira $3$: de um lado ficam as cadeiras $4$, $5$, $6$ e $7$, e do outro lado ficam as cadeiras $2$, $1$, $8$ e $7$, e as duas contagens chegam à cadeira $7$ depois de $4$ passos, confirmando que ela está exatamente na metade da volta.

[Inserir aqui a figura `pos_roda_resultado.svg`.]

**Guarde. Numa roda com um número par de lugares, o lugar oposto a qualquer lugar $k$ é $k$ mais metade do total, voltando a contar do $1$ se a soma passar do total.**

***Duas filas de frente se correspondem em espelho***

Numa mesa comprida, com gente sentada dos dois lados, de frente uma para a outra, cada lado costuma ser numerado separadamente, da esquerda para a direita, do ponto de vista de quem está sentado ali. Mas os dois lados apontam para direções opostas, então a pessoa na posição $1$ de um lado não fica de frente para a posição $1$ do outro lado, e sim para a última posição. A correspondência funciona como um espelho: a posição $i$ de um lado encontra a posição (total de lugares por lado, mais $1$, menos $i$) do outro lado.

**Exemplo 2:** Numa mesa comprida, $6$ amigos sentam de um lado, numerados de $1$ a $6$. Do outro lado, outros $6$ amigos sentam de frente para eles, também numerados de $1$ a $6$, cada um do seu próprio ponto de vista. **Quem fica de frente para a pessoa $2$?**

[Inserir aqui a figura `pos_mesa_estrutura.svg`.]

Para achar a posição correspondente, somamos $1$ ao total de lugares por lado, e depois subtraímos a posição dada.

$6 + 1 = 7$

$7 - 2 = 5$

A pessoa que fica de frente para a pessoa $2$ é a pessoa $5$, do outro lado. Conferimos pensando nas duas pontas da mesa: a posição $1$ de um lado fica de frente para a posição $6$ do outro (porque $7 - 1 = 6$), e a posição $6$ de um lado fica de frente para a posição $1$ do outro (porque $7 - 6 = 1$), então as duas filas se encontram de trás para a frente, como um espelho.

[Inserir aqui a figura `pos_mesa_resultado.svg`.]

**Guarde. Em duas filas de frente uma para a outra, a posição $i$ de um lado corresponde à posição (total mais $1$, menos $i$) do outro lado. É a mesma conta que espelha a ponta $1$ na ponta final.**

***Um par de opostos revela o total de lugares***

A mesma conta que acha o lugar oposto também pode ser usada ao contrário. Quando já se sabe que dois lugares numa mesa circular são opostos um do outro, a diferença entre os dois números é exatamente metade do total de lugares, então o total é o dobro dessa diferença.

**Exemplo 3:** Numa mesa redonda, com lugares numerados em sequência ao redor de toda a mesa, o lugar $3$ fica de frente para o lugar $10$. **Quantos lugares tem a mesa ao todo?**

[Inserir aqui a figura `pos_total_estrutura.svg`.]

Antes de multiplicar, achamos a diferença entre os dois lugares opostos.

$10 - 3 = 7$

Essa diferença é metade do total de lugares, porque ir de um lugar ao seu oposto é andar meia volta inteira. Para achar o total, dobramos esse valor.

$7 \times 2 = 14$

A mesa tem $14$ lugares. Conferimos aplicando a fórmula da primeira seção ao resultado: metade de $14$ é $7$, e $3 + 7 = 10$, que é exatamente o lugar oposto dado no enunciado.

[Inserir aqui a figura `pos_total_resultado.svg`.]

**Guarde. A diferença entre dois lugares opostos numa mesa circular é sempre metade do total de lugares. Para achar o total a partir de um par de opostos, basta dobrar essa diferença.**

Este capítulo reuniu três formas de raciocinar sobre posições que se correspondem. Achar o lugar oposto somando metade do total de lugares. Achar quem fica de frente numa fila dupla espelhando a posição na ponta final. E, ao contrário, achar o total de lugares a partir de um par de opostos, dobrando a diferença entre eles. Nas três, a ideia de fundo é a mesma: contar quantos lugares cabem numa volta inteira, ou em meia volta, e usar essa contagem nos dois sentidos.

---

***Ilustrações***

| Arquivo | Onde entra | O que mostra |
|---|---|---|
| `pos_roda_estrutura.svg` | Após o problema fechado da roda-gigante | As $8$ cadeiras numeradas em círculo, com a cadeira $3$ marcada, sem a cadeira oposta indicada |
| `pos_roda_resultado.svg` | Ao final da resolução do exemplo da roda-gigante | As $8$ cadeiras, com a cadeira $3$ e a cadeira $7$ ligadas por um diâmetro em destaque |
| `pos_mesa_estrutura.svg` | Após o problema fechado da mesa comprida | Os dois lados da mesa numerados de $1$ a $6$, sem as correspondências marcadas |
| `pos_mesa_resultado.svg` | Ao final da resolução do exemplo da mesa comprida | Os dois lados da mesa com a pessoa $2$ e a pessoa $5$ ligadas por uma linha em destaque |
| `pos_total_estrutura.svg` | Após o problema fechado da mesa redonda | A mesa redonda com os lugares $3$ e $10$ marcados e ligados, sem os demais lugares numerados |
| `pos_total_resultado.svg` | Ao final da resolução do exemplo da mesa redonda | A mesa redonda completa, com os $14$ lugares numerados e o total em destaque |
