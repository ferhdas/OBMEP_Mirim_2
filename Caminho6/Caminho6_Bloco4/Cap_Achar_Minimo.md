# O menor número de vezes

> Trilha Mirim 2 (4º e 5º anos) · Caminho 6 · Bloco 4 · Achar o mínimo. Nó da grade: Raciocínio Lógico › Problemas de Otimização e Estratégia de Mínimos/Máximos (ver `Classificacao_Achar_Minimo.md`).

Este capítulo é sobre achar o menor número de vezes que algo precisa acontecer para resolver um problema. Às vezes é o menor número de viagens que um transporte precisa fazer, respeitando um limite de peso. Às vezes é o menor número de cadeados que alguém precisa abrir para completar um pedido. Às vezes é o menor número de movimentos que peças de um tabuleiro precisam fazer até se organizarem do jeito pedido. E às vezes é o menor número de contas que precisam sair de um cordão para libertar tudo que estava preso nele. Em todos os casos, a estratégia é a mesma, calcular um limite que não dá para escapar, e depois conferir se esse limite realmente pode ser alcançado.

***Quantas viagens cabem dentro do limite de peso***

Quando um transporte tem um peso máximo por viagem, o primeiro passo é somar o peso de tudo que precisa ser levado e dividir pelo limite de cada viagem. Esse cálculo dá um limite que não dá para escapar, porque nenhuma quantidade menor de viagens consegue levar tanto peso. Mas esse limite só vale de verdade se der para separar as pessoas ou os objetos em grupos que respeitem o peso máximo, e por isso o segundo passo é sempre testar se uma divisão assim existe.

**Exemplo 1:** Um barco aguenta no máximo $200$ quilos por viagem. Cinco amigos, pesando $45$, $50$, $55$, $60$ e $65$ quilos, precisam atravessar um rio. **Qual é o menor número de viagens que o barco deve fazer?**

Somamos o peso de todo mundo.

$45+50+55+60+65=275$

Dividindo esse total pelo limite de $200$ quilos, $275 \div 200$ dá $1$ com resto, então uma viagem não é suficiente, e o menor número possível de viagens é $2$.

Para confirmar que $2$ viagens realmente bastam, procuramos um jeito de separar os cinco amigos em dois grupos que não passem de $200$ quilos cada. Colocando os três mais pesados numa viagem,

$65+60+55=180$

e os dois mais leves na outra,

$50+45=95$

as duas viagens ficam dentro do limite. O menor número de viagens é $2$.

**Guarde. Somar o peso total e dividir pelo limite dá um número que nenhuma quantidade menor de viagens consegue vencer. Mas esse número só é a resposta se existir mesmo um jeito de separar as pessoas ou os objetos em grupos dentro do limite. Quando dois itens já passam do limite sozinhos, pode ser preciso mais viagens do que essa primeira conta sugere.**

***Quantos cadeados até completar o pedido***

Quando um pedido está guardado atrás de várias camadas trancadas, sala, armário, caixa, o menor número de cadeados não é abrir tudo, é abrir só o necessário para juntar a quantidade pedida. A estratégia é calcular quantas caixas, no mínimo, dão conta do pedido, e depois contar os cadeados de cada camada que precisa ser aberta para chegar até essas caixas.

**Exemplo 2:** Num depósito há uma prateleira trancada, e atrás dela há $2$ baús, também trancados. Em cada baú há $3$ caixas trancadas, e em cada caixa há $8$ bombons. Alguém precisa pegar $30$ bombons. **Qual é o menor número de cadeados que essa pessoa precisa abrir?**

Cada caixa tem $8$ bombons. Para juntar $30$ bombons, calculamos quantas caixas são necessárias, sabendo que $3$ caixas dão $24$ bombons, ainda não é suficiente, e $4$ caixas dão $32$ bombons, já é suficiente.

$3\times8=24 \quad\quad 4\times8=32$

São precisas $4$ caixas, no mínimo. Só que cada baú tem só $3$ caixas, então $4$ caixas não cabem dentro de um único baú, é preciso abrir os dois baús, $3$ caixas de um e $1$ caixa do outro.

Contamos os cadeados, a prateleira, os dois baús, e as $4$ caixas.

$1+1+1+3+1=7$

O menor número de cadeados é $7$. Conferimos separando cada camada, $1$ prateleira, $2$ baús e $4$ caixas, que juntos somam $7$ cadeados abertos.

**Guarde. Primeiro calcule o menor número de caixas que dá conta do pedido, testando quantas caixas já bastam. Depois conte os cadeados de cada camada que precisa abrir para alcançar essas caixas, sem esquecer que quando as caixas necessárias não cabem numa única camada, é preciso abrir mais de uma.**

***Quantos movimentos até equilibrar linhas e colunas***

Num tabuleiro com peças espalhadas de forma desigual entre as linhas e as colunas, mover uma peça para uma casa vizinha livre muda ao mesmo tempo a contagem da linha e da coluna de onde ela saiu e da linha e da coluna para onde ela foi. Para descobrir o menor número de movimentos, o caminho mais seguro é testar primeiro se um único movimento resolve tudo, e só concluir que são precisos mais movimentos depois de conferir que nenhum movimento único funciona.

**Exemplo 3:** No tabuleiro $4\times4$ abaixo há $8$ peças. Cláudia quer que cada linha e cada coluna fiquem com exatamente $2$ peças. **Qual é o menor número de movimentos, para uma casa vizinha livre, que ela precisa fazer?**

[Inserir aqui a figura `tabuleiro_pecas_estrutura.svg`.]

Contando as peças por linha, a linha $1$ tem $3$, a linha $2$ tem $1$, a linha $3$ tem $3$ e a linha $4$ tem $1$. As colunas já estão certas, com $2$ peças cada uma.

Como as linhas $1$ e $3$ têm uma peça a mais, e as linhas $2$ e $4$ têm uma peça a mais, um único movimento não resolve os dois problemas ao mesmo tempo, porque cada movimento só tira uma peça de uma linha e põe numa outra. São precisos pelo menos $2$ movimentos, um para acertar a primeira dupla de linhas, outro para acertar a segunda.

Movendo uma peça da linha $1$ para a linha $2$, na mesma coluna que ela já estava, a linha $1$ fica com $2$ e a linha $2$ fica com $2$, sem mexer em nenhuma coluna. Movendo outra peça da linha $3$ para a linha $4$, também na mesma coluna, a linha $3$ fica com $2$ e a linha $4$ fica com $2$.

$1+1=2$

O menor número de movimentos é $2$. Conferimos contando de novo, cada linha e cada coluna do tabuleiro final têm exatamente $2$ peças.

[Inserir aqui a figura `tabuleiro_pecas_resultado.svg`.]

**Guarde. Antes de testar movimentos, conte quantas peças cada linha e cada coluna já têm. Quando duas linhas ou colunas diferentes precisam de ajuste ao mesmo tempo, geralmente é preciso um movimento para cada uma, porque um único movimento só consegue corrigir uma linha e uma coluna por vez, movendo a peça dentro da mesma coluna ou da mesma linha para não estragar o que já estava certo.**

***Quantas bolinhas ficam presas entre duas estrelas***

Num cordão com bolinhas e algumas estrelas presas, tirar as bolinhas e as estrelas só é possível pelas duas pontas do cordão, puxando de um lado ou do outro. Para tirar todas as estrelas gastando o menor número possível de bolinhas, a estratégia é deixar sem tirar só o maior trecho de bolinhas que existe entre duas partes já retiradas, seja esse trecho antes da primeira estrela, entre duas estrelas, ou depois da última.

**Exemplo 4:** Um colar tem bolinhas e $3$ estrelas presas no cordão. Da ponta esquerda até a primeira estrela há $2$ bolinhas. Entre a primeira e a segunda estrela há $5$ bolinhas. Entre a segunda e a terceira estrela há $1$ bolinha. Da terceira estrela até a ponta direita há $3$ bolinhas. **Qual é o menor número de bolinhas que precisam ser retiradas para tirar as três estrelas?**

Somamos todas as bolinhas do colar.

$2+5+1+3=11$

Agora comparamos os quatro trechos de bolinhas, o de antes da primeira estrela, os dois entre estrelas, e o de depois da última, $2$, $5$, $1$ e $3$. O maior deles é o trecho de $5$ bolinhas, entre a primeira e a segunda estrela.

Esse é o único trecho que pode ficar sem ser tirado. Para isso, puxamos pela ponta esquerda até passar da primeira estrela, e puxamos pela ponta direita até passar da terceira estrela, deixando só o trecho do meio intocado.

$11-5=6$

O menor número de bolinhas a retirar é $6$. Conferimos contando o que sobra no cordão, as $5$ bolinhas do trecho do meio, exatamente o trecho que decidimos não tirar.

**Guarde. Compare todos os trechos de bolinhas do colar, o de antes da primeira estrela, os de entre cada par de estrelas vizinhas, e o de depois da última, não só os trechos do meio. O maior desses trechos é o único que pode ficar sem ser retirado, e a resposta é o total de bolinhas menos esse maior trecho.**

---

## Ilustrações

- `tabuleiro_pecas_estrutura.svg` / `.png` — um tabuleiro $4\times4$ com $8$ peças nas posições descritas no Exemplo $3$, sem nenhum movimento feito ainda.
- `tabuleiro_pecas_resultado.svg` / `.png` — o mesmo tabuleiro depois dos $2$ movimentos, com as duas peças que se moveram destacadas em verde e cada linha e coluna mostrando exatamente $2$ peças.
