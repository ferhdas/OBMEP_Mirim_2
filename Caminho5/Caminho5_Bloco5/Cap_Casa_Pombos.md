# Não tem como caber sem repetir

> Trilha Mirim 2 · Caminho 5 · Bloco 5 · Não tem como caber sem repetir. Nó da grade: Raciocínio Lógico › Problemas com Princípios de Existência / Princípio da Casa dos Pombos (ver `Classificacao_Casa_Pombos.md`).

Este capítulo é sobre garantir que uma repetição vai acontecer, sem precisar saber os detalhes de como. Quando há mais objetos do que gavetas, por que é impossível guardar cada objeto numa gaveta diferente? E se quisermos garantir não duas, mas três ou quatro repetições na mesma gaveta, quantos objetos precisamos? E como reconhecer uma "gaveta" escondida numa situação que nem parece, à primeira vista, um problema de guardar coisas? As três perguntas se resolvem imaginando o pior cenário possível, o que mais adia a repetição, e então mostrando que, mesmo nesse cenário, ela é obrigatória.

***Mais objetos do que gavetas obriga uma gaveta a receber dois***

Quando há mais objetos do que gavetas disponíveis, é impossível guardar cada objeto numa gaveta diferente, porque as gavetas acabam antes dos objetos. Para garantir isso sem testar todas as formas de distribuir, basta imaginar o cenário que mais adia a repetição: um objeto por gaveta, até as gavetas acabarem. O próximo objeto, o que seria o de número gavetas $+ 1$, não tem mais gaveta vazia esperando por ele, e cai numa gaveta que já tem um.

**Exemplo 1:** Numa gaveta há meias de $5$ cores diferentes, muitas de cada cor. Tirando meias sem olhar, uma de cada vez, **quantas meias são precisas para garantir duas meias da mesma cor?**

[Inserir aqui a figura `pombos_basico_estrutura.svg`.]

Primeiro, imaginamos o pior cenário, o que mais adia a repetição. É possível tirar uma meia de cada cor, sem repetir nenhuma, e isso usa exatamente $5$ meias, uma para cada uma das $5$ cores.

Em seguida, olhamos para a próxima meia, a sexta. Como já existe uma meia de cada uma das $5$ cores, a sexta meia obrigatoriamente repete uma cor que já apareceu.

$5 + 1 = 6$

São precisas $6$ meias para garantir duas da mesma cor. Conferimos porque, com apenas $5$ meias, ainda é possível ter uma de cada cor, sem repetir nenhuma, então $5$ não garante nada. Só a sexta meia fecha a garantia.

[Inserir aqui a figura `pombos_basico_resultado.svg`.]

**Guarde. Com $n$ gavetas, $n + 1$ objetos sempre garantem que pelo menos uma gaveta recebe dois. Com $n$ objetos ou menos, ainda é possível espalhar um por gaveta, sem repetir nenhuma.**

***Para garantir mais repetições, o pior cenário cresce junto***

Quando o que se quer garantir não é só uma repetição, mas um número maior de objetos na mesma gaveta, o raciocínio do pior cenário continua o mesmo, só que agora cada gaveta pode "aguentar" mais objetos antes de estourar. Se queremos garantir $k$ objetos numa mesma gaveta, o pior cenário deixa cada gaveta com $k - 1$ objetos, o máximo que ainda evita a repetição desejada, e só o próximo objeto força a garantia.

**Exemplo 2:** Numa caixa há bolinhas de $3$ cores diferentes, muitas de cada cor. Tirando bolinhas sem olhar, **quantas são precisas para garantir $3$ bolinhas da mesma cor?**

[Inserir aqui a figura `pombos_minimo_estrutura.svg`.]

Primeiro, imaginamos o pior cenário para evitar $3$ bolinhas repetidas. É possível tirar $2$ bolinhas de cada cor, sem que nenhuma cor chegue a $3$, e isso usa $2$ bolinhas para cada uma das $3$ cores.

$2 \times 3 = 6$

Em seguida, olhamos para a próxima bolinha, a sétima. Como todas as $3$ cores já têm $2$ bolinhas cada, a sétima bolinha obrigatoriamente faz alguma cor chegar a $3$.

$6 + 1 = 7$

São precisas $7$ bolinhas para garantir $3$ da mesma cor. Conferimos porque, com $6$ bolinhas, o cenário de $2$ de cada cor é possível e não tem $3$ repetidas, então $6$ não garante nada. Só a sétima bolinha fecha a garantia.

[Inserir aqui a figura `pombos_minimo_resultado.svg`.]

**Guarde. Para garantir $k$ objetos numa mesma gaveta, com $n$ gavetas, o número mínimo de objetos é $(k - 1) \times n + 1$. O caso mais simples, garantir só $2$ na mesma gaveta, é esse mesmo cálculo com $k = 2$.**

***Nem toda "gaveta" parece uma gaveta***

O princípio da casa dos pombos se aplica em muitas situações que não parecem, à primeira vista, um problema de guardar objetos em gavetas. O primeiro passo, nesses casos, é identificar o que está fazendo o papel de gaveta (uma categoria com um número fixo de opções) e o que está fazendo o papel de objeto (a quantidade de coisas sendo distribuídas entre essas opções).

**Exemplo 3:** Numa turma de $8$ alunos, cada um nasceu num dos $7$ dias da semana. **É possível garantir que pelo menos dois alunos nasceram no mesmo dia da semana?**

[Inserir aqui a figura `pombos_disfarcada_estrutura.svg`.]

Primeiro, identificamos as gavetas e os objetos escondidos no enunciado. As gavetas são os $7$ dias da semana, porque cada aluno nasce em exatamente um deles, e os objetos são os $8$ alunos, cada um caindo numa dessas gavetas.

Em seguida, comparamos o número de objetos com o número de gavetas. Como há $8$ alunos para apenas $7$ dias da semana, e $8$ é maior que $7$, a mesma regra do primeiro exemplo se aplica direto.

$7 + 1 = 8$

Sim, é possível garantir que pelo menos dois alunos nasceram no mesmo dia da semana. Conferimos porque, com $7$ alunos, seria possível ter um aluno nascido em cada dia diferente, sem repetir nenhum, mas o oitavo aluno obrigatoriamente cai num dia que já tem alguém.

[Inserir aqui a figura `pombos_disfarcada_resultado.svg`.]

**Guarde. Antes de aplicar a régua, pergunte: o que está fazendo o papel de gaveta aqui, e o que está fazendo o papel de objeto? Uma vez identificados os dois, o problema vira um caso comum de casa dos pombos.**

Este capítulo reuniu três formas de garantir repetições sem testar todas as possibilidades. No caso básico, $n + 1$ objetos em $n$ gavetas sempre garantem uma repetição. Para garantir mais de duas repetições na mesma gaveta, o pior cenário cresce, e o mínimo vira $(k - 1) \times n + 1$. E, em situações disfarçadas, o primeiro passo é sempre achar a gaveta e o objeto escondidos no enunciado, antes de aplicar a régua. Em todos os casos, a mesma ideia de fundo resolve: imaginar o cenário que mais adia a repetição, e mostrar que, mesmo nele, ela é obrigatória.

---

***Ilustrações***

| Arquivo | Onde entra | O que mostra |
|---|---|---|
| `pombos_basico_estrutura.svg` | Após o problema fechado das meias | As $5$ gavetas de cor, cada uma com uma meia, sem a sexta meia desenhada |
| `pombos_basico_resultado.svg` | Ao final da resolução do exemplo das meias | As $5$ gavetas cheias e a sexta meia caindo numa delas, forçando a repetição, em destaque |
| `pombos_minimo_estrutura.svg` | Após o problema fechado das bolinhas | As $3$ gavetas de cor, cada uma com $2$ bolinhas, sem a sétima bolinha desenhada |
| `pombos_minimo_resultado.svg` | Ao final da resolução do exemplo das bolinhas | As $3$ gavetas com $2$ bolinhas cada e a sétima bolinha, em destaque, completando a terceira numa delas |
| `pombos_disfarcada_estrutura.svg` | Após o problema fechado da turma | As $7$ gavetas de dia da semana, com $7$ alunos distribuídos, sem o oitavo aluno desenhado |
| `pombos_disfarcada_resultado.svg` | Ao final da resolução do exemplo da turma | As $7$ gavetas com o oitavo aluno caindo numa delas, forçando a repetição, em destaque |
