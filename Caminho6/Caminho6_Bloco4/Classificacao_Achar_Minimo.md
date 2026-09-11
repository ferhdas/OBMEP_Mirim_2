Ficha de classificação · Bloco $4$ · Achar o mínimo

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as quatro questões de referência do bloco: `2020/Q5` (código `NA20-Q05`), `2020/Q7` (código `NA20-Q07`), `2020/Q11` (código `NA20-Q11`) e `2024/F2/Q7` (código `M2-24-F2-Q07`).

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Achar o menor número de repetições de uma ação, viagem, abertura de cadeado, movimento de peça ou remoção de bolinha, que resolve um problema com uma restrição fixa. O bloco reúne quatro variações do mesmo cuidado, calcular primeiro um limite que nenhuma quantidade menor consegue vencer, e só depois confirmar que esse limite é mesmo alcançável: (a) o menor número de viagens de um transporte com peso máximo, (b) o menor número de cadeados abertos para reunir uma quantidade pedida guardada em camadas trancadas, (c) o menor número de movimentos de peças num tabuleiro até equilibrar linhas e colunas, e (d) o menor número de bolinhas retiradas de um cordão para libertar todas as estrelas presas nele.

**Nó principal (Apêndice D, grade oficial).** `Raciocínio Lógico › Problemas de Otimização e Estratégia de Mínimos/Máximos`. É o nó que cobre diretamente as quatro variações, porque em todas elas a pergunta é sempre pelo menor número de repetições de uma ação sob uma restrição, nunca pela quantidade de jeitos diferentes de fazer algo.

**Descritores secundários.**
- Limite por divisão com resto: quando um total precisa ser repartido em partes que não passam de um valor máximo, dividir o total pelo máximo e arredondar para cima dá um limite que nenhuma quantidade menor de partes consegue vencer, o mesmo raciocínio usado nos blocos de contagem por intervalos, aqui aplicado a peso ou a quantidade de itens.
- Verificação de alcançabilidade: o limite calculado por divisão só vira resposta depois de se confirmar que existe mesmo uma separação válida dentro dele. Quando dois itens já ultrapassam o limite sozinhos, o número de viagens ou de grupos pode ter que ser maior do que a divisão sugere.
- Camadas trancadas em cascata: um pedido guardado atrás de várias camadas de cadeado exige abrir cada camada até alcançar as unidades menores, e quando as unidades necessárias não cabem numa única camada intermediária, mais de uma camada precisa ser aberta.
- Correção de linha e coluna por movimento único: mover uma peça de tabuleiro muda a contagem de uma linha e de uma coluna ao mesmo tempo, e cada movimento só resolve um desequilíbrio de cada vez, o que ajuda a estimar quantos movimentos, no mínimo, são necessários antes de testar arranjos.
- Maior trecho preservável entre dois pontos fixos: numa sequência de itens presa por dois pontos que só podem ser acessados pelas pontas, o maior trecho contínuo entre dois desses pontos fixos, incluindo os trechos das pontas até o primeiro e o último ponto, é o único que pode ficar intocado.

**Não é X (e por quê).**
- Não é Contagem e Combinatória, porque nenhuma variação pergunta de quantos jeitos diferentes algo pode ser feito. A pergunta é sempre pelo menor número de repetições de uma mesma ação, um valor único, não uma contagem de possibilidades.
- Não é o Bloco $1$ deste Caminho, porque ali o objetivo é descobrir um número escondido a partir de pistas, e aqui o número buscado não está escondido, ele é o resultado de uma otimização sob uma restrição declarada.
- Não é Grandezas e Medidas como nó principal, mesmo quando a variação (a) envolve peso em quilos. A unidade de medida é só o contexto da restrição, o que resolve a questão é achar o menor número de viagens, não calcular ou converter uma grandeza.
- Não é Percepção Espacial no Plano (Caminho $4$), mesmo quando a variação (c) usa um tabuleiro. O que importa não é a posição visual das peças, é a contagem de quantas peças há em cada linha e coluna, e quantos movimentos corrigem esse desequilíbrio.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 6** › **Bloco 4 · Achar o mínimo** › capítulo de teoria "O menor número de vezes" (`Cap_Achar_Minimo.md`).

---

***Notas específicas de cada questão de referência***

`2020/Q5` (código `NA20-Q05`)
- **Motor aplicado:** variação (a), menor número de viagens com limite de peso. Seis pessoas, pesando $50$, $55$, $60$, $65$, $70$ e $75$ quilos, precisam subir num elevador que aguenta no máximo $180$ quilos por viagem. A soma dos pesos é $375$ quilos, e como $2\times180=360$ é menor que $375$, duas viagens são impossíveis. Com três viagens, é possível separar as seis pessoas em três duplas dentro do limite. Gabarito **B ($3$)** ✅, conferido contra a solução oficial (`sf1na-2020.pdf`, questão $5$).
- **Não é X específico:** não basta calcular $375\div180$ e arredondar, é preciso confirmar que $3$ viagens realmente permitem separar as seis pessoas em grupos dentro do limite, o que a solução oficial faz explicitamente.

`2020/Q7` (código `NA20-Q07`)
- **Motor aplicado:** variação (b), menor número de cadeados em camadas trancadas. Uma sala com $3$ armários, cada um com $4$ caixas de $10$ celulares, precisa fornecer $52$ celulares. São necessárias $6$ caixas, no mínimo ($5$ caixas dão $50$, ainda insuficiente, $6$ caixas dão $60$). Como cada armário só tem $4$ caixas, as $6$ caixas exigem abrir dois armários, $4$ caixas de um e $2$ do outro. Cadeados: a sala, os dois armários e as $6$ caixas, $1+1+4+1+2=9$. Gabarito **E ($9$)** ✅, conferido contra a solução oficial (`sf1na-2020.pdf`, questão $7$).
- **Não é X específico:** não é preciso abrir o terceiro armário, porque as $6$ caixas necessárias já cabem em dois armários juntos, abrir o terceiro seria desperdiçar cadeados.

`2020/Q11` (código `NA20-Q11`)
- **Motor aplicado:** variação (c), menor número de movimentos para equilibrar linhas e colunas. Um tabuleiro $4\times4$ tem $8$ peças distribuídas de forma desigual entre as linhas, e Cláudio quer exatamente $2$ peças por linha e por coluna. Testando um único movimento, nenhuma combinação resolve o desequilíbrio das linhas sem estragar as colunas, então um movimento não basta. Com dois movimentos, uma peça de cada linha cheia demais se move para a linha vizinha que precisa, mantendo a coluna. Gabarito **C ($2$)** ✅, conferido contra a solução oficial (`sf1na-2020.pdf`, questão $11$).
- **Não é X específico:** não é uma questão sobre qual arranjo final é possível, é sobre o menor número de passos para chegar a um arranjo válido a partir do arranjo dado.

`2024/F2/Q7` (código `M2-24-F2-Q07`)
- **Motor aplicado:** variação (d), maior trecho preservável entre pontos fixos. Um colar com $10$ bolinhas e algumas estrelas só permite retirar itens pelas pontas do cordão. Puxando só pela esquerda, são $8$ bolinhas retiradas. Só pela direita, são $9$. Pelos dois lados ao mesmo tempo, sobra sem retirar o maior trecho entre duas estrelas, que tem $3$ bolinhas, e por isso $10-3=7$ bolinhas precisam sair. Gabarito **B ($7$)** ✅, conferido contra a solução oficial (`sf2m2-2024.pdf`, questão $7$).
- **Não é X específico:** não é preciso cortar o cordão nem retirar as bolinhas em qualquer ordem, elas só podem sair pelas pontas, o que faz o trecho preservado ser sempre um único trecho contínuo, nunca pedaços espalhados.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Achar_Minimo.md` seguem a classificação acima:
- Exercícios $1$, $2$ e $3$: variação (a), menor número de viagens com limite de peso, o exercício $3$ mostrando um caso em que a divisão simples não basta.
- Exercícios $4$ e $5$: variação (b), menor número de cadeados em camadas trancadas.
- Exercícios $6$ e $7$: variação (c), menor número de movimentos para equilibrar linhas e colunas.
- Exercícios $8$, $9$ e $10$: variação (d), maior trecho preservável entre pontos fixos, o exercício $9$ mostrando um caso em que o maior trecho fica numa ponta, não entre duas estrelas.
