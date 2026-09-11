# Padrões nos números e no calendário

> Trilha Mirim 2 (4º e 5º anos) · Caminho 8 · Bloco 4 · Regularidades de algarismos e datas. Nó da grade: Aritmética › Problemas com Algarismos e Criptografia Aritmética (ver `Classificacao_Regularidades_Algarismos_Datas.md`).

Este capítulo é sobre regularidades escondidas dentro dos próprios números, não em figuras que crescem, mas nos algarismos que formam um ano, ou numa data inteira. Duas ideias aparecem aqui, a soma dos algarismos de um número muda de um jeito previsível de ano para ano, e alguns números, olhados como uma sequência de algarismos, são iguais lidos da esquerda para a direita ou da direita para a esquerda.

***Quando a soma dos algarismos volta a se repetir***

A soma dos algarismos de um ano muda a cada ano que passa, mas não sempre do mesmo jeito. Na maioria das vezes, passar para o ano seguinte soma $1$ à soma dos algarismos, porque só o último algarismo aumenta $1$. Mas quando o último algarismo era $9$ e vira $0$, a soma dos algarismos pode cair bastante, porque um novo algarismo do meio também muda.

**Exemplo 1:** A soma dos algarismos do ano $2013$ é $2+0+1+3=6$. **Depois de quantos anos a soma dos algarismos volta a ser $6$ de novo?**

[Inserir aqui a figura `soma_estrutura.svg`.]

Calculamos a soma dos algarismos de cada ano seguinte, um por um. De $2013$ até $2019$, o último algarismo sobe de $3$ até $9$, e a soma sobe junto, de $6$ até $12$. Em $2020$, o último algarismo volta a $0$ e o algarismo das dezenas sobe de $1$ para $2$, então a soma cai bastante, para $2+0+2+0=4$. Continuando, $2021$ tem soma $5$, e $2022$ tem soma $2+0+2+2=6$.

$2022-2013=9$

A soma dos algarismos volta a ser $6$ depois de $9$ anos, em $2022$. Conferimos contando os anos de $2013$ a $2022$, um por um, $9$ anos se passaram.

[Inserir aqui a figura `soma_resultado.svg`.]

**Guarde. A soma dos algarismos de um ano sobe $1$ a cada ano, até o último algarismo chegar a $9$. No ano seguinte, o último algarismo volta a $0$ e o algarismo das dezenas sobe $1$, o que derruba a soma. Para a maioria dos anos de um século, esse ciclo de subida e queda faz a mesma soma voltar a aparecer depois de $9$ anos, mas vale a pena conferir cada caso contando ano por ano, porque perto da virada de um século o padrão pode mudar.**

***Quando uma data é igual lida dos dois lados***

Juntando o dia, o mês e o ano de uma data, um após o outro, forma-se uma sequência de algarismos. Algumas datas são especiais porque essa sequência é igual lida da esquerda para a direita ou da direita para a esquerda, um padrão chamado de palíndromo.

**Exemplo 2:** A data $17/02/2071$ é especial, porque juntando o dia, o mês e o ano, $17022071$, essa sequência de $8$ algarismos é igual lida dos dois lados. **Entre as datas $19/03/3091$, $31/03/3014$ e $12/12/2112$, qual também tem essa propriedade?**

[Inserir aqui a figura `data_espelho_dada.svg`.]

Testamos cada data, juntando dia, mês e ano, e comparando com a sequência invertida.

$19/03/3091 \to 19033091$, invertida $19033091$, igual.

$31/03/3014 \to 31033014$, invertida $41033013$, diferente.

$12/12/2112 \to 12122112$, invertida $21122121$, diferente.

Só a data $19/03/3091$ tem a sequência de algarismos igual dos dois lados. Conferimos comparando algarismo por algarismo, da ponta para o centro, o $1$º com o $8$º, o $2$º com o $7$º, o $3$º com o $6$º, e o $4$º com o $5$º, todos batendo.

[Inserir aqui a figura `data_espelho_resultado.svg`.]

**Guarde. Para saber se uma data é igual lida dos dois lados, junte o dia, o mês e o ano numa única sequência de algarismos, e compare cada algarismo com o algarismo que fica na mesma distância da outra ponta. Todos precisam bater, não só os das pontas.**

---

## Ilustrações

- `soma_estrutura.svg` / `.png` — os anos de $2013$ a $2022$ com a soma dos algarismos de cada um, do Exemplo $1$.
- `soma_resultado.svg` / `.png` — a mesma faixa de anos, com $2013$ e $2022$ destacados, ambos com soma $6$, resultado do Exemplo $1$.
- `data_espelho_dada.svg` / `.png` — os $8$ algarismos da data $17/02/2071$, mostrando que são iguais lidos dos dois lados, do Exemplo $2$.
- `data_espelho_resultado.svg` / `.png` — os $8$ algarismos da data $19/03/3091$, mostrando que também são iguais lidos dos dois lados, resultado do Exemplo $2$.
