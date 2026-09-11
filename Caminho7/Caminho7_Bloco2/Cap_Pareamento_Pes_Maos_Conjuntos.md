# Juntar aos pares

> Trilha Mirim 2 (4º e 5º anos) · Caminho 7 · Bloco 2 · Pareamento: pés, mãos e conjuntos. Nó da grade: Análise Combinatória › Contagem Direta e Contagem por Posição (ver `Classificacao_Pareamento_Pes_Maos_Conjuntos.md`).

Este capítulo é sobre juntar itens aos pares e descobrir o que sobra quando o pareamento não fecha perfeitamente. Um pé só forma par com outro pé do mesmo número. Um chinelo esquerdo só forma par com um chinelo direito. Uma mão carimbada revela, pela posição do dedão, se é a mão esquerda ou a direita de quem carimbou. E um conjunto completo, com uma peça de cada tipo, só existe enquanto o tipo mais escasso ainda tiver peças sobrando. Quatro situações diferentes de juntar aos pares organizam este capítulo.

***Pares que precisam do mesmo número***

Quando vários pés soltos, meias ou sapatos, estão misturados, cada um marcado com um número, um par só se forma entre dois itens do **mesmo** número. Itens com números que não se repetem ficam sem par, mesmo que sobrem no monte.

**Exemplo 1:** As meias abaixo estão todas misturadas, cada uma marcada com o número do seu dono. **Quantos pares completos, com o mesmo número, dá para formar?**

[Inserir aqui a figura `meias_estrutura.svg`.]

Contamos quantas vezes cada número aparece. O $32$ aparece $2$ vezes, o $35$ aparece $2$ vezes, o $38$ aparece $2$ vezes, o $40$ aparece $2$ vezes, e o $41$ aparece $2$ vezes.

Como cada número aparece exatamente $2$ vezes, cada um deles forma exatamente $1$ par.

$1+1+1+1+1=5$

Dá para formar $5$ pares completos. Conferimos separando as meias em grupos do mesmo número, um grupo para cada par formado.

[Inserir aqui a figura `meias_resultado.svg`.]

**Guarde. Para formar pares por número, primeiro conte quantas vezes cada número aparece. Um número que aparece uma quantidade ímpar de vezes sempre deixa uma sobra sem par, e um número que aparece só uma vez nunca forma par nenhum.**

***Pares que precisam de lados opostos***

Alguns pares não precisam do mesmo número ou do mesmo tipo, precisam de dois lados que se completam, um esquerdo com um direito. Quando um lado aparece mais vezes que o outro, o excesso do lado mais comum não tem com quem formar par, e cada item desse excesso exige uma pessoa a mais.

**Exemplo 2:** Alguns alunos tiraram os chinelos para a aula de natação. Entre os chinelos soltos, há $6$ chinelos do pé esquerdo e $9$ chinelos do pé direito. **Qual é o menor número de alunos que podem ter participado dessa aula?**

[Inserir aqui a figura `chinelos_estrutura.svg`.]

Cada aluno usa, no máximo, um chinelo esquerdo e um chinelo direito. Formando pares entre os $6$ chinelos esquerdos e $6$ dos $9$ chinelos direitos, sobram

$9-6=3$

chinelos direitos sem par. Cada um desses $3$ chinelos direitos sem par pertence a um aluno diferente, que só tirou o chinelo direito, ou perdeu o esquerdo.

$6+3=9$

O menor número de alunos é $9$, o mesmo que o total de chinelos direitos, porque esse é o lado que mais aparece. Conferimos separando os $6$ pares completos e os $3$ chinelos direitos que sobram, cada um contando como um aluno a mais.

[Inserir aqui a figura `chinelos_resultado.svg`.]

**Guarde. Quando um pareamento é entre dois lados opostos, o menor número de "donos" possível é sempre igual à contagem do lado que mais aparece, nunca a soma dos dois lados. O lado menos numeroso inteiro forma par, e o excesso do lado maior é que decide a resposta.**

***Descobrir a mão pela posição do dedão***

Quando uma mão é carimbada numa folha, a posição do dedão no carimbo revela qual mão foi usada. Um carimbo de mão esquerda tem o dedão do lado direito da figura, e um carimbo de mão direita tem o dedão do lado esquerdo. Saber essa regra transforma a contagem de "mão esquerda ou direita" numa simples contagem de posição.

**Exemplo 3:** Oito crianças carimbaram as mãos numa folha, formando $8$ carimbos dispostos em círculo. **Olhando a folha, $5$ carimbos têm o dedão do lado direito da figura. Quantas vezes a mão esquerda foi carimbada?**

[Inserir aqui a figura `maos_circulo_estrutura.svg`.]

Pela regra, um carimbo com o dedão do lado direito é um carimbo de mão esquerda. Como $5$ carimbos têm essa posição,

$5$

a mão esquerda foi carimbada $5$ vezes. Os outros $3$ carimbos, com o dedão do lado esquerdo, são de mão direita.

$8-5=3$

Conferimos contando os dois grupos juntos, $5$ carimbos de mão esquerda mais $3$ de mão direita, que soma os $8$ carimbos da folha.

[Inserir aqui a figura `maos_circulo_resultado.svg`.]

**Guarde. Antes de contar "quantas vezes a mão esquerda apareceu", confirme qual posição do dedão corresponde a qual mão. Trocar as duas posições é o erro mais comum nesse tipo de questão, e o resultado sai invertido.**

***Quando o total esconde uma pergunta indireta***

Às vezes a pergunta não dá direto quantos carimbos são de cada mão, dá o total de carimbos e uma informação sobre quem carimbou as duas mãos, e pede para descobrir quem esqueceu de carimbar uma delas.

**Exemplo 4:** Numa turma de $10$ crianças, todas carimbaram a mão esquerda numa cartolina. Algumas também carimbaram a mão direita. Ao todo, a cartolina tem $14$ carimbos. **Quantas crianças esqueceram de carimbar a mão direita?**

[Inserir aqui a figura `maos_grade_estrutura.svg`.]

Como todas as $10$ crianças carimbaram a mão esquerda, existem exatamente $10$ carimbos de mão esquerda na cartolina. Os carimbos restantes são todos de mão direita.

$14-10=4$

Existem $4$ carimbos de mão direita, feitos por $4$ crianças que também carimbaram essa mão. As crianças que esqueceram são as que carimbaram só a esquerda.

$10-4=6$

Seis crianças esqueceram de carimbar a mão direita. Conferimos somando os três grupos, $4$ crianças que carimbaram as duas mãos, $6$ que carimbaram só a esquerda, e $14$ carimbos ao todo, $4+4+6=14$.

[Inserir aqui a figura `maos_grade_resultado.svg`.]

**Guarde. Quando o total de carimbos é dado junto com "todas fizeram pelo menos uma mão", ache primeiro quantos carimbos sobram para a outra mão, subtraindo o total de crianças do total de carimbos. Quem esqueceu é a diferença entre o total de crianças e essa sobra.**

***Conjuntos completos, limitados pelo tipo mais escasso***

Para montar um conjunto com uma peça de cada tipo diferente, o número de conjuntos completos nunca passa da quantidade do tipo que existe em menor número. Ter muitas peças dos outros tipos não ajuda, porque cada conjunto sempre precisa de uma peça do tipo mais escasso.

**Exemplo 5:** Numa caixa de material escolar há $9$ lápis, $6$ canetinhas e $8$ borrachas. **Quantos conjuntos completos de $1$ lápis, $1$ canetinha e $1$ borracha dá para formar?**

Comparamos as três quantidades, $9$ lápis, $6$ canetinhas e $8$ borrachas. A canetinha é o tipo mais escasso, com só $6$ unidades.

$9 \quad 6 \quad 8$

Mesmo sobrando lápis e borrachas depois de montar $6$ conjuntos, não há mais nenhuma canetinha para um sétimo conjunto.

$6$

Dá para montar $6$ conjuntos completos. Conferimos vendo o que sobra, $3$ lápis e $2$ borrachas ficam sem usar, mas nenhuma canetinha sobra, confirmando que $6$ é mesmo o máximo.

**Guarde. Num conjunto que precisa de uma peça de cada tipo, o número de conjuntos completos é sempre igual à quantidade do tipo mais escasso, nunca à média ou à soma dos tipos. Sobrar peças dos outros tipos não aumenta a resposta.**

---

## Ilustrações

- `meias_estrutura.svg` / `.png` — dez meias espalhadas, cada uma com um número, sem indicação de quais formam par.
- `meias_resultado.svg` / `.png` — as mesmas dez meias, todas destacadas em verde, confirmando que os cinco números formam cinco pares completos.
- `chinelos_estrutura.svg` / `.png` — os $6$ chinelos esquerdos e $9$ chinelos direitos espalhados, marcados E ou D, sem indicação de pares.
- `chinelos_resultado.svg` / `.png` — os mesmos chinelos, com os $6$ pares completos em azul e laranja e os $3$ chinelos direitos sem par destacados em vermelho como "sobra".
- `maos_circulo_estrutura.svg` / `.png` — os $8$ carimbos de mão dispostos em círculo, sem destaque.
- `maos_circulo_resultado.svg` / `.png` — os mesmos $8$ carimbos, com os $5$ carimbos de dedão à direita (mão esquerda) destacados em verde.
- `maos_grade_estrutura.svg` / `.png` — os $14$ carimbos de mão espalhados numa grade, sem destaque.
- `maos_grade_resultado.svg` / `.png` — os mesmos $14$ carimbos, com os $4$ carimbos de mão direita destacados em verde.
