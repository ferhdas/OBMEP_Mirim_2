> Trilha Mirim 2 · Caminho 5 · Bloco 5 · Não tem como caber sem repetir. 10 questões autorais, múltipla escolha, mesmo raciocínio do capítulo de teoria.

Exercícios · Não tem como caber sem repetir

**1)** Uma caixa tem lápis de $4$ cores diferentes, muitos de cada cor. Tirando lápis sem olhar, um de cada vez, **quantos são precisos para garantir $2$ da mesma cor?**

[Inserir aqui a figura `q_fig_ex1_enunciado.svg`.]

A) $4$
B) $5$
C) $6$
D) $8$
E) $9$

**2)** Uma caixa tem bolinhas de $4$ cores diferentes, muitas de cada cor. Tirando bolinhas sem olhar, **quantas são precisas para garantir $3$ da mesma cor?**

[Inserir aqui a figura `q_fig_ex2_enunciado.svg`.]

A) $6$
B) $8$
C) $9$
D) $12$
E) $13$

**3)** Numa turma de alunos, cada um faz aniversário num dos $12$ meses do ano. **Quantos alunos são precisos para garantir que pelo menos dois fazem aniversário no mesmo mês?**

[Inserir aqui a figura `q_fig_ex3_enunciado.svg`.]

A) $11$
B) $12$
C) $13$
D) $24$
E) $25$

**4)** Uma loja tem sapatos de $6$ tamanhos diferentes numa caixa de promoção, muitos de cada tamanho. Tirando sapatos sem olhar, **quantos são precisos para garantir $2$ do mesmo tamanho?**

[Inserir aqui a figura `q_fig_ex4_enunciado.svg`.]

A) $6$
B) $7$
C) $5$
D) $12$
E) $13$

**5)** Uma caixa tem lápis de $5$ cores diferentes, muitos de cada cor. Tirando lápis sem olhar, **quantos são precisos para garantir $4$ da mesma cor?**

[Inserir aqui a figura `q_fig_ex5_enunciado.svg`.]

A) $10$
B) $15$
C) $16$
D) $20$
E) $21$

**6)** Numa escola, cada criança torce para um de $8$ times de futebol diferentes. **Quantas crianças são precisas para garantir que pelo menos duas torcem para o mesmo time?**

[Inserir aqui a figura `q_fig_ex6_enunciado.svg`.]

A) $7$
B) $8$
C) $9$
D) $16$
E) $17$

**7)** Um álbum tem figurinhas repetidas de $3$ tipos diferentes à venda num pacote misto, muitas de cada tipo. Comprando figurinhas sem olhar, **quantas são precisas para garantir $2$ do mesmo tipo?**

[Inserir aqui a figura `q_fig_ex7_enunciado.svg`.]

A) $3$
B) $4$
C) $5$
D) $6$
E) $7$

**8)** Uma loja tem camisetas de $3$ tamanhos diferentes numa caixa de promoção, muitas de cada tamanho. Tirando camisetas sem olhar, **quantas são precisas para garantir $5$ do mesmo tamanho?**

[Inserir aqui a figura `q_fig_ex8_enunciado.svg`.]

A) $9$
B) $12$
C) $13$
D) $15$
E) $18$

**9)** Jogamos um dado comum, de $6$ faces, várias vezes seguidas, anotando o resultado de cada jogada. **Quantas jogadas são precisas para garantir que um mesmo resultado saiu duas vezes?**

[Inserir aqui a figura `q_fig_ex9_enunciado.svg`.]

A) $5$
B) $6$
C) $7$
D) $12$
E) $13$

**10)** Uma gaveta tem meias de $8$ cores diferentes, muitas de cada cor. Tirando meias sem olhar, **quantas são precisas para garantir $2$ da mesma cor?**

[Inserir aqui a figura `q_fig_ex10_enunciado.svg`.]

A) $8$
B) $9$
C) $10$
D) $16$
E) $17$

---

**Gabarito**

| Questão | Resposta | Tipo de raciocínio |
|---|---|---|
| $1$ | B | Garantia básica de uma repetição |
| $2$ | C | Mínimo para garantir um número maior de repetições |
| $3$ | C | Reconhecimento de uma gaveta escondida |
| $4$ | B | Garantia básica de uma repetição |
| $5$ | C | Mínimo para garantir um número maior de repetições |
| $6$ | C | Reconhecimento de uma gaveta escondida |
| $7$ | B | Garantia básica de uma repetição |
| $8$ | C | Mínimo para garantir um número maior de repetições |
| $9$ | C | Reconhecimento de uma gaveta escondida |
| $10$ | B | Garantia básica de uma repetição |

---

**Notas rápidas para quem for corrigir**

- Nos exercícios básicos ($1$, $4$, $7$, $10$), a resposta é sempre o número de gavetas mais $1$. O distrator mais comum entrega o próprio número de gavetas, esquecendo que, com esse número, ainda dá para ter um objeto por gaveta sem repetir nenhuma.
- Nos exercícios de mínimo generalizado ($2$, $5$, $8$), a resposta sai de $(k - 1) \times n + 1$, com $n$ gavetas e $k$ repetições a garantir. Todos os valores foram conferidos por código. O distrator mais comum usa $k \times n$ em vez de $(k - 1) \times n + 1$, contando uma rodada a mais do que o pior cenário realmente permite.
- Nos exercícios de gaveta escondida ($3$, $6$, $9$), o primeiro passo é sempre identificar o que faz o papel de gaveta (meses, times, faces do dado) antes de aplicar a régua do $n + 1$. O distrator mais comum aplica a régua ao número errado, confundindo gavetas com objetos.
