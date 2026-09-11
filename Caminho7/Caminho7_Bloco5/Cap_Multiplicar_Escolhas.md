# Cada escolha multiplica

> Trilha Mirim 2 (4º e 5º anos) · Caminho 7 · Bloco 5 · Multiplicar as escolhas. Nó da grade: Análise Combinatória › Princípio Multiplicativo da Contagem (ver `Classificacao_Multiplicar_Escolhas.md`).

Este capítulo é sobre contar quantas combinações existem quando duas ou mais escolhas independentes acontecem juntas. Quando cada escolha da primeira categoria pode se combinar com qualquer escolha da segunda, o total de combinações é sempre o produto das duas quantidades. Às vezes, porém, algumas dessas combinações precisam ser tiradas, porque violam uma condição, ou o que interessa não é a combinação em si, mas o resultado que ela produz, que pode se repetir. E às vezes a própria quantidade de escolhas de um lado depende de uma regra, como garantir pelo menos um item de cada tipo em cada grupo.

***Multiplicar escolhas independentes***

Quando uma escolha não interfere na outra, cada opção da primeira categoria pode se combinar com cada opção da segunda, e o total de combinações é o produto das duas quantidades.

**Exemplo 1:** Uma sorveteria tem $5$ sabores de sorvete e $3$ tipos de casquinha. **De quantas maneiras um cliente pode escolher $1$ sabor e $1$ tipo de casquinha?**

[Inserir aqui a figura `sorveteria_estrutura.svg`.]

Cada um dos $5$ sabores pode se combinar com qualquer um dos $3$ tipos de casquinha. Multiplicando as duas quantidades,

$5\times3=15$

há $15$ combinações possíveis. Conferimos organizando as escolhas numa tabela, $5$ linhas de sabores por $3$ colunas de casquinhas, com uma combinação válida em cada uma das $15$ casas.

[Inserir aqui a figura `sorveteria_resultado.svg`.]

**Guarde. Quando duas escolhas são independentes, isto é, a escolha de uma não muda as opções disponíveis da outra, o total de combinações é sempre o produto das duas quantidades, nunca a soma.**

***Multiplicar e depois tirar os casos que não valem***

Às vezes nem toda combinação do produto é válida, porque uma condição extra proíbe algumas delas. Nesses casos, o caminho é multiplicar as duas quantidades normalmente, e depois subtrair as combinações que a condição exclui.

**Exemplo 2:** Marina tem $3$ saias, azul, verde e amarela, e $4$ blusas, azul, verde, amarela e branca. **De quantas maneiras ela pode se vestir com uma saia e uma blusa de cores diferentes?**

[Inserir aqui a figura `roupas_estrutura.svg`.]

Sem nenhuma restrição, o total de combinações entre $3$ saias e $4$ blusas seria

$3\times4=12$

Mas a pergunta proíbe combinações da mesma cor. Como as três cores das saias, azul, verde e amarela, também aparecem entre as blusas, existem $3$ combinações de mesma cor a excluir, saia azul com blusa azul, saia verde com blusa verde, e saia amarela com blusa amarela.

$12-3=9$

Há $9$ maneiras de se vestir com cores diferentes. Conferimos contando direto na tabela de combinações, quantas casas ficam marcadas como válidas depois de excluir as três da mesma cor.

[Inserir aqui a figura `roupas_resultado.svg`.]

**Guarde. Quando uma condição proíbe algumas combinações do produto, calcule primeiro o produto total, sem restrição nenhuma, e só depois subtraia as combinações proibidas. Contar direto só as combinações válidas, sem passar pelo produto total, é mais fácil de errar.**

***Contar resultados diferentes, não escolhas diferentes***

Quando a pergunta pede quantos **resultados** diferentes uma operação pode dar, e não quantas escolhas diferentes existem, é preciso lembrar que escolhas diferentes às vezes produzem o mesmo resultado, e esse resultado só conta uma vez.

**Exemplo 3:** Pedro escolhe dois algarismos diferentes do número $2046$ (os algarismos $2$, $0$, $4$ e $6$) e multiplica os dois. **Quantos resultados diferentes ele pode obter?**

Listamos todos os produtos possíveis, escolhendo dois algarismos diferentes de cada vez.

$2\times0=0 \quad\quad 2\times4=8 \quad\quad 2\times6=12$
$0\times4=0 \quad\quad 0\times6=0 \quad\quad 4\times6=24$

Juntando os seis produtos calculados, $0$, $8$, $12$, $0$, $0$ e $24$, alguns se repetem. O valor $0$ aparece três vezes, porque qualquer algarismo multiplicado por $0$ dá $0$.

$0,\ 8,\ 12,\ 24$

Descontando as repetições, sobram $4$ resultados diferentes, $0$, $8$, $12$ e $24$. Conferimos separando os seis produtos calculados em grupos de valores iguais, três produtos valem $0$, e os outros três, $8$, $12$ e $24$, não se repetem entre si.

**Guarde. Quando a pergunta pede quantos resultados diferentes existem, liste todos os produtos calculados e depois junte os valores repetidos, contando cada valor só uma vez. Um algarismo $0$ no meio das escolhas costuma criar várias repetições, porque qualquer multiplicação por $0$ dá sempre $0$.**

***Quando a quantidade de escolhas também precisa de uma regra***

Às vezes o número de opções de uma das categorias não é dado direto, precisa ser calculado a partir de uma condição, como "pelo menos um item de cada tipo em cada grupo". Nesses casos, primeiro descobrimos de quantos jeitos cada tipo pode se dividir respeitando a condição, e só depois multiplicamos as duas contagens.

**Exemplo 4:** Lucas tem $2$ caixas diferentes, $5$ bolinhas de gude iguais e $3$ botões iguais. **De quantas maneiras ele pode distribuir essas peças nas duas caixas, de modo que haja pelo menos uma peça de cada tipo em cada caixa?**

Para as $5$ bolinhas de gude, a primeira caixa pode receber $1$, $2$, $3$ ou $4$ delas, sempre deixando pelo menos uma para a segunda caixa. São $4$ jeitos possíveis.

Para os $3$ botões, a primeira caixa pode receber $1$ ou $2$ deles, sempre deixando pelo menos um para a segunda caixa. São $2$ jeitos possíveis.

$4\times2=8$

Como a divisão das bolinhas e a divisão dos botões são escolhas independentes, multiplicamos as duas contagens, chegando a $8$ maneiras diferentes. Conferimos testando um caso, por exemplo $3$ bolinhas e $1$ botão na primeira caixa, e $2$ bolinhas e $2$ botões na segunda, que respeita a condição de ter pelo menos uma peça de cada tipo nas duas caixas.

**Guarde. Quando uma quantidade de $n$ itens iguais precisa ser dividida em dois grupos com pelo menos um item em cada grupo, existem $n-1$ jeitos de fazer essa divisão, porque a primeira parte pode variar de $1$ até $n-1$. Ache esse número para cada tipo de item antes de multiplicar.**

---

## Ilustrações

- `sorveteria_estrutura.svg` / `.png` — a tabela de $5$ sabores por $3$ tipos de casquinha do Exemplo $1$, todas as $15$ casas marcadas como combinações válidas, sem contagem ainda.
- `sorveteria_resultado.svg` / `.png` — a mesma tabela, com a contagem final de $15$ combinações válidas destacada.
- `roupas_estrutura.svg` / `.png` — a tabela de $3$ saias por $4$ blusas do Exemplo $2$, com as $3$ combinações da mesma cor marcadas como inválidas.
- `roupas_resultado.svg` / `.png` — a mesma tabela, com a contagem final de $9$ combinações válidas destacada.
