# Contar tudo e tirar o proibido

> Trilha Mirim 2 (4º e 5º anos) · Caminho 7 · Bloco 6 · Contar tirando os casos que não valem. Nó da grade: Análise Combinatória › Princípio Multiplicativo da Contagem (ver `Classificacao_Contar_Tirando_Proibido.md`).

Este capítulo é sobre contar um total completo primeiro, e só depois tirar o que uma regra proíbe, ou descobrir o que sobra depois que tudo o mais já foi distribuído. Às vezes o que se tira são categorias inteiras de um produto de escolhas. Às vezes o que se tira são combinações que juntam dois itens que nunca podem aparecer ao mesmo tempo. E às vezes não existe conta de subtração nenhuma, só um inventário cuidadoso do que já foi usado, para achar o que ainda falta.

***Contar o total e tirar categorias inteiras***

Quando um produto de escolhas perde algumas categorias inteiras, o caminho mais seguro é calcular o total sem restrição nenhuma, e depois subtrair, um de cada vez, cada pedaço que deixou de existir.

**Exemplo 1:** Uma fábrica de brinquedos produzia bolas nas cores verde, azul e amarela, e nos tamanhos pequeno, médio e grande, $9$ tipos ao todo. A fábrica parou de produzir a bola verde pequena, e parou de produzir bolas amarelas de qualquer tamanho. **Quantos tipos diferentes de bola a fábrica produz agora?**

[Inserir aqui a figura `bolas_estrutura.svg`.]

O total original, sem nenhuma restrição, é

$3\times3=9$

Desse total, tiramos a bola verde pequena, que é só $1$ tipo, e tiramos as bolas amarelas de todos os tamanhos, que são $3$ tipos.

$9-1-3=5$

A fábrica produz $5$ tipos de bola agora. Conferimos contando direto na tabela, quantas casas continuam válidas depois de marcar a bola verde pequena e a linha inteira das bolas amarelas como fora de produção.

[Inserir aqui a figura `bolas_resultado.svg`.]

**Guarde. Ao tirar categorias de um produto de escolhas, calcule sempre o total sem restrição primeiro. Tirar uma célula única do produto é diferente de tirar uma linha ou coluna inteira, e as duas coisas podem acontecer ao mesmo tempo na mesma questão.**

***Contar combinações e tirar as que juntam dois itens proibidos***

Quando a pergunta pede quantas combinações de $1$ ou mais itens são possíveis, mas proíbe que dois itens específicos apareçam juntos, o total sem restrição é sempre $2^n-1$, onde $n$ é o número de itens disponíveis (excluindo a combinação vazia, sem nenhum item). Desse total, tiram-se as combinações que incluem os dois itens proibidos ao mesmo tempo.

**Exemplo 2:** Beto tem $5$ tipos de queijo para um sanduíche, prato, muçarela, cheddar, gorgonzola e brie. Ele pode usar $1$ ou mais tipos ao mesmo tempo, mas nunca gorgonzola e brie juntos. **Quantos sanduíches diferentes ele pode montar?**

Sem nenhuma restrição, o total de combinações de $1$ ou mais tipos, entre $5$ tipos de queijo, é

$2^5-1=31$

Agora contamos quantas dessas combinações têm gorgonzola e brie juntos. Fixando esses dois queijos como presentes, os outros $3$ queijos podem estar presentes ou não, cada um de forma independente, dando

$2^3=8$

combinações proibidas. Subtraindo,

$31-8=23$

Beto pode montar $23$ sanduíches diferentes. Conferimos separando as combinações proibidas, todas elas têm gorgonzola e brie juntos, mais qualquer combinação dos outros $3$ queijos, $2^3=8$ jeitos.

**Guarde. Quando uma restrição proíbe dois itens específicos juntos, conte primeiro o total de $2^n-1$ combinações não vazias, depois conte as combinações proibidas fixando os dois itens proibidos como presentes e deixando os demais livres, e subtraia.**

***Achar o que sobra por inventário***

Nem toda questão de "contar tirando o proibido" pede uma subtração de números. Às vezes o que se pede é achar exatamente quais itens sobraram depois de uma distribuição, o que se resolve conferindo, item por item, quanto já foi usado.

**Exemplo 3:** Dez adesivos, dois de cada tipo, bola, estrela, coração, lua e sol, foram distribuídos entre Ana, Beto, Carla, Diego e Elis. Ana recebeu bola e coração. Beto recebeu estrela e lua. Carla recebeu coração e sol. Diego recebeu bola e estrela. **Quais adesivos Elis recebeu?**

[Inserir aqui a figura `adesivos_estrutura.svg`.]

Conferimos tipo por tipo quantos adesivos de cada um já foram distribuídos. A bola foi usada por Ana e por Diego, os $2$ que existiam. A estrela foi usada por Beto e por Diego, os $2$ que existiam. O coração foi usado por Ana e por Carla, os $2$ que existiam.

A lua só foi usada uma vez, por Beto, sobrando $1$. O sol só foi usado uma vez, por Carla, sobrando $1$.

$\text{lua e sol}$

Elis recebeu a lua e o sol que sobraram. Conferimos somando tudo, cada um dos cinco tipos aparece exatamente duas vezes ao todo, uma vez para cada uma das cinco pessoas.

[Inserir aqui a figura `adesivos_resultado.svg`.]

**Guarde. Quando a pergunta pede o que sobrou depois de uma distribuição, confira tipo por tipo quantas unidades de cada um já foram usadas. O que sobra para o último grupo é sempre o que ainda não completou sua cota total.**

---

## Ilustrações

- `bolas_estrutura.svg` / `.png` — a tabela de $3$ cores por $3$ tamanhos do Exemplo $1$, com a bola verde pequena e a linha inteira das bolas amarelas marcadas como fora de produção.
- `bolas_resultado.svg` / `.png` — a mesma tabela, com a contagem final de $5$ tipos restantes destacada.
- `adesivos_estrutura.svg` / `.png` — os adesivos recebidos por Ana, Beto, Carla e Diego no Exemplo $3$, com a linha de Elis em branco, marcada com um ponto de interrogação.
- `adesivos_resultado.svg` / `.png` — a mesma distribuição, com a lua e o sol de Elis preenchidos e destacados em verde.
