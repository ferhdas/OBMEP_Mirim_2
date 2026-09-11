Ficha de classificação · Bloco $1$ · Contar figuras e ocorrências

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as quatro questões de referência do bloco: `2024/F2/Q1` (código `M2-24-F2-Q01`), `2019/Q1` (código `NA19-Q01`), `2025/F2/Q2` (código `M2-25-F2-Q02`) e `2023/F2/Q9` (código `M2-23-F2-Q09`).

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Contar quantas vezes um item aparece, sem pular nenhum e sem repetir a contagem, quando o item está espalhado numa figura, misturado com outros tipos de item, ou escondido dentro da escrita de vários números. O bloco reúne três variações: (a) contar diretamente figuras pequenas dentro de uma malha ou mosaico, seguindo um caminho fixo pela figura, (b) contar quantas vezes cada tipo de símbolo aparece numa figura com vários tipos misturados, e (c) contar quantas vezes um algarismo aparece ao escrever todos os números de uma faixa, somando as ocorrências dentro de cada número.

**Nó principal (Apêndice D, grade oficial).** `Análise Combinatória › Contagem Direta e Contagem por Posição` (subnó proposto). O Apêndice D marca "Análise Combinatória" como `[+]`, sem filhos transcritos, então abrimos este subnó para reunir as três variações, todas motivadas pelo mesmo cuidado, contar sem pular e sem repetir, usando uma estratégia de percurso ou de separação por posição.

**Descritores secundários.**
- Percurso fixo pela figura: contar figuras numa malha funciona melhor com um caminho decidido antes de começar, por exemplo linha por linha, para que cada figura seja vista exatamente uma vez.
- Uma contagem por tipo: quando vários tipos de símbolo estão misturados, contar todos ao mesmo tempo, num único percurso, é a fonte mais comum de erro. Contar um tipo de cada vez, com um percurso completo pela figura para cada tipo, evita confundir um símbolo com outro.
- Contagem por casa decimal: um algarismo pode aparecer mais de uma vez dentro do mesmo número, uma vez em cada casa, unidade, dezena ou centena. A contagem certa soma essas ocorrências por casa, não conta só quantos números contêm o algarismo pelo menos uma vez.
- Separação da faixa em pedaços: faixas de números com muitos itens ficam mais fáceis de contar quando divididas em pedaços onde o comportamento do algarismo procurado é constante, por exemplo todos os números de uma mesma dezena.

**Não é X (e por quê).**
- Não é Raciocínio Lógico › Problemas com Conjuntos e Diagramas de Venn (Bloco $2$ do Caminho $6$), porque aqui não existem regiões que se cruzam nem categorias sobrepostas. Cada figura ou cada ocorrência de algarismo pertence a um único tipo, contado de uma vez.
- Não é Sequências, Padrões e Regularidades (Caminho $8$), porque a faixa de números da variação (c) não segue uma regra que se estende, ela é só o intervalo dentro do qual se conta uma ocorrência, com início e fim fixos.
- Não é Geometria › Percepção Espacial no Plano (Caminho $4$), mesmo quando a variação (a) usa uma malha com triângulos. O que se pede não é reconhecer nem compor uma forma, é contar quantas figuras de um tipo já definido existem, uma contagem direta.
- Não é Raciocínio Lógico › Dedução com Pistas Numéricas (Bloco $1$ do Caminho $6$), porque nenhuma das três variações depende de cruzar pistas para descobrir um número escondido. A resposta sai inteiramente de contar o que já está visível na figura ou na lista de números.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 7** › **Bloco 1 · Contar figuras e ocorrências** › capítulo de teoria "Contar sem perder a conta" (`Cap_Contar_Figuras_Ocorrencias.md`).

---

***Notas específicas de cada questão de referência***

`2024/F2/Q1` (código `M2-24-F2-Q01`)
- **Motor aplicado:** variação (a), percurso fixo pela figura. Um mosaico $4\times4$ com diagonais forma triângulos brancos e verdes, e a pergunta pede quantos triângulos brancos há ao todo. Contando linha por linha, sem pular nenhum quadrado, o total dá $12$. Gabarito **C ($12$)** ✅, conferido contra a solução oficial (`sf2m2-2024.pdf`, questão $1$).
- **Não é X específico:** não é preciso reconhecer nenhum padrão de repetição no mosaico, é uma contagem direta, figura por figura, sem regra de crescimento envolvida.

`2019/Q1` (código `NA19-Q01`)
- **Motor aplicado:** variação (b), uma contagem por tipo. Um quadro tem as letras O, B, M, E e P espalhadas em posições e tamanhos diferentes, e a pergunta pede qual letra aparece mais vezes. Contando cada letra separadamente, O aparece $3$ vezes, B aparece $3$ vezes, M aparece $3$ vezes, E aparece $6$ vezes, e P aparece $2$ vezes. Gabarito **D (a letra E)** ✅, conferido contra a solução oficial (`snA-2019.pdf`, questão $1$).
- **Não é X específico:** não basta contar de relance qual letra "parece" mais frequente, porque várias letras têm contagens parecidas ($3$ vezes cada), e só uma contagem separada por letra revela que a letra E se destaca com o dobro das outras.

`2025/F2/Q2` (código `M2-25-F2-Q02`)
- **Motor aplicado:** variação (c), contagem por casa decimal. Rafael escreveu todos os números de $10$ a $30$, e a pergunta pede quantas vezes ele escreveu o algarismo $1$. De $10$ a $19$, o algarismo $1$ aparece uma vez na casa das dezenas em cada um dos dez números, e mais uma vez na casa das unidades do número $11$, totalizando $11$. Somando o $21$, que tem um $1$ na casa das unidades, o total chega a $12$. Gabarito **C ($12$)** ✅, conferido contra a solução oficial (`sf2m2-2025.pdf`, questão $2$).
- **Não é X específico:** não é contar quantos números contêm o algarismo $1$ pelo menos uma vez, é contar as ocorrências do algarismo, e o número $11$ conta duas vezes por ter o $1$ em duas casas diferentes.

`2023/F2/Q9` (código `M2-23-F2-Q09`)
- **Motor aplicado:** variação (c), separação da faixa em pedaços. Mariana escreveu todos os números de $2000$ a $2023$, e a pergunta pede quantas vezes ela escreveu o algarismo $0$. O número $2000$ sozinho tem três algarismos $0$. Os números de $2001$ a $2010$ mais o $2020$, onze números ao todo, têm dois algarismos $0$ cada. Os demais números de $2011$ a $2023$, exceto o $2020$, doze números ao todo, têm um algarismo $0$ cada. Somando, $3+22+12=37$. Gabarito **E ($37$)** ✅, conferido contra a solução oficial (`sf2m2-2023.pdf`, questão $9$).
- **Não é X específico:** não é uma questão de Sistema de Numeração sobre o valor posicional dos algarismos, é uma contagem de ocorrências, o valor posicional só ajuda a organizar em que casa cada zero aparece.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Contar_Figuras_Ocorrencias.md` seguem a classificação acima:
- Exercícios $1$ e $2$: variação (a), percurso fixo pela figura, contando triângulos num mosaico.
- Exercícios $3$ e $4$: variação (b), uma contagem por tipo, em quadros com símbolos misturados.
- Exercícios $5$ a $10$: variação (c), contagem de um algarismo dentro de uma faixa de números, em faixas de dificuldade crescente.
