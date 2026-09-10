Ficha de classificação · Bloco $6$ · Descobrir o escondido

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as três questões de referência do bloco: `2022/F2/Q15`, `2022/F2/Q11` e `2023/F2/Q12`.

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Deduzir um único valor escondido, sem casar listas inteiras de pessoas com atributos, usando propriedades numéricas, um padrão fixo ou uma correspondência de forma. O bloco cobre três variações: (a) descobrir uma senha de vários algarismos combinando pistas sobre soma, dobro e posição, (b) descobrir o que está atrás de uma carta virada, aplicando um padrão fixo já confirmado pelas cartas viradas antes, e (c) descobrir qual peça encaixa noutra, casando duas listas por uma regra de correspondência (mesma forma, mesma cor, mesmo desenho).

**Nó principal (Apêndice D, grade oficial).** `Raciocínio Lógico › Problemas com Restrições e Dedução › Correspondência Oculta e Padrão Escondido` (subnó proposto). Os nós existentes mais próximos, "Dedução com Pistas Numéricas" (cobre bem a variação a) e "Decodificação de Idiomas / Sistemas Simbólicos" (parente distante da variação c), não cobrem sozinhos as três variações do bloco, por isso abrimos este subnó, irmão deles dentro de "Problemas com Restrições e Dedução".

**Descritores secundários.**
- Sistema de pistas numéricas (variação a): cada pista (soma, dobro, posição fixa) reduz o número de senhas possíveis, e a senha só fica determinada quando as pistas, juntas, sobram numa única combinação.
- Extrapolação de padrão confirmado (variação b): quando várias cartas já viradas confirmam a mesma regra entre frente e verso, essa regra pode ser aplicada com confiança a uma carta ainda não virada, sem precisar virá-la de verdade.
- Correspondência por regra de casamento (variação c): parente da associação por pistas do Bloco $3$ deste Caminho, mas aqui a "pista" é sempre a mesma regra fixa (mesma forma, mesma cor), aplicada a todos os pares de uma vez, em vez de pistas soltas e variadas.

**Não é X (e por quê).**
- Não é Associação por Pistas (Bloco $3$ deste Caminho), porque ali várias pistas diferentes eliminam combinações numa grade de várias pessoas e vários atributos, enquanto aqui o alvo é sempre um único valor ou uma única peça, e a regra de dedução costuma ser uma só, aplicada de forma direta.
- Não é Casa dos Pombos (Bloco $5$ deste Caminho), porque não existe nenhuma contagem de objetos e gavetas forçando uma repetição, o alvo é sempre descobrir um valor específico e determinado.
- Não é Regras Condicionais (Bloco $4$ deste Caminho), porque a variação (b) usa um padrão numérico confirmado por repetição, não uma regra do tipo "se... então" com uma condição lógica explícita.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 5** › **Bloco 6 · Descobrir o escondido** › capítulo de teoria "Descobrir o escondido" (`Cap_Deduzir_Oculto.md`).

---

***Notas específicas de cada questão de referência***

`2022/F2/Q15`
- **Motor aplicado:** variação (a), senha por pistas numéricas combinadas. 🖼️ (conferir a solução oficial antes de publicar).
- **Não é X específico:** não é uma questão de casa dos pombos, o valor buscado é único e determinado pelas pistas, não uma garantia de repetição.

`2022/F2/Q11`
- **Motor aplicado:** variação (b), verso de carta por padrão confirmado.
- **Não é X específico:** não é Regras Condicionais, porque a regra aqui vem da repetição observada em vários casos, não de uma afirmação lógica dada de antemão.

`2023/F2/Q12`
- **Motor aplicado:** variação (c), encaixe por correspondência de forma.
- **Não é X específico:** não é Associação por Pistas, porque a correspondência usa uma única regra fixa (mesma forma), não várias pistas textuais diferentes.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Deduzir_Oculto.md` seguem a classificação acima, variando o motor específico dentro do bloco:
- Exercícios $1$, $4$, $7$, $10$: variação (a), senha por pistas numéricas combinadas.
- Exercícios $2$, $5$, $8$: variação (b), verso de carta por padrão confirmado.
- Exercícios $3$, $6$, $9$: variação (c), encaixe por correspondência de forma.
