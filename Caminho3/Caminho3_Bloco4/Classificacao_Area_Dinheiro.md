Ficha de classificação · Bloco $4$ · Área e dinheiro

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as duas questões de referência do bloco: `2019/Q10`, `2022/F1/Q15`. O bloco é heterogêneo, reúne dois submotores irmãos sob a mesma ideia de "contar unidades para medir uma grandeza", por isso a ficha traz um nó principal para cada um, em vez de um único nó comum.

***Por que dois nós principais neste bloco***

O Bloco $4$ é o mais magro do Caminho $3$ em questões oficiais, só $2$, e cada uma vem de um submotor diferente dentro de Grandezas e Medidas: uma conta quadradinhos numa malha para achar área, a outra conta moedas sob uma restrição de quantidade para formar um troco. Os dois submotores compartilham o mesmo raciocínio de fundo, contar quantas peças de tamanho fixo cabem dentro de uma quantidade maior, mas se arquivam em nós diferentes da grade oficial, porque um mede uma grandeza geométrica (área) e o outro lida com o sistema monetário. Por isso a ficha classifica cada questão separadamente, e a seção final amarra os dez exercícios autorais aos dois submotores.

---

***Questão de referência 1: contagem de área em malha***

`2019/Q10` (código técnico `NA19-Q10`)

**Motor cognitivo (Apêndice A, uso interno).** Contar quadradinhos de uma malha quadriculada para achar a área de uma figura recortada, e comparar essa contagem com a área de outras figuras (aqui, retângulos) até achar a que tem o mesmo valor. O motor não usa nenhuma fórmula, só contagem direta e, no caso de retângulos, a multiplicação de linhas por colunas como atalho da própria contagem.

**Nó principal (Apêndice D, grade oficial).** `Aritmética › Grandezas e Medidas › Área › Contagem de Unidades em Malha Quadriculada`. A grade oficial tem "Grandezas e Medidas" marcado como nó em aberto (`[+]`, sem filhos transcritos), então este subnó é proposto para arquivar especificamente as questões que medem área contando quadradinhos, sem entrar em fórmulas de área de figuras planas do ensino fundamental $2$.

**Descritores secundários.**
- Comparação de duas figuras de formatos diferentes com a mesma área (a aparência do contorno não decide, só a contagem).
- Atalho de multiplicação para área de retângulo (linhas × colunas), quando a figura candidata é um retângulo.

**Não é X (e por quê).**
- Não é Geometria › perímetro ou contorno, porque a pergunta é sobre quantos quadradinhos a figura cobre por dentro, não sobre o comprimento da borda.
- Não é Aritmética › Razão e Proporção, porque não há duas grandezas proporcionais em jogo, só uma contagem direta de unidades.
- Não é Problemas com Restrições de Soma (Linhas e Colunas / Matrizes), porque a malha aqui não representa uma tabela com condições de linha e coluna a satisfazer, é só a superfície onde a figura foi recortada.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 3** › **Bloco 4 · Área e dinheiro** › capítulo de teoria "Área e dinheiro" (`Cap_Area_Dinheiro.md`), seção "Quadradinhos e a ideia de área" e seguintes.

---

***Questão de referência 2: troco com restrição do número de moedas***

`2022/F1/Q15` (código técnico `M2-22-F1-Q15`)

**Motor cognitivo (Apêndice A, uso interno).** Calcular o troco de uma compra e testar se esse valor pode ser formado usando exatamente um número dado de moedas, dentre as moedas do sistema monetário brasileiro. A questão pede a alternativa em que essa formação é impossível, o que exige testar as combinações de moedas, não só calcular o valor do troco.

**Nó principal (Apêndice D, grade oficial).** `Aritmética › Operações com Números Naturais › Sistema monetário e troco`, com o descritor "restrição do número de moedas". Este é o nó já citado no §$3$ do protocolo entre os "nós que mais aparecem", então a questão se encaixa diretamente nele, sem necessidade de subnó novo.

**Descritores secundários.**
- Restrição de inteiros / paridade como peneira (aqui, restrição sobre quantas parcelas de determinados valores fixos podem somar um total).
- Menu completo de uma categoria (todas as alternativas são preços plausíveis de doce, e só o teste da restrição de moedas separa a impossível das possíveis).

**Não é X (e por quê).**
- Não é Raciocínio Lógico › Problemas com Restrições e Dedução, porque a resposta não vem de eliminar casos por contradição entre falas ou regras de posicionamento, vem de uma conta de subtração seguida de um teste aritmético sobre combinações de moedas.
- Não é Álgebra pré-algébrica, porque não há incógnita para isolar por operação inversa, o preço de cada doce já está dado, o trabalho é testar viabilidade.
- Não é Comparação de dois cenários (real × hipotético), porque não há duas versões da mesma compra para comparar, e sim várias compras candidatas independentes.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 3** › **Bloco 4 · Área e dinheiro** › capítulo de teoria "Área e dinheiro" (`Cap_Area_Dinheiro.md`), seção "Moedas, troco e a ideia de completar um valor" e seguintes.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Area_Dinheiro.md` alternam entre os dois submotores, $5$ questões de área e $5$ de dinheiro, intercaladas:

**Submotor de área (`Aritmética › Grandezas e Medidas › Área › Contagem de Unidades em Malha Quadriculada`).**
- Exercício $1$: contagem direta de quadradinhos numa figura irregular.
- Exercício $3$: achar, entre retângulos descritos por linhas e colunas, o que tem a mesma área de uma figura irregular dada (mesmo motor da questão de referência `2019/Q10`).
- Exercício $5$: contagem direta de quadradinhos numa figura irregular maior, em formato de losango.
- Exercício $7$: comparar a área de duas figuras irregulares diferentes e achar a diferença entre elas.
- Exercício $9$: achar, entre retângulos descritos por linhas e colunas, o que tem a mesma área de uma figura em formato de L (segunda aplicação do motor da questão de referência `2019/Q10`, com contagem mais longa).

**Submotor de dinheiro (`Aritmética › Operações com Números Naturais › Sistema monetário e troco`, descritor "restrição do número de moedas").**
- Exercício $2$: troco formado só com moedas de um único valor, contando quantas moedas são necessárias.
- Exercício $4$: achar, entre preços candidatos, o único que NÃO pode ter gerado troco em exatamente $3$ moedas (mesmo motor da questão de referência `2022/F1/Q15`).
- Exercício $6$: troco formado em exatamente $3$ moedas de valores diferentes, perguntando quantas moedas de um valor específico entram na combinação.
- Exercício $8$: menor quantidade possível de moedas para formar um valor exato, sem restrição de quantidade dada de antemão.
- Exercício $10$: achar, entre preços candidatos, o único que PODE ter gerado troco em exatamente $2$ moedas (versão em espelho do motor da questão de referência `2022/F1/Q15`, com pergunta positiva em vez de negativa).
