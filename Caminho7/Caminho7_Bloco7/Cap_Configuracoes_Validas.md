# Quantos jeitos respeitam a regra

> Trilha Mirim 2 (4º e 5º anos) · Caminho 7 · Bloco 7 · Contar configurações válidas. Nó da grade: Análise Combinatória › Princípio Multiplicativo da Contagem (ver `Classificacao_Configuracoes_Validas.md`).

Este capítulo é sobre contar, entre várias possibilidades, quantas respeitam uma regra dada. Numa brincadeira de par ou ímpar, nem toda quantidade de dedos vale, só as que têm a paridade certa. Num quadriculado que precisa ter números diferentes em cada linha e em cada coluna, nem todo preenchimento vale, só os que respeitam essa regra em todas as direções ao mesmo tempo. Uma coisa interessante aparece nos dois casos, o número de jeitos válidos não depende dos detalhes exatos da situação, ele é sempre o mesmo, contanto que a estrutura do problema seja a mesma.

***Contar quantos valores têm a paridade certa***

Numa brincadeira de par ou ímpar, quem ganha depende da soma dos dedos mostrados pelas duas pessoas ter a paridade certa, par ou ímpar. Para contar de quantas maneiras uma pessoa pode ganhar, o caminho é descobrir que paridade ela precisa mostrar, e depois contar quantos valores possíveis têm essa paridade.

**Exemplo 1:** Duda e Ana brincam de par ou ímpar, cada uma mostrando uma mão. Duda escolheu ímpar, o que quer dizer que ela ganha se a soma total for ímpar, e Ana ganha se a soma for par. Duda mostrou a mão com $3$ dedos levantados. **De quantas maneiras Ana pode mostrar a mão e ganhar?**

[Inserir aqui a figura `mao_3dedos_estrutura.svg`.]

Para Ana ganhar, a soma dos dedos das duas precisa ser par. Como Duda mostrou $3$, um número ímpar, Ana precisa mostrar também um número ímpar, porque ímpar mais ímpar dá par.

Uma mão pode mostrar $0$, $1$, $2$, $3$, $4$ ou $5$ dedos. Entre esses seis valores, os ímpares são $1$, $3$ e $5$.

$1,\ 3,\ 5$

Ana tem $3$ maneiras de ganhar. Conferimos testando cada uma, $3+1=4$, $3+3=6$ e $3+5=8$, as três somas dando par.

[Inserir aqui a figura `mao_3dedos_resultado.svg`.]

**Guarde. Numa mão só, de $0$ a $5$ dedos, existem sempre $3$ valores pares ($0$, $2$, $4$) e $3$ valores ímpares ($1$, $3$, $5$). Por isso, não importa o que a primeira pessoa mostrou nem qual paridade ela escolheu, a segunda pessoa sempre tem exatamente $3$ maneiras de ganhar. Esse número muda se a brincadeira usar as duas mãos, de $0$ a $10$ dedos, porque aí os pares e os ímpares não ficam mais em quantidades iguais.**

***Contar quantos preenchimentos respeitam linhas e colunas***

Num quadriculado que precisa ter números diferentes em cada linha e em cada coluna, algumas casas já vêm preenchidas, e a pergunta pede de quantas maneiras dá para terminar de preencher o resto. O caminho mais seguro é testar as possibilidades passo a passo, linha por linha, eliminando a cada passo o que já não é mais possível.

**Exemplo 2:** Um quadriculado $3\times3$ deve ser preenchido com os números $1$, $2$ e $3$, de modo que cada linha e cada coluna tenham os três números diferentes. Uma casa já foi preenchida, a da segunda linha com a segunda coluna, com o número $2$. **De quantas maneiras diferentes dá para terminar de preencher o quadriculado?**

[Inserir aqui a figura `quadriculado_estrutura.svg`.]

Testamos as possibilidades por partes. A primeira linha pode ser preenchida de várias formas, mas como a casa central da segunda linha já é $2$, a primeira linha não pode ter $2$ na coluna do meio.

Seguindo esse raciocínio linha por linha, e testando cada escolha contra as que já foram feitas, encontramos exatamente $4$ preenchimentos diferentes que respeitam a regra em todas as linhas e colunas ao mesmo tempo.

$4$

Existem $4$ maneiras diferentes de terminar o quadriculado. Conferimos olhando os quatro preenchimentos encontrados, um por um, checando que cada linha e cada coluna realmente têm os três números diferentes.

[Inserir aqui a figura `quadriculado_resultado.svg`.]

**Guarde. Num quadriculado $3\times3$ com os números $1$, $2$ e $3$, não importa qual casa já vem preenchida nem qual número está nela, sempre existem exatamente $4$ maneiras de terminar o preenchimento respeitando linhas e colunas diferentes. Essa contagem não muda com a posição nem com o valor da casa já dada.**

---

## Ilustrações

- `mao_3dedos_estrutura.svg` / `.png` — a mão de Duda do Exemplo $1$, mostrando $3$ dedos levantados.
- `mao_3dedos_resultado.svg` / `.png` — as três mãos que Ana pode mostrar para ganhar, com $1$, $3$ e $5$ dedos levantados.
- `quadriculado_estrutura.svg` / `.png` — o quadriculado $3\times3$ do Exemplo $2$, com a casa central da segunda linha já preenchida com o número $2$.
- `quadriculado_resultado.svg` / `.png` — os quatro preenchimentos válidos do quadriculado, lado a lado.
