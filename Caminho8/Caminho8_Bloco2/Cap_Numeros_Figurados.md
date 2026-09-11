# Quando o crescimento acelera

> Trilha Mirim 2 (4º e 5º anos) · Caminho 8 · Bloco 2 · Números figurados. Nó da grade: Aritmética › Quadrados Perfeitos (ver `Classificacao_Numeros_Figurados.md`).

No capítulo anterior, cada passo de uma sequência somava sempre a mesma quantidade. Neste capítulo, o salto entre um termo e o próximo também segue uma regra, só que esse salto vai aumentando, o crescimento acelera. Isso acontece quando a sequência vem de arrumar objetos numa figura, como um quadrado ou um triângulo, que vai crescendo camada por camada, e cada camada nova é maior que a anterior.

***Quando a figura é um quadrado que cresce***

Um quadrado perfeito é o resultado de organizar objetos em fileiras iguais, tanto na horizontal quanto na vertical, com o mesmo número de fileiras dos dois lados. Uma figura com $n$ fileiras de $n$ objetos tem $n\times n$ objetos ao todo.

**Exemplo 1:** Manuela organiza fichas redondas em quadrados. A $1$ª figura tem $1$ fileira de $1$ ficha. A $2$ª figura tem $2$ fileiras de $2$ fichas. A $3$ª figura tem $3$ fileiras de $3$ fichas. A $4$ª figura tem $4$ fileiras de $4$ fichas. **Quantas fichas tem a $6$ª figura?**

[Inserir aqui a figura `quadrados_estrutura.svg`.]

Contando cada figura, $1\times1=1$, $2\times2=4$, $3\times3=9$, $4\times4=16$. O salto entre uma figura e a próxima não é sempre o mesmo, de $1$ para $4$ o salto foi $3$, de $4$ para $9$ foi $5$, de $9$ para $16$ foi $7$. O salto cresce sempre $2$ a mais que o anterior, mas o jeito mais direto de achar qualquer figura da sequência é multiplicar o número da figura por ele mesmo.

A $6$ª figura tem $6$ fileiras de $6$ fichas.

$6\times6=36$

A $6$ª figura tem $36$ fichas. Conferimos continuando os saltos a partir da $4$ª figura, $16+9=25$ (a $5$ª figura, salto de $9$), e $25+11=36$ (a $6$ª figura, salto de $11$), o mesmo resultado de multiplicar $6\times6$.

[Inserir aqui a figura `quadrados_6x6_resultado.svg`.]

**Guarde. Numa sequência de quadrados perfeitos, a figura de número $n$ sempre tem $n\times n$ objetos, não importa quão longe $n$ esteja. Os saltos entre figuras vizinhas crescem, sempre $2$ a mais que o salto anterior, mas multiplicar $n$ por ele mesmo dá a resposta direto, sem precisar somar salto por salto.**

***Quando a figura é uma pilha que cresce em camadas triangulares***

Outra família de figuras cresce empilhando camadas triangulares, cada camada sendo maior que a anterior. Uma camada com $n$ fileiras, a fileira de cima com $1$ objeto e cada fileira seguinte com $1$ objeto a mais, tem $1+2+\dots+n$ objetos ao todo, o chamado número triangular de $n$.

**Exemplo 2:** Rafael empilha laranjas numa banca de feira, formando uma pirâmide. A $1$ª camada, sozinha, tem $1$ laranja. Colocando a $2$ª camada embaixo, com $3$ laranjas a mais, a pilha passa a ter $4$ laranjas. Colocando a $3$ª camada, com $6$ laranjas a mais, a pilha passa a ter $10$. Colocando a $4$ª camada, com $10$ laranjas a mais, a pilha passa a ter $20$. **Quantas laranjas tem a pilha depois de colocar a $6$ª camada?**

[Inserir aqui a figura `pilhas_camadas_estrutura.svg`.]

O tamanho de cada camada nova também segue um padrão, $1$, $3$, $6$, $10$, sempre somando $1$ a mais de fileiras que a anterior, o salto entre esses tamanhos cresce, $2$, $3$, $4$. Seguindo esse padrão, a $5$ª camada tem $10+4=14$ ... na verdade, o tamanho de cada camada é o próprio número triangular, $1$, $1+2=3$, $1+2+3=6$, $1+2+3+4=10$, então a $5$ª camada tem $1+2+3+4+5=15$ e a $6$ª camada tem $1+2+3+4+5+6=21$.

Somando a $5$ª e a $6$ª camada à pilha que já tinha $20$,

$20+15=35 \quad\quad 35+21=56$

A pilha depois da $6$ª camada tem $56$ laranjas. Conferimos somando os tamanhos de todas as camadas de uma vez, $1+3+6+10+15+21=56$.

[Inserir aqui a figura `pilha_camada6_resultado.svg`.]

**Guarde. Numa pilha que cresce em camadas triangulares, o tamanho de cada camada nova é o número triangular daquela posição ($1$, $3$, $6$, $10$, $15$, $21$, sempre somando $1$ a mais de fileiras), e o total da pilha é a soma de todos os tamanhos de camada até ali. Como o tamanho de cada camada já cresce sozinho, a pilha inteira cresce ainda mais rápido, um crescimento que acelera duas vezes.**

---

## Ilustrações

- `quadrados_estrutura.svg` / `.png` — as quatro primeiras figuras de quadrados perfeitos ($1\times1$, $2\times2$, $3\times3$, $4\times4$) lado a lado, do Exemplo $1$.
- `quadrados_6x6_resultado.svg` / `.png` — a $6$ª figura, um quadrado $6\times6$ com $36$ fichas, resultado do Exemplo $1$.
- `pilhas_camadas_estrutura.svg` / `.png` — os tamanhos das quatro primeiras camadas triangulares ($1$, $3$, $6$, $10$) e o total acumulado depois de cada uma, do Exemplo $2$.
- `pilha_camada6_resultado.svg` / `.png` — o tamanho da $6$ª camada ($21$ laranjas novas) e o total final da pilha ($56$), resultado do Exemplo $2$.
