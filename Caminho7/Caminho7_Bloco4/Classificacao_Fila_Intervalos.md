Ficha de classificação · Bloco $4$ · Organizar em fila e nos intervalos

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as duas questões de referência do bloco: `2022/F2/Q7` (código `M2-22-F2-Q07`) e `2025/F2/Q5` (código `M2-25-F2-Q05`).

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Organizar itens numa fila e contar com cuidado o que existe entre eles ou como eles podem se arranjar respeitando uma condição de vizinhança. O bloco reúne duas variações: (a) contar quantos itens cabem nos espaços entre os elementos de uma fila, sabendo que uma fila de $n$ itens tem $n-1$ espaços entre vizinhos, e (b) contar de quantas maneiras itens de tipos diferentes podem se organizar numa fileira quando os itens do mesmo tipo precisam ficar juntos, tratando cada tipo como um bloco.

**Nó principal (Apêndice D, grade oficial).** `Análise Combinatória › Contagem Direta e Contagem por Posição` (mesmo subnó proposto dos demais blocos deste Caminho). A variação (b) também encosta em `Análise Combinatória › Princípio Multiplicativo da Contagem`, quando disponível na árvore, porque a contagem final multiplica escolhas independentes, a ordem dos blocos e a ordem dentro de cada bloco.

**Descritores secundários.**
- Espaços de uma fila é sempre um a menos: numa fila com $n$ itens, o número de espaços entre vizinhos é $n-1$, porque as duas pontas da fila só têm vizinho de um lado.
- Multiplicação de itens por espaço: quando cada espaço entre vizinhos recebe a mesma quantidade fixa de itens novos, o total desses itens novos é essa quantidade multiplicada pelo número de espaços, e o total geral soma esse resultado aos itens que já estavam na fila.
- Blocos por tipo, depois embaralhamento interno: quando itens do mesmo tipo precisam ficar juntos, a contagem de arranjos possíveis se separa em duas partes independentes, de quantas formas os blocos de tipos diferentes trocam de ordem entre si, e de quantas formas os itens de dentro de cada bloco trocam de posição entre si, multiplicadas ao final.

**Não é X (e por quê).**
- Não é o Bloco $2$ deste Caminho (Pareamento: pés, mãos e conjuntos), porque ali a pergunta é sobre formar pares ou conjuntos completos, e aqui é sobre organizar uma sequência inteira numa fila, contando espaços ou arranjos.
- Não é o Bloco $5$ deste Caminho (Multiplicar as escolhas), mesmo quando a variação (b) usa multiplicação de contagens independentes. A diferença é que aqui a multiplicação nasce de uma restrição de vizinhança específica, "itens do mesmo tipo juntos", não de escolhas livres e independentes entre categorias diferentes.
- Não é Sequências, Padrões e Regularidades (Caminho $8$), porque a fila do bloco não segue uma regra que se repete e se estende. O número de itens e de espaços é sempre fixo e dado no enunciado.
- Não é Grandezas e Medidas, mesmo quando a variação (a) descreve uma fila com distância física entre os itens. O que importa é a contagem de espaços e do que cabe neles, não uma medida de comprimento.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 7** › **Bloco 4 · Organizar em fila e nos intervalos** › capítulo de teoria "Pôr em ordem e contar os espaços" (`Cap_Fila_Intervalos.md`).

---

***Notas específicas de cada questão de referência***

`2022/F2/Q7` (código `M2-22-F2-Q07`)
- **Motor aplicado:** variação (a), contar itens nos espaços entre vizinhos. Seis meninos ficam em fila, e três meninas se posicionam em cada um dos espaços entre dois meninos vizinhos. Com $6$ meninos, há $6-1=5$ espaços, cada um com $3$ meninas, totalizando $5\times3=15$ meninas. Somando aos $6$ meninos, $6+15=21$ crianças ao todo. Gabarito **D ($21$)** ✅, conferido contra a solução oficial (`sf2m2-2022.pdf`, questão $7$).
- **Não é X específico:** não é multiplicar $6$ meninos por $3$ meninas por espaço direto ($6\times3=18$), o número certo de espaços é $5$, não $6$, porque as duas pontas da fila são ocupadas por meninos, sem meninas além deles.

`2025/F2/Q5` (código `M2-25-F2-Q05`)
- **Motor aplicado:** variação (b), blocos por tipo com embaralhamento interno. Marcelina quer guardar $4$ livros numa estante, $2$ de português e $2$ de matemática, com os livros da mesma matéria juntos. Os dois blocos de matéria podem trocar de ordem de $2$ maneiras, e dentro de cada bloco os $2$ livros trocam de posição de $2$ maneiras cada. Multiplicando, $2\times2\times2=8$. Gabarito **D ($8$)** ✅, conferido contra a solução oficial (`sf2m2-2025.pdf`, questão $5$).
- **Não é X específico:** não é somar as possibilidades dos blocos com as possibilidades internas ($2+2+2=6$), as três escolhas são independentes entre si e por isso se multiplicam, não se somam.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Fila_Intervalos.md` seguem a classificação acima:
- Exercícios $1$ a $5$: variação (a), contar itens nos espaços entre vizinhos de uma fila, em dificuldade crescente.
- Exercícios $6$ a $10$: variação (b), blocos por tipo com embaralhamento interno, incluindo casos com contagens desiguais entre os tipos e um caso com três tipos em vez de dois.
