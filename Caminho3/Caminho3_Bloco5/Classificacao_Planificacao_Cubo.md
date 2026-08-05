Ficha de classificação · Bloco $5$ · Planificação do cubo

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as três questões de referência do bloco: `2018/Q15` (código `NA18-Q15`), `2020/Q15` (código `NA20-Q15`), `2023/F2/Q13` (código `M2-23-F2-Q13`).

***Nó proposto na grade (Apêndice D)***

A seção "Geometria" da grade oficial estava marcada `[+]`, sem nenhum filho registrado. Este bloco é o primeiro de geometria espacial 3D a entrar na grade, então propomos o subnó:

`Geometria › Sólidos Geométricos › Planificação e Faces Opostas do Cubo`

**Justificativa.** As três questões de referência têm o mesmo motor de fundo (dobrar mentalmente um molde plano em cubo), mas pedem three saídas diferentes (achar o molde certo, achar o cubo certo, achar a face certa). Não existe hoje, na grade, nenhum nó de geometria espacial 3D, e este Caminho $3$ traz mais dois blocos do mesmo assunto vindos da mesma fonte (CM5, "questões de sólidos"). O Bloco $6$ (vistas de uma montagem de cubinhos) e o Bloco $7$ (contagem e cortes num sólido) abrem os dois subnós irmãos deste, todos filhos de "Sólidos Geométricos". Nomear o subnó pela dupla "planificação" e "faces opostas" evita confundir com os blocos vizinhos, que não lidam com dobradura de molde.

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Raciocínio espacial de dobradura: reconhecer, mentalmente ou olhando um molde plano de seis quadrados, qual arranjo tridimensional (cubo) resulta ao dobrar nas linhas entre os quadrados. Não há conta numérica, o raciocínio é inteiramente visual e depende de rastrear a posição relativa das faces antes e depois da dobra.

**Nó principal (Apêndice D, grade oficial).** `Geometria › Sólidos Geométricos › Planificação e Faces Opostas do Cubo` (subnó proposto acima).

**Descritores secundários.**
- Pares de faces opostas por posição na planificação (regra de "pular uma casa" numa fileira reta de quadrados grudados).
- Confusão entre "face oposta" e "face vizinha" (a armadilha mais comum: opostas nunca aparecem juntas numa mesma vista do cubo montado).
- Rastreamento de orientação de face ao dobrar (um desenho que estava numa posição no papel muda de direção relativa depois de montado).

**Não é X (e por quê).**
- Não é Raciocínio Lógico › Problemas com Visualização Espacial como nó principal isolado, porque esse nó da grade é genérico demais (cobre qualquer visualização espacial, inclusive vistas de cima e contagem de blocos, que são o assunto dos Blocos $6$ e $7$ deste Caminho, não deste). Preferimos o subnó específico de planificação e faces opostas, mais preciso para este bloco.
- Não é Aritmética › Grandezas e Medidas, porque não há medida, comparação de tamanho nem unidade envolvida, só a forma do molde e a posição das faces.
- Não é Álgebra pré-algébrica, porque não existe incógnita numérica a descobrir por operação inversa, o "desconhecido" aqui é uma posição ou uma cor, não um número.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 3** › **Bloco 5 · Planificação do cubo** › capítulo de teoria "Planificação do cubo" (`Cap_Planificacao_Cubo.md`).

---

***Notas específicas de cada questão de referência***

`2018/Q15` (código `NA18-Q15`)
- **Enunciado original (resumo):** entre cinco planificações desenhadas em cruz, cada uma com duas casas sombreadas em tons diferentes, achar a que forma um cubo com as faces opostas da mesma cor.
- **Motor aplicado:** variação "achar a planificação certa", comparando vários moldes desenhados e escolhendo o único cujas casas sombreadas realmente caem em faces opostas ao dobrar.
- **Não é X específico:** não pede montar o cubo nem escolher entre cubos já desenhados, a resposta fica inteira dentro do próprio molde plano.

`2020/Q15` (código `NA20-Q15`)
- **Enunciado original (resumo):** dada uma planificação específica, com algumas casas sombreadas em cinza, achar entre cinco cubos já montados e desenhados qual é o resultado certo de dobrar aquele molde.
- **Motor aplicado:** variação "achar o cubo certo", partindo de um único molde fixo e comparando contra cubos-candidatos que testam cor certa em posição errada, cor errada, ou faces opostas mostradas juntas (erro impossível).
- **Não é X específico:** ao contrário da `NA18-Q15`, aqui o molde já está fixado e o trabalho é escolher entre representações 3D já prontas, não comparar moldes entre si.

`2023/F2/Q13` (código `M2-23-F2-Q13`)
- **Enunciado original (resumo):** uma planificação em cruz tem um desenho (carinha feliz ou triste) em cada face. Dobrada em cubo, dois desenhos aparecem numa vista e uma terceira face está marcada com "?". Descobrir qual desenho fica ali.
- **Motor aplicado:** variação "achar a face que fica em determinado lugar", a mais fina das três, porque exige saber não só quais faces são opostas, mas também quais faces ficam mutuamente visíveis (adjacentes) na mesma vista do cubo montado.
- **Não é X específico:** não basta achar um par oposto, é preciso identificar uma face entre as que restam, cruzando a informação das duas faces já visíveis.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Planificacao_Cubo.md` cobrem as três variações do motor, na mesma proporção das questões oficiais:

- **Achar a planificação certa** (como `NA18-Q15`): exercícios $3$, $7$ e $8$. O $3$ e o $8$ pedem achar, entre vários moldes do mesmo formato com duas casas sombreadas em posições diferentes, aquele em que as casas realmente caem em faces opostas. O $7$ pede achar, entre vários formatos diferentes de molde, o único que não fecha um cubo.
- **Achar o cubo certo** (como `NA20-Q15`): exercícios $1$, $5$ e $10$. Cada um parte de um único molde colorido e pede escolher, entre cinco cubos já desenhados, o que realmente resulta da dobra, contra distratores de rotação errada, cor trocada com a face oposta e cor inventada que não está no molde.
- **Achar a face que fica em determinado lugar** (como `M2-23-F2-Q13`): exercícios $2$, $4$, $6$ e $9$. Os exercícios $2$ e $4$ mostram um cubo com duas faces visíveis e uma marcada "?", a resposta é o desenho que falta. Os exercícios $6$ e $9$ perguntam direto qual cor fica oposta a uma cor dada, um caso mais simples da mesma habilidade, o $9$ aplicado a um molde em fileira, para reforçar que a regra de pular uma casa não vale só para a cruz.

Todas as figuras dos exercícios autorais foram geradas a partir de um simulador de dobradura (rotações no espaço aplicadas a cada quadrado do molde, ver nota de verificação abaixo), de modo que cada par oposto, cada cubo-candidato e cada face marcada com "?" tem solução única e matematicamente conferida, não apenas desenhada "de olho".

**Nota de verificação (§$13$/§$16$).** Como não existe gabarito oficial para as questões autorais, cada planificação foi dobrada por código, aresta por aresta, calculando a direção final de cada face no espaço. A partir disso, o par de faces opostas, o trio de faces visíveis num cubo montado e a face que ocupa uma posição "?" saem do cálculo, não de estimativa visual. O mesmo cálculo garante que cada distrator nasce de um erro nomeável (rotação errada das faces visíveis, cor da face oposta usada no lugar da face da frente, cor que não pertence ao molde, ou formato de molde que realmente não fecha um cubo), nunca de um valor aleatório.
