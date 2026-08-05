# OBMEP Mirim 2 — Engenharia Reversa para Trilha de Curso (4º e 5º anos)
### Classificação por assunto e organização em Caminhos (Unidades)

> Documento-base para alimentar a plataforma. Cada questão tem **dois identificadores**: um **nome fácil** (ano/fase/número) para busca humana e um **código técnico** estável para a base do site.

> **Atualização (jun/2026):** incorporado o lote **2023** — Olimpíada Mirim · Mirim 2 · 1ª e 2ª Fases (30 questões). Total da base subiu de **80 → 110 questões**.

> **Atualização (jun/2026, lote 2):** incorporado o lote **2024** — Olimpíada Mirim · Mirim 2 · **3ª Edição** · 1ª e 2ª Fases (30 questões). Total da base subiu de **110 → 140 questões**. Achado editorial do lote: 2024 **não tem nenhuma questão de Frações (CM2) nem de Sequências/Padrões (CM8)** — duas ausências completas. O peso migrou para **Raciocínio Lógico (CM6)**, que sozinho levou 11 das 30 questões novas, e para **Contagem (CM7)**, com 7. A vinheta de abertura também mudou: 2024/F1 abre com uma **balança** e 2024/F2 com uma **contagem de triângulos** (não mais o "maior resultado" de 2023).

> **Atualização (jun/2026, lote 3):** incorporado o lote **2025** — Olimpíada Mirim · Mirim 2 · **4ª Edição** · 1ª e 2ª Fases (30 questões). Total da base subiu de **140 → 170 questões**. Achado editorial do lote: 2025 **repete a ausência de Frações (CM2)** — agora **dois anos seguidos sem CM2** — e ainda **zera Tempo/Calendário (CM4)**. Em compensação, **traz CM8 de volta** (2 questões, após o branco de 2024) e é a edição **mais espacial de toda a base**: **CM5 = 9 das 30**, empatada com CM6 (9). As aberturas mudaram de novo: 2025/F1 abre com uma **tabela numérica 1–50** (recorte de peça) e 2025/F2 com **dedos numerados** (transformação espacial).

> **Atualização (v3 — estrutura do Caminho 1, jun/2026):** formalizada a **estrutura pedagógica do Caminho 1 em 8 blocos de curso** (nova **§7**). Ajustes desta versão: (a) o antigo bloco de tabelas foi **dividido** em **Tabelas** e **Duas pistas para duas quantidades**; (b) a questão `2018/Q16` (invariância da diferença) **migrou** do bloco de estratégias para o de comparação / diferença constante; (c) o bloco de estratégias passou a tratar **só piso e teto** (supor o mínimo e maximizar com restrição). **Nenhuma classificação por Caminho mudou** — as 27 questões seguem todas em CM1; mudou apenas a organização interna em blocos.

> **Atualização (v4 — estrutura de blocos e Caminhos de plataforma, jun/2026):** concluída a engenharia reversa pedagógica de **todos os 8 Caminhos** (na v3 só o CM1 estava formalizado). As 170 questões foram organizadas em **50 blocos de curso** e os 8 Caminhos analíticos (CM1–CM8) foram **reempacotados em 8 unidades de plataforma** (nova **§8**, índice mestre bloco → questão). Remapeamentos: **CM2 + CM4** dividem a unidade **2**; o **CM5** se divide entre a unidade **3** (sólidos) e a **4** (no plano); o **CM6** se divide entre a **5** (lógica) e a **6** (quantitativo). Nenhuma classificação analítica mudou — cada questão mantém seu CM na tabela-mestre (§4); mudou só o agrupamento navegável e a partição interna em blocos. Pendência cosmética nos tiles: padronizar a caixa dos títulos (unidades 1, 7 e 8 ainda em Title Case) e remover o artigo de "A lógica e dedução" → "Lógica e dedução".

---

## 1. Material analisado (170 questões)

| Sigla | Prova | Fase | Nº de questões |
|---|---|---|---|
| **NA18** | OBMEP Nível A 2018 | única | 20 |
| **NA19** | OBMEP Nível A 2019 | única | 15 |
| **NA20** | OBMEP Nível A "2020" | única | 15 |
| **M2-22-F1** | Olimpíada Mirim · Mirim 2 · 2022 | 1ª Fase | 15 |
| **M2-22-F2** | Olimpíada Mirim · Mirim 2 · 2022 | 2ª Fase | 15 |
| **M2-23-F1** | Olimpíada Mirim · Mirim 2 · 2023 | 1ª Fase | 15 |
| **M2-23-F2** | Olimpíada Mirim · Mirim 2 · 2023 | 2ª Fase | 15 |
| **M2-24-F1** | Olimpíada Mirim · Mirim 2 · 2024 | 1ª Fase | 15 |
| **M2-24-F2** | Olimpíada Mirim · Mirim 2 · 2024 | 2ª Fase | 15 |
| **M2-25-F1** | Olimpíada Mirim · Mirim 2 · 2025 | 1ª Fase | 15 |
| **M2-25-F2** | Olimpíada Mirim · Mirim 2 · 2025 | 2ª Fase | 15 |

**Notas de procedência (importantes para a engenharia reversa):**

- O **Nível A** (2018–2021) é o **precursor** da Olimpíada Mirim para 4º/5º anos. A partir de 2022, o nome passa a ser **Olimpíada Mirim – Mirim 2**. As duas linhas formam um continuum de banco de questões e podem ser tratadas como mesma trilha.
- O arquivo nomeado `NA20` corresponde à **3ª edição do Nível A**, cuja prova foi **aplicada em 26/10/2021** (edição de 2020 remanejada). Mantenho o ano **2020** nos nomes por consistência com o arquivo, mas registre internamente "aplicação 2021".
- O Nível A é **prova única**; Mirim 2 (2022 e 2023) tem **1ª e 2ª Fase**.
- A prova de 2023 é a **2ª Edição da Olimpíada Mirim** (Realização IMPA). A 1ª Fase e a 2ª Fase abrem ambas com uma questão "qual conta tem o maior resultado" (`2023/F1/Q1` e `2023/F2/Q1`) — vinheta de abertura recorrente da banca, útil como questão-âncora de entrada.
- A prova de 2024 é a **3ª Edição da Olimpíada Mirim** (Realização IMPA), também com **1ª e 2ª Fase**. A vinheta de abertura mudou de feição: `2024/F1/Q1` abre com uma **balança** (medida/massa) e `2024/F2/Q1` com uma **contagem de triângulos** num mosaico — ou seja, a banca não fixou ainda um "tipo de abertura" canônico, mas mantém o hábito de começar por uma questão visual e de baixa barreira de entrada.
- A prova de 2025 é a **4ª Edição da Olimpíada Mirim** (Realização IMPA), com **1ª e 2ª Fase**. A abertura volta a ser visual, mas agora **numérico-posicional**: `2025/F1/Q1` parte de uma **tabela de 1 a 50 em 10 colunas** (qual peça pode ser recortada) e `2025/F2/Q1` de **dedos numerados de 1 a 10** (soma após cruzar os braços). É a edição que mais pesa em **percepção espacial** (cubo pintado, encaixes, contornos, rotação de pista) e que repõe **padrões com palitos** (`2025/F1/Q8`).

---

## 2. Convenção de nomes (dois modos)

**Nome fácil — `ano/fase/número`** (use para buscar e conversar):

| Fonte | Formato | Exemplos |
|---|---|---|
| Nível A 2018 (fase única) | `2018/Q__` | `2018/Q1`, `2018/Q20` |
| Nível A 2019 (fase única) | `2019/Q__` | `2019/Q7` |
| Nível A 2020 (fase única) | `2020/Q__` | `2020/Q1` |
| Mirim 2 · 2022 · 1ª Fase | `2022/F1/Q__` | `2022/F1/Q10` |
| Mirim 2 · 2022 · 2ª Fase | `2022/F2/Q__` | `2022/F2/Q2` |
| Mirim 2 · 2023 · 1ª Fase | `2023/F1/Q__` | `2023/F1/Q11` |
| Mirim 2 · 2023 · 2ª Fase | `2023/F2/Q__` | `2023/F2/Q9` |
| Mirim 2 · 2024 · 1ª Fase | `2024/F1/Q__` | `2024/F1/Q12` |
| Mirim 2 · 2024 · 2ª Fase | `2024/F2/Q__` | `2024/F2/Q9` |
| Mirim 2 · 2025 · 1ª Fase | `2025/F1/Q__` | `2025/F1/Q12` |
| Mirim 2 · 2025 · 2ª Fase | `2025/F2/Q__` | `2025/F2/Q09` |

> Como **2018–2020 = Nível A (fase única)** e **2022/2023 = Mirim 2**, o ano já identifica a prova; por isso a fase só aparece a partir de 2022.

**Código técnico — `SIGLA-Qnn`** (estável, para a base do site, com zero à esquerda): `NA18-Q01`, `NA19-Q07`, `NA20-Q01`, `M2-22-F1-Q10`, `M2-22-F2-Q02`, `M2-23-F1-Q11`, `M2-23-F2-Q09`, `M2-24-F1-Q12`, `M2-24-F2-Q09`, `M2-25-F1-Q12`, `M2-25-F2-Q09`.

**Legenda de gabarito:**
- ✅ = determinado pelo enunciado/cálculo (independe da figura).
- 🖼️ = depende de figura/imagem; resposta estimada — **conferir no gabarito oficial** antes de publicar.
- ✅🖼️ = resposta já **calculada/determinada**, mas a **leitura da figura** (contagem, marcas, posições) deve ser conferida.

---

## 3. Os 8 Caminhos da Trilha Mirim 2

Para evitar colisão com a sua trilha do **Nível 1** (que usa C1–C8), aqui os Caminhos recebem o prefixo **CM** (Caminho Mirim). A estrutura foi **derivada do conteúdo real** das provas: "Tempo/Calendário" virou Caminho próprio (peso alto nesta faixa etária) e "Divisibilidade/Porcentagem" não existe como Caminho (praticamente ausente em 4º/5º anos).

| Caminho | Nome | Foco |
|---|---|---|
| **CM1** | Números, Operações e Problemas Aritméticos | Adição, subtração, multiplicação, divisão, problemas de idade, sistema de numeração e valor posicional, lacunas/borrões em contas, tabelas |
| **CM2** | Frações, Proporção e Raciocínio Multiplicativo | Frações de quantidades, proporção, razão, "preço do conjunto", capacidade proporcional |
| **CM3** | Grandezas e Medidas | Comprimento/régua, massa/balança/equilíbrio, área, dinheiro, altura de pilhas, contagem de marcas |
| **CM4** | Tempo, Calendário e Dias da Semana | Relógio, leitura de horas, duração, dias da semana, calendário |
| **CM5** | Geometria e Percepção Espacial | Planificação de cubos, composição/decomposição de figuras, simetria/reflexão, vistas, encaixe, rotação, lateralidade/caminhos, volume |
| **CM6** | Raciocínio Lógico e Dedução | Puzzles lógicos, casa dos pombos, jogo de senha, otimização, substituição, faces de cubo, leitura de diagramas/gráficos, correspondência de posições |
| **CM7** | Contagem e Combinatória | Contagem direta, pareamento, intervalos (poste/cerca), quadro latino, contagem de ocorrências, combinações com restrição |
| **CM8** | Sequências, Padrões e Regularidades | Sequências figurais e periódicas, números figurados, soma de algarismos, palíndromos, padrões de crescimento |

**Distribuição (insight para o design do curso) — base 170:**

| Caminho | Qtde | Peso |
|---|---|---|
| CM6 | 43 | ●●●●●●●●●●●●●●● |
| CM5 | 36 | ●●●●●●●●●●●● |
| CM1 | 27 | ●●●●●●●●● |
| CM7 | 23 | ●●●●●●●● |
| CM3 | 13 | ●●●● |
| CM4 | 11 | ●●●● |
| CM8 | 11 | ●●●● |
| CM2 | 6 | ●● |

> **Leitura editorial (atualizada com 2024):** a Mirim 2 consolidou de vez seu **DNA lógico-espacial**: **CM6 (34) + CM5 (27) = 61 das 140** questões (44%). E 2024 reforçou isso de forma extrema — das 30 questões da 3ª Edição, **11 foram CM6** e **5 CM5**, ou seja, mais da metade do lote. **CM7 (Contagem) saltou para 18** e virou o quarto pilar sólido, à frente de CM3 e CM4. O dado mais marcante de 2024, porém, são as **duas ausências completas**: **nenhuma questão de Frações (CM2)** e **nenhuma de Sequências/Padrões (CM8)**. CM2 segue como o Caminho estruturalmente mais magro de toda a base (6) e CM8 estacionou em 9 — ambos sustentados quase só pelas edições antigas (Nível A e 2022/2023). Implicação para o curso: **CM2 e CM8 são candidatos a blocos curtos ou a tratamento "de manutenção"**, enquanto o tempo de aula deve se concentrar em CM6, CM5, CM1 e CM7.

> **Leitura editorial (atualizada com 2025):** a 4ª Edição **confirma e radicaliza** o padrão. **CM6 (43) + CM5 (36) = 79 das 170** questões (**46%**) — e em 2025 esses dois Caminhos empataram em **9 questões cada**, somando 18 das 30. **CM5 atingiu seu recorde** (cubo pintado 3×3×3, encaixes forma+cor, contorno de figura composta, rotação de pista, dedos cruzados). **CM2 ficou zerada pelo segundo ano consecutivo** (2024 e 2025) e segue presa em 6 — é, sem disputa, o **Caminho mais ameaçado** da base. **CM4 (Tempo) também zerou em 2025**, ficando em 11. A novidade boa é **CM8 voltando** (2 questões), o que reequilibra o bloco para 11. Resumo operacional: o curso deve assumir **CM6+CM5 como núcleo absoluto**, **CM1 e CM7 como pilares de apoio**, e tratar **CM2 (e, em menor grau, CM4/CM8) como blocos curtos de manutenção**, sustentados pelas edições antigas + questões autorais.

---

## 4. Tabela-mestre (índice rápido para a base do site)

| Nome fácil | Código técnico | Caminho | Tópico específico | Gabarito |
|---|---|---|---|---|
| 2018/Q1 | NA18-Q01 | CM1 | Adição de naturais | C ✅ |
| 2018/Q2 | NA18-Q02 | CM1 | Problema aditivo (entra/sai) | D ✅ |
| 2018/Q3 | NA18-Q03 | CM6 | Leitura de diagrama (Venn) | 🖼️ |
| 2018/Q4 | NA18-Q04 | CM1 | Problema de idade | D ✅ |
| 2018/Q5 | NA18-Q05 | CM5 | Caminho mais curto em malha | 🖼️ |
| 2018/Q6 | NA18-Q06 | CM3 | Régua sem partir do zero | B 🖼️ |
| 2018/Q7 | NA18-Q07 | CM5 | Ordem de sobreposição | 🖼️ |
| 2018/Q8 | NA18-Q08 | CM4 | Dia da semana (+17 dias) | E ✅ |
| 2018/Q9 | NA18-Q09 | CM7 | Contagem em malha (igualar) | 🖼️ |
| 2018/Q10 | NA18-Q10 | CM8 | Sequência figural (quadrados) | C ✅ |
| 2018/Q11 | NA18-Q11 | CM5 | Sobreposição transparente | 🖼️ |
| 2018/Q12 | NA18-Q12 | CM3 | Massa na balança | 🖼️ |
| 2018/Q13 | NA18-Q13 | CM1 | Tabela 2×2 (somas) | A ✅ |
| 2018/Q14 | NA18-Q14 | CM1 | Contagem de páginas | C ✅ |
| 2018/Q15 | NA18-Q15 | CM5 | Planificação de cubo (cores) | 🖼️ |
| 2018/Q16 | NA18-Q16 | CM1 | Equivalência de subtrações | D ✅ |
| 2018/Q17 | NA18-Q17 | CM6 | Fila / posições | D ✅ |
| 2018/Q18 | NA18-Q18 | CM2 | Frações de quantidades | D ✅ |
| 2018/Q19 | NA18-Q19 | CM3 | Comprimento (desvio) | E 🖼️ |
| 2018/Q20 | NA18-Q20 | CM6 | Dedução (casas coloridas) | D ✅ |
| 2019/Q1 | NA19-Q01 | CM7 | Contagem de letras | 🖼️ |
| 2019/Q2 | NA19-Q02 | CM4 | Dia da semana (+9 dias) | B ✅ |
| 2019/Q3 | NA19-Q03 | CM5 | Reflexão no espelho | 🖼️ |
| 2019/Q4 | NA19-Q04 | CM5 | Comparar comprimentos em malha | 🖼️ |
| 2019/Q5 | NA19-Q05 | CM5 | Peça faltante (encaixe) | 🖼️ |
| 2019/Q6 | NA19-Q06 | CM2 | Proporção/divisão (½ pacote) | C ✅ |
| 2019/Q7 | NA19-Q07 | CM8 | Soma de algarismos do ano | C ✅ |
| 2019/Q8 | NA19-Q08 | CM8 | Padrão mesas–cadeiras | B ✅ |
| 2019/Q9 | NA19-Q09 | CM6 | Pesos em gavetas (dedução) | A ✅ |
| 2019/Q10 | NA19-Q10 | CM3 | Área equivalente (malha) | 🖼️ |
| 2019/Q11 | NA19-Q11 | CM5 | Peça não usada (frente/verso) | 🖼️ |
| 2019/Q12 | NA19-Q12 | CM6 | Dedução (andares) | E ✅ |
| 2019/Q13 | NA19-Q13 | CM7 | Quadro latino 3×3 | 🖼️ |
| 2019/Q14 | NA19-Q14 | CM6 | Paridade (soma3 − soma2) | D ✅ |
| 2019/Q15 | NA19-Q15 | CM3 | Móbile / equilíbrio (massa) | 🖼️ |
| 2020/Q1 | NA20-Q01 | CM1 | Igualdade com incógnita | B ✅ |
| 2020/Q2 | NA20-Q02 | CM5 | Classificar figuras (lados) | E ✅ |
| 2020/Q3 | NA20-Q03 | CM2 | Preço do conjunto (proporção) | C ✅ |
| 2020/Q4 | NA20-Q04 | CM1 | Pés de animais (total 10) | C ✅ |
| 2020/Q5 | NA20-Q05 | CM6 | Otimização (elevador) | B ✅ |
| 2020/Q6 | NA20-Q06 | CM2 | Frações (torta) | 🖼️ |
| 2020/Q7 | NA20-Q07 | CM6 | Mínimo de cadeados | E ✅ |
| 2020/Q8 | NA20-Q08 | CM1 | Ponto médio (postes) | D ✅ |
| 2020/Q9 | NA20-Q09 | CM7 | Pareamento (sapatos) | 🖼️ |
| 2020/Q10 | NA20-Q10 | CM6 | Substituição (feira) | D ✅ |
| 2020/Q11 | NA20-Q11 | CM6 | Mover peças (2 por linha/coluna) | 🖼️ |
| 2020/Q12 | NA20-Q12 | CM1 | Maior diferença par | B ✅ |
| 2020/Q13 | NA20-Q13 | CM6 | Faces opostas do cubo | A ✅ |
| 2020/Q14 | NA20-Q14 | CM6 | Joaninhas (5p / 6p = 43) | C ✅ |
| 2020/Q15 | NA20-Q15 | CM5 | Planificação de cubo | 🖼️ |
| 2022/F1/Q1 | M2-22-F1-Q01 | CM5 | Quebra-cabeça → número | 🖼️ |
| 2022/F1/Q2 | M2-22-F1-Q02 | CM5 | Qual NÃO é pedaço do traçado | 🖼️ |
| 2022/F1/Q3 | M2-22-F1-Q03 | CM8 | Padrão (carrinhos encaixados) | B ✅ |
| 2022/F1/Q4 | M2-22-F1-Q04 | CM5 | Chave × fechadura (simetria) | 🖼️ |
| 2022/F1/Q5 | M2-22-F1-Q05 | CM4 | Dia da semana (ontem/depois) | B ✅ |
| 2022/F1/Q6 | M2-22-F1-Q06 | CM4 | Relógio (−45 min) | 🖼️ |
| 2022/F1/Q7 | M2-22-F1-Q07 | CM7 | Par ou ímpar (maneiras) | C 🖼️ |
| 2022/F1/Q8 | M2-22-F1-Q08 | CM5 | Rotação (roda gigante) | 🖼️ |
| 2022/F1/Q9 | M2-22-F1-Q09 | CM5 | Composição de triângulos | C 🖼️ |
| 2022/F1/Q10 | M2-22-F1-Q10 | CM1 | Problema de idade | C ✅ |
| 2022/F1/Q11 | M2-22-F1-Q11 | CM3 | Comprimento (ida e volta) | E ✅ |
| 2022/F1/Q12 | M2-22-F1-Q12 | CM1 | Lacunas na adição (menor dif.) | A ✅ |
| 2022/F1/Q13 | M2-22-F1-Q13 | CM5 | Lateralidade (caminho esq/dir) | 🖼️ |
| 2022/F1/Q14 | M2-22-F1-Q14 | CM5 | Recompor quadradinhos (área) | 🖼️ |
| 2022/F1/Q15 | M2-22-F1-Q15 | CM3 | Dinheiro (troco em 3 moedas) | B ✅ |
| 2022/F2/Q1 | M2-22-F2-Q01 | CM8 | Padrão (estrelas → pontas) | C ✅ |
| 2022/F2/Q2 | M2-22-F2-Q02 | CM1 | Ábaco / valor posicional | C ✅ |
| 2022/F2/Q3 | M2-22-F2-Q03 | CM7 | Contagem (mãos carimbadas) | 🖼️ |
| 2022/F2/Q4 | M2-22-F2-Q04 | CM3 | Equilíbrio (transferir bola) | C ✅ |
| 2022/F2/Q5 | M2-22-F2-Q05 | CM5 | Vista de cima (torres) | 🖼️ |
| 2022/F2/Q6 | M2-22-F2-Q06 | CM4 | Calendário (1→31 jan) | A ✅ |
| 2022/F2/Q7 | M2-22-F2-Q07 | CM7 | Intervalos (meninos/meninas) | D ✅ |
| 2022/F2/Q8 | M2-22-F2-Q08 | CM8 | Números tetraédricos (pilhas) | A ✅ |
| 2022/F2/Q9 | M2-22-F2-Q09 | CM3 | Régua: contagem de marcas | E ✅ |
| 2022/F2/Q10 | M2-22-F2-Q10 | CM8 | Palíndromo de data | C ✅ |
| 2022/F2/Q11 | M2-22-F2-Q11 | CM6 | Dedução (cartas frente/verso) | 🖼️ |
| 2022/F2/Q12 | M2-22-F2-Q12 | CM6 | Casa dos pombos (13/12) | B ✅ |
| 2022/F2/Q13 | M2-22-F2-Q13 | CM2 | Proporção (jarra/garrafa/copo) | C ✅ |
| 2022/F2/Q14 | M2-22-F2-Q14 | CM6 | Faces do cubo (afirmação certa) | B ✅ |
| 2022/F2/Q15 | M2-22-F2-Q15 | CM6 | Jogo de senha (tipo Mastermind) | B ✅ |
| 2023/F1/Q1 | M2-23-F1-Q01 | CM1 | Maior resultado (comparar somas) | E ✅ |
| 2023/F1/Q2 | M2-23-F1-Q02 | CM8 | Padrão periódico (período 4) | A ✅ |
| 2023/F1/Q3 | M2-23-F1-Q03 | CM7 | Contagem (mãos: esquerda) | 🖼️ |
| 2023/F1/Q4 | M2-23-F1-Q04 | CM1 | Ábaco (retirar 2 peças) | E ✅ |
| 2023/F1/Q5 | M2-23-F1-Q05 | CM1 | Tabela (igualar nº de alunos) | D ✅ |
| 2023/F1/Q6 | M2-23-F1-Q06 | CM4 | Dia do mês (próxima quarta) | C ✅ |
| 2023/F1/Q7 | M2-23-F1-Q07 | CM2 | Fração de quantidade (⅓ pretas) | 🖼️ |
| 2023/F1/Q8 | M2-23-F1-Q08 | CM6 | Balanças (ordenar a mais pesada) | 🖼️ |
| 2023/F1/Q9 | M2-23-F1-Q09 | CM7 | Produtos distintos (algarismos) | D ✅ |
| 2023/F1/Q10 | M2-23-F1-Q10 | CM5 | Vistas (frente/lado/cima) | 🖼️ |
| 2023/F1/Q11 | M2-23-F1-Q11 | CM3 | Altura de pilhas (2 caixas) | C ✅🖼️ |
| 2023/F1/Q12 | M2-23-F1-Q12 | CM6 | Leitura de gráfico de barras | 🖼️ |
| 2023/F1/Q13 | M2-23-F1-Q13 | CM1 | Gomos 2/3 sementes (total 20) | B ✅ |
| 2023/F1/Q14 | M2-23-F1-Q14 | CM6 | Roda gigante (cabines opostas) | C ✅ |
| 2023/F1/Q15 | M2-23-F1-Q15 | CM7 | Combinações com restrição (chás) | E ✅ |
| 2023/F2/Q1 | M2-23-F2-Q01 | CM1 | Maior resultado (com ×, −) | E ✅ |
| 2023/F2/Q2 | M2-23-F2-Q02 | CM4 | Calendário (qual NÃO é sábado) | D ✅ |
| 2023/F2/Q3 | M2-23-F2-Q03 | CM4 | Relógio atrasado (+10 min) | C ✅🖼️ |
| 2023/F2/Q4 | M2-23-F2-Q04 | CM8 | Padrão (diagonais 2n−1) | C ✅🖼️ |
| 2023/F2/Q5 | M2-23-F2-Q05 | CM6 | Correspondência de quartos | D ✅ |
| 2023/F2/Q6 | M2-23-F2-Q06 | CM1 | Tabela (dobro de estudantes) | E ✅ |
| 2023/F2/Q7 | M2-23-F2-Q07 | CM4 | Duração de trajeto (ida=volta) | B ✅ |
| 2023/F2/Q8 | M2-23-F2-Q08 | CM6 | Face de dado (ímpar; opostas 7) | 🖼️ |
| 2023/F2/Q9 | M2-23-F2-Q09 | CM7 | Contagem do algarismo zero | E ✅ |
| 2023/F2/Q10 | M2-23-F2-Q10 | CM1 | Borrões na adição (soma) | B ✅🖼️ |
| 2023/F2/Q11 | M2-23-F2-Q11 | CM5 | Vista de cima (7 cubinhos) | 🖼️ |
| 2023/F2/Q12 | M2-23-F2-Q12 | CM6 | Encaixe por bordas (cartões) | 🖼️ |
| 2023/F2/Q13 | M2-23-F2-Q13 | CM5 | Planificação de cubo (faces) | 🖼️ |
| 2023/F2/Q14 | M2-23-F2-Q14 | CM5 | Decompor cubo em 4 peças | 🖼️ |
| 2023/F2/Q15 | M2-23-F2-Q15 | CM6 | Mínimo de livros (posições) | C ✅ |
| 2024/F1/Q1 | M2-24-F1-Q01 | CM3 | Balança (1 tijolo = ½ + 1 kg) | D ✅🖼️ |
| 2024/F1/Q2 | M2-24-F1-Q02 | CM7 | Conjuntos (lápis+borracha+apontador) | 🖼️ |
| 2024/F1/Q3 | M2-24-F1-Q03 | CM3 | Comprimento na régua (lápis × pincel) | D ✅🖼️ |
| 2024/F1/Q4 | M2-24-F1-Q04 | CM6 | Dado 3× soma 17 (qual face) | E ✅ |
| 2024/F1/Q5 | M2-24-F1-Q05 | CM1 | Locomotiva + vagões (2 pistas) | C ✅ |
| 2024/F1/Q6 | M2-24-F1-Q06 | CM6 | Regra condicional (branco⇒preto) | D ✅🖼️ |
| 2024/F1/Q7 | M2-24-F1-Q07 | CM6 | Pinóquio (nariz 18 cm; qual verdade) | B ✅ |
| 2024/F1/Q8 | M2-24-F1-Q08 | CM7 | Tipos de bola (3×3 com restrição) | B ✅ |
| 2024/F1/Q9 | M2-24-F1-Q09 | CM5 | Perímetro de região (composição) | 🖼️ |
| 2024/F1/Q10 | M2-24-F1-Q10 | CM6 | Corrida (dedução de posições) | C ✅ |
| 2024/F1/Q11 | M2-24-F1-Q11 | CM1 | Soma linha de cima = de baixo (★) | C ✅ |
| 2024/F1/Q12 | M2-24-F1-Q12 | CM6 | Torneio (nº de jogos; grafo) | B ✅ |
| 2024/F1/Q13 | M2-24-F1-Q13 | CM4 | Dia da semana (5 falas; quem erra) | E ✅ |
| 2024/F1/Q14 | M2-24-F1-Q14 | CM7 | Flores em 2 vasos (≥1 de cada) | B ✅ |
| 2024/F1/Q15 | M2-24-F1-Q15 | CM6 | Moedas (casa dos pombos) | C ✅ |
| 2024/F2/Q1 | M2-24-F2-Q01 | CM7 | Contar triângulos brancos (mosaico) | 🖼️ |
| 2024/F2/Q2 | M2-24-F2-Q02 | CM7 | Pintar até pretas = 2× brancas | D ✅🖼️ |
| 2024/F2/Q3 | M2-24-F2-Q03 | CM5 | Vista de cima (21 cubinhos) | 🖼️ |
| 2024/F2/Q4 | M2-24-F2-Q04 | CM7 | Chinelos esq/dir (mínimo de alunos) | 🖼️ |
| 2024/F2/Q5 | M2-24-F2-Q05 | CM5 | Maior contorno (perímetro em malha) | 🖼️ |
| 2024/F2/Q6 | M2-24-F2-Q06 | CM6 | Escolher o gráfico (M=2P=2C=3I) | 🖼️ |
| 2024/F2/Q7 | M2-24-F2-Q07 | CM6 | Colar (mínimo de bolinhas; otimização) | 🖼️ |
| 2024/F2/Q8 | M2-24-F2-Q08 | CM7 | Camiseta × bermuda (cores diferentes) | C ✅ |
| 2024/F2/Q9 | M2-24-F2-Q09 | CM6 | Conjuntos/Venn (só Matemática) | B ✅ |
| 2024/F2/Q10 | M2-24-F2-Q10 | CM4 | Relógio no espelho (reflexão) | A ✅🖼️ |
| 2024/F2/Q11 | M2-24-F2-Q11 | CM1 | Soma de distâncias = 110 (casa) | D ✅ |
| 2024/F2/Q12 | M2-24-F2-Q12 | CM6 | Palhaços (dedução chapéu/gravata/sapato) | E ✅🖼️ |
| 2024/F2/Q13 | M2-24-F2-Q13 | CM6 | Agenda olímpica (intervalos; máximo) | C ✅🖼️ |
| 2024/F2/Q14 | M2-24-F2-Q14 | CM5 | Ladrilhamento (nº de peças vermelhas) | 🖼️ |
| 2024/F2/Q15 | M2-24-F2-Q15 | CM5 | Quadrado em 5 regiões (área das rosas) | 🖼️ |
| 2025/F1/Q1 | M2-25-F1-Q01 | CM8 | Tabela 1–50 (10 colunas, +10/linha); qual peça recortar | C ✅ |
| 2025/F1/Q2 | M2-25-F1-Q02 | CM1 | Diferença maior−menor preço (177−107) | D (70) ✅ |
| 2025/F1/Q3 | M2-25-F1-Q03 | CM5 | Três bolas em tubos cruzados; ordem na saída | 🖼️ |
| 2025/F1/Q4 | M2-25-F1-Q04 | CM3 | Alturas por marcas igualmente espaçadas (maior 175) | B (150) ✅🖼️ |
| 2025/F1/Q5 | M2-25-F1-Q05 | CM7 | Vagas livres × 2 (frente/ré): 11×2 | E (22) ✅🖼️ |
| 2025/F1/Q6 | M2-25-F1-Q06 | CM5 | Sobrepor 4 adesivos centralizados; silhueta (união) | 🖼️ |
| 2025/F1/Q7 | M2-25-F1-Q07 | CM1 | Tabela ração × contagem do aquário; total/dia | D (105) ✅🖼️ |
| 2025/F1/Q8 | M2-25-F1-Q08 | CM8 | Faixa de palitos (casinhas), 30 cm, palito 3 cm | D (51) ✅🖼️ |
| 2025/F1/Q9 | M2-25-F1-Q09 | CM6 | Tabuleiro 3×3 com 1–9; somas de linhas/colunas; casa cinza | A (4) ✅ |
| 2025/F1/Q10 | M2-25-F1-Q10 | CM5 | Figura de 3 quadrados; contorno (perímetro) | B (22) ✅🖼️ |
| 2025/F1/Q11 | M2-25-F1-Q11 | CM5 | Encaixe de 4 peças (forma+cor); nº de quadrados cinza | 🖼️ |
| 2025/F1/Q12 | M2-25-F1-Q12 | CM5 | 5 peças de cubinhos; qual usou mais cola (contatos de face) | 🖼️ |
| 2025/F1/Q13 | M2-25-F1-Q13 | CM6 | Labirinto, regra "vira à direita na parede"; ponto de saída | 🖼️ |
| 2025/F1/Q14 | M2-25-F1-Q14 | CM5 | Encaixe de peça no quadriculado (sem girar); cobre o "?" | 🖼️ |
| 2025/F1/Q15 | M2-25-F1-Q15 | CM6 | Meninas (olhos/boca/laço + lado a lado); ordem esq→dir | 🖼️ |
| 2025/F2/Q1 | M2-25-F2-Q01 | CM5 | Dedos 1–10; cruzou braços, dobrou 2; soma dos dobrados | 🖼️ |
| 2025/F2/Q2 | M2-25-F2-Q02 | CM7 | Contar o algarismo 1 de 10 a 30 | C (12) ✅ |
| 2025/F2/Q3 | M2-25-F2-Q03 | CM5 | 3 carrinhos, meia volta (5s de 10s); posições | 🖼️ |
| 2025/F2/Q4 | M2-25-F2-Q04 | CM6 | Fila (Ana última; Duda entre Bia e Ana); duas primeiras | B ✅ |
| 2025/F2/Q5 | M2-25-F2-Q05 | CM7 | 4 livros (2P+2M) mesma matéria juntos; arranjos | D (8) ✅ |
| 2025/F2/Q6 | M2-25-F2-Q06 | CM1 | Tabela ração, total 105; quanto o polvo come (inverso de F1/Q7) | D (25) ✅🖼️ |
| 2025/F2/Q7 | M2-25-F2-Q07 | CM5 | Cubo 3×3×3 pintado; quantos com exatamente 1 face | B (6) ✅ |
| 2025/F2/Q8 | M2-25-F2-Q08 | CM7 | 10 figuras (2 de cada) distribuídas; o que sobra p/ Elisa | A ✅ |
| 2025/F2/Q9 | M2-25-F2-Q09 | CM6 | Cubo com letras A–F (3 vistas); face oposta a F | 🖼️ |
| 2025/F2/Q10 | M2-25-F2-Q10 | CM1 | Paulinho/Aninha (P+A=25; P+A/2=19); quanto Paulinho tem | B (13) ✅ |
| 2025/F2/Q11 | M2-25-F2-Q11 | CM7 | Virar quadradinhos: xadrez 7×5 → bloco preto 5×3; quantos | D (18) ✅🖼️ |
| 2025/F2/Q12 | M2-25-F2-Q12 | CM6 | Colar 8 miçangas, tira 4 pelas pontas; qual NÃO pode | 🖼️ |
| 2025/F2/Q13 | M2-25-F2-Q13 | CM6 | Cartaz, regras condicionais de cor; combinação possível | E ✅ |
| 2025/F2/Q14 | M2-25-F2-Q14 | CM6 | Doces, tabela de gosto; com o que uma delas ficou | E ✅🖼️ |
| 2025/F2/Q15 | M2-25-F2-Q15 | CM6 | Mágico (4 chapéus↔1 varinha); estado final | A ✅ |

---

## 5. Detalhamento por Caminho

Cada ficha traz: **nome fácil** · `código técnico` · resumo do enunciado, conteúdo/habilidade, elementos de figura (quando houver) e gabarito.

### CM1 — Números, Operações e Problemas Aritméticos (27)

- **2018/Q1** · `NA18-Q01` · Valor de 2018 + 8012. Adição com reagrupamento. → **C (10 030)** ✅
- **2018/Q2** · `NA18-Q02` · Ônibus com 25; descem 7, sobem 5. Operação aditiva sequencial. → **D (23)** ✅
- **2018/Q4** · `NA18-Q04` · Irmã nasceu quando Geraldo tinha 5; hoje ela faz 9. Idade relativa. → **D (14)** ✅
- **2018/Q13** · `NA18-Q13` · Tabela 2×2: soma 1ª linha 8, 2ª linha 3, 1ª coluna 7; achar soma 2ª coluna. Total − coluna conhecida. → **A (4)** ✅
- **2018/Q14** · `NA18-Q14` · Páginas saltam de 24 para 55; quantas faltam. Contagem de inteiros num intervalo (25–54). → **C (30)** ✅
- **2018/Q16** · `NA18-Q16` · Qual resultado é diferente de 52 − 39. Invariância da diferença / equivalência. → **D (54 − 37 = 17)** ✅ *(v3: realocada para o **Bloco 3 — Diferença constante**; é a versão "duas subtrações com o mesmo vão" da diferença que não muda, reforço da idade relativa.)*
- **2020/Q1** · `NA20-Q01` · 2020 − 10 = 2005 + ▢ (borboleta cobre o número). Igualdade/incógnita. → **B (5)** ✅
- **2020/Q4** · `NA20-Q04` · 3 animais com 1 dezena de pés (coelho 4, passarinho 2, peixe 0). → **C (2 coelhos e 1 passarinho)** ✅
- **2020/Q8** · `NA20-Q08` · Andorinha 380 m; bem-te-vi 450 m no meio entre andorinha e canário. Ponto médio. → **D (520)** ✅
- **2020/Q12** · `NA20-Q12` · Maior diferença PAR entre nº de 3 e nº de 2 algarismos. Maximização + paridade (999 − 11). → **B (988)** ✅
- **2022/F1/Q10** · `M2-22-F1-Q10` · Ana 5 anos < Beatriz e 7 anos < Carla (15). → **C (13)** ✅
- **2022/F1/Q12** · `M2-22-F1-Q12` · 3▢ + 2▢ = 61, com a menor diferença entre as parcelas. Lacunas na adição (a+b=11; 32 e 29). → **A (2 e 9)** ✅
- **2022/F2/Q2** · `M2-22-F2-Q02` · Ábaco mostra 142; move 1 disco D→U, depois 1 disco D→C. Valor posicional. → **C (223)** ✅
- **2023/F1/Q1** · `M2-23-F1-Q01` · Qual conta tem o maior resultado: 2+0+2+3 / 20+2+3 / 2+0+23 / 20+23 / **202+3**. Valor posicional × soma de parcelas. → **E (205)** ✅
- **2023/F1/Q4** · `M2-23-F1-Q04` · Ábaco mostra 369 (C=3, D=6, U=9); que número se obtém retirando **exatamente 2 peças**. Retirar 1 da centena + 1 da unidade → 268. Valor posicional. → **E (268)** ✅
- **2023/F1/Q5** · `M2-23-F1-Q05` · Tabela meninos/meninas em 2 salas; Sala 1 = 8+9 = 17; salas com mesmo total; meninos da Sala 2 = 17 − 6. → **D (11)** ✅
- **2023/F1/Q13** · `M2-23-F1-Q13` · Tangerina com 9 gomos, cada um com 2 ou 3 sementes; total 20 sementes; quantos gomos com 3. Mínimo 9·2=18; sobra 2 → 2 gomos com 3. → **B (2)** ✅ *(família "supor o mínimo e distribuir o excedente"; parente de joaninhas `2020/Q14` e pés `2020/Q4`)*
- **2023/F2/Q1** · `M2-23-F2-Q01` · Maior resultado: 2+0+2−3 / 20×2+3 / 2×0×23 / 20+23 / **202−3**. Inclui ×, −, e "× por 0". → **E (199)** ✅ *(gêmea de `2023/F1/Q1` com operações mistas — ótima para ensinar prioridade/efeito do zero)*
- **2023/F2/Q6** · `M2-23-F2-Q06` · Tabela: Sala 1 = 8+6 = 14; Sala 2 tem o **dobro** de estudantes (28) e 8 meninos; meninas da Sala 2 = 28 − 8. → **E (20)** ✅ *(evolução da `2023/F1/Q5`: troca "igual" por "dobro")*
- **2023/F2/Q10** · `M2-23-F2-Q10` · Conta com borrões: ▢023 + 202▢ = 7▢51; reconstruir (5023 + 2028 = 7051) e somar os algarismos borrados (5+8+0). → **B (13)** ✅🖼️ *(parente de `2022/F1/Q12`; confirmar quais casas estão borradas na figura)*

- **2024/F1/Q5** · `M2-24-F1-Q05` · *(lote 2024)* Mesma locomotiva puxa 2 ou 3 vagões iguais; 1º trem 34 m, 2º trem 45 m; achar o comprimento da locomotiva. L+2V=34 e L+3V=45 → V=11, L=12. "Duas pistas para duas quantidades" (subtração das equações). → **C (12 m)** ✅
- **2024/F1/Q11** · `M2-24-F1-Q11` · Linha de cima 1,2,…,7,★ e linha de baixo 2,3,…,9; somas iguais. ★ = (2+…+9) − (1+…+7) = 44 − 28. Igualdade com incógnita (parente de `2020/Q1`). → **C (16)** ✅
- **2024/F2/Q11** · `M2-24-F2-Q11` · Casas nas posições 10, 30, 50, 60 e 80 m; soma das distâncias percorridas por todos = 110; em qual casa estudaram. Testar cada ponto: m=60 dá 50+30+10+0+20 = 110. Soma de distâncias em reta numérica (parente de `2020/Q8`; minimiza perto da mediana). → **D (Duda — casa 60)** ✅

- **2025/F1/Q2** · `M2-25-F1-Q02` · *(lote 2025)* Cinco etiquetas de preço (127, 107, 177, 172, 170); diferença entre o mais caro e o mais barato (177 − 107). Subtração/comparação de valores. → **D (R$ 70,00)** ✅
- **2025/F1/Q7** · `M2-25-F1-Q07` · Tabela de ração por bicho (polvo 25 g, peixe "longo" 15 g, listrado 20 g, redondo 10 g) × contagem no aquário (1 polvo + 2 longos + 1 listrado + 3 redondos); total por dia. Tabela + multiplicação e soma. → **D (105 g)** ✅🖼️ *(contagem conferida na figura; é a "ida" do par F1/Q7 ↔ F2/Q6)*
- **2025/F2/Q6** · `M2-25-F2-Q06` · Mesmo aquário/tabela de F1/Q7, agora **inverso**: total 105 g/dia, polvo = "?"; 105 − (2·15 + 1·20 + 3·10) = 105 − 80. Subtração a partir do total (parente direto de F1/Q7). → **D (25 g)** ✅🖼️ *(mesma contagem de peixes de F1/Q7)*
- **2025/F2/Q10** · `M2-25-F2-Q10` · Paulinho dá tudo → Aninha fica com 25 (P+A=25); Aninha dá **metade** → Paulinho fica com 19 (P + A/2 = 19); quanto tem Paulinho. Sistema limpo → P = 13. "Duas pistas para duas quantidades" (parente de `2024/F1/Q5`). → **B (13)** ✅

### CM2 — Frações, Proporção e Raciocínio Multiplicativo (6)

- **2018/Q18** · `NA18-Q18` · José come ½ das laranjas e ¼ das maçãs; o que sobrou. Fração de quantidades (sobra ¾ + ½ > metade). → **D (mais da metade)** ✅
- **2019/Q6** · `NA19-Q06` · Sanduíche usa 2 fatias; pacote tem 24; 2,5 pacotes (60 fatias). Proporção com "meio pacote". → **C (30)** ✅
- **2020/Q3** · `NA20-Q03` · Conjunto de 4 colheres R$20 e 4 garfos R$28; preço de 2+2. Valor unitário e proporção. → **C (24)** ✅
- **2020/Q6** · `NA20-Q06` · Torta dividida em partes iguais; cada neto come 1 pedaço; figura mostra a sobra. Fração/divisão da figura. → 🖼️ *(conferir: depende de quantos pedaços a figura exibe)*
- **2022/F2/Q13** · `M2-22-F2-Q13` · Jarra = 10 copos = 2 garrafas; 3 garrafas em copos. Proporção (1 garrafa = 5 copos). → **C (15)** ✅
- **2023/F1/Q7** · `M2-23-F1-Q07` · Em qual colar **um terço** das miçangas é preta. Comparar nº de pretas com o total em cada colar (preta = total/3). Fração de quantidade. → 🖼️ *(contar pretas e total em cada opção)*

> **Sem entradas em 2024 — nem em 2025.** Tanto a 3ª quanto a **4ª Edição** passaram em branco em Frações/Proporção: são **dois anos consecutivos sem CM2**. Segue como o Caminho **mais enxuto e mais ameaçado** da base (6 questões, todas de 2018–2023). Decisão para o curso: tratar como **bloco curto/de manutenção**, sustentado pelas questões existentes + gêmeas autorais; **não contar com reforço do banco oficial recente**.

### CM3 — Grandezas e Medidas (13)

- **2018/Q6** · `NA18-Q06` · Altura de figurinha medida com régua que **não começa no zero**. Leitura por diferença. → **B (2 cm)** 🖼️ *(confirmar pelos limites na figura)*
- **2018/Q12** · `NA18-Q12` · 10 bombons de mesmo peso numa balança com peso de 300 g. Massa/divisão. → 🖼️ *(estimativa 50 g; depende da contagem de bombons em cada prato)*
- **2018/Q19** · `NA18-Q19` · Estrada com trecho de 40 km interrompido; desvio (20 + 50 + 30); km a mais. Comprimento de percurso. → **E (60)** 🖼️ *(confirmar geometria do desvio)*
- **2019/Q10** · `NA19-Q10` · Achar o retângulo com a mesma **área** de uma figura recortada em malha. → 🖼️
- **2019/Q15** · `NA19-Q15` · Móbile em equilíbrio; achar o peso do objeto "?". Massa + equilíbrio. → 🖼️
- **2022/F1/Q11** · `M2-22-F1-Q11` · Corrida ida-e-volta até 3 bandeiras (10, 12, 15 m entre marcas). Comprimento total. Bandeiras a 10/22/37 m → 2·(10+22+37). → **E (138)** ✅
- **2022/F1/Q15** · `M2-22-F1-Q15` · R$2,00; compra 1 doce; volta com **3 moedas**. Qual doce com certeza NÃO comprou (troco impossível com 3 moedas). Sistema monetário. → **B (60 centavos)** ✅
- **2022/F2/Q4** · `M2-22-F2-Q04` · 8 bolas (kg) em 2 caixas; transferir 1 para igualar. Caixa A = 1+6+2 = 9; Caixa B = 1+2+3+4+5 = 15; total 24 (12 cada) → transferir bola **3**. Equilíbrio/média. → **C (3)** ✅
- **2022/F2/Q9** · `M2-22-F2-Q09` · Régua de 15 cm com marca a cada mm; total de marcas. 150 intervalos → 151 marcas (efeito "poste"). → **E (151)** ✅
- **2023/F1/Q11** · `M2-23-F1-Q11` · Duas caixas iguais empilhadas de 3 modos; alturas 5 cm e 8 cm; achar a 3ª. As 3 alturas são deitada+deitada, deitada+em pé, em pé+em pé → formam P.A. (5, 8, **11**). → **C (11)** ✅🖼️ *(determinável pela P.A.; confirmar na figura qual pilha é a menor/maior; técnica "duas pistas para duas quantidades" aplicada a medidas)*

- **2024/F1/Q1** · `M2-24-F1-Q01` · *(lote 2024)* Balança equilibrada: 1 tijolo num prato; meio tijolo + 1 kg no outro. Logo ½ tijolo = 1 kg → tijolo = 2 kg. Equilíbrio com foco em **massa/medida** (vide regra: balança vai a CM3 quando se calcula peso). → **D (2 quilos)** ✅🖼️ *(determinável; confirmar leitura da figura)*
- **2024/F1/Q3** · `M2-24-F1-Q03` · Diferença entre os comprimentos do lápis e do pincel, lidos numa régua. Lápis ≈ 1→14 (13 cm), pincel ≈ 0→11 (11 cm) → diferença 2 cm. Comprimento/leitura por diferença (parente de `2018/Q6`, `2018/Q19`). → **D (2 cm)** ✅🖼️ *(confirmar as marcas onde começam/terminam na figura)*

- **2025/F1/Q4** · `M2-25-F1-Q04` · *(lote 2025)* Dois atletas medidos por **marcas igualmente espaçadas** na parede; o maior mede 175 cm; achar a altura do menor. Intervalo = 175/7 = 25 cm; o menor fica uma marca abaixo → 150 (única opção múltipla de 25). Medida por escala/contagem de marcas (parente de `2018/Q6`). → **B (150 cm)** ✅🖼️ *(confirmar quantas marcas cada atleta alcança)*

### CM4 — Tempo, Calendário e Dias da Semana (11)

- **2018/Q8** · `NA18-Q08` · Beatriz faz aniversário 17 dias depois de Antônio (domingo). 17 mod 7 = 3 → domingo+3. → **E (Quarta-feira)** ✅
- **2019/Q2** · `NA19-Q02` · Joana viaja no sábado e volta 9 dias depois. 9 mod 7 = 2 → sábado+2. → **B (Segunda-feira)** ✅
- **2022/F1/Q5** · `M2-22-F1-Q05` · Ontem Maria disse "depois de amanhã será quarta". Logo ontem+2 = quarta → hoje = terça. → **B (Terça-feira)** ✅
- **2022/F1/Q6** · `M2-22-F1-Q06` · Padeiro leva 45 min; relógio mostra a hora de tirar os pães; achar a hora em que pôs (−45 min). Leitura de relógio. → 🖼️
- **2022/F2/Q6** · `M2-22-F2-Q06` · 1º jan 2000 = sábado; que dia foi 31 jan. +30 dias; 30 mod 7 = 2 → sábado+2. → **A (Segunda-feira)** ✅
- **2023/F1/Q6** · `M2-23-F1-Q06` · "Hoje é dia 15 e amanhã será sexta" → dia 15 = quinta; "próxima quarta-feira" → 15 + 6 = 21. Dia do mês por contagem de dias da semana. → **C (21)** ✅
- **2023/F2/Q2** · `M2-23-F2-Q02` · 1º jul 2023 = sábado; qual dia listado **NÃO** caiu em sábado. Sábados: 1, 8, 15, 22, 29; logo 27 não é. Calendário (mesmo dia a cada 7). → **D (27)** ✅
- **2023/F2/Q3** · `M2-23-F2-Q03` · Relógio **10 min atrasado** marcando ~3h05; hora certa = +10 min. Leitura de relógio analógico + correção. → **C (3h15)** ✅🖼️ *(confirmar a leitura dos ponteiros na figura)*
- **2023/F2/Q7** · `M2-23-F2-Q07` · Tempo de ida = tempo de volta; ida 06:24→07:52 (1h28); volta saiu 15:32; chegada = 15:32 + 1h28. Duração e soma de horário. → **B (17h00)** ✅

- **2024/F1/Q13** · `M2-24-F1-Q13` · *(lote 2024)* Cinco amigos esqueceram o dia da semana; cada um faz uma afirmação ("ontem foi quarta", "amanhã será sexta", "anteontem foi terça", "depois de amanhã será sábado", "hoje é segunda"). Apenas um errou. Quatro convergem para **quinta-feira**; só Ernesto ("segunda") destoa. Consistência de falas + dias da semana. → **E (Ernesto)** ✅
- **2024/F2/Q10** · `M2-24-F2-Q10` · Relógio visto no **espelho retrovisor**; que horas marcava. Lido como ~7h30 no espelho → hora real = 12h00 − 7h30 = **4h30** (ponteiro de minutos para baixo = :30; ponteiro de horas espelhado). Leitura de relógio analógico + **reflexão** (ponte com CM5; parente de `2019/Q3`). → **A (4h30)** ✅🖼️ *(confirmar a posição dos ponteiros)*

> **Sem entradas em 2025.** A 4ª Edição **não trouxe nenhuma questão de Tempo/Calendário** (a 3ª ainda tivera duas: dia da semana `2024/F1/Q13` e relógio no espelho `2024/F2/Q10`). CM4 fica em 11; manter como unidade própria (a faixa etária ainda cobra calendário/relógio), mas vigiar se a ausência vira tendência.

### CM5 — Geometria e Percepção Espacial (36)

- **2018/Q5** · `NA18-Q05` · Caminho mais curto entre escola e circo (labirinto/malha). Percepção + comprimento. → 🖼️
- **2018/Q7** · `NA18-Q07` · 5 quadrados sobrepostos um a um; descobrir a ordem. Sobreposição/oclusão. → 🖼️
- **2018/Q11** · `NA18-Q11` · Retângulo com casas brancas transparentes sobreposto a outro; qual fica todo preto. Sobreposição. → 🖼️
- **2018/Q15** · `NA18-Q15` · Planificação que monta cubo com faces opostas da mesma cor. Planificação. → 🖼️
- **2019/Q3** · `NA19-Q03` · Imagem do palhaço vista no espelho. Reflexão (simetria espelhada). → 🖼️
- **2019/Q4** · `NA19-Q04` · Qual linha é mais comprida (traçados em malha quadriculada). Comparação visual de comprimento. → 🖼️
- **2019/Q5** · `NA19-Q05` · Espelho partido; qual é o pedaço que falta. Encaixe/complemento. → 🖼️
- **2019/Q11** · `NA19-Q11` · Peças pretas-e-brancas (frente/verso) de um quebra-cabeça; qual NÃO foi usada. Orientação/giro. → 🖼️
- **2020/Q2** · `NA20-Q02` · 3 triângulos, 5 quadrados, 4 círculos; apagam-se as figuras de 4 lados; quantas sobram. Classificação por nº de lados (3+4). → **E (7)** ✅
- **2020/Q15** · `NA20-Q15` · Planificação recortada → qual cubo se obtém. Planificação + posição das faces coloridas. → 🖼️
- **2022/F1/Q1** · `M2-22-F1-Q01` · Encaixar peças de quebra-cabeça (algarismos 6, 4, 8); qual número aparece. Orientação de algarismos. → 🖼️ *(estimativa 648/684)*
- **2022/F1/Q2** · `M2-22-F1-Q02` · Traçado de um castelo; qual alternativa NÃO é um pedaço do desenho. Reconhecimento de trecho de contorno. → 🖼️
- **2022/F1/Q4** · `M2-22-F1-Q04` · Qual fechadura a chave desenhada consegue abrir. Encaixe/silhueta complementar. → 🖼️
- **2022/F1/Q8** · `M2-22-F1-Q08` · 4 das figuras são a mesma roda-gigante; qual NÃO é. Rotação/invariância sob giro. → 🖼️
- **2022/F1/Q9** · `M2-22-F1-Q09` · Dois triângulos iguais (juntos ou empilhados); qual figura NÃO pode ser montada. Composição de figuras. → **C (estrela)** 🖼️ *(2 triângulos não formam estrela de 6 pontas; confirmar opções)*
- **2022/F1/Q13** · `M2-22-F1-Q13` · Caminho de casa à escola com 4 viradas à esquerda e 2 à direita. Lateralidade/sequência de giros. → 🖼️
- **2022/F1/Q14** · `M2-22-F1-Q14` · Recortar folha quadrada (malha 1 cm) e remontar em quadradinhos iguais ao central; quantos no total. Decomposição/área. → 🖼️
- **2022/F2/Q5** · `M2-22-F2-Q05` · Torres de cubinhos num círculo, com o nº no topo; o que se vê **de cima**. Vista superior + leitura. → 🖼️
- **2023/F1/Q10** · `M2-23-F1-Q10` · Pilha de cubos vista de frente, de lado e de cima; qual pilha corresponde às 3 vistas. Reconstrução a partir de vistas ortogonais. → 🖼️ *(parente de `2022/F2/Q5` e `2023/F2/Q11`)*
- **2023/F2/Q11** · `M2-23-F2-Q11` · 7 cubinhos empilhados, 1 escondido atrás; qual é a **vista de cima**. Vista superior com cubo oculto. → 🖼️
- **2023/F2/Q13** · `M2-23-F2-Q13` · Planificação (rostinhos) dobrada em cubo; qual desenho fica na face "?". Planificação + orientação das faces. → 🖼️ *(parente de `2018/Q15`, `2020/Q15`)*
- **2023/F2/Q14** · `M2-23-F2-Q14` · Cubo de 2 cm dividido em **4 peças iguais**; qual pode ser uma peça. Decomposição de sólido / volume (cada peça = 2 cm³). → 🖼️ *(provável prisma triangular; confirmar opções)*

- **2024/F1/Q9** · `M2-24-F1-Q09` · *(lote 2024)* Figura com 2 quadrados iguais + 2 triângulos iguais (lados todos iguais); contorno destacado da figura = 24 cm; achar o contorno de toda a **região cinza**. Composição/decomposição de figuras com lados congruentes (perímetro por partes). → 🖼️ *(depende da leitura da figura; conferir gabarito oficial)*
- **2024/F2/Q3** · `M2-24-F2-Q03` · Montagem com 21 cubinhos vista **de cima**; qual desenho corresponde à vista superior. Vista superior / projeção (parente de `2022/F2/Q5`, `2023/F1/Q10`, `2023/F2/Q11`). → 🖼️
- **2024/F2/Q5** · `M2-24-F2-Q05` · Cinco figuras numa malha de quadradinhos; qual tem o **maior contorno**. Comparar perímetros em malha (parente de `2019/Q4`). → 🖼️
- **2024/F2/Q14** · `M2-24-F2-Q14` · Quadriculado preenchido com **peças iguais** sem sobreposição; além de 3 peças já postas, +3 verdes, +2 amarelas e algumas vermelhas; total de vermelhas. Ladrilhamento/decomposição por peças congruentes (parente de `2022/F1/Q14`). → 🖼️ *(contar células da malha e o tamanho da peça; conferir gabarito)*
- **2024/F2/Q15** · `M2-24-F2-Q15` · Quadrado maior dividido em 5 regiões; região azul = 15 quadradinhos pretos, amarela = 8, preto = 1; achar a **área de cada retângulo rosa**. Área por decomposição/relação entre regiões. → 🖼️ *(conferir gabarito oficial)*

- **2025/F1/Q3** · `M2-25-F1-Q03` · *(lote 2025)* Três bolas (1,2,3) soltas ao mesmo tempo em tubos que se cruzam; ordem em que saem. Seguir o trajeto dos tubos (rastreamento de caminho / percepção espacial). → 🖼️
- **2025/F1/Q6** · `M2-25-F1-Q06` · Quatro adesivos (losango, quadrado, elipse em pé, elipse deitada) colados **centralizados, sem girar**; qual a silhueta resultante. União das formas sobrepostas (sobreposição/oclusão; parente de `2018/Q7`, `2018/Q11`). → 🖼️
- **2025/F1/Q10** · `M2-25-F1-Q10` · Figura de **3 quadrados** em escada (base 4 cm, degrau 3 cm); medida do contorno. Escada monótona → perímetro = 2·(largura + altura) = 2·(7+4). Contorno de figura composta (parente de `2024/F1/Q9`, `2024/F2/Q5`). → **B (22 cm)** ✅🖼️
- **2025/F1/Q11** · `M2-25-F1-Q11` · Encaixar 4 peças de quebra-cabeça respeitando **forma e cor**; quantos quadrados cinza se formam. Montagem/encaixe espacial + contagem do resultado. → 🖼️
- **2025/F1/Q12** · `M2-25-F1-Q12` · Cinco peças feitas de cubinhos; em qual há **mais pingos de cola** (mais faces em contato). Contagem de contatos internos em poliedros (percepção 3D). → 🖼️
- **2025/F1/Q14** · `M2-25-F1-Q14` · Quebra-cabeça num quadriculado **sem girar nem virar**; qual das 5 peças cobre o "?". Encaixe/ladrilhamento por forma e posição (parente de `2022/F1/Q14`, `2024/F2/Q14`). → 🖼️
- **2025/F2/Q1** · `M2-25-F2-Q01` · Dedos numerados 1–10; vira as mãos, **cruza os braços** e dobra 2 dedos; soma dos números dobrados. Transformação espacial (orientação após cruzar/virar) + leitura. → 🖼️
- **2025/F2/Q3** · `M2-25-F2-Q03` · Três carrinhos na pista (volta em 10 s) após **5 s = meia volta**; configuração final. Cada carro vai à posição **oposta** (rotação de 180°; parente da roda-gigante `2022/F1/Q8`). → 🖼️
- **2025/F2/Q7** · `M2-25-F2-Q07` · Cubo pintado de vermelho cortado em **27 cubinhos** (3×3×3); quantos têm **exatamente uma** face pintada. Os 6 centros de face → 6. Decomposição 3D / cubo pintado. → **B (6)** ✅

### CM6 — Raciocínio Lógico e Dedução (43)

- **2018/Q3** · `NA18-Q03` · Soma dos números dentro do círculo **e** do retângulo, mas **fora** do triângulo. Leitura de diagrama (Venn). → 🖼️
- **2018/Q17** · `NA18-Q17` · Fila: Maria tem 17 atrás (um é Tiago); Tiago tem 14 à frente (uma é Maria); 5 alunos entre eles. Posições. → **D (26)** ✅
- **2018/Q20** · `NA18-Q20` · Casas coloridas com pistas de vizinhança; cor da casa nº 4. Cadeia dedutiva. → **D (verde)** ✅
- **2019/Q9** · `NA19-Q09` · 6 pesos (1–6 g) em 3 gavetas; gaveta 1 soma 9, gaveta 2 soma 8; achar a 3ª. Total 21 − 17 = 4 = {1,3}. → **A (1 g e 3 g)** ✅
- **2019/Q12** · `NA19-Q12` · 5 amigas em 2 andares (2 + 3); restrições de "não no mesmo andar". → **E (Ana e Olga)** ✅
- **2019/Q14** · `NA19-Q14` · Com 5,6,7,8,9 (cada um 1 vez): soma de 3 menos soma de 2. Resultado = 2·S₃ − 35 (sempre ímpar). → **D (11)** ✅
- **2020/Q5** · `NA20-Q05` · Elevador (máx 180 kg) para 6 pessoas (375 kg total); mínimo de viagens. ≥3 e dá em 3 (145/125/105). → **B (3)** ✅
- **2020/Q7** · `NA20-Q07` · Sala→armários→caixas, todos com cadeado; pegar 52 celulares (caixa = 10). 6 caixas em 2 armários: 1+2+6. → **E (9)** ✅
- **2020/Q10** · `NA20-Q10` · Feira: pato = 2 galinhas; leitão + 3 patos = cabra; 2 patos + 2 galinhas = leitão. Cabra em patos. C = 6p. → **D (6)** ✅
- **2020/Q11** · `NA20-Q11` · 8 peças num tabuleiro 4×4; mover para vizinhas até 2 por linha e 2 por coluna; mínimo de movimentos. → 🖼️
- **2020/Q13** · `NA20-Q13` · Faces de cubo 1–6; um par oposto soma 3 (= {1,2}); qual soma os outros pares **com certeza não** dão. Min de par em {3,4,5,6} é 7. → **A (6)** ✅
- **2020/Q14** · `NA20-Q14` · Joaninhas pequenas 5 pintas, grandes 6; total 43. 5p + 6g = 43 → única solução (5+3) = 8. → **C (8)** ✅
- **2022/F2/Q11** · `M2-22-F2-Q11` · 3 cartas com figuras nos 2 lados (sem repetição), postas de 3 maneiras; achar o verso da carta com o Sol. Dedução de pares. → 🖼️
- **2022/F2/Q12** · `M2-22-F2-Q12` · 13 alunos, 12 meses; o que ocorre com certeza. **Princípio da casa dos pombos**. → **B (um mês com 2 ou mais)** ✅
- **2022/F2/Q14** · `M2-22-F2-Q14` · Cubo com apenas 1, 2 e 4 (cada um ao menos 1 face); faces visíveis 1,1,4; afirmação certa. Soma mín. = 10. → **B (soma ≥ 10)** ✅
- **2022/F2/Q15** · `M2-22-F2-Q15` · Jogo de senha (3 algarismos) com pistas verm/amarela/verde (estilo Mastermind). → **B (130)** ✅
- **2023/F1/Q8** · `M2-23-F1-Q08` · Quatro balanças de 2 pratos comparando 5 bolinhas; achar a **mais pesada**. Ordenação por transitividade (não é cálculo de massa). → 🖼️ *(balança classificada em CM6 quando o foco é ordenar/deduzir, não medir — vide regra de classificação)*
- **2023/F1/Q12** · `M2-23-F1-Q12` · Tabela de marcas (sexta 4, sábado 5, domingo 3); qual **gráfico de barras** representa. Leitura/correspondência de dados. → 🖼️ *(barras: sábado > sexta > domingo)*
- **2023/F1/Q14** · `M2-23-F1-Q14` · Roda gigante; cabine 6 no ponto mais baixo, cabine 21 no mais alto (opostas). Opostas distam meia-volta → nº de cabines = 2·(21−6). → **C (30)** ✅
- **2023/F2/Q5** · `M2-23-F2-Q05` · Corredor de hotel: um lado ímpares crescentes (1,3,…,19), outro pares decrescentes (20,18,…,2); qual está em frente ao 17. Quarto 17 = posição 9; em frente = 22 − 2·9. → **D (4)** ✅
- **2023/F2/Q8** · `M2-23-F2-Q08` · Dado com faces opostas somando 7; face de cima coberta e **ímpar**; quantos pontos. Dedução faces de dado. → 🖼️ *(resposta ímpar: 1, 3 ou 5; depende das faces visíveis — conferir gabarito)*
- **2023/F2/Q12** · `M2-23-F2-Q12` · 5 cartões com números nas bordas; dois só se unem com bordas iguais; qual vai na casa central (cinza). Encaixe por correspondência (tipo dominó). → 🖼️
- **2023/F2/Q15** · `M2-23-F2-Q15` · Prateleira: 6 livros à esquerda do mais grosso, 7 à direita do mais fino; mais grosso e mais fino ladeiam o mais velho; **mínimo** de livros. Sobreposição máxima das condições (fino–velho–grosso nas posições 5-6-7). → **C (12)** ✅ *(parente de `2018/Q17`)*

- **2024/F1/Q4** · `M2-24-F1-Q04` · *(lote 2024)* Dado lançado 3 vezes, soma 17 nas faces de cima; qual face certamente apareceu. Único modo: 6+6+5 → o **5** é obrigatório. Dedução a partir de soma com dados. → **E (5)** ✅
- **2024/F1/Q6** · `M2-24-F1-Q06` · Regra condicional: se pintar uma figura de branco, ao menos outra deve ser preta; qual desenho **não pode** ser o de Ana. Viola quem tem branco sem nenhum preto. Lógica condicional/contraexemplo. → **D** ✅🖼️ *(confirmar as cores de cada opção)*
- **2024/F1/Q7** · `M2-24-F1-Q07` · Nariz de Pinóquio: 3 cm normal, +5 por mentira, volta a 3 na verdade; após 5 falas mede 18 cm. 18 = 3 + 3×5 → as 3 últimas foram mentiras e a 2ª foi a última verdade. Raciocínio "de trás para frente" com acúmulo/reset. → **B (a segunda)** ✅
- **2024/F1/Q10** · `M2-24-F1-Q10` · Corrida: Abel 2º; nem Carlos nem Dudu em 3º; Beto logo atrás de Emanuel; sem empates. Único arranjo válido põe Emanuel em 3º (Beto 4º). Dedução/ordenação com pistas. → **C (3º)** ✅
- **2024/F1/Q12** · `M2-24-F1-Q12` · Campeonato entre 5 jogadores (cada par no máx. uma vez); jogador 1 jogou 1, o 3º jogou 2, o 4º jogou 3, o 5º jogou 4; quantas o 2º jogou. Dedução de "graus" num grafo de partidas → 2º jogou 2. → **B (duas)** ✅
- **2024/F1/Q15** · `M2-24-F1-Q15` · 3+3+3 moedas (3 tipos); tira 4 sem olhar; o que é certo. Com 3 tipos e 4 retiradas, **casa dos pombos** garante 2 do mesmo tipo. → **C (ao menos duas de um mesmo tipo)** ✅
- **2024/F2/Q6** · `M2-24-F2-Q06` · M = 2P = 2C = 3I; qual **gráfico de barras** representa. Alturas na razão 6:3:3:2 (P = C; I pouco menor). Leitura/escolha de gráfico (parente de `2023/F1/Q12`). → 🖼️ *(tentativa E; conferir alturas no gabarito)*
- **2024/F2/Q7** · `M2-24-F2-Q07` · Tirar todas as estrelas do colar pelo cordão sem cortar; **mínimo de bolinhas** a remover. Otimização sobre a sequência de contas/estrelas no fio (parente de `2020/Q7`, `2023/F2/Q15`). → 🖼️
- **2024/F2/Q9** · `M2-24-F2-Q09` · 36 alunos; 28 gostam de Português, 32 de Matemática, 1 de nenhum; quantos gostam de Mat. **mas não** de Port. União = 35 → interseção = 25 → só Matemática = 7. Conjuntos/Venn (inclusão–exclusão). → **B (7)** ✅
- **2024/F2/Q12** · `M2-24-F2-Q12` · Três palhaços; pistas de igualdade/desigualdade sobre chapéus, gravatas e sapatos; achar o conjunto de Zé Grilo. Gravata única (azul) força os outros dois ao par; dedução fecha verde/azul/cinza. Lógica de associação (grade). → **E (chapéu verde, gravata azul, sapato cinza)** ✅🖼️ *(confirmar as figuras das opções)*
- **2024/F2/Q13** · `M2-24-F2-Q13` · Gráfico de horários de modalidades olímpicas; **máximo** de modalidades assistidas inteiras sem sobreposição. Seleção gulosa de intervalos por término → 5. Leitura de gráfico + otimização de intervalos. → **C (5)** ✅🖼️ *(confirmar os horários de início/fim no gráfico)*

- **2025/F1/Q9** · `M2-25-F1-Q09` · *(lote 2025)* Tabuleiro 3×3 com 1–9; somas das duas primeiras linhas (6 e 22) e colunas (20 e 14); achar a **casa cinza** (linha 3, coluna 3). Dedução por mín/máx e unicidade: {3,2,1 / 9,7,6 / 8,5,4} → 4. Puzzle lógico-aritmético (estilo KenKen). → **A (4)** ✅
- **2025/F1/Q13** · `M2-25-F1-Q13` · Roberto anda reto e **vira à direita** ao bater na parede; por qual ponto sai do labirinto. Aplicar regra de movimento determinística (procedimento lógico; ponte com CM5 pela navegação). → 🖼️
- **2025/F1/Q15** · `M2-25-F1-Q15` · Cinco meninas com pistas (olhos abertos / boca aberta / laço) + "Duda e Ana lado a lado"; ordem esq→dir. Cada menina fica única por (olhos, boca, laço); dedução por tabela de atributos. → 🖼️
- **2025/F2/Q4** · `M2-25-F2-Q04` · Fila de 4 (Ana **última**; Duda **entre** Bia e Ana); as duas primeiras. Bia-Duda-Ana ocupam 2-3-4 → Carla é 1ª. Ordenação por pistas (parente de `2024/F1/Q10`). → **B (Carla e Bia)** ✅
- **2025/F2/Q9** · `M2-25-F2-Q09` · Cubo com letras A–F rolado 3 vezes; achar a face **oposta a F**. Dedução de faces opostas a partir de vistas (faces de cubo → CM6, vide regra). → 🖼️
- **2025/F2/Q12** · `M2-25-F2-Q12` · Colar de 8 miçangas; remove 4 **pelas pontas**; qual alternativa **NÃO** é possível. O que resta tem de ser um trecho **contíguo** do original; a opção não-contígua é impossível. Lógica de remoção pelas extremidades (parente de `2024/F2/Q7`). → 🖼️
- **2025/F2/Q13** · `M2-25-F2-Q13` · Cartaz com regras condicionais (amarela⇒¬branca; cinza⇒¬dourada; cinza⇒branca); qual combinação é possível. Só **branca+dourada** satisfaz tudo. Lógica condicional (parente de `2024/F1/Q6`). → **E (branca e dourada)** ✅
- **2025/F2/Q14** · `M2-25-F2-Q14` · Seis doces (2 laranja, 2 rosa, 2 azul) divididos 3-3 por **tabela de gosto** (Ana ¬azul; Bia ¬rosa); com o que uma delas fica. Força: Ana = {1 laranja, 2 rosa}; Bia = {1 laranja, 2 azul}. Dedução por preferências. → **E (Bia: 1 laranja + 2 azul)** ✅🖼️
- **2025/F2/Q15** · `M2-25-F2-Q15` · Mágico: 4 chapéus→1 varinha e 4 varinhas→1 chapéu; transforma **enquanto possível**; de 3 chapéus + 7 varinhas, o que sobra. Processo iterativo até estabilizar → 1 chapéu. Transformações sucessivas / invariante. → **A (1 chapéu)** ✅

### CM7 — Contagem e Combinatória (23)

- **2018/Q9** · `NA18-Q09` · Quantos quadrados brancos pintar para igualar pretos e brancos. Contagem em malha. → 🖼️
- **2019/Q1** · `NA19-Q01` · Qual letra aparece mais vezes no quadro espalhado. Contagem de ocorrências. → 🖼️ *(estimativa: E)*
- **2019/Q13** · `NA19-Q13` · Preencher quadriculado 3×3 com 1,2,3 sem repetir em linha/coluna (1 já dado); de quantas maneiras. Quadro latino. → 🖼️
- **2020/Q9** · `NA20-Q09` · Sapatos misturados; quantos pares (pé direito + esquerdo, mesmo número). Pareamento por atributos. → 🖼️
- **2022/F1/Q7** · `M2-22-F1-Q07` · Par ou ímpar: Paula (par) já mostrou a mão; de quantas maneiras Isabel ganha. Contagem por paridade (soma ímpar). → **C (3)** 🖼️ *(depende de quantos dedos Paula mostra)*
- **2022/F2/Q3** · `M2-22-F2-Q03` · Crianças carimbaram as mãos; todas a esquerda; quantas esqueceram a direita. Contagem/pareamento esq–dir. → 🖼️
- **2022/F2/Q7** · `M2-22-F2-Q07` · 6 meninos em fila, 3 meninas entre cada par. Intervalos (5 espaços) → 6 + 15. → **D (21)** ✅
- **2023/F1/Q3** · `M2-23-F1-Q03` · Mãos carimbadas dispostas em círculo; quantas vezes carimbou a mão **esquerda**. Contagem por orientação (esq × dir). → 🖼️ *(parente de `2022/F2/Q3`)*
- **2023/F1/Q9** · `M2-23-F1-Q09` · Escolher 2 algarismos de 1023 ({1,0,2,3}) e multiplicar; quantos resultados **diferentes**. Produtos: {0, 2, 3, 6} → 4. Combinações + contagem de valores distintos. → **D (4)** ✅
- **2023/F1/Q15** · `M2-23-F1-Q15` · 4 ervas; chás com 1 ou mais; **anis e hortelã nunca juntos**; quantos chás. 2⁴−1 = 15 menos os 4 que têm anis+hortelã = 11. Subconjuntos com restrição. → **E (11)** ✅
- **2023/F2/Q9** · `M2-23-F2-Q09` · Escrever todos os números de 2000 a 2023; quantas vezes aparece o algarismo **zero**. Contagem por casa (centena fixa 0 = 24; dezena/unidade = 13) → 37. Contagem sistemática de ocorrências. → **E (37)** ✅ *(parente de `2019/Q1`; ótima para ensinar contagem por posição)*

- **2024/F1/Q2** · `M2-24-F1-Q02` · *(lote 2024)* Quantos conjuntos com 1 lápis + 1 borracha + 1 apontador dá para formar com os objetos da figura. Resposta = **menor contagem** entre os três tipos (pareamento limitado pelo mais escasso). → 🖼️ *(contar lápis × borrachas × apontadores; resposta = o menor; tentativa D 5)*
- **2024/F1/Q8** · `M2-24-F1-Q08` · Bolas em 3 tamanhos × 3 cores; deixa de fabricar verde-pequena e amarelas (todos os tamanhos); quantos tipos restam. 9 − 1 − 3 = 5. Contagem com restrição/subtração de casos. → **B (5)** ✅
- **2024/F1/Q14** · `M2-24-F1-Q14` · 2 vasos diferentes, 4 rosas iguais, 3 margaridas iguais; ao menos uma flor de cada tipo em cada vaso; de quantas maneiras. Rosas: 3 modos (1,2,3 num vaso); margaridas: 2 modos; total 3×2. Contagem com restrição (≥1 de cada). → **B (6)** ✅
- **2024/F2/Q1** · `M2-24-F2-Q01` · Quantos **triângulos brancos** há no mosaico (malha 4×4 com diagonais). Contagem direta de figuras na malha. → 🖼️ *(tentativa C 12; conferir contagem)*
- **2024/F2/Q2** · `M2-24-F2-Q02` · Quantas bolinhas brancas pintar de preto para que pretas = **dobro** das brancas. 9 bolinhas (2 pretas, 7 brancas): 2+x = 2(7−x) → x = 4. Contagem + relação de dobro (parente de `2018/Q9` "pintar para igualar"). → **D (4)** ✅🖼️ *(contagem confirmada: 9 no total, 2 pretas)*
- **2024/F2/Q4** · `M2-24-F2-Q04` · Chinelos (esquerdo/direito) retirados; **menor número de alunos** que podem ter participado. Mínimo = maior entre (nº de pés esquerdos) e (nº de pés direitos) mostrados. Pareamento esq/dir (parente de `2022/F2/Q3`, `2023/F1/Q3`). → 🖼️ *(contar pés esq × dir; tentativa B 4)*
- **2024/F2/Q8** · `M2-24-F2-Q08` · 4 camisetas × 3 bermudas; quantas combinações com **cores diferentes**. 12 totais − 2 de cor igual (branca-branca, azul-azul) = 10. Contagem com restrição (excluir coincidências). → **C (10)** ✅

- **2025/F1/Q5** · `M2-25-F1-Q05` · *(lote 2025)* Garagem de 2 fileiras de **7 vagas** (14 no total), 3 ocupadas → 11 livres; cada vaga aceita "de frente ou de ré" (×2). 11 × 2 = 22. Contagem com fator de orientação. → **E (22)** ✅🖼️ *(contagem de vagas conferida na figura)*
- **2025/F2/Q2** · `M2-25-F2-Q02` · Escrever de 10 a 30; quantas vezes aparece o algarismo **1**. Dezenas 10–19 = 10 + o "1" extra do 11 = 11; mais o 21 → 12. Contagem de ocorrências por posição (parente de `2019/Q1`, `2023/F2/Q9`). → **C (12)** ✅
- **2025/F2/Q5** · `M2-25-F2-Q05` · Guardar 4 livros (2 Português, 2 Matemática) com os de **mesma matéria juntos**; de quantos modos. Blocos: 2! (ordem dos blocos) × 2! × 2! (internos) = 8. Arranjos com agrupamento. → **D (8)** ✅
- **2025/F2/Q8** · `M2-25-F2-Q08` · Dez figuras (2 de cada de 5 tipos) distribuídas a 5 crianças; o que sobra para **Elisa**. Inventário: restam 1 estrela + 1 coração. Contagem por eliminação (parente de `2024/F1/Q8`). → **A (estrela e coração)** ✅
- **2025/F2/Q11** · `M2-25-F2-Q11` · Quadradinhos branco/verso-preto; quantos **virar** para o xadrez 7×5 (canto branco) virar um bloco preto **5×3** central. Diferenças = 8 (brancas dentro) + 10 (pretas fora) = 18. Contagem de células que mudam (parente de `2018/Q9`, `2024/F2/Q2`). → **D (18)** ✅🖼️

### CM8 — Sequências, Padrões e Regularidades (11)

- **2018/Q10** · `NA18-Q10` · Sequência de triângulos pequenos; 4ª figura tem 16; achar a 5ª. Quadrados perfeitos (n²). → **C (25)** ✅
- **2019/Q7** · `NA19-Q07` · Soma dos algarismos de 2019 é 12; daqui a quantos anos volta a ser 12. Próximo ano: 2028. → **C (9)** ✅
- **2019/Q8** · `NA19-Q08` · Mesas quadradas (4 cadeiras; 2 juntas = 6); 10 mesas em fila. Padrão 2n + 2. → **B (22)** ✅
- **2022/F1/Q3** · `M2-22-F1-Q03` · 1 carrinho 70 cm; 2 encaixados 80 cm; 5 encaixados. Padrão linear (70 + 10·(n−1)). → **B (110)** ✅
- **2022/F2/Q1** · `M2-22-F2-Q01` · Estrelas feitas com pares de polígonos iguais (triângulo→6, quadrado→8 pontas); pentágono. Padrão 2n. → **C (10)** ✅
- **2022/F2/Q8** · `M2-22-F2-Q08` · Pilhas de cubinhos 1, 4, 10, 20…; achar a 5ª. **Números tetraédricos** (próximo 35). → **A (35)** ✅
- **2022/F2/Q10** · `M2-22-F2-Q10` · 22/02/2022 é palíndromo; qual outra data também é. Regularidade simétrica. → **C (13/02/2031)** ✅
- **2023/F1/Q2** · `M2-23-F1-Q02` · Fila de figuras que se repetem "de 4 em 4" (período 4: ■○▲△); 9ª figura é ■; próximas 3 = posições 2-3-4 do ciclo. Padrão periódico. → **A (○ ▲ △)** ✅
- **2023/F2/Q4** · `M2-23-F2-Q04` · Tabuleiros com **as duas diagonais** pintadas (3×3, 5×5, 7×7, 9×9); contar os pretos do maior (coberto). Padrão 2n−1 (5, 9, 13, **17**). → **C (17)** ✅🖼️ *(confirmar os tamanhos dos tabuleiros visíveis na figura)*

- **2025/F1/Q1** · `M2-25-F1-Q01` · *(lote 2025)* Tabela preenchida 1→50 em **10 colunas** (cada linha +10); qual "peça" (tetrominó) pode ser recortada. Usar a **regularidade posicional** (abaixo = +10, ao lado = +1): só 22-32-33-43 é coerente. Padrão de grade numérica (com recorte espacial). → **C** ✅
- **2025/F1/Q8** · `M2-25-F1-Q08` · Faixa de "casinhas" com palitos de 3 cm num total de 30 cm (10 casas, paredes compartilhadas); quantos palitos. Base 10 + paredes 11 + topos 10 + telhados 20 = 51 (regra 5n+1). Padrão de crescimento com **palitos** (matchstick → CM8). → **D (51)** ✅🖼️

> **CM8 voltou em 2025.** Depois do branco da 3ª Edição, a 4ª trouxe **2 questões** (tabela numérica `2025/F1/Q1` e palitos `2025/F1/Q8`), levando o bloco a 11. Em 2024 o eixo de regularidades ficara totalmente ausente; 2025 o repõe — note que o tipo mudou: não veio padrão figural "clássico", e sim **regularidade de grade numérica** e **palitos** (crescimento linear). Para o curso: manter CM8 como bloco médio (11), agora com um exemplar recente de cada subtipo (numérico-posicional e matchstick).

---

## 6. Notas para o sequenciamento do curso

1. **Backbone do curso = CM1 → CM6 → CM5.** Os três pilares por volume (CM1 **27**, CM6 **43**, CM5 **36**) e por dependência conceitual. CM1 sustenta tudo; CM5 e CM6 carregam o "DNA olímpico" da Mirim e, com 2024–2025, se consolidam como o coração absoluto da prova: **CM6 + CM5 = 79 de 170 questões (46%)**. A 3ª Edição despejou 16 das suas 30 questões nesses dois Caminhos; a 4ª despejou **18 de 30** (CM5 e CM6 empatados em 9 cada). CM7 (**23**) firmou-se como quarto pilar.
2. **CM4 (Tempo) virou unidade própria; CM2 e CM8 são os enxutos.** CM4 chegou a 11 questões e cobre **cinco** sub-habilidades: *dia da semana por resto/consistência* (calendário), *leitura de relógio analógico*, *correção de relógio*, *duração de trajeto* e — novidade de 2024 — *relógio no espelho (reflexão)*. O quadro de 2025 mexeu nas pontas: **CM4 zerou** (sem Tempo na 4ª Edição) e fica em 11; **CM2 zerou pela segunda vez seguida** e segue preso em **6** — o Caminho mais frágil da base; e **CM8 voltou** com 2 itens (tabela numérica + palitos), subindo para **11**. Tradução para o curso: **CM2 é o único bloco verdadeiramente "de manutenção"** (cobertura mínima + gêmeas autorais); **CM4 e CM8 são blocos médios** (11 cada) ainda exigidos pela prova histórica; vigiar se as ausências recentes viram tendência.
3. **Recorrências fortes a explorar como "famílias" de questão** (ótimas para gêmeas/teoria):
   - *Vinheta de abertura "maior resultado"*: `2023/F1/Q1` (só somas) e `2023/F2/Q1` (com ×, −, ×0) — par perfeito para abrir o curso e discutir valor posicional × operações.
   - *Tabela meninos/meninas*: `2018/Q13`, `2023/F1/Q5` (igualar) e `2023/F2/Q6` (dobro) — progressão natural de dificuldade.
   - *Ábaco / valor posicional*: `2022/F2/Q2`, `2023/F1/Q4`.
   - *Borrões/lacunas em contas*: `2022/F1/Q12`, `2023/F2/Q10`.
   - *"Supor o mínimo e distribuir o excedente"*: `2020/Q4` (pés), `2020/Q14` (joaninhas, em CM6), `2023/F1/Q13` (tangerina) — **atenção**: a família está hoje partida entre CM1 e CM6; ver nota 6.
   - *Dias da semana por resto*: `2018/Q8`, `2019/Q2`, `2022/F1/Q5`, `2022/F2/Q6`, `2023/F1/Q6`, `2023/F2/Q2`.
   - *Leitura/duração de relógio*: `2022/F1/Q6`, `2023/F2/Q3`, `2023/F2/Q7`.
   - *Vistas e planificação de cubo*: vistas `2022/F2/Q5`, `2023/F1/Q10`, `2023/F2/Q11`; planificação `2018/Q15`, `2020/Q15`, `2023/F2/Q13`; faces de cubo/dado `2020/Q13`, `2022/F2/Q14`, `2023/F2/Q8`.
   - *Padrões figurais/figurados*: `2018/Q10`, `2019/Q8`, `2022/F1/Q3`, `2022/F2/Q1`, `2022/F2/Q8`, `2023/F1/Q2` (periódico), `2023/F2/Q4` (2n−1).
   - *Contagem por orientação esq/dir*: mãos `2022/F2/Q3`, `2023/F1/Q3`; chinelos `2024/F2/Q4`.
   - *Contagem de ocorrências*: `2019/Q1` (letras), `2023/F2/Q9` (algarismo zero).
   - *Combinatória com restrição*: `2023/F1/Q9` (produtos distintos), `2023/F1/Q15` (subconjuntos com proibição), `2024/F1/Q8` (tipos de bola), `2024/F1/Q14` (flores em vasos), `2024/F2/Q8` (camiseta×bermuda, cores diferentes).
   - *Duas pistas para duas quantidades*: `2024/F1/Q5` (locomotiva+vagões; subtração de equações) — ponte natural com as tabelas meninos/meninas.
   - *Igualdade com incógnita / quadro numérico*: `2020/Q1`, `2024/F1/Q11` (somas de duas linhas iguais).
   - *Casa dos pombos*: `2022/F2/Q12` (13/12), `2024/F1/Q15` (moedas, 3 tipos / 4 retiradas).
   - *Dedução com dados (faces/soma)*: `2024/F1/Q4` (soma 17), além das faces de cubo de CM6.
   - *Lógica de associação por grade*: `2024/F2/Q12` (palhaços: chapéu/gravata/sapato).
   - *Ordenação por pistas (corrida/ranking)*: `2024/F1/Q10`.
   - *Conjuntos/Venn (inclusão–exclusão)*: `2024/F2/Q9` (só Matemática).
   - *Mínimo em sequência / otimização*: cadeados `2020/Q7`, livros `2023/F2/Q15`, colar `2024/F2/Q7`, agenda de intervalos `2024/F2/Q13`.
   - *Pintar para criar uma relação (igualar/dobrar)*: `2018/Q9` (igualar), `2024/F2/Q2` (dobro).
   - *Reflexão/espelho*: palhaço `2019/Q3`, relógio retrovisor `2024/F2/Q10`.
   - *Distâncias em reta numérica*: postes `2020/Q8`, casas/soma de distâncias `2024/F2/Q11`.
   - *Tabela de ração (aquário) — direta × inversa*: `2025/F1/Q7` (dá os bichos, acha o total = 105) e `2025/F2/Q6` (dá o total 105, acha o polvo = 25) — **mesma figura**, par perfeito de "montar a conta" × "desmontar a conta".
   - *Regra condicional de cores*: `2024/F1/Q6` (pintar branco exige um preto) e `2025/F2/Q13` (cartaz: amarela⇒¬branca; cinza⇒¬dourada; cinza⇒branca).
   - *Remoção pelas pontas (colar/sequência)*: `2024/F2/Q7` (mínimo de bolinhas) e `2025/F2/Q12` (o que resta tem de ser contíguo).
   - *Cubo pintado / faces opostas*: cubo 3×3×3 pintado `2025/F2/Q7` (CM5) e dedução de face oposta `2025/F2/Q9` (CM6) — somam-se às vistas/planificações já listadas.
   - *Contagem de ocorrências de algarismo*: agora trio — `2019/Q1` (letras), `2023/F2/Q9` (zeros em 2000–2023), `2025/F2/Q2` (uns em 10–30).
   - *Virar/pintar quadradinhos para uma relação*: `2018/Q9` (igualar), `2024/F2/Q2` (dobro), `2025/F2/Q11` (xadrez → bloco preto).
   - *Duas pistas para duas quantidades (sistema limpo)*: `2024/F1/Q5` (locomotiva+vagões) e `2025/F2/Q10` (Paulinho/Aninha).
   - *Ordenação por pistas (fila/ranking)*: `2018/Q17`, `2024/F1/Q10` (corrida), `2025/F2/Q4` (fila da lanchonete).
   - *Padrão com palitos (matchstick)*: `2025/F1/Q8` (casinhas, 5n+1) — primeiro exemplar do tipo na base.
   - *Novos tipos de 2025 a explorar*: **grade numérica + recorte de peça** `2025/F1/Q1` (CM8, regularidade +10); **processo iterativo até estabilizar / invariante** `2025/F2/Q15` (mágico, CM6); **labirinto com regra "vira à direita"** `2025/F1/Q13` (CM6, ponte CM5); **rotação de pista (meia-volta)** `2025/F2/Q3` (CM5).
4. **Progressão de dificuldade:** o Nível A (2018–2020) tende a ser mais direto; a **2ª Fase** (de 2022 e 2023) concentra os itens mais densos (casa dos pombos, Mastermind, faces de cubo, mínimo de livros, contagem de zeros). Use a 2ª Fase como teto de dificuldade de cada Caminho.
5. **Pendência operacional:** **83 questões** dependem de figura — **64** marcadas **🖼️** (resposta a confirmar pela leitura/contagem) e **19** marcadas **✅🖼️** (resposta já calculada; só a leitura da figura precisa ser conferida). O lote 2025 trouxe 19 itens com figura, dos quais **8 já foram determinados na análise**: garagem `2025/F1/Q5` (E, 22), aquário `2025/F1/Q7` (D, 105) e seu inverso `2025/F2/Q6` (D, 25), alturas `2025/F1/Q4` (B, 150), contorno `2025/F1/Q10` (B, 22), palitos `2025/F1/Q8` (D, 51), xadrez `2025/F2/Q11` (D, 18) e doces `2025/F2/Q14` (E). O lote 2024 sozinho trouxe 17 itens com figura, vários de **contagem fina** (triângulos `2024/F2/Q1`, bolinhas `2024/F2/Q2`, chinelos `2024/F2/Q4`, conjuntos lápis/borracha/apontador `2024/F1/Q2`, ladrilhamento `2024/F2/Q14`) e de **área/perímetro** (`2024/F1/Q9`, `2024/F2/Q5`, `2024/F2/Q15`). Antes de publicar, **bater todos os 🖼️ contra as chaves oficiais** e gerar os SVGs no padrão da casa. Casos **✅🖼️** atuais: `2023/F1/Q11`, `2023/F2/Q3`, `2023/F2/Q4`, `2023/F2/Q10`, `2024/F1/Q1`, `2024/F1/Q3`, `2024/F1/Q6`, `2024/F2/Q2`, `2024/F2/Q10`, `2024/F2/Q12`, `2024/F2/Q13`.
6. **Decisão de classificação — família "duas categorias + total" (resolvida na v3).** As questões `2020/Q4` (pés de animais) e `2023/F1/Q13` (tangerina) ficam em **CM1**, formando o sub-arco **"supor o mínimo e distribuir o excedente"** do novo **Bloco 8 (Estratégias de extremos)**. A `2020/Q14` (joaninhas) permanece em **CM6** (o total é incógnito → exige busca da solução única) e entra, quando CM6 for montado, como o **"degrau a mais"** dessa família. Critério mantido: total dado → CM1; total incógnito → CM6.
7. **Tema emergente confirmado — leitura de dados/gráficos.** O que em 2023 era um único caso (`2023/F1/Q12`, gráfico de barras) virou **tendência em 2024**: `2024/F2/Q6` (escolher o gráfico de barras que modela M=2P=2C=3I) e `2024/F2/Q13` (gráfico de horários / agenda olímpica com intervalos). São **três** questões de interpretação de dados na base, todas acomodadas em **CM6**. Recomendação reforçada: **abrir um micro-bloco "Tabelas e Gráficos"** dentro de CM6 — espelhando exatamente o desdobramento que você fez na trilha do **Nível 1** (a divisão de "Relações, raciocínio e informação" em duas unidades). O par `2024/F2/Q6` (montar/escolher gráfico) + `2024/F2/Q13` (ler gráfico para decidir) cobre os dois movimentos: **representar** e **interpretar**.
8. **Assinatura dos lotes recentes (3ª e 4ª Edições).** 2024 zerou CM2 e CM8; **2025 zerou CM2 (de novo) e CM4**, mas **trouxe CM8 de volta** e bateu o **recorde de CM5 (9 numa só prova)**. Ou seja, a banca está estável no eixo **lógico-espacial-contagem-aritmético** e instável nas pontas (Frações sumiu de vez do recente; Tempo e Padrões oscilam). Recomendação consolidada: **núcleo do curso em CM6+CM5+CM1+CM7**; **CM2 como bloco mínimo/autoral**; **CM4 e CM8 como blocos médios**; manter a cobertura dos 8 Caminhos (a prova histórica ainda os exige) e revisar o balanço a cada nova edição.

---

## 7. Estrutura pedagógica do Caminho 1 (8 blocos do curso)

> Resultado da engenharia reversa de CM1: as 27 questões organizadas em **8 blocos** de ensino, em rampa de dificuldade. A partição é exata — cada questão está em **um** bloco. Cada bloco tem um capítulo de teoria próprio (Protocolo v5.5). Os nomes em negrito são os **atuais da plataforma**; entre parênteses, o **nome didático proposto** (a confirmar).

**Bloco 1 · As operações em problemas (porta de entrada)** *(didático: Problemas com as quatro operações)* — ler o enunciado, montar a conta e resolver com as quatro operações, às vezes em etapas. Questões: `2018/Q1`, `2018/Q2`, `2018/Q14`, `2025/F1/Q2`.

**Bloco 2 · Valor posicional e sistema de numeração** — o que cada algarismo vale, juntar × somar algarismos, efeito das operações (inclusive ×0). Questões: `2022/F2/Q2`, `2023/F1/Q1`, `2023/F1/Q4`, `2023/F2/Q1`.

**Bloco 3 · Diferença constante** *(didático: Comparar e ordenar quantidades)* — a diferença que não muda quando tudo varia por igual, e comparações encadeadas (A < B < C). Questões: `2018/Q4`, `2022/F1/Q10`, **`2018/Q16`** *(entrou na v3, vinda do bloco de estratégias: invariância da diferença, a versão "duas subtrações com o mesmo vão")*.

**Bloco 4 · Igualdades e contas escondidas** *(didático: Igualdades e o número que falta)* — achar o número que fecha a igualdade e reconstruir algarismos apagados (operação inversa). Questões: `2020/Q1`, `2024/F1/Q11`, `2022/F1/Q12`, `2023/F2/Q10`.

**Bloco 5 · Reta numérica e distâncias** — posição e distância numa reta, soma de distâncias, ponto médio. Questões: `2020/Q8`, `2024/F2/Q11`.

**Bloco 6 · Tabelas** *(didático: Leitura e interpretação de tabelas)* — ler a tabela e montar a conta (direta), desmontar a partir do total (inversa), o total de uma grade por linha ou coluna, e relação entre dois grupos (igual / dobro). Questões: `2018/Q13`, `2025/F1/Q7`, `2025/F2/Q6`, `2023/F1/Q5`, `2023/F2/Q6`.

**Bloco 7 · Duas pistas** *(didático: Duas pistas para duas quantidades)* — duas quantidades escondidas, resolvidas comparando as pistas (subtração de equações) ou substituindo uma na outra. *(Bloco criado na v3, desmembrado de Tabelas.)* Questões: `2024/F1/Q5` (locomotiva + vagões), `2025/F2/Q10` (Paulinho / Aninha).

**Bloco 8 · Estratégias olímpicas de fechamento** *(didático: Estratégias de extremos)* — começar de um extremo garantido e ajustar: supor o mínimo e distribuir o excedente (piso) e maximizar com restrição (teto). *(Na v3 ficou só com piso e teto; a invariância saiu para o Bloco 3.)* Questões: `2020/Q4` (pés), `2023/F1/Q13` (tangerina), `2020/Q12` (maior diferença par).

> **Partição conferida:** 4 + 4 + 3 + 4 + 2 + 5 + 2 + 3 = **27** questões, todas de CM1, sem repetição entre blocos. Os blocos mais magros (3 e 5) são os que mais pedem **gêmeas autorais**; nenhum dos workbooks IMO/SOF analisados fornece semente para o Bloco 5.

---

## 8. Estrutura de blocos da plataforma — os 8 Caminhos e seus 50 blocos

> Concluída a engenharia reversa pedagógica dos oito Caminhos. As 170 questões estão organizadas em **50 blocos de curso**, em rampa de dificuldade, cada bloco com um capítulo de teoria próprio (Protocolo v5.5). Esta seção é o índice mestre **bloco → questão**.
>
> **Plataforma × classificação analítica.** Os 8 Caminhos analíticos (CM1–CM8) da §3 foram reempacotados em **8 unidades de plataforma**. A classificação não mudou — cada questão mantém seu CM na tabela-mestre (§4). Mudou só o agrupamento navegável: **CM2 + CM4** dividem a unidade 2; o **CM5** se divide entre a unidade 3 (sólidos) e a 4 (no plano); o **CM6** se divide entre a 5 (lógica) e a 6 (quantitativo). Os nomes abaixo são os dos tiles, no registro seco da casa.

| Unidade (plataforma) | Origem analítica | Questões | Blocos |
|---|---|---|---|
| 1 · Números, operações e problemas aritméticos | CM1 | 27 | 8 |
| 2 · Frações, proporção e medidas de tempo | CM2 + CM4 | 17 | 6 |
| 3 · Grandezas, medidas e sólidos | CM3 + sólidos de CM5 | 23 | 7 |
| 4 · Geometria e percepção espacial no plano | CM5 (no plano) | 26 | 7 |
| 5 · Lógica e dedução | CM6 (metade A) | 19 | 6 |
| 6 · Raciocínio quantitativo, dados e processos | CM6 (metade B) | 24 | 5 |
| 7 · Contagem e combinatória | CM7 | 23 | 7 |
| 8 · Sequências, padrões e regularidades | CM8 | 11 | 4 |

> **Total: 170 questões, 50 blocos.** Partição exata, sem questão órfã e sem repetição. Pontos a manter na memória: **CM5 mora em duas unidades** (sólidos na 3, plano na 4 — manter o link cruzado de área entre elas) e **CM6 está partido** (lógica na 5, quantitativo na 6).

### Caminho 1 · Números, operações e problemas aritméticos *(CM1 — 27 questões, 8 blocos)*

> Detalhamento pedagógico estendido na §7; reproduzido aqui em formato de índice.

**Bloco 1 · As operações em problemas** *(didático: Problemas com as quatro operações)* — ler o enunciado, montar a conta e resolver, às vezes em etapas. Questões: `2018/Q1`, `2018/Q2`, `2018/Q14`, `2025/F1/Q2`.

**Bloco 2 · Valor posicional e sistema de numeração** — o que cada algarismo vale, juntar × somar, efeito das operações. Questões: `2022/F2/Q2`, `2023/F1/Q1`, `2023/F1/Q4`, `2023/F2/Q1`.

**Bloco 3 · Diferença constante** *(didático: Comparar e ordenar quantidades)* — a diferença que não muda e comparações encadeadas. Questões: `2018/Q4`, `2022/F1/Q10`, `2018/Q16`.

**Bloco 4 · Igualdades e contas escondidas** *(didático: Igualdades e o número que falta)* — achar o número que fecha a igualdade e reconstruir algarismos apagados. Questões: `2020/Q1`, `2024/F1/Q11`, `2022/F1/Q12`, `2023/F2/Q10`.

**Bloco 5 · Reta numérica e distâncias** — posição, distância e ponto médio numa reta. Questões: `2020/Q8`, `2024/F2/Q11`.

**Bloco 6 · Tabelas** *(didático: Leitura e interpretação de tabelas)* — ler a tabela e montar a conta, direta ou inversa, e relação entre grupos. Questões: `2018/Q13`, `2025/F1/Q7`, `2025/F2/Q6`, `2023/F1/Q5`, `2023/F2/Q6`.

**Bloco 7 · Duas pistas** *(didático: Duas pistas para duas quantidades)* — duas quantidades escondidas, resolvidas comparando as pistas. Questões: `2024/F1/Q5`, `2025/F2/Q10`.

**Bloco 8 · Estratégias olímpicas de fechamento** *(didático: Estratégias de extremos)* — supor o mínimo e distribuir o excedente (piso) e maximizar com restrição (teto). Questões: `2020/Q4`, `2023/F1/Q13`, `2020/Q12`.

> Partição: 4+4+3+4+2+5+2+3 = **27**.

### Caminho 2 · Frações, proporção e medidas de tempo *(CM2 + CM4 — 17 questões, 6 blocos)*

**Bloco 1 · Frações de uma quantidade** *(didático: A fração como parte de um todo)* — ler a fração numa figura, reconhecer a fração de um conjunto e calcular o que sobra. Questões: `2020/Q6`, `2023/F1/Q7`, `2018/Q18`.

**Bloco 2 · Proporção e raciocínio multiplicativo** *(didático: Valor unitário, equivalência e proporção)* — achar o valor de uma parte, converter entre unidades equivalentes e resolver em etapas com sobra. Questões: `2020/Q3`, `2022/F2/Q13`, `2019/Q6`.

**Bloco 3 · Dias da semana por salto de dias** *(didático: De um dia da semana a outro)* — somar N dias pelo resto da divisão por 7. Questões: `2019/Q2`, `2018/Q8`, `2022/F2/Q6`.

**Bloco 4 · Dias da semana por ontem, hoje e amanhã** — amarrar falas relativas a um dia fixo e testar consistência. Questões: `2022/F1/Q5`, `2024/F1/Q13`.

**Bloco 5 · Calendário e dia do mês** — usar a repetição de 7 em 7 para achar e testar datas. Questões: `2023/F1/Q6`, `2023/F2/Q2`.

**Bloco 6 · Relógio e horários** — ler o relógio analógico, corrigir e calcular durações. Questões: `2022/F1/Q6`, `2023/F2/Q3`, `2024/F2/Q10`, `2023/F2/Q7`.

> Partição: 3+3+3+2+2+4 = **17**. CM2 e CM4 são os Caminhos de manutenção; blocos magros (4, 5) pedem gêmeas autorais. Borda: `2024/F2/Q10` (relógio no espelho) é ponte com a percepção espacial do Caminho 4.

### Caminho 3 · Grandezas, medidas e sólidos *(CM3 + sólidos de CM5 — 23 questões, 7 blocos)*

**Bloco 1 · Comprimento na régua e na escala** *(didático: Ler a régua, mesmo fora do zero)* — medir por diferença e por contagem de marcas/intervalos. Questões: `2018/Q6`, `2024/F1/Q3`, `2022/F2/Q9`, `2025/F1/Q4`.

**Bloco 2 · Somar comprimentos: percursos e alturas** *(didático: Juntar pedaços de comprimento)* — compor um comprimento total a partir de trechos. Questões: `2018/Q19`, `2022/F1/Q11`, `2023/F1/Q11`.

**Bloco 3 · Massa e equilíbrio na balança** — achar massa por divisão, equilibrar pratos e resolver igualdade de massa. Questões: `2018/Q12`, `2019/Q15`, `2022/F2/Q4`, `2024/F1/Q1`.

**Bloco 4 · Área e dinheiro** — área equivalente em malha e troco com restrição de moedas. Questões: `2019/Q10`, `2022/F1/Q15`.

**Bloco 5 · Planificação do cubo** *(vindo de CM5)* — dobrar a planificação, faces opostas e orientação. Questões: `2018/Q15`, `2020/Q15`, `2023/F2/Q13`.

**Bloco 6 · Vistas do sólido** *(vindo de CM5)* — vista ortogonal, reconstrução por três vistas e cubo oculto. Questões: `2022/F2/Q5`, `2023/F1/Q10`, `2023/F2/Q11`, `2024/F2/Q3`.

**Bloco 7 · Decompor o sólido** *(vindo de CM5, a ponte do volume)* — decompor sólidos, volume por cubinhos, faces em contato e cubo pintado. Questões: `2023/F2/Q14`, `2025/F1/Q12`, `2025/F2/Q7`.

> Partição: 4+3+4+2+3+4+3 = **23**. O termo "sólidos" do nome cobre os blocos 5–7 (vindos de CM5, pela porta do volume). Unidade quase toda 🖼️. Bloco 4 (área e dinheiro) é heterogêneo e prioritário em gêmeas autorais.

### Caminho 4 · Geometria e percepção espacial no plano *(CM5 no plano — 26 questões, 7 blocos)*

**Bloco 1 · Reconhecer, classificar e compor figuras** *(didático: Conhecer as figuras e montá-las)* — identificar por propriedade, reconhecer trecho de contorno e compor por peças. Questões: `2020/Q2`, `2022/F1/Q2`, `2022/F1/Q9`.

**Bloco 2 · Recortar, remontar e ladrilhar** *(didático: Quebrar e remontar figuras)* — decompor, ladrilhar sem sobreposição e relacionar áreas. Questões: `2022/F1/Q14`, `2024/F2/Q14`, `2025/F1/Q14`, `2024/F2/Q15`.

**Bloco 3 · Contorno e perímetro em malha** *(didático: Medir o contorno na malha)* — comparar e medir o contorno de figuras compostas. Questões: `2019/Q4`, `2024/F2/Q5`, `2024/F1/Q9`, `2025/F1/Q10`.

**Bloco 4 · Sobreposição, transparência e silhueta** *(didático: O que fica por cima)* — ordem de empilhamento, camadas transparentes e união de formas. Questões: `2018/Q7`, `2018/Q11`, `2025/F1/Q6`.

**Bloco 5 · Espelhar e girar** *(didático: Reflexão, giro e invariância)* — transformar por espelho ou rotação e reconhecer o que não muda. Questões: `2019/Q3`, `2019/Q11`, `2022/F1/Q8`, `2025/F2/Q3`, `2025/F2/Q1`.

**Bloco 6 · Encaixe e a peça que falta** *(didático: Achar a peça que encaixa)* — complemento, silhueta complementar e montagem por forma e cor. Questões: `2019/Q5`, `2022/F1/Q4`, `2022/F1/Q1`, `2025/F1/Q11`.

**Bloco 7 · Lateralidade e caminhos** *(didático: Achar o caminho)* — navegar em malha ou labirinto, seguir giros e rastrear trajetos. Questões: `2018/Q5`, `2022/F1/Q13`, `2025/F1/Q3`.

> Partição: 3+4+4+3+5+4+3 = **26**. Caminho mais 🖼️-dependente da base. As questões de área por decomposição (`2024/F2/Q14`, `2024/F2/Q15`) ficam aqui no Bloco 2 mas encostam no Bloco 4 do Caminho 3 — manter o link cruzado de área entre as duas unidades.

### Caminho 5 · Lógica e dedução *(CM6 metade A — 19 questões, 6 blocos)*

**Bloco 1 · Ordenar por pistas e por comparação** *(didático: Achar a ordem)* — deduzir posições em fila ou ranking e ordenar por transitividade. Questões: `2018/Q17`, `2024/F1/Q10`, `2025/F2/Q4`, `2023/F2/Q15`, `2023/F1/Q8`.

**Bloco 2 · Posições que se correspondem** *(didático: Opostos e frente a frente)* — aritmética de posições opostas ou que se encaram. Questões: `2023/F1/Q14`, `2023/F2/Q5`.

**Bloco 3 · Associação por pistas** *(didático: Quem tem o quê)* — casar pessoas e atributos por uma grade. Questões: `2018/Q20`, `2019/Q12`, `2024/F2/Q12`, `2025/F1/Q15`, `2025/F2/Q14`.

**Bloco 4 · A lógica do "se... então"** *(didático: Regras condicionais)* — aplicar implicações e achar o contraexemplo. Questões: `2024/F1/Q6`, `2025/F2/Q13`.

**Bloco 5 · Casa dos pombos** *(didático: Não tem como caber sem repetir)* — garantir repetição pelo número de gavetas. Questões: `2022/F2/Q12`, `2024/F1/Q15`.

**Bloco 6 · Deduzir o que está oculto** *(didático: Descobrir o escondido)* — senha por pistas, verso de cartas e encaixe por correspondência. Questões: `2022/F2/Q15`, `2022/F2/Q11`, `2023/F2/Q12`.

> Partição: 5+2+5+2+2+3 = **19**. Blocos magros (2, 4, 5) pedem gêmeas autorais.

### Caminho 6 · Raciocínio quantitativo, dados e processos *(CM6 metade B — 24 questões, 5 blocos)*

**Bloco 1 · Deduzir números por pistas** *(didático: Descobrir os números que faltam)* — achar valores por total, substituição, unicidade ou contagem de partidas. Questões: `2019/Q9`, `2020/Q10`, `2020/Q14`, `2025/F1/Q9`, `2024/F1/Q12`.

**Bloco 2 · Diagramas e gráficos** *(didático: Ler e montar a informação)* — interpretar Venn e representar ou ler gráficos de barras. Questões: `2018/Q3`, `2024/F2/Q9`, `2023/F1/Q12`, `2024/F2/Q6`, `2024/F2/Q13`.

**Bloco 3 · Deduzir as faces de dados e cubos** *(didático: O que está na face escondida)* — faces opostas, soma fixa e dedução por vistas. Questões: `2020/Q13`, `2022/F2/Q14`, `2023/F2/Q8`, `2024/F1/Q4`, `2025/F2/Q9`.

**Bloco 4 · Achar o mínimo** *(didático: O menor número de vezes)* — otimizar viagens, aberturas, movimentos e cortes. Questões: `2020/Q5`, `2020/Q7`, `2020/Q11`, `2024/F2/Q7`.

**Bloco 5 · Processos passo a passo** *(didático: Seguir, inverter e o que não muda)* — percorrer um procedimento, voltar de trás para frente, iterar até estabilizar e reconhecer o invariante. Questões: `2024/F1/Q7`, `2025/F2/Q15`, `2019/Q14`, `2025/F1/Q13`, `2025/F2/Q12`.

> Partição: 5+5+5+4+5 = **24**. Bordas: `2024/F2/Q13` (agenda olímpica) tem viés de otimização de intervalos; `2025/F1/Q13` (labirinto) é ponte com a navegação do Caminho 4.

### Caminho 7 · Contagem e combinatória *(CM7 — 23 questões, 7 blocos)*

**Bloco 1 · Contar figuras e ocorrências** *(didático: Contar sem perder a conta)* — contar figuras direto e contar ocorrências por posição. Questões: `2024/F2/Q1`, `2019/Q1`, `2025/F2/Q2`, `2023/F2/Q9`.

**Bloco 2 · Pareamento: pés, mãos e conjuntos** *(didático: Juntar aos pares)* — parear esquerda/direita e montar conjuntos limitados pelo mais escasso. Questões: `2020/Q9`, `2022/F2/Q3`, `2023/F1/Q3`, `2024/F2/Q4`, `2024/F1/Q2`.

**Bloco 3 · Pintar ou virar para criar uma relação** *(didático: Pintar para igualar ou dobrar)* — pintar ou virar quadradinhos até bater uma relação entre as cores. Questões: `2018/Q9`, `2024/F2/Q2`, `2025/F2/Q11`.

**Bloco 4 · Organizar em fila e nos intervalos** *(didático: Pôr em ordem e contar os espaços)* — arrumar numa linha e contar o que cabe nos espaços. Questões: `2022/F2/Q7`, `2025/F2/Q5`.

**Bloco 5 · Multiplicar as escolhas** *(didático: Cada escolha multiplica)* — multiplicar opções independentes e corrigir o produto. Questões: `2025/F1/Q5`, `2024/F1/Q14`, `2024/F2/Q8`, `2023/F1/Q9`.

**Bloco 6 · Contar tirando os casos que não valem** *(didático: Contar tudo e tirar o proibido)* — contar o total e subtrair o que a regra exclui, ou achar o que resta. Questões: `2024/F1/Q8`, `2023/F1/Q15`, `2025/F2/Q8`.

**Bloco 7 · Contar configurações válidas** *(didático: Quantos jeitos respeitam a regra)* — contar de quantos modos dá para preencher ou vencer respeitando uma condição. Questões: `2019/Q13`, `2022/F1/Q7`.

> Partição: 4+5+3+2+4+3+2 = **23**. 🖼️ concentrado nos blocos 1–2 (contagem concreta); o Arco de combinatória (5–7) é quase todo ✅. Bloco 7 é heterogêneo (quadro latino + paridade) e pede gêmeas autorais.

### Caminho 8 · Sequências, padrões e regularidades *(CM8 — 11 questões, 4 blocos)*

**Bloco 1 · Padrões que crescem em ritmo constante** *(didático: Achar a regra que soma sempre o mesmo)* — descobrir a regra linear (an + b) de uma sequência figural e estendê-la, inclusive para um termo que não dá para desenhar. Questões: `2022/F1/Q3`, `2022/F2/Q1`, `2019/Q8`, `2025/F1/Q8`, `2023/F2/Q4`.

**Bloco 2 · Números figurados** *(didático: Quando o crescimento acelera)* — sequências em que o salto entre termos aumenta. Questões: `2018/Q10`, `2022/F2/Q8`.

**Bloco 3 · Achar pela posição: ciclos e grades** *(didático: Descobrir quem cai em cada lugar)* — localizar um elemento pela regularidade da posição, num ciclo ou numa grade numérica. Questões: `2023/F1/Q2`, `2025/F1/Q1`.

**Bloco 4 · Regularidades de algarismos e datas** *(didático: Padrões nos números e no calendário)* — somas de algarismos que se repetem e datas simétricas. Questões: `2019/Q7`, `2022/F2/Q10`.

> Partição: 5+2+2+2 = **11**. Caminho de manutenção; blocos 2–4 pedem gêmeas autorais. Borda: `2023/F2/Q4` é figura mas crescimento linear (fica no Bloco 1); `2025/F1/Q1` tem recorte espacial (ponte com o Caminho 4), mas o núcleo é a regularidade posicional.

> **Conferência global:** 27+17+23+26+19+24+23+11 = **170** questões em **50 blocos** (8+6+7+7+6+5+7+4). Partição exata de toda a base.

---

### Regras de classificação aplicadas (memória da casa)
- **Balança/equilíbrio:** vai para **CM3** quando o foco é massa/medida (calcular peso, equilibrar) e para **CM6** quando o foco é ordenar/deduzir por transitividade (`2023/F1/Q8`).
- **Cubos:** vistas e planificação → **CM5**; faces opostas e dedução de pontos → **CM6**; decomposição/volume → **CM5**.
- **Roda gigante:** rotação/invariância → CM5 (`2022/F1/Q8`); contagem por posições opostas → CM6 (`2023/F1/Q14`).
- **Contagem de ocorrências e combinações** → **CM7** (mesmo quando o objeto é número, como a contagem de zeros).
- **Medida com padrão** (altura de pilhas, comprimento) → **CM3** quando se resolve achando dimensões; **CM8** quando é sequência a estender.
- **Pintar para criar uma relação** (igualar, dobrar, triplicar quantidades de cor) → **CM7** (contagem + ajuste), seguindo o precedente de `2018/Q9`. Aplicado a `2024/F2/Q2` (dobro).
- **Relógio no espelho/retrovisor** → **CM4** (o conteúdo central é leitura de horas), com **ponte para CM5** pela reflexão. Aplicado a `2024/F2/Q10`.
- **Comprimento/perímetro em malha e contorno de figura composta** → **CM5** (percepção espacial), p.ex. `2024/F2/Q5` e `2024/F1/Q9`; reserva-se **CM3** para medida com régua/diferença de comprimentos (`2024/F1/Q3`).
- **Soma de distâncias em reta numérica** → **CM1** (problema aritmético), seguindo `2020/Q8`. Aplicado a `2024/F2/Q11`.
- **Leitura/escolha de gráfico e agendamento de intervalos** → **CM6** (interpretação de dados/dedução). Aplicado a `2024/F2/Q6` e `2024/F2/Q13`.
- **Duas pistas para duas quantidades** (duas equações lineares limpas, resolvidas por subtração) → **CM1**; reserva-se **CM6** para substituições encadeadas (feira `2020/Q10`). Aplicado a `2024/F1/Q5`.
- **Tabela + operações (ração/aquário)** → **CM1** (o núcleo é multiplicar/somar/subtrair a partir da tabela), tanto na forma direta (`2025/F1/Q7`) quanto inversa (`2025/F2/Q6`).
- **Grade numérica preenchida em ordem + recorte de peça** → **CM8** (a chave é a **regularidade posicional**, ex. +10 por linha), com componente espacial secundário. Aplicado a `2025/F1/Q1`.
- **Palitos (matchstick) em faixa que se repete** → **CM8** (padrão de crescimento; conta-se por regra, ex. 5n+1). Aplicado a `2025/F1/Q8`.
- **Cubo pintado / contagem de faces em sólido** → **CM5** (decomposição 3D), distinto de **faces opostas por dedução**, que vai a **CM6**. Aplicado a `2025/F2/Q7` (CM5) e `2025/F2/Q9` (CM6).
- **Rotação circular / meia-volta** (pista, roda) → **CM5** (posição após giro de 180°). Aplicado a `2025/F2/Q3` (cf. roda-gigante `2022/F1/Q8`).
- **Processo iterativo até estabilizar / invariante** (transformações sucessivas) → **CM6**. Aplicado a `2025/F2/Q15` (mágico).
- **Labirinto com regra de movimento determinística** ("vira à direita na parede") → **CM6** (aplicar um procedimento), com **ponte para CM5** pela navegação espacial. Aplicado a `2025/F1/Q13`.
- **Contorno de figura composta em escada** → **CM5**; quando a escada é **monótona**, vale o atalho perímetro = 2·(largura+altura). Aplicado a `2025/F1/Q10`.
