Ficha de classificação · Bloco $3$ · Achar pela posição: ciclos e grades

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as duas questões de referência do bloco: `2023/F1/Q2` (código `M2-23-F1-Q02`) e `2025/F1/Q1` (código `M2-25-F1-Q01`).

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Descobrir o que ocupa uma posição específica dentro de uma estrutura regular, seja um padrão que se repete em ciclos, seja uma tabela numérica preenchida em ordem, usando a regularidade da posição em vez de listar ou desenhar tudo até chegar lá.

**Nó principal (Apêndice D, grade oficial).** `Raciocínio Lógico › Sequências e Padrões Numéricos`. Propõe-se o subnó nomeado **Regularidade Posicional em Ciclos e Grades**, distinguindo esse raciocínio (onde importa a posição de um elemento dentro de uma estrutura) do raciocínio dos Blocos $1$ e $2$ deste Caminho (onde importa o valor de uma grandeza que cresce).

**Descritores secundários.**
- Posição dentro de um ciclo pelo resto da divisão: numa sequência periódica, a posição de um elemento dentro de um único ciclo se descobre dividindo sua posição na fila pelo tamanho do ciclo, o resto da divisão aponta a posição dentro do ciclo (e resto zero indica o fim exato de um ciclo completo).
- Número numa grade pela combinação de dois deslocamentos: numa tabela preenchida em ordem, o número de qualquer casa se calcula combinando dois deslocamentos fixos a partir do canto inicial, descer uma linha soma o número de colunas, andar para o lado soma $1$.
- Verificação de um conjunto de casas pela mesma regra: a mesma regra de deslocamento (descer soma o número de colunas, andar para o lado soma $1$) serve para conferir se um conjunto de números realmente forma um grupo de casas vizinhas na tabela, não só para calcular uma casa isolada.

**Não é X (e por quê).**
- Não são os Blocos $1$ e $2$ deste Caminho, porque ali a pergunta é sobre o valor de uma grandeza que cresce ao longo da sequência (comprimento, quantidade de peças, número de pontas), enquanto aqui a pergunta é sobre qual elemento ocupa uma posição específica dentro de uma estrutura que se repete ou que se organiza em linhas e colunas.
- Não é Restrição de Quantidade em Linhas e Colunas (Caminho $6$), mesmo quando a estrutura também é uma grade, porque ali o objetivo é descobrir valores desconhecidos a partir de somas ou pistas dadas, e aqui a grade já está completamente preenchida em ordem crescente, o objetivo é só localizar ou verificar posições.
- Não é Percepção Espacial (Caminho $5$), mesmo quando a questão envolve o formato de uma peça a ser recortada de uma grade, porque o núcleo da dificuldade não é visualizar rotações ou encaixes espaciais, é aplicar corretamente a regra numérica de deslocamento (linha e coluna) para validar quais números pertencem a casas vizinhas.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 8** › **Bloco 3 · Achar pela posição: ciclos e grades** › capítulo de teoria "Descobrir quem cai em cada lugar" (`Cap_Achar_Pela_Posicao.md`).

---

***Notas específicas de cada questão de referência***

`2023/F1/Q2` (código `M2-23-F1-Q02`)
- **Motor aplicado:** uma fila de figuras se repete num padrão de $4$ símbolos (quadrado preto, círculo branco, triângulo, losango). A $9$ª figura da fila é o quadrado preto, o primeiro símbolo do padrão, porque $9=4\times2+1$, ou seja, $9$ está $1$ posição depois de $2$ ciclos completos. As três próximas figuras, a $10$ª, $11$ª e $12$ª, são então o círculo, o triângulo e o losango, as posições $2$, $3$ e $4$ do padrão. Gabarito **A (círculo, triângulo, losango)** ✅, conferido contra a solução oficial (`sf1m2-2023.pdf`, questão $2$).
- **Não é X específico:** não é uma questão de continuar desenhando a fila até a posição pedida, é sobre reconhecer em qual ponto do ciclo de $4$ símbolos a $9$ª figura cai, e contar as posições seguintes a partir dali.

`2025/F1/Q1` (código `M2-25-F1-Q01`)
- **Motor aplicado:** uma tabela é preenchida em ordem crescente de $1$ a $50$, com $10$ números por linha. Entre alguns conjuntos de $4$ números candidatos a formar uma peça recortável (um tetrominó), só um respeita a regra de deslocamento da grade, descer uma linha soma $10$, andar para o lado soma $1$, o conjunto $22$, $32$, $33$, $43$ (de $22$ para $32$, desce uma linha e soma $10$, de $32$ para $33$, anda um e soma $1$, de $33$ para $43$, desce uma linha e soma $10$). Gabarito **C** ✅, conferido contra a solução oficial (`sf1m2-2025.pdf`, questão $1$).
- **Não é X específico:** não é suficiente visualizar o formato da peça olhando o desenho, os outros conjuntos candidatos têm formatos parecidos mas os números não respeitam a regra de deslocamento da grade (por exemplo, um número que deveria estar $10$ a mais ou $1$ a mais aparece com uma diferença errada), então a verificação numérica, casa por casa, é o que decide qual conjunto é válido.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Achar_Pela_Posicao.md` seguem a classificação acima:
- Exercícios $1$ a $5$: achar a posição dentro de um ciclo que se repete, em contextos diferentes (contas, bandeirinhas, adesivos, carimbos, blocos coloridos), com ciclos de tamanhos diferentes.
- Exercícios $6$ a $10$: achar um número numa grade preenchida em ordem, em tabelas com números de colunas diferentes.
