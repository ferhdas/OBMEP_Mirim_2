# Descobrir quem cai em cada lugar

> Trilha Mirim 2 (4º e 5º anos) · Caminho 8 · Bloco 3 · Achar pela posição: ciclos e grades. Nó da grade: Raciocínio Lógico › Sequências e Padrões Numéricos (ver `Classificacao_Achar_Pela_Posicao.md`).

Este capítulo é sobre descobrir o que cai numa posição específica, sem precisar desenhar ou listar tudo até lá. Duas situações aparecem bastante, um padrão que se repete de tanto em tanto (um ciclo), e uma tabela preenchida em ordem, linha por linha (uma grade). Nos dois casos, existe uma regra fixa que liga a posição ao que está nela, e essa regra é o único jeito seguro de responder sobre uma posição distante.

***Achar a posição dentro de um ciclo que se repete***

Quando um padrão se repete sempre do mesmo jeito, de tanto em tanto, cada posição da fila corresponde a uma posição dentro de um único ciclo. Para descobrir qual, o caminho mais seguro é contar quantos ciclos completos já passaram até ali.

**Exemplo 1:** Beatriz enfileira contas coloridas, sempre repetindo o mesmo padrão de $5$ cores, na ordem azul, verde, amarelo, vermelho, roxo, e recomeçando do azul depois do roxo. A $35$ª conta da fileira é roxa, exatamente o fim de um ciclo completo. **Quais são as cores da $36$ª, da $37$ª e da $38$ª conta?**

[Inserir aqui a figura `ciclo_estrutura.svg`.]

Como a $35$ª conta termina um ciclo completo ($35=5\times7$, ou seja, $7$ ciclos completos de $5$ cores), a $36$ª conta começa um novo ciclo, do zero, com a cor azul.

$36\text{ª}=\text{azul} \quad\quad 37\text{ª}=\text{verde} \quad\quad 38\text{ª}=\text{amarelo}$

A $36$ª conta é azul, a $37$ª é verde, e a $38$ª é amarela. Conferimos contando as $5$ cores do início do novo ciclo, azul ($36$ª), verde ($37$ª), amarelo ($38$ª), exatamente as três primeiras cores do padrão.

[Inserir aqui a figura `ciclo_resultado.svg`.]

**Guarde. Quando uma posição é um múltiplo exato do tamanho do ciclo, ela fecha um ciclo completo, e a posição seguinte sempre recomeça do início do padrão. Para posições que não fecham um ciclo exato, o caminho é dividir a posição pelo tamanho do ciclo e usar o resto da divisão para achar a posição correspondente dentro de um único ciclo.**

***Achar um número dentro de uma grade preenchida em ordem***

Numa tabela preenchida em ordem crescente, da esquerda para a direita e de cima para baixo, cada linha nova começa exatamente onde a linha anterior terminou. Descer uma linha, na mesma coluna, sempre soma a mesma quantidade, o número de colunas da tabela. Andar uma casa para a direita, na mesma linha, sempre soma $1$.

**Exemplo 2:** Uma tabela é preenchida em ordem crescente, começando em $1$ no canto superior esquerdo, com $6$ números em cada linha. **Que número fica na $5$ª linha, $4$ª coluna?**

[Inserir aqui a figura `grade_estrutura.svg`.]

A $5$ª linha começa logo depois do último número da $4$ª linha. Como cada linha tem $6$ números, a $4$ª linha termina em $4\times6=24$, então a $5$ª linha começa em $25$.

$4\times6=24 \quad\quad 24+1=25$

Andando mais $3$ casas para a direita, da $1$ª coluna até a $4$ª coluna da $5$ª linha, somamos mais $3$.

$25+3=28$

O número da $5$ª linha, $4$ª coluna, é $28$. Conferimos pela fórmula direta, o número de uma linha $l$ e coluna $c$, numa tabela com $6$ colunas, é $(l-1)\times6+c$, e $(5-1)\times6+4=24+4=28$.

[Inserir aqui a figura `grade_resultado.svg`.]

**Guarde. Numa grade preenchida em ordem, o número de qualquer casa se calcula sem precisar contar todas as casas anteriores, descer uma linha soma o número de colunas da tabela, e andar para o lado soma $1$. Combinando os dois movimentos a partir do canto onde a tabela começa, chega-se a qualquer casa, mesmo uma bem distante.**

---

## Ilustrações

- `ciclo_estrutura.svg` / `.png` — as contas da posição $31$ até a $35$ da fileira de Beatriz, mostrando o fim de um ciclo completo, do Exemplo $1$.
- `ciclo_resultado.svg` / `.png` — as três contas seguintes, $36$ª, $37$ª e $38$ª, com suas cores, resultado do Exemplo $1$.
- `grade_estrutura.svg` / `.png` — a tabela de $5$ linhas por $6$ colunas do Exemplo $2$, com a casa da $5$ª linha e $4$ª coluna marcada com "?".
- `grade_resultado.svg` / `.png` — a mesma tabela, com a casa da $5$ª linha e $4$ª coluna preenchida com o número $28$, resultado do Exemplo $2$.
