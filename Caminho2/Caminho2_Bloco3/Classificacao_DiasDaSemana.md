# Classificação — Bloco 3 · Dias da semana por salto de dias

Ficha de produção (uso interno), no modelo do §3 do Protocolo_OBMEP_v5.5. Cobre as três questões de referência do bloco: `2019/Q2`, `2018/Q8`, `2022/F2/Q6`.

## Classificação comum às três questões

As três compartilham o mesmo motor cognitivo e o mesmo nó, mudando apenas o dia de partida e o número de dias. A classificação abaixo vale para as três, com a nota específica de cada uma logo depois.

**Motor cognitivo (Apêndice A, uso interno).** Nenhum descritor existente do Apêndice A cobre bem o motor "andar N passos numa roda de 7 posições, usando o resto da divisão por 7 para descontar as voltas completas". O descritor mais próximo, **processo iterativo / máquina** (§3, "Descritores recorrentes"), captura a ideia de aplicar um passo fixo repetidas vezes, mas não nomeia o papel específico do resto da divisão por 7. Registro sugerido para o Apêndice A: **"Aritmética modular do calendário — resto da divisão por 7"**, como descritor irmão de "processo iterativo / máquina", a validar se o padrão recorrer em levas futuras.

**Nó principal (Apêndice D, grade oficial).** `Aritmética › Grandezas e Medidas › Medidas de tempo › Dias da semana por resto da divisão por 7` — **subnó proposto**. O nó existente "Medidas de tempo (sistema sexagesimal) e de capacidade" não serve porque trata de conversão de horas, minutos e capacidade, não do ciclo de 7 dias da semana. Abro o subnó por analogia com a própria estrutura da trilha Mirim 2, que já reserva um Caminho inteiro (CM4) para "Tempo, Calendário e Dias da Semana".

**Descritores secundários.**
- Achar a parte que falta de um total (quando o problema dá duas datas e pede a diferença de dias antes de aplicar o resto).
- Processo iterativo / máquina (a roda dos 7 dias como ciclo fixo que se repete).

**Não é X (e por quê).**
- Não é Aritmética › Operações com Números Naturais › Medidas de tempo (sistema sexagesimal), porque não há conversão de horas ou minutos, só contagem de dias inteiros.
- Não é Raciocínio Lógico › Problemas com Restrições e Dedução › Restrições Temporais e Dias da Semana, porque essa questão não pede dedução por eliminação de casos a partir de pistas cruzadas (do tipo "ontem", "hoje", "amanhã" de pessoas diferentes); aqui a resposta sai de uma conta direta, sem eliminar hipóteses.
- Não é Aritmética › Raciocínio temporal em linha do tempo (idade ↔ ano de nascimento), porque esse descritor trata de posição de anos numa linha do tempo, não do ciclo semanal de 7 dias.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 4** (Tempo, Calendário e Dias da Semana) › **Bloco 3 · Dias da semana por salto de dias** › capítulo de teoria "Dias da semana por salto de dias" (`Cap_DiasDaSemana_SaltoDeDias.md`).

---

## Notas específicas de cada questão

### `2019/Q2` (código técnico `NA19-Q02`)
- **Motor aplicado:** salto de dias simples, resto menor que o número de dias original. Joana viaja num sábado e volta 9 dias depois.
- **Verificação independente:** sábado tem índice 6 na roda (domingo = 0). 9 ÷ 7 = 1, resto 2. 6 + 2 = 8, e 8 mod 7 = 1, que corresponde a segunda-feira. Confere com o gabarito registrado (alternativa B, Segunda-feira).
- **Não é X específico:** não é uma questão de duas datas em calendário (não há "dia X do mês"), então não usa a etapa de subtração da Seção 5 do capítulo, só a etapa do resto.

### `2018/Q8` (código técnico `NA18-Q08`)
- **Motor aplicado:** salto de dias simples, com o número de dias (17) exigindo claramente o atalho do resto em vez da contagem um a um. Beatriz faz aniversário 17 dias depois de Antônio, que fez aniversário num domingo.
- **Verificação independente:** domingo tem índice 0. 17 ÷ 7 = 2, resto 3. 0 + 3 = 3, que corresponde a quarta-feira. Confere com o gabarito registrado (alternativa E, Quarta-feira).
- **Não é X específico:** mesma observação da `2019/Q2`, não envolve duas datas de calendário.

### `2022/F2/Q6` (código técnico `M2-22-F2-Q06`)
- **Motor aplicado:** a variante de duas datas dentro do mesmo mês (Seção 5 do capítulo), porque o problema não dá diretamente "quantos dias depois", e sim duas datas do calendário (1º de janeiro e 31 de janeiro) para comparar.
- **Verificação independente:** do dia 1 ao dia 31 são 30 dias de diferença. 1º de janeiro de 2000 foi um sábado (índice 6). 30 ÷ 7 = 4, resto 2. 6 + 2 = 8, e 8 mod 7 = 1, que corresponde a segunda-feira. Confere com o gabarito registrado (alternativa A, Segunda-feira).
- **Não é X específico:** aqui sim é preciso a etapa extra de subtração (31 − 1 = 30) antes do resto, o que a diferencia das outras duas questões do bloco e justifica por que ela é a âncora escolhida para a Seção 5 do capítulo (a variante "duas contas").

---

## Cobertura nos exercícios autorais

Os 10 exercícios de `Lista_Exercicios_DiasDaSemana_SaltoDeDias.md` seguem a mesma classificação acima (nó, campo de trilha e "Não é X"), variando apenas o motor específico dentro do bloco:
- Exercícios 1, 2: salto simples, N menor que 7 (mesmo motor da Seção 2 do capítulo).
- Exercícios 3, 4, 8: salto simples com resto não nulo (mesmo motor de `2019/Q2` e `2018/Q8`).
- Exercício 5: salto com resto 0, caso particular guardado na Seção 5 do capítulo.
- Exercícios 6, 7, 10: duas datas no mesmo mês (mesmo motor de `2022/F2/Q6`), com o exercício 7 explorando o caso de resto 0 e o exercício 10 acrescentando uma pista redundante.
- Exercício 9: variante de duração contando o dia de início, ligada à Seção 3 do capítulo (o cuidado de não contar hoje como um dos dias que passam).
