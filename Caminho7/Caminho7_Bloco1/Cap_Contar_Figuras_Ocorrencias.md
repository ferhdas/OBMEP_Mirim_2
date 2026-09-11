# Contar sem perder a conta

> Trilha Mirim 2 (4º e 5º anos) · Caminho 7 · Bloco 1 · Contar figuras e ocorrências. Nó da grade: Análise Combinatória › Contagem Direta e Contagem por Posição (ver `Classificacao_Contar_Figuras_Ocorrencias.md`).

Este capítulo é sobre contar sem pular nenhum item e sem contar o mesmo item duas vezes. Às vezes o que se conta é uma figura espalhada numa malha, um triângulo entre vários outros. Às vezes é um símbolo que aparece repetido várias vezes numa figura bagunçada, e a pergunta é qual símbolo aparece mais. E às vezes o que se conta não é uma figura, é um algarismo, escondido dentro de todos os números de uma faixa, algarismo que pode aparecer mais de uma vez dentro do mesmo número. Três formas diferentes de fazer a mesma pergunta, quantas vezes isso aparece, organizam o capítulo.

***Contar figuras direto, sem pular nem repetir***

Quando uma malha ou um mosaico tem muitas figuras pequenas, o jeito mais seguro de contar é escolher um caminho fixo, por exemplo linha por linha, e ir contando cada figura exatamente uma vez, na ordem desse caminho. Contar "de olho", pulando entre partes diferentes do desenho, é a causa mais comum de errar por um a mais ou um a menos.

**Exemplo 1:** O mosaico abaixo é formado por $16$ quadrados, cada um dividido ao meio por uma linha diagonal, formando dois triângulos. **Quantos triângulos brancos há no mosaico?**

[Inserir aqui a figura `mosaico_estrutura.svg`.]

Percorremos o mosaico linha por linha, de cima para baixo, e dentro de cada linha, quadrado por quadrado, da esquerda para a direita. Em cada quadrado, olhamos os dois triângulos e marcamos os que são brancos, sem pular nenhum quadrado e sem contar o mesmo triângulo duas vezes.

Contando dessa forma, a primeira linha tem $3$ triângulos brancos, a segunda tem $4$, a terceira tem $3$, e a quarta tem $2$.

$3+4+3+2=12$

O mosaico tem $12$ triângulos brancos. Conferimos numerando cada triângulo branco na ordem em que foi contado, do primeiro ao último, sem pular nenhum.

[Inserir aqui a figura `mosaico_resultado.svg`.]

**Guarde. Para contar figuras numa malha sem errar, escolha um caminho fixo antes de começar, por exemplo linha por linha, e siga esse caminho até o fim. Contar "de olho", pulando entre partes diferentes da figura, é o jeito mais fácil de contar um item a mais ou esquecer um item.**

***Contar quantas vezes cada símbolo aparece***

Numa figura com vários símbolos espalhados, formas ou letras repetidas em posições diferentes, a pergunta "qual aparece mais vezes" pede contar cada tipo de símbolo separadamente, uma contagem de cada vez, em vez de tentar comparar todos ao mesmo tempo.

**Exemplo 2:** No quadro abaixo há estrelas, corações e luas espalhados. **Qual desses três símbolos aparece mais vezes?**

[Inserir aqui a figura `simbolos_estrutura.svg`.]

Contamos cada símbolo separadamente, percorrendo o quadro inteiro uma vez para cada tipo. Contando as estrelas, encontramos $5$. Contando as luas, encontramos $4$. Contando os corações, encontramos $8$.

$5 \quad 4 \quad 8$

O coração é o símbolo que mais aparece, com $8$ ocorrências. Conferimos numerando cada coração encontrado, do primeiro ao oitavo, sem pular nenhum e sem contar um símbolo de outro tipo por engano.

[Inserir aqui a figura `simbolos_resultado.svg`.]

**Guarde. Quando vários tipos de símbolo estão misturados numa figura, conte um tipo de cada vez, percorrendo a figura inteira para cada contagem. Tentar contar os três tipos ao mesmo tempo, num único percurso pela figura, é o jeito mais fácil de confundir um símbolo com outro.**

***Contar um algarismo escondido dentro dos números de uma faixa***

Quando a pergunta pede quantas vezes um algarismo aparece ao escrever todos os números de uma faixa, é importante lembrar que um mesmo número pode ter esse algarismo mais de uma vez, e a contagem certa soma as ocorrências dentro de cada número, casa por casa, não conta só quantos números contêm o algarismo.

**Exemplo 3:** Beatriz escreveu todos os números de $90$ a $110$, incluindo esses dois. **Quantas vezes ela escreveu o algarismo $0$?**

Separamos a faixa em pedaços, para não perder nenhuma ocorrência. De $90$ a $99$, só o próprio $90$ tem um algarismo $0$, na casa das unidades, então esse pedaço dá $1$ ocorrência.

O número $100$ sozinho já tem dois algarismos $0$, na casa das dezenas e na casa das unidades, então esse número dá $2$ ocorrências.

De $101$ a $109$, todos os nove números têm um algarismo $0$ na casa das dezenas, então esse pedaço dá $9$ ocorrências.

O número $110$ tem um algarismo $0$ na casa das unidades, então esse número dá mais $1$ ocorrência.

$1+2+9+1=13$

Beatriz escreveu o algarismo $0$ um total de $13$ vezes. Conferimos somando os pedaços de novo, o $90$ sozinho, o $100$ que vale por dois, os nove números de $101$ a $109$, e o $110$.

**Guarde. Para contar um algarismo dentro de uma faixa de números, separe a faixa em pedaços onde a contagem fica mais fácil de enxergar, e lembre-se de que um número como $100$ pode contribuir com mais de uma ocorrência do mesmo algarismo, uma para cada casa em que ele aparece.**

**Exemplo 4:** Pedro escreveu todos os números de $20$ a $40$, incluindo esses dois. **Quantas vezes ele escreveu o algarismo $2$?**

De $20$ a $29$, todos os dez números têm um algarismo $2$ na casa das dezenas, o que já dá $10$ ocorrências. Dentro desse mesmo pedaço, o número $22$ tem um segundo algarismo $2$, na casa das unidades, o que soma mais $1$ ocorrência.

$10+1=11$

De $30$ a $39$, nenhum número tem $2$ na casa das dezenas, mas o número $32$ tem um $2$ na casa das unidades, o que dá mais $1$ ocorrência. O número $40$ não tem nenhum algarismo $2$.

$11+1+0=12$

Pedro escreveu o algarismo $2$ um total de $12$ vezes. Conferimos separando de novo os três pedaços, as dez dezenas de $20$ a $29$ mais o $22$ repetido, o $32$ sozinho, e o $40$ sem nenhum $2$.

**Guarde. Numa faixa de números, o algarismo que se repete na casa das dezenas ao longo de dez números seguidos costuma ser a maior fonte de ocorrências. Depois de contar essa parte, procure separadamente os números em que o mesmo algarismo aparece de novo na casa das unidades, para não esquecer essas ocorrências extras.**

---

## Ilustrações

- `mosaico_estrutura.svg` / `.png` — o mosaico $4\times4$ do Exemplo $1$, com os $32$ triângulos coloridos de verde ou deixados em branco, sem numeração.
- `mosaico_resultado.svg` / `.png` — o mesmo mosaico com os $12$ triângulos brancos numerados de $1$ a $12$, na ordem da contagem linha por linha.
- `simbolos_estrutura.svg` / `.png` — o quadro do Exemplo $2$ com as estrelas, os corações e as luas espalhados, sem marcação.
- `simbolos_resultado.svg` / `.png` — o mesmo quadro com os $8$ corações destacados por um círculo pontilhado e numerados de $1$ a $8$.
