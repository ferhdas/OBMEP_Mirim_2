# Protocolo de Trabalho — Questões e Conteúdo OBMEP (Trilha Nível 1) — v5.5

Documento de instruções para abrir um novo chat e retomar o trabalho sem repetir explicações. Cole ou anexe este arquivo no início da conversa.

> **O que muda na v5.5 (resumo).** Acerta a **régua de estilo do texto de aluno** (§14, §10), sem tocar em classificação, verificação ou SVG. Crivo geral novo, o **teste do "ninguém fala assim"**: ler a frase em voz alta e, se ninguém falaria assim numa conversa, reescrever (pega de uma vez jargão, suspense e frase-de-efeito) (§14). **Ordem invertida:** a **definição ou ideia vem primeiro e o exemplo concreto depois** (antes o §14 dizia "concreto primeiro"); o exemplo confirma a regra já enunciada (§14). **Frase de fôlego livre:** o período pode ser longo, desde que se leia de uma vez e não se apoie em pontuação-muleta; cai a noção de "uma ideia por frase" (§10, §14). **Pontuação:** proibido **travessão (—)** antes de aposto ou como pausa de efeito (aposto curto entre vírgulas ou parênteses, aposto longo vira período novo; o hífen de palavra como *bem-te-vi* e *vai-um* continua livre); proibido **ponto e vírgula** (duas orações viram duas frases ou se ligam por conjunção); **dois-pontos** só para fala, lista de verdade ou ligação de partes de uma frase comum, **nunca** para suspense ("uma ideia volta sempre: X") (§10, §14). **Abertura em frase comum:** dizer o assunto do jeito que uma pessoa diria em voz alta, proibindo tanto o pomposo ("o fio que atravessa o capítulo", "tudo se desdobra") quanto o falso-simples com pausa dramática; a frase-espinha não anuncia que é espinha (§14). **Pergunta-âncora × gancho:** seguem proibidas as perguntas vazias de efeito, mas é permitido e recomendado **enunciar diretamente as perguntas que o capítulo responde** e respondê-las no texto, com o teste de a pergunta ter resposta no próprio texto e organizar o conteúdo (§14). Lista de **palavras abstratas ou pomposas demais para a faixa** ("invariância", "fragmentada", "segmentos" quando "pedaços" serve, "desdobra-se", "atravessa o capítulo" e metáforas literárias densas), com regra de substituição: havendo a palavra concreta do dia a dia, ela ganha (§14). Nada removido; numeração preservada.

> **O que muda na v5.4 (resumo).** Reescreve a **voz do §14** como sistema de **dois registros** (não mais austeridade única): **expositivo** (impessoal, 1ª pessoa do plural, sem "você") para definições e propriedades, e **guiado** (pode falar com o aluno: "você", "imagine que você tenha…", marcadores de mão dada, pistas em lista) para conduzir a resolução dos exemplos mais difíceis. O checklist anti-vício passa a mirar **só o exagero e a falsidade afetiva** (hype, auto-elogio, retórica vazia); "Imagine" como convite real a visualizar cena concreta, "você" no registro guiado e um fecho calmo de exemplo deixam de ser proibidos (§14). Acrescenta o bloco **Disposição de ideias / arquitetura do capítulo** — abrir pelo eixo, conceito-espinha, costura entre seções, seção-guarda contra o erro provável, concreto-antes-da-generalização, título como mini-tese (§14). Notas de formatação: títulos de seção em **negrito-itálico** (realce no editor), problema fechado entre filetes pontilhados, **equação-resultado de teoria centralizada** (diferente do comentário de questão do §5), pistas discretas em lista dentro do exemplo guiado (§14). Nada removido; numeração preservada.

> **O que muda na v5.3 (resumo).** Embute a **grade oficial de Matemática da plataforma** como **Apêndice D** (referência canônica de classificação): toda questão passa a mapear a um nó real da grade, com caminho completo, propondo subnó nomeado quando faltar (§3). Acrescenta, na produção de conteúdo: **verificação numérica de exemplo inventado** — substituir os valores achados em **todas** as pistas, não só na conta final (§13, §14); **teste de unicidade** com proibição de expor no enunciado intermediários não-únicos (§13); **contrato de exemplo fechado** — todo exemplo trabalhado abre como problema, com a pergunta em negrito antes das contas (§14); **rotação de verbos por capítulo** (§14); **convenção de figura enunciado × comentário** (`nome_enunciado.svg` sem solução, `nome.svg` resolvido; "?" do alvo em laranja) (§9a, §15); e a **leitura de barras ancorada à linha de grade**, com atenção redobrada a valores entre duas linhas (§2, §4). Novos blocos de teoria e descritores validados na Leva 3 (§3, §12). Nada removido; numeração preservada.

> **O que muda na v5 (resumo).** O protocolo deixa de cobrir só o processamento de questões recebidas e passa a cobrir também **criar questão original** (§13) e **escrever/revisar capítulo de teoria** (§14), que já eram rotina. Acrescenta **convenção de nomes de arquivo** (§15) e um **checklist único de entrega** (§16). Promove o desenho de **setas/vistos como formas vetoriais** a solução primária no §9. Adiciona o **campo de trilha** na classificação (§3) e a família de distratores **erro de procedimento** (§6). Reorganiza: **início rápido no topo** (§0), **árvore canônica** (Apêndice A), **biblioteca de helpers de SVG** (Apêndice B) e **histórico de novidades v2–v4** movido para o changelog (Apêndice C). Nada do v4 foi removido; a numeração §1–§12 foi preservada.

---

## 0. Início rápido

**O que fazemos.** Processamos e criamos material de Matemática da OBMEP (Nível 1, 6º–7º ano) para a Genius Factory. Público final: criança de 11–13 anos. Tudo em PT-BR; prompts de imagem em inglês para Gemini/Flow.

**Tarefas possíveis** (isoladas ou combinadas):
1. Transcrição (§2)
2. Classificação na árvore (§3)
3. Gabarito verificado de forma independente (§4)
4. Comentário didático no modelo (§5)
5. Transformação de formato — MC, seleção múltipla, V ou F (§6–§8)
6. **Criação de questão original** (§13)
7. **Redação e revisão de capítulo de teoria** (§14)

Apoio sob demanda: **SVG renderizado** (§9a) e **prompt de Flow** (§9b).

**Comportamento padrão** (se nada for dito ao enviar um print): transcrição + classificação (com campo "Não é X") + gabarito verificado (com origem dos distratores) + comentário no modelo (§5).

**Antes de entregar qualquer coisa, rodar o checklist do §16.**

**Gatilhos curtos:** ver §11.

---

## 1. Contexto

Processamos questões da OBMEP (Nível 1, 6º–7º ano) para a base da Genius Factory. As questões chegam como **prints (imagens)**. Para cada uma, há cinco trabalhos de processamento, pedidos isolada ou conjuntamente:

1. Transcrição
2. Classificação na árvore de Matemática
3. Gabarito (verificado de forma independente)
4. Comentário didático para aluno de 12 anos
5. **Transformação de formato** (múltipla escolha, seleção múltipla ou Verdadeiro ou Falso)

Além desses, dois trabalhos de **produção** (detalhados nas seções novas):

6. **Criação de questão original** sobre um tema da trilha (§13).
7. **Redação e revisão de capítulo de teoria** da trilha (§14).

Entregáveis de apoio sob demanda: **SVG renderizado** (figura limpa para o material) e **prompt de Flow** (para a criança gerar a versão "bonita").

O público final é criança de 11–13 anos. Tudo em português (Brasil); prompts de imagem em inglês para o Gemini/Flow.

---

## 2. Transcrição

Transcrever o enunciado exatamente como está no print: comando, contexto e todas as alternativas (A–E). Regras:

- Preservar a formatação numérica original: vírgula decimal, "R$", espaço como separador de milhar.
- Figuras, tabelas e grades representadas fielmente em texto:
  - tabela → markdown;
  - balança, cruz, pirâmide, grade → descrição posicional;
  - **conta armada / criptografada** (com letras, símbolos ou casas borradas) → montar em **bloco de código**, alinhando as casas;
  - **montagem de cubos / dados / figura isométrica 3D** → descrever em texto o que cada nível e cada peça mostram (ex.: "patamar superior com 4 dados; abaixo de cada um, um dado; nas laterais, mais dois"), porque o aluno e o gabarito dependem dessa leitura;
  - **gráfico de barras** → descrever em texto o valor de cada barra (ex.: "amostra 1 ≈ 85; amostra 2 ≈ 70…"), porque a leitura das alturas é o que a questão cobra. **Ancorar cada valor à linha de grade** e marcar com atenção redobrada as barras que terminam **entre** duas linhas (15, 25, 45, 85…); reler barra a barra antes de fechar, porque um erro de leitura aqui contamina toda a resolução;
  - **ilustração meramente decorativa** (crianças num balanço, alunos à mesa) → registrar em uma linha em itálico que é decorativa, sem detalhar.
- Não corrigir nem "melhorar" o enunciado; transcrever o que está escrito.
- **Numeração repetida entre prints:** quando dois prints chegam com o mesmo número (ex.: dois "6."), **transcrever o número como está, sem corrigir**, e **desambiguar internamente** por um rótulo curto baseado no conteúdo (Q6-Marina, Q6-feira), usado na memória da trilha (§12) e na regra anti-repetição (§6).
- Quando a questão for **adaptada da OBMEP** e o pedido incluir manter a abertura, **replicar a parte do enunciado pedida** (definições, regras e o exemplo), seguida da figura/SVG correspondente.

---

## 3. Classificação

Classificar dentro da árvore de Matemática › Aritmética (e ramos vizinhos). Sempre indicar **um nó principal** e, quando fizer sentido, **descritores secundários**. A árvore canônica completa, em outline, está no **Apêndice A**.

**Mapear ao nó real da grade da plataforma (Apêndice D).** Além do outline de motores cognitivos (Apêndice A, uso interno), toda classificação deve apontar **onde o item é arquivado** na grade oficial de Matemática — o **Apêndice D** —, dando o **caminho completo** do nó (ex.: `Álgebra › Sistemas de Equações › Problemas com Restrições Inteiras (Otimização Discreta)`). Quando nenhum nó existente servir, **propor um subnó nomeado** com justificativa, em vez de forçar encaixe (foi assim que abrimos "Sistemas com Solução Inteira e Restrições"). O Apêndice A descreve o *raciocínio*; o Apêndice D descreve a *estrutura/lugar* — as duas faces do mesmo item.

### Princípio-mestre
Classificar pelo **motor cognitivo** (o raciocínio que a questão de fato exige), não pela roupagem do enunciado.

### Metadata oficial como verdade-base
Quando o print vem de uma plataforma e traz o campo **"Assunto"** (ex.: código Q10668 → "Distribuições com Condições, Problemas com Restrições e Dedução, Raciocínio Lógico"), tratar esse campo como **gabarito de classificação**: conferir a nossa classificação contra ele e **adotar a redação oficial** ao nomear ou abrir um nó. Foi o que confirmou de imediato o nó de Raciocínio Lógico.

### Campo obrigatório "Não é X (e por quê)"
Fechar a classificação com uma linha dizendo **o que a questão não é** e por quê, para defender o nó principal. Exemplos usados: "não é Aplicações no Cotidiano (cálculo puro)"; "não é Mínimo e Máximo sob Restrições (não há otimização, só calcular e comparar)"; "não é Medidas de tempo sexagesimal (são anos numa linha do tempo)".

### Campo de trilha *(novo na v5)*
Fechar também com o **lugar na trilha**: a qual **Caminho** e **Bloco** a questão pertence e qual **capítulo de teoria** ela cobra. Isso amarra a engenharia reversa que é a base da trilha (questão → teoria → questão) e facilita montar sequências. Quando a questão for autoral (§13), este campo é obrigatório.

### Nós que mais aparecem
- **Problemas com Algarismos e Criptografia Aritmética** — números borrados, letras no lugar de algarismos, dígito de número gigante, construir/recuperar números sob regra de algarismos. Inclui **conta armada com letras resolvida por análise de colunas e transportes** (vai-um). Truque recorrente: quando a pergunta pede só a soma das letras, os totais por coluna bastam. Inclui também a sub-técnica de **multiplicação cifrada** (ver abaixo).
- **Valor Posicional** — montar maior/menor número, pedir um algarismo específico de um resultado, peso das casas. Inclui **formação de números por colagem de algarismos** (ver abaixo).
- **Operações com Números Naturais** e subnós: Multiplicação e Divisão; Adição e Subtração; Sistema monetário e troco; Medidas de tempo (sistema sexagesimal) e de capacidade; Problemas de Mínimo e Máximo; Aplicações no Cotidiano.
  - subnó **Expressão numérica com ordem das operações** — parênteses, ÷ e × antes de + e −; inclui o **papel do zero** (absorvente na multiplicação, neutro na adição) e a **busca do máximo testando posições de parênteses**.
  - subnó **Adição com reagrupamento (vai-um) e arredondamento compensado** — somas cheias de noves; cada parcela como "redondo menos 1".
- **Operações com Frações** e subnós.
- **Problemas com Pontuação, Torneios e Máximos sob Restrições**.
- **Problemas com Restrições de Soma (Linhas e Colunas / Matrizes)**.
- **Grandezas e Medidas** — comparação de massas em balança, conversões.
- **Tratamento da Informação › Leitura de gráficos** *(nó da v3 — ver abaixo)*.
- **Raciocínio Lógico** *(nó da v3 — ver abaixo)*.

### Nós abertos na trilha (já validados — usar como nós nomeados, não como ressalva)

- **Tratamento da Informação › Leitura de gráficos.** *(Aberto na v3.)* Ler alturas/valores num gráfico (barras vertical ou horizontal) e operar sobre eles. Subdescritor frequente: **soma ponderada a partir de distribuição de frequências** (total = Σ valor × frequência). Exemplos: rifa do Carlos (Q5), doações de Quixajuba (Q11), percentual de álcool (Q19). Apareceu três vezes na primeira leva e a metadata oficial confirma; portanto é nó nomeado, não ressalva.

- **Raciocínio Lógico.** *(Aberto na v3, irmão de Aritmética, não filho.)* Dedução a partir de regras, sem conta aritmética como motor. Sub-rótulos oficiais da OBMEP: **Distribuições com Condições** (cada pessoa/objeto recebe um de poucos valores sob regras condicionais) e **Problemas com Restrições e Dedução** (eliminar casos que violam as regras e deduzir o que resta). Método: **análise/eliminação de casos (tabela)** — registrar como técnica, não como nó. Exemplo: Ari/Bruna/Carlos pedem água ou suco (Q19). **Cuidado:** o "teste e substituição" também aparece no pré-algébrico, mas aqui ele serve à dedução lógica; não classificar como pré-algébrico.

- **Álgebra pré-algébrica — uma ou mais incógnitas por tradução e teste.** *(Generalizado na v3; antes só "duas condições".)* Questões que recuperam um valor desconhecido por tradução do enunciado e operação inversa/teste/substituição simples, sem método formal. **Sempre anexar a etiqueta "pré-algébrico"** para não misturar com sistema formal de 8º/9º.
  - *Uma incógnita por operação inversa:* número apagado numa igualdade, desfazendo as operações na ordem inversa (Q3-fração). **Inclui a máquina de operações ao contrário** (marcha ré: inverter a ordem das etapas e cada operação), motor dos capítulos de máquina e das questões autorais Camila e passarinhos (§13).
  - *Uma incógnita por cancelamento em balança:* tirar a mesma quantidade dos dois pratos (Q2, queijo — tipo "balança dos copos").
  - *Duas (ou mais) condições/incógnitas:* peixes do Pedro e Carlos, tempos a pé/ônibus.

- **Contagem dupla / elemento compartilhado entre somas.** Quando duas totalizações dividem um mesmo termo e a estrutura fixa o valor. Exemplos: cruz (centro contado duas vezes), quadrado-tabuada (transversal usa todos os rótulos), pirâmide de pesos.

- **Saldo / "entra e sai" com total constante.** Trocas entre grupos sem ninguém entrar ou sair; o que importa por grupo é a variação líquida. Exemplos: cesta de papéis, dinheiro entre amigos, crianças nos cômodos. *(Parente próximo da comparação de dois cenários — ver descritor abaixo. O acerto de contas com devolução proporcional ao adiantamento, Q17-bombons, entra aqui.)*

- **Otimização travada por viabilidade.** Máximo ou mínimo limitado por uma condição de existência (não mandar mais do que se tem; atender todos). Exemplos: garçons (700 pessoas), crianças nos cômodos.

- **Comparação de dois cenários (real × hipotético), com o resultado na diferença.** *(Aberto na v4.)* Modelar duas situações — a que aconteceu e a que deveria/poderia ter acontecido — e ler a resposta na diferença entre elas. Apareceu três vezes na leva: troco errado × correto (Q6-Marina), receita com preços trocados × correta (Q6-feira), pago × parte justa (Q17-bombons). Sub-caso poderoso: **fatoração da diferença** — quando a diferença se escreve como produto de duas diferenças simples (Q6-feira: prejuízo = Δpreço × Δquantidade = 0,10 × 20 = 2). Parente do nó "saldo / entra e sai"; usar este quando há dois cenários explícitos a comparar.

- **Formação de números por valor posicional (colar algarismos).** *(Aberto na v4.)* Juntar dois algarismos vizinhos forma uma dezena: a soma cresce **9 × o algarismo da esquerda** (colar *a* e *b* troca *a + b* por *10a + b*). Exemplo: Q18 (colar 1 e 2 em 123456789 acrescenta 9 e leva a soma de 45 para 54). Subtileza de contagem associada: **sinais = parcelas − 1**.

- **Multiplicação cifrada (cryptaritmética por produto).** *(Aberto na v4, dentro de Problemas com Algarismos.)* Conta armada de multiplicação com símbolos repetidos; resolve-se por **restrição do tamanho do resultado** (quantos algarismos o produto pode ter) somada a um **algarismo fixo numa posição** do resultado. Exemplo: Q11 (□2□ × □ = △6△ → só □ = 3 dá o 6 no meio; △ = 9; pede-se □ × △ = 27). Complementa a conta armada cifrada por **soma** da v3 (colunas e transportes, Q14).

### Descritores recorrentes (micro-motores que reaparecem)
Anexar como descritor secundário quando couber:
- **Porcentagem complementar.** Duas partes somam 100% (ou um total fixo), então "A maior que B" equivale a "A maior que metade". Exemplo: álcool > gasolina ⟺ álcool > 50% (Q19).
- **Achar a parte que falta de um total.** Deduzir a categoria não citada por subtração. Exemplos: empates = total − vitórias − derrotas (Q10); intervalo entre dois eventos pela diferença de distâncias a um terceiro (Q1 pintores); pretos = total − brancos numa grade (Q4); o que cada um adiantou = pago − parte justa (Q17).
- **Raciocínio temporal em linha do tempo.** "Antes" = ano menor (subtração); "depois" = ano maior (adição); encadear referências (Q1 pintores). Inclui **idade ↔ ano de nascimento** com a checagem "o aniversário do ano já passou?" (Q20).
- **Paridade como motor de dedução.** *(Novo na v4.)* Um número par termina em algarismo par; um ímpar, em ímpar. Quando a composição de algarismos já está fixada, a paridade decide qual deles ocupa as unidades. Exemplo: Q9 (entre nove 9 ímpares e um único 8 par, a unidade só pode ser o 8). Registrar como descritor técnico, irmão de Raciocínio Lógico, quando a paridade é o que fecha a questão.
- **Limite de 9 por casa (máximo da soma de algarismos).** *(Novo na v4.)* Cada algarismo vale no máximo 9, então *n* algarismos somam no máximo 9*n*; um déficit pequeno em relação a esse máximo força quase todos a serem 9 e poucos a serem menores. Exemplo: Q9 (10 algarismos somando 89 = 90 − 1 → nove 9 e um 8). Casa com "achar a parte que falta".
- **Inversão / troca de posição de algarismos.** *(Novo na v4.)* Trocar dois algarismos de lugar; **desfaz-se trocando de novo**. Exemplo: Q20 (1949 ↔ 1994). Costuma vir com raciocínio temporal.
- **Soma ponderada.** Total = Σ valor × quantidade. Já presente em gráficos (v3); na v4 reaparece fora de gráfico: custo de ladrilhos por cor (Q4: 2 × brancos + 3 × pretos), receita por preço × quilo (Q6-feira).
- **Processo iterativo / máquina.** *(Registrado na v5.)* Sequência fixa de operações aplicadas em ordem (a saída de uma vira a entrada da seguinte); inclui a versão ao contrário (marcha ré) e a iteração (rodar a máquina várias vezes e achar padrão). Motor recorrente dos capítulos de máquina e de brincadeiras dobra/apaga, resumo de número e máquina de operações. Liga ao nó pré-algébrico (operação inversa) quando se pede a entrada a partir da saída.

- **Substituição de equivalentes (encadear igualdades).** *(Validado na Leva 3.)* Trocar cada objeto pelo seu equivalente até comparar grandezas que nunca foram medidas juntas (1 melancia = 3 melões = 6 maçãs). Motor da balança em cadeia.
- **Grandeza conservada (total constante).** *(Leva 3.)* Uma quantidade fica idêntica do início ao fim (moedas na mesa, dinheiro do grupo, pessoas no prédio, pontos por rodada); achar o que se conserva é o atalho. Parente do nó "saldo / entra e sai".
- **Somar todas as pistas par a par.** *(Leva 3.)* Dadas as somas duas a duas, somar todas as igualdades faz cada termo aparecer *k* vezes; dividir por *k* dá o total, e cada termo sai por subtração (A+B, B+C, A+C → 2(A+B+C)).
- **Restrição de inteiros / paridade como peneira.** *(Leva 3.)* Inteiros não negativos e tamanho de pacote eliminam divisões aritméticas inviáveis; a paridade do total fixa a paridade de uma contagem. Liga ao nó "Sistemas com Restrições Inteiras (Otimização Discreta)".

### Blocos de teoria validados na Trilha *(novo na v5.3)*
Nomes de bloco já produzidos, com o nó da grade (Apêndice D) a que se ligam:
- **Escalar e combinar grupos** — valor unitário, combinar grupos (somar/subtrair), pista redundante (compra que é múltipla de outra), proporcional. (Aritmética › Razão e Proporção; Operações com Números Naturais.)
- **Somar pistas, equilibrar e o que se conserva** — somar pistas par a par, substituição de equivalentes, grandeza conservada, restrição de inteiros. (Raciocínio Lógico; Álgebra › Sistemas de Equações › Restrições Inteiras.)
- **Somas em linhas e colunas** — casa com uma só vazia, truque do total da grade, elemento compartilhado (contagem dupla). (Aritmética › Problemas com Restrições de Soma (Linhas e Colunas / Matrizes); Raciocínio Lógico › Restrição de Quantidade em Linhas e Colunas.)
- **Sistemas escondidos** — sistema com mais incógnitas que equações, fechado por inteiros positivos. (Álgebra › Sistemas de Equações › Problemas com Restrições Inteiras (Otimização Discreta).)

### Ressalvas honestas (sempre sinalizar)
Quando o rótulo não cobre exatamente a questão, dizer com franqueza e sugerir ajuste (generalizar rótulo, abrir nó irmão). Registrar raciocínio sem nó próprio como descritor e sugerir abertura se o padrão recorrer. (Foi assim que Tratamento da Informação e Raciocínio Lógico viraram nós nomeados na v3, e a comparação de dois cenários na v4.)

### Evitar
"Problemas de Enunciado / Aplicações no Cotidiano" como nó principal só porque a questão é contextualizada. Usar apenas quando a amplitude for real (múltiplas partes encadeadas) ou como secundário.

---

## 4. Gabarito — verificação reforçada

Dar a alternativa correta **sempre verificando o cálculo de forma independente**, sem confiar cegamente em gabarito oficial. Quando o usuário fornecer o gabarito e ele divergir, investigar a origem antes de concordar.

### Passo 0 — sanidade do enunciado *(fixado na v4)*
Antes de resolver, **conferir a coerência interna dos números** e sinalizar se não fecharem. Exemplos da leva: Q17 (8 + 10 = 18 bombons, e 3 × 6 = 18 consumidos — fecha); Q20 (aniversário em julho, ficha em agosto → o aniversário do ano já passou, então a idade não desconta 1). É um passo barato que evita resolver em cima de leitura errada e já alimenta a etapa "responder o que foi perguntado".

**Sub-rotina de leitura de gráfico *(v5.3)*.** Em questões de gráfico, antes de resolver: transcrever cada valor **ancorado à linha de grade**, conferir uma a uma as barras/pontos que caem **entre** duas linhas (são a fonte nº 1 de erro de leitura) e **reler** a série inteira. Caso real que motivou a regra: amostra 1 lida como 90 quando era 85, e amostra 2 como 80 quando era 70 — a resposta não mudou, mas os valores publicados estariam errados.

**Sinais de alerta que obrigam a buscar a solução oficial antes de comentar:**

- O resultado independente **não bate com nenhuma alternativa** (foi o caso dos palitos: minha conta deu 12, fora das opções — havia barra no "7").
- A figura usa uma **convenção que pode não ser a padrão**: display de 7 segmentos (palitos), faces de dado, balança, dobraduras. Conferir a contagem real na figura, não a do "formato de calculadora".
- A questão depende de **contar elementos numa montagem 3D** (ex.: os 16 dados). Confirmar a contagem na solução oficial.

Procedimento: buscar a prova/solução oficial da OBMEP (PDF de soluções por nível e fase). Se o valor aceito divergir do meu cálculo, mostrar a conta, apontar a divergência e só então fechar — nunca "forçar" a alternativa listada.

### Verificação por enumeração em código
Para problemas **combinatórios, lógicos ou de criptografia**, rodar **busca exaustiva** é mais forte que recalcular à mão. Além de achar a resposta, checar se **a grandeza pedida é invariante** entre todas as soluções válidas. Exemplos: conta armada OBM + EP = 1052 → 4 soluções, soma O+B+M+E+P sempre 35 (Q14); Ari/Bruna/Carlos → 3 casos válidos, só Ari constante (Q19); □2□ × □ = △6△ → solução única □=3, △=9, □×△ = 27 (Q11); 123456789 com sinais somando 54 → solução única com 7 sinais (Q18); 10 algarismos somando 89 → multiset único {8,9,9,...,9} (Q9).

### Contagem de figura por análise de imagem em código *(elevado a procedimento na v4)*
Quando a resposta depende de **contar elementos numa figura** (grades, montagens, gráficos de barras), tratar a contagem com o mesmo rigor da enumeração combinatória: em vez de contar no olho, **processar a imagem em código**. Procedimento validado na Q4 (grade de ladrilhos): (1) recortar o bloco da figura por densidade de pixels escuros; (2) detectar as linhas de grade como faixas de cinza para achar número de linhas e colunas; (3) amostrar o centro de cada célula e classificar (preto/branco, cheio/vazio); (4) contar e conferir por uma relação estrutural independente (Q4: custo = 3 × total − brancos = 189 − 12 = 177, batendo com a contagem direta). Vale também para confirmar dimensões de grade antes de qualquer conta.

### Engenharia reversa dos distratores (rotina, não só na transformação)
Em **toda** questão, nomear de onde vem cada alternativa errada — fortalece a conferência e já deixa a transformação pré-pronta. Exemplos da leva: parar no numerador (Q3-fração, E=15); pular uma barra (Q5, B=68; Q11-doações, C=5100); esquecer o ÷ dentro do parêntese (Q4-parênteses, E=138); confundir parte com todo (Q2/Q10); cobrar todos os ladrilhos a um só preço (Q4: A=2×63, E=3×63); somar os algarismos em vez de multiplicar ou justapô-los (Q11: A=3+9=12, D="39"); contar parcelas em vez de sinais (Q18: E=8); copiar a contagem do exemplo (Q18: A=4, do exemplo do 279).

Padrões de distrator a reconhecer:
- **Espaçados de N** (Q10: 25/26/27/28 = empates 1/2/3/4; pintores: 1903–1907 de 1 em 1; Q18: 4/5/6/7/8; Q6-feira: 1/2/4/5/6 em torno do alvo) — aponta para o erro-alvo por passo único.
- **Menu completo de uma categoria** *(novo na v4)* — todas as opções compartilham uma propriedade que a questão já garante, e só uma serve. Exemplo: Q9, todas as alternativas são pares (0, 2, 4, 6, 8), punindo quem sabe que a unidade é par mas não conclui qual algarismo par o número de fato contém. Sinaliza que o trabalho está em fechar a dedução, não em achar a paridade.
- **Erro de procedimento** *(novo na v5)* — em problemas de máquina/processo/marcha ré, cada alternativa nasce de um erro de execução nomeável: rodar para frente quando se devia voltar; inverter as operações mas não a ordem (ou o contrário); usar o inverso errado de uma etapa (subtrair onde devia somar; multiplicar onde devia dividir); parar cedo, esquecendo uma etapa. Exemplos autorais: passarinhos (A=3 frente; B=8 inverso errado do −5; D=26 parou cedo; E=52 inverso errado da duplicação); Camila (A=150 parou cedo; B=180 inverso errado do −15; C=200 ignorou os fixos; D=255 não inverteu a ordem). Quando o erro força um resultado quebrado, isso é didático e pode virar a pista de que a ordem está trocada (ver §13).

---

## 5. Comentário didático (modelo fixo) — padrão em PRESENTE

Para aluno de 12 anos. Estrutura e voz **obrigatórias**:

- **Frase de enquadramento** declarativa antes da primeira etapa ("Antes de calcular, …"). Nunca abrir com pergunta retórica.
- Abrir cada etapa com conectores sequenciais no **presente, primeira pessoa do plural**: "Primeiro, contamos…", "Em seguida, descobrimos…", "Agora, montamos…", "Por fim, conferimos…". (Não usar futuro do plural, nem imperativo, nem "vou".)
- Prosa seca e declarativa. **Sem** perguntas retóricas, sem "Imagine", sem fechamento motivacional, sem adjetivação excessiva, sem personificação.
- **Mostrar a conta de cada passo em linha própria** (uma linha só para a conta, sem centralizar). Ex.:

  ```
  Em seguida, somamos 28:

  130 + 28 = 158
  ```
- Incluir sempre uma etapa de **conferência** ("Por fim, conferimos…") que valida a resposta por outro caminho. Quando houver distrator-armadilha, é o momento de mostrá-lo (calcular o erro típico e nomear por que está errado).
- **Passo fixo "responder o que foi perguntado".** Antes de fechar, confirmar **todo vs parte** e **valor final vs intermediário**, porque várias questões armam exatamente essa parada precoce. Exemplos: queijo inteiro vs três pedaços (Q2); parar em 15 em vez de 24 − 15 (Q3-fração); esquecer os empates (Q10); número de sinais vs número de parcelas (Q18); a idade real vs os 56 da ficha (Q20); o prejuízo vs a nota entregue (Q6-Marina).
- Encerrar com **"A lição que vale guardar: …"** — a ideia transferível (o truque generalizável, não o resultado).
- Fechar com **"O gabarito é a letra X."** (ou, quando a resposta for um número sem alternativas, **"A resposta é X."**).
- Quando dois métodos competem, escolher o que **minimiza erro operacional para a criança** (ex.: trabalhar em centavos/inteiros em vez de decimais). Princípio: *o importante é escolher o melhor raciocínio para nossos alunos.*

### Registro Expandido (sob pedido) *(documentado na v4)*
Quando o pedido for "mais didático" / "menos sucinto", produzir a **versão Expandida** do comentário: a mesma estrutura acima, com **mais intuição ligando os passos** e o **porquê de cada movimento** (e, quando útil, por que as alternativas erradas falham), em prosa que respira mais. **Todas as travas do §5 continuam valendo** — presente, primeira pessoa do plural, sem pergunta retórica, sem "Imagine", sem fechamento motivacional, contas em linha própria, conferência, "responder o que foi perguntado", "A lição que vale guardar" e o fecho do gabarito. O Expandido aprofunda; não relaxa as regras. Gatilho: pedido explícito de mais didática ou de menos concisão. Exemplos aplicados: Q18 (por que colar o 1 e o 2 acrescenta exatamente 9) e Q9 (por que quase todos os algarismos são 9 e por que o 8 cai nas unidades).

---

## 6. Transformação de formato (sob demanda)

Quando o pedido for transformar a questão, **escolher o formato pelo tipo de tarefa**:

- **Múltipla escolha** — a pergunta pede **um número/único resultado** (ex.: "quantos", "qual o valor").
- **Seleção múltipla** ("marque todas as que se aplicam") — a pergunta pede **uma lista / todos os valores possíveis**.
- **Verdadeiro ou Falso** — questão **discursiva**, de "explique por quê", ou com **vários itens de ideias distintas**; o V ou F separa cada ideia numa afirmação.

### Regra anti-repetição de motor
**Se o motor cognitivo já apareceu numa questão anterior da mesma prova/série, trocar de formato** para não repetir (ex.: os dados e a pirâmide tiveram itens em MC e em V/F alternadamente). Antes de transformar, dizer em uma linha qual é o motor e se ele é novo ou já usado. *(Registro vivo: as três de soma ponderada a partir de gráfico — Q5, Q11-doações e parte de Q10 — compartilham motor; e os dois de comparação de cenários monetários — Q6-Marina e Q6-feira — também; se forem juntas ao banco, alternar formato entre elas.)*

### Distratores (múltipla escolha) e afirmações falsas (V/F)
- Cada distrator deve ser o **resultado de um erro nomeável** (fencepost "+1"; somar a linha em vez da diagonal; ignorar a restrição; calcular o máximo em vez do mínimo; copiar valor do exemplo; confundir "faces opostas" com "faces em contato"; parar na primeira operação; parar no valor intermediário; esquecer o ÷ dentro do parêntese; somar as frequências em vez de ponderar; somar algarismos em vez de multiplicar; contar parcelas em vez de sinais; **na máquina, inverter as operações sem inverter a ordem, usar o inverso errado de uma etapa, rodar para frente, ou parar cedo**). Nada de número aleatório.
- **No comentário, explicar de onde vem cada distrator/erro.** (Já é rotina no §4.)
- Nas afirmações **falsas** do V/F, embutir o erro mais provável e **nomear sua origem** entre parênteses.
- Misturar afirmações **computacionais** com **estruturais** (paridade, unicidade, limites).
- Manter (ou aumentar) o nível de dificuldade e cobrir **todo** o raciocínio que a questão original exigia.
- Conhecer os três padrões de distrator do §4 (**espaçados de N**, **menu completo de uma categoria** e **erro de procedimento**) ajuda a montar opções coerentes.

### Quando a questão for adaptada da OBMEP
Manter a **abertura do enunciado pedida** (definições, regras, exemplo) antes da figura/SVG.

---

## 7. Versão Verdadeiro ou Falso — regras

- Em geral **seis afirmações** (ajustar se a questão pedir).
- Cobrir **todos os raciocínios** da questão original — mapear cada item/parte para uma ou mais afirmações.
- Dificuldade alta: nenhuma afirmação óbvia ou resolvível "no olho".
- Entregar o **gabarito** no formato "V – F – V – V – F – V".
- Oferecer, ao final, versão **gêmea** ou **SVG** de apoio.

---

## 8. Comentário de Verdadeiro ou Falso (modelo fixo) — presente

- Abrir com um **setup compartilhado** quando útil ("Antes de julgar as afirmações, montamos…").
- Comentar uma a uma: "A primeira afirmação é verdadeira/falsa." seguida do raciocínio no mesmo estilo do §5 (presente, conta em linha própria, conferência).
- Em cada falsa, **nomear de onde vem o erro** que ela induz, e indicar entre parênteses qual item original a afirmação cobre.
- Fechar com "Gabarito final: V, F, V, V, F, V."

---

## 9. SVG renderizado e prompts de Flow (sob demanda)

Há dois usos de SVG, distintos. A **biblioteca de helpers reutilizável** (paleta + funções de desenho + render) está no **Apêndice B**: usá-la garante consistência e já embute a regra de desenhar setas/vistos como formas.

### 9a. SVG renderizado como entregável (diagramas didáticos)
Figura limpa para o material (pirâmides, quadrados mágicos, balança, fluxos, contas armadas, linhas do tempo, tabelas de casos, máquinas de operações). Convenções da casa:

- Estilo flat 2D vector, fundo branco, texto em **PT-BR com acentos**.
- **Paleta nomeada.** A **fonte canônica das cores é a Bíblia de Ilustração**; o protocolo apenas referencia. Valores de trabalho usados no chat (confirmar os hex exatos contra a Bíblia):
  - NAVY `#14365A`, ORANGE `#E0701B`, BLUE `#2F80C4`, YELLOW `#F6C445`, SAGE/GREEN `#3E9B6B`, PURPLE `#7A5CC0`;
  - preenchimentos claros: azul `#E6F0FA`, laranja `#FCEBD9`, amarelo `#FCEFC2`, verde `#E2F2EA`, roxo `#EEE8FA`, neutro `#EEF3F8` / borda `#CBD5DF`; vermelho de erro `#C0392B`.
- Fontes: `Poppins`/`Inter` (texto) e `DejaVu Sans Mono` (números) — trocam sozinhas pela fonte da casa no pipeline. (No render local com cairosvg, usar `DejaVu Sans` para garantir acentos.)
- **Uma cor por elemento**, consistente entre figuras da mesma questão (ex.: cada canto/peso com sua cor, mantida em todos os SVGs daquele item).
- **Indicar sempre onde inserir** cada SVG no comentário ou capítulo (etapa correspondente, em geral na conferência ou ao lado do passo que ilustra), com o marcador `[Inserir aqui o SVG \`nome.svg\`.]`.

**Mapa semântico de cor (fixar o significado, não só os hex):**
- **verde** `#3E9B6B` / `#E2F2EA` = resposta / caso válido / vencedor;
- **amarelo** `#F6C445` / `#FCEFC2` = destaque do resultado final;
- **laranja** `#E0701B` / `#FCEBD9` = termo que muda, vai-um, parte que se descobre (inclui as **manchas recuperadas** numa conta armada);
- **vermelho** `#C0392B` = erro, armadilha, caso inválido (uso legítimo em SVG de explicação);
- **azul** `#2F80C4` / `#E6F0FA` e **cinza** `#EEF3F8` = categorias neutras.

**Padrão "estrutura + cálculo" (default de dois SVGs):** um SVG da **estrutura/figura** (gráfico, balança, linha do tempo, conta armada, tabela de casos, planta da máquina sem resultado) e um SVG da **conta/conclusão** com o resultado em destaque. Convergiu como padrão em quase toda questão da leva.

**Convenção figura de enunciado × figura de comentário *(v5.3)*.** Quando uma questão/exemplo entra na trilha ou no blog, gerar **duas versões** da figura:
- **Enunciado** (`nome_enunciado.svg`): só o problema. A casa/alvo a descobrir aparece como **"?" em laranja**; **nenhum** valor de resposta, **nenhuma** dica (não destacar a faixa/coluna "certa", não pré-marcar o caminho). Mostrar apenas o que o enunciado realmente dá.
- **Comentário** (`nome.svg`): a versão resolvida, com cores semânticas e a conferência.
Regra de honestidade da figura de enunciado: **não exibir intermediários que não são únicos** — se só o alvo é determinado (ex.: na cruz, só o centro), as demais casas ficam em branco, nunca preenchidas com um arranjo possível.

**Armadilhas técnicas do cairosvg (renderizar com cuidado):**
- **Acentos são OK.** `é ê ã ç õ á ú` renderizam bem nas fontes do pipeline — usar acentuação completa desde o início.
- **Glifos ausentes**: setas e check viram quadradinho — `→`, `←`, `↔`, `✓`, `✗`. **Solução primária *(v5)*: desenhar a seta/visto/X como forma vetorial** (`polyline`/`polygon`/`line`), via os helpers `arrow()`, `check()`, `xmark()` do Apêndice B. Solução plano B: trocar por ":", "logo", "vira", destaque de cor ou "•". Os sinais `× ÷ − > <` renderizam bem (escapar `&gt;` e `&lt;` no XML).
- **Não usar `tspan` coloridos em sequência** — saem sobrepostos/embaralhados.
- **Token posicionado é o padrão para equação multicolor:** um `<text>` por token, com `x` próprio e `text-anchor="middle"`, em vez de `tspan`. Funciona perfeito (decodificação de criptografia, parcelas coloridas por sinal, sinais de adição destacados um a um como na Q18).
- **Conferir o render em PNG antes de entregar** (gerar PNG e revisar) — não confiar no código às cegas.
- Para contas armadas: alinhar vírgula sob vírgula (ou casa sob casa), resultado em destaque.

**Checklist anti-sobreposição (o defeito nº 1 da sessão):**
- Caixa de resultado sempre **afastada** do texto à direita (deixar folga horizontal; não sobrepor a fórmula).
- **Rótulo de caixa-resultado curto:** "algarismo das unidades = 8" estourou a caixa na Q9; resolvido encurtando para "unidades = 8" e garantindo folga horizontal. Encurtar o rótulo antes de espremer a fonte.
- **Legenda de seta curta:** legendas longas sobre setas curtas encavalam nos chips vizinhos (visto nos SVGs de máquina); encurtar a legenda ou alongar o segmento.
- Conferir a **largura do viewBox** contra o rótulo mais à direita (eixo "% álcool" foi cortado por viewBox estreito).
- **Rótulo longo** ganha linha própria, ou os ícones/colunas vão para **depois** do texto, não por baixo.
- Encurtar rótulos de quadros ("inteiro:" em vez de "queijo inteiro:") quando o valor fica colado.
- Dar **folga vertical** à legenda de rodapé para não ser cortada pela borda do viewBox.
- Fluxo obrigatório: **render → revisar PNG → corrigir → re-render** antes de entregar.

**Conta armada de divisão — padrão em escada (fixado na v4):**
- Os **restos parciais recuam uma casa à direita** a cada zero que desce: o resto entra sob as unidades do número de cima, e o zero baixado ocupa a casa seguinte. Alinhar pela **borda esquerda crescente** (cada linha começa uma casa adiante da anterior). Exemplo validado (Q3, 25 ÷ 8 = 3,125): 25 no topo; depois 10, 20, 40 e 0, cada um deslocado uma casa à direita do anterior.
- A **barra da chave é curta** — só no topo, ao lado do divisor —, **nunca atravessando a escada** de restos. O traço horizontal fica sob o divisor, sobre o quociente.
- Divisor e quociente à direita, bem separados da escada; as **manchas recuperadas** entram em laranja (mapa de cor).
- Anotações de passo ("25 ÷ 8 = 3, sobra 1", …) alinhadas a cada linha, à direita, longe da conta.
- Modelo reutilizável salvo para as próximas divisões manchadas da trilha.

### 9b. SVG como plano de referência para o Flow
Quando o destino é a imagem "bonita" gerada pela criança, a entrega principal é o **prompt de Flow**; o SVG é o plano B (anexado no Flow como referência de layout). No prompt, embutir os travamentos anti-erro:
- **Travar o texto exato** a renderizar (anti-Erro 027).
- **Bloquear infiltração de inglês** (Erro 020) — todo texto em PT-BR.
- Proibir marcas/anotações/números extras inventados.
- Exigir vírgula decimal (nunca ponto).

**Dois estilos de Flow, não confundir** *(consolidado na v5)*:
- **Cena com personagens → estilo oficial 3D Pixar/Disney cinematográfico:** fundo branco puro, nuvens recortadas matte-white, tufos de grama brancos, luz difusa suave, elenco recorrente de estudantes. **Regra de filtro obrigatória:** nunca "child/kid" → "young animated character", sem idade explícita, traços simplificados. Anexar a imagem de referência da casa.
- **Diagrama matemático → estilo editorial** (não Pixar): flat vector com gradientes e sombras sutis, mais elaborado. É o mesmo registro dos SVGs da casa, só que "renderizado bonito".
- **Em ambos:** nenhum texto/número confiável fica na arte do Flow (Veo/Gemini erram texto). Os números vivem nos SVGs; oferecer sobreposição de símbolos limpos no CapCut. Separar o conteúdo em faixas/blocos no prompt impede que setas cubram texto.

---

## 10. Convenções editoriais (aplicar automaticamente)

- **Comentário em presente** (ver §5); **contas em linha própria, sem centralizar**; **sem ponto e vírgula**; **sem perguntas retóricas**.
- Vírgula decimal; "R$" com espaço; unidades SI em romano.
- **Separador de milhar em três contextos** *(esclarecido na v3):*
  - na **transcrição**, preservar exatamente como no print;
  - em **prosa e SVGs de resultado**, espaço como separador de milhar (1 800, 11 097, 6 100);
  - na **conta armada e em grades alinhadas por casa**, manter **sólido** (sem separador), porque o alinhamento posicional manda mais que o separador.
  - Exceção geral mantida: quando o número é uma **cadeia de algarismos** — visor, prefixo, conta de calculadora, o próprio 123456789 da Q18 — manter sólido (ex.: 2601, 780).
- Variar verbos de abertura de exemplo (Considere, Pegue como exemplo, Tomemos, Imaginemos, Veja o caso de, Tome o caso de); **nunca repetir "Considere" em sequência**.
- Títulos de seção secos, sem subtítulo após dois-pontos.
- Sem personificação de profissões; sem marcadores de escrita de IA.
- **Sem travessão (—)** antes de aposto nem como pausa de efeito *(reforçado na v5.5)*. Aposto curto entre vírgulas ou parênteses, aposto longo vira período novo. O **hífen de palavra** (bem-te-vi, vai-um) é livre, porque a proibição é só do travessão longo.
- **Sem ponto e vírgula** no texto de aluno *(v5.5)*. Duas orações viram duas frases com ponto, ou se ligam por conjunção (e, mas, porque, então).
- **Dois-pontos só para trabalho honesto** *(v5.5)*: introduzir uma fala, abrir uma lista de verdade, ou ligar duas partes de uma frase comum. Nunca para criar pausa dramática antes de uma palavra ("uma ideia volta sempre: X").
- **Fôlego de frase livre** *(v5.5)*: o período pode ser longo, desde que se leia de uma vez e não dependa de travessão, ponto e vírgula ou dois-pontos decorativo para se sustentar. Não há regra de "uma ideia por frase". O crivo é o teste do "ninguém fala assim" (§14): se a frase, longa ou curta, não se sustenta lida em voz alta, está mal construída.
- Tudo em PT-BR; prompts de imagem em inglês para Gemini/Flow.

---

## 11. Como me acionar (gatilhos curtos)

Ao enviar o print, indicar o que quer. Exemplos:

- "transcreva, classifique, dê o gaba e comente para uma criança de 12 anos"
- "classifique" / "classificação mais específica?" / "pode ser classificado em álgebra?" / "pode ser classificado em lógica?"
- "confira contra o Assunto oficial da plataforma"
- "transforme essa questão em MC, seleção múltipla ou V ou F (você escolhe)"
- "mantenha o nível (ou aumente) e o raciocínio necessário"
- "se o raciocínio já apareceu antes, troque de formato"
- "comente do modo mais didático possível" / "deixe a explicação ainda mais didática, menos sucinta" (aciona o **registro Expandido**, §5)
- "crie os SVGs necessários à explicação e diga onde inserir" / "uma cor por elemento"
- "mantenha a parte inicial do enunciado (print da GF)"
- **"crie uma questão desafiadora sobre esse tema, em MC"** (aciona o §13)
- **"melhore/aprofunde este capítulo de teoria"** / "tire os vícios de IA" / "explique melhor a teoria, não só o exemplo" (aciona o §14)
- **"ilustre esta máquina/figura no Flow"** (estilo oficial 3D Pixar para cena; editorial para diagrama — §9b)

Se nada for dito, o padrão é: transcrição + classificação (com campo "Não é X") + gabarito verificado (com origem dos distratores) + comentário didático no modelo (§5).

---

## 12. Registro de motores já vistos (memória da trilha)

Lista viva para a regra anti-repetição (§6) e para reconhecer nós. Atualizar a cada leva.

**Leva 1**
- **Soma ponderada a partir de gráfico** (Tratamento da Informação) — Q5 (rifa), Q11-doações. Motor repetido; alternar formato.
- **Soma ponderada + achar a parte que falta** — Q10 (pontos do time: empates = 20 − 8 − 8, depois 3/1/0).
- **Expressão numérica com controle de sinais** — Q1 (2005 − 205 + 25 − 2).
- **Expressão numérica: papel do zero + comparar para o maior** — Q2 (qual expressão dá o maior).
- **Expressão numérica: parênteses e busca do máximo por enumeração** — Q4-parênteses (onde pôr um par de parênteses).
- **Adição com reagrupamento + arredondamento compensado** — Q1-noves (99 + 999 + 9999).
- **Criptografia por substituição de algarismos e operadores** — Q9-trocas (trocas do Carlos) + expressão com ordem das operações.
- **Criptografia em conta armada por colunas e transportes** — Q14 (OBM + EP = 1052); soma das letras pelos totais de coluna.
- **Pré-algébrico, uma incógnita por operação inversa** — Q3-fração (número apagado na fração).
- **Pré-algébrico, balança por cancelamento** — Q2-queijo (3 pedaços = 1 pedaço + 0,8 kg).
- **Raciocínio temporal em linha do tempo** — Q1-pintores (391 antes, 451 antes; diferença = 60).
- **Raciocínio lógico, distribuições com condições** — Q19 (Ari/Bruna/Carlos, água ou suco).
- **Tratamento da informação + porcentagem complementar** — Q19-álcool (álcool > gasolina ⟺ álcool > 50%).

**Leva 2** *(adicionada na v4)*
- **Sistema monetário, achar a parte que falta** — Q1-moedas (4,30 − 10 moedas de 25 → 18 moedas de 10).
- **Soma ponderada por cor + contagem de figura em código** — Q4-ladrilhos (grade 7×9, 12 brancos, 51 pretos; custo = 2×12 + 3×51 = 177).
- **Comparação de dois cenários, troco** — Q6-Marina (entregou 60, contado como 20 → prejuízo 40).
- **Comparação de dois cenários, receita + fatoração da diferença** — Q6-feira (prejuízo = Δpreço × Δquantidade = 0,10 × 20 = 2).
- **Saldo / acerto de contas com devolução proporcional ao adiantamento** — Q17-bombons (preço 0,30; devolver 0,60 a Ana e 1,20 a Beatriz).
- **Inversão de algarismos + idade ↔ ano** — Q20 (1949 ↔ 1994; idade 11; checar aniversário já passado).
- **Multiplicação cifrada por restrição de tamanho do resultado** — Q11-multiplicação (□2□ × □ = △6△ → 323 × 3 = 969; □×△ = 27; solução única).
- **Formação de números por valor posicional (colar algarismos) + sinais = parcelas − 1** — Q18 (123456789 com sinais somando 54 → colar 1 e 2; 7 sinais).
- **Paridade + limite de 9 por casa** — Q9 (10 algarismos somando 89 → nove 9 e um 8; unidade par = 8).
- **Divisão armada manchada (escada) + duas manchas comparadas** — Q3-Lucinda (25 ÷ 8 = 3,125; manchas 8 e 5; menor = 5).

**Conteúdo autoral e capítulos** *(adicionada na v5)*
- **Máquina de operações (ida, arredondamento para cima, trocar a entrada, marcha ré, teste de ida e volta)** — capítulo de teoria + SVGs `maq_regra`, `maq_simples`, `maq_arredonda`, `maq_trocar`, `maq_re`, `maq_idavolta`, `maq_ordem_re`, `maq_teste`.
- **Expressões numéricas (pódio, leitura × hierarquia, zero, sinal de menos, máx/mín)** — capítulo + SVGs `ex_podio`, `ex_ordem`, `ex_zero`, `ex_menos`, `ex_estrategia`.
- **Valor posicional (peso de cada casa)** — capítulo revisado.
- **Questão autoral, máquina ao contrário (passarinhos)** — MC; entrada 13; distratores por erro de procedimento.
- **Questão autoral, máquina ao contrário com gasto fixo + proporcional (Camila no shopping)** — MC; início 300; distratores por erro de procedimento.

**Leva 3** *(adicionada na v5.3 — capítulos e questões de relações/grades/grupos)*
- **Sistema escondido fechado por inteiros positivos** — Q10 curral (pessoas, vacas, banquinhos; 2v + 3b = 12 com b par → 1 caso). Nó da grade: Álgebra › Sistemas de Equações › Restrições Inteiras.
- **Grade tipo Sudoku com condição nas diagonais + paridade** — Q20 tabuleiro 3×3 (5/8/x; soma par decide centro 8). Nó: Raciocínio Lógico › Restrição de Quantidade em Linhas e Colunas.
- **Preenchimento de tabuleiro por região (tê) + não-consecutivos** — Q16 (regiões em tê com {1,3,5,7}/{2,4,6,8}; casas cinza somam 20). Mesmo nó de Matrizes/Tabuleiros.
- **Leitura de gráfico contra limiar + porcentagem complementar** — Q19 álcool (> 50%; 3 amostras); Q4 consultas (> 1200; 8 meses, atalho 12 − 4). Tratamento da Informação.
- **Escalar e combinar grupos** — valor unitário; combinar grupos (somar A+B = grupo novo, subtrair para isolar item); pista redundante (compra múltipla de outra). Capítulo + SVGs `cap_escalar`, `cap_combos`, `cap_combos_soma`, `cap_repete`, `cap_repete_tabela`, `cap_cores`.
- **Somar pistas / equilibrar / conservar** — somar pistas par a par (caixas A,B,C); substituição de equivalentes (melancia = 6 maçãs); grandeza conservada; restrição de inteiros/paridade (pacotes de 9 e 2). Capítulo + SVGs `maq_balancas_somas`, `maq_balanca_substituicao`.
- **Somas em linhas e colunas** — casa com uma só vazia; truque do total da grade; elemento compartilhado (cruz, centro = soma dos braços − total). Capítulo + SVGs `q_grade_uma_incognita`, `q_truque_do_total`, `q_sobreposicao_cruz` (com pares `_enunciado`).

---

## 13. Criação de questão original *(novo na v5)*

Quando o pedido for **criar uma questão** sobre um tema da trilha (com tema/cenário sugerido ou livre), seguir este fluxo. Vale a mesma régua de qualidade das questões recebidas, mais a verificação reforçada, porque **não há gabarito oficial para conferir**.

**Fluxo:**
1. **Escolher o motor cognitivo** e dizer qual é, e se é novo ou já usado na trilha (§6, §12). Casar o motor com o tema pedido (ex.: passarinhos pulando galhos → máquina ao contrário; gastos no shopping → máquina com etapas fixas e proporcionais).
2. **Projetar a estrutura para inteiros limpos** em todas as etapas: cada valor intermediário deve ser inteiro, positivo e coerente com a história (passarinhos não viram fração; dinheiro não fica negativo). Escolher os números resolvendo de trás para frente, a partir do valor final desejado.
3. **Escolher o formato pelo §6** (MC para um valor único; seleção múltipla para lista; V ou F para várias ideias).
4. **Desenhar os distratores como erros nomeáveis** (§4, §6). Em problema de máquina/processo, usar a família **erro de procedimento**: rodar para frente, inverter operação sem inverter a ordem, inverso errado de uma etapa, parar cedo. Todos os distratores **inteiros e do mesmo tipo do gabarito**. Um distrator não inteiro só entra se o **próprio erro** o produzir **e** isso for didático (ex.: resultado quebrado denunciando ordem trocada).
5. **Verificar por código** antes de fechar: a resposta correta, a unicidade da solução (enunciado bem-posto) e a aritmética de **cada** distrator (confirmar que cada um cai no número que o erro produz). **Substituir os valores achados de volta em *todas* as pistas do enunciado**, não só na conta final — foi a falta disso que deixaria passar um exemplo impossível (tipo "COCO = 22" quando CO = 15 obriga COCO = 30). **Teste de unicidade explícito:** confirmar que a grandeza pedida é unicamente determinada; se houver intermediários **não** únicos (ex.: as casas dos braços de uma cruz, quando só o centro é fixo), **não exibi-los** como se fossem a resposta, nem no enunciado nem na figura.
6. **Escrever o enunciado limpo** (voz da casa) e o **comentário no modelo §5**, com a origem de cada alternativa, o passo "responder o que foi perguntado", "A lição que vale guardar" e o fecho do gabarito. Para questão de máquina, o comentário traz a marcha ré e o teste de ida e volta.
7. **Classificar como uma questão recebida** (§3), com "Não é X" e o **campo de trilha** (§3) preenchido.
8. **Ilustrar** (§9): SVG de apoio no padrão estrutura + cálculo (ex.: a planta da máquina sem resultado para o enunciado; a marcha ré para o gabarito) e/ou prompt de Flow no estilo certo.
9. **Persistir a verificação:** guardar o código e a saída da verificação junto do entregável, porque o gabarito é nosso e precisa de auditoria.

**Travas:** enunciado com **solução única** (garantida por determinismo da máquina ou por enumeração); dificuldade calibrada para 6º/7º; oferecer, ao final, uma **questão-gêmea** (mesmo motor, números diferentes) para o banco.

---

## 14. Redação e revisão de capítulo de teoria *(novo na v5)*

Quando o pedido for **escrever ou revisar um capítulo expositivo** da trilha.

**Crivo geral — o teste do "ninguém fala assim" *(novo na v5.5)*.** Acima de qualquer regra de voz: leia a frase em voz alta. Se ninguém falaria assim numa conversa, reescreva. Esse teste pega de uma vez o jargão, o suspense e a frase-de-efeito, e vale tanto contra o pomposo ("o fio que atravessa o capítulo") quanto contra o falso-simples com pausa dramática ("uma ideia volta sempre: a distância"). Ele governa por cima dos dois registros abaixo e de todo o resto do §14.

**Voz da casa — dois registros *(reescrito na v5.4)*.** A voz não é uniformemente austera. Há dois registros, e o capítulo **alterna** entre eles conforme a função do trecho:

- **Registro expositivo (teoria).** Presente, declarativo, prosa seca mas **não robótica**. Primeira pessoa do plural ("usamos", "fazemos", "perceberemos") e construções impessoais; **sem "você"**. É o registro das definições e das propriedades (seções como "A diferença é uma distância", "Quando a diferença não muda").
- **Registro guiado (passo a passo).** Quando conduzimos o aluno pela resolução de um exemplo mais difícil, ou o convidamos a visualizar uma cena concreta, **é permitido falar com ele**: "você", imperativo ("imagine que você tenha diante de si…", "olhe para a torre azul", "pense na fila") e marcadores de mão dada ("o segredo é…", "juntando as pistas…", "ligando todas as comparações"). É o registro do exemplo das torres. Quente sem virar fofo: nada de auto-elogio nem de hype (ver checklist).

Os dois registros convivem no mesmo capítulo. A teoria explica **de fora**; o exemplo guiado caminha **ao lado** do aluno. Na dúvida, definição e propriedade vão no expositivo; resolução conduzida de exemplo difícil pode ir no guiado.

- **Definições em negrito-itálico na primeira aparição** (ex.: ***diferença***, ***diferença constante***, ***comparações encadeadas***).

**Checklist anti-vício de IA (o que continua proibido) *(revisto na v5.4)*.** O alvo é o **exagero e a falsidade afetiva**, não a proximidade com o aluno:
- exclamação inflada e auto-elogio ("Viu que genial?", "corretíssima", "boa caçada aos números!");
- hype e adjetivação vazia ("devastador", "absolutamente", "genial", "incrível");
- perguntas retóricas vazias de efeito ("Você já parou para pensar…?", "Percebeu que…", "Pois é") — ver, logo abaixo, a distinção entre pergunta-âncora e gancho;
- fechamento motivacional postiço;
- dois-pontos de suspense (pausa dramática antes de uma palavra, "uma ideia volta sempre: X"); título com dois-pontos + subtítulo;
- travessão (—) antes de aposto ou como pausa de efeito; ponto e vírgula; personificação de profissões/objetos;
- palavras abstratas ou pomposas demais para a faixa: "invariância", "fragmentada", "segmentos" (quando "pedaços" serve), "desdobra-se", "atravessa o capítulo", e metáforas literárias densas que não ajudam a criança a ver a conta. Regra de substituição: havendo a palavra concreta do dia a dia, ela ganha;
- emojis e callouts decorativos (💡 ⚠️ ❌) → virar caixa limpa "**Guarde.**" / "**Regra de ouro.**".

**O que deixou de ser proibido *(v5.4)*.** "Imagine" **não** é vício quando abre um convite real a visualizar uma cena concreta e manipulável ("Imagine que você tenha diante de si quatro torres"), em vez de um gancho vazio. "você" é permitido no **registro guiado** (§ acima). Um fecho calmo de exemplo ("Pronto." / "Pronto!") é aceitável como marca de encerramento, **desde que não venha colado a auto-elogio** ("Pronto, viu como é fácil?" continua proibido).

**Pergunta-âncora × gancho retórico *(novo na v5.5)*.** Nem toda pergunta é vício. Fica proibida a pergunta vazia de efeito ("Você já parou para pensar…?"), mas é permitido e recomendado **enunciar diretamente as perguntas que o capítulo vai responder** e respondê-las no próprio texto ("Onde um número fica? Qual é a distância entre dois números?"). O teste é simples: a pergunta tem resposta no próprio texto e organiza o conteúdo? Então é âncora, não gancho. (Vale para a abertura do capítulo, item 1 da arquitetura abaixo; em comentário de questão isolada, §5, segue a moldura declarativa.)

**Princípio pedagógico (o que mais apareceu na prática):** **ensinar a teoria, não só rodar o exemplo.** Para cada conceito, deixar claros o **objetivo**, a **dificuldade real** e o **porquê**, em torno do exemplo. Ordem útil: *o que é → onde está a dificuldade → exemplo → para que serve*. (Foi o que transformou as seções "máquina simples", "marcha ré" e "arredondamento".)

**Disposição de ideias / arquitetura do capítulo *(novo na v5.4)*.** Tão importante quanto a frase é o **encadeamento das ideias**. Padrão validado em "Diferença e comparações":

1. **Abrir dizendo o assunto numa frase comum.** A primeira seção enuncia a **pergunta** (ou as perguntas) que o capítulo responde e nomeia o **conceito-espinha**, do jeito que uma pessoa diria em voz alta. Proibido tanto o pomposo ("o fio que atravessa o capítulo") quanto o falso-simples com pausa dramática ("uma ideia volta sempre: a distância"). A frase-espinha não anuncia que é espinha, ela só diz a coisa ("Este capítulo é todo sobre distância." ou "As duas perguntas têm a ver com a mesma coisa, a distância."). O capítulo inteiro é a entrega dessa promessa.
2. **Conceito-espinha reaparecendo em cada virada.** A mesma ideia volta em cada seção, e cada seção é uma face dela (a diferença é distância, depois não muda, depois vira idade, depois não é dobro, depois encadeia, depois dá o valor). A progressão é a ideia ganhando faces novas, não uma lista de tópicos soltos. Ao escrever isso para o aluno, não usar "atravessa o capítulo" nem "se desdobra" (ver palavras abstratas/pomposas no checklist anti-vício).
3. **Costura explícita entre seções.** Cada seção se situa em relação à anterior **antes** de avançar ("Até aqui comparamos dois por vez, mas…", "Saber a ordem é um começo, mas queremos os valores…"). A transição carrega o argumento, não só amacia o corte. Mais forte que o "suavizar transições" do bloco Ritmo.
4. **Seção-guarda contra o erro provável.** Quando há uma confusão típica (diferença × dobro, parte × todo, intermediário × final), abrir uma seção curta que a **desarma de propósito**, mesmo sem conteúdo novo. ("A diferença não é o dobro.")
5. **Definição primeiro, exemplo depois; título como mini-tese *(invertido na v5.5)*.** Numa exposição didática, enunciar a ideia ou a definição e **então** trazer o exemplo concreto, que vem confirmar o que já foi dito (a reta numérica é definida e só depois aparece o "3 vem antes do 8"). O exemplo ilustra a regra, não prepara o terreno para ela. Casa com a ordem útil do Princípio pedagógico (o que é, onde está a dificuldade, exemplo, para que serve). Os títulos **afirmam a ideia** ("A diferença é uma distância"), não rotulam o tópico ("Conceito de diferença").

**Ritmo (anti-robótico):** variar comprimento e estrutura das frases (evitar série de declarativas no mesmo molde "O X está em Y e vale Z"); suavizar transições (trocar "Um cuidado fecha a ideia" por algo natural como "Falta um cuidado com o zero"); rotacionar a abertura dos exemplos (§10) sem repetir "Considere".

**Exemplos como problemas fechados *(v5.3; formatação detalhada na v5.4)*.** Todo exemplo trabalhado abre como **problema fechado**: contexto → pistas → **pergunta em negrito**, antes de qualquer conta. Sem isso o aluno acompanha a resolução sem saber aonde se quer chegar. Padrão usado em "Escalar e combinar grupos", "Somar pistas…", "Somas em linhas e colunas" e nos exemplos de "Diferença e comparações". A resolução vem depois e **fecha com a conferência** (substituir os valores nas pistas). Formatação validada nos prints:
- O enunciado fechado fica **delimitado por filetes pontilhados** acima e abaixo, em **itálico**, com a **pergunta em negrito** ao fim.
- A **conta-resultado da teoria vai em equação centralizada de bloco** (display): `20 − 14 = 6` centralizado. Isso é diferente do comentário de questão (§5), que mantém conta em linha própria **sem** centralizar.
- A resolução de exemplo difícil pode usar o **registro guiado** (§ Voz da casa) e **pistas discretas em lista** ("a torre azul é mais baixa que a vermelha (azul menor que vermelha)"), quando isso organiza melhor o raciocínio do que a prosa corrida.

**Verificação numérica do exemplo inventado *(v5.3)*.** Antes de publicar, **substituir os valores encontrados em todas as pistas** do exemplo (mesma trava do §13). Pegou um exemplo impossível na prática (COCO = 22 com CO = 15). Vale também o **teste de unicidade**: se a figura do exemplo só determina uma grandeza, não preencher as demais com um arranjo possível.

**Rotação de verbos por capítulo *(v5.3)*.** Mais forte que a regra geral do §10: rastrear os verbos de abertura já usados **no capítulo corrente** (Considere, Tomemos, Imaginemos, Veja o caso de, Pegue como exemplo, Tome o caso de) e **não repetir nenhum** dentro do mesmo capítulo.

**Estrutura de entrega:**
- Arquivo markdown, **títulos curtos e assertivos** (mini-tese, sem dois-pontos + subtítulo; em negrito-itálico, que o editor realça), com o marcador `[Inserir aqui o SVG \`nome.svg\`.]` em cada ponto de figura.
- **Diagramas matemáticos → SVG editorial** (§9a); **cenas → prompt de Flow no estilo oficial 3D Pixar** (§9b). Não trocar os dois.
- Apêndice "Ilustrações" no fim do arquivo, listando os SVGs e os prompts de Flow (em inglês).

---

## 15. Convenção de nomes de arquivo *(novo na v5)*

Tudo em `/mnt/user-data/outputs`.

- **Capítulo de teoria:** `Cap_<Tema>_revisado.md` (ou sem `_revisado` quando original). Ex.: `Maquina_de_operacoes_revisado.md`.
- **SVG de teoria:** `<prefixo-tema>_<slug>.svg`, prefixo curto e estável por tema. Ex.: `maq_simples.svg`, `ex_podio.svg`.
- **Questão (recebida ou autoral):** `Q_<Tema>_<formato-ou-slug>.md`. Ex.: `Q_passaros_maquina_adaptada.md`. SVGs da questão: `q_<tema>_<slug>.svg`.
- **Par enunciado × comentário *(v5.3)*:** quando a figura tem versão de problema e versão resolvida, a do enunciado leva o sufixo `_enunciado` (`q_<tema>_<slug>_enunciado.svg`) e a resolvida fica com o nome base (`q_<tema>_<slug>.svg`). Ver a convenção no §9a.
- **Prompt de Flow:** dentro do `.md` do capítulo ou questão, no apêndice "Ilustrações", em inglês.
- Sempre **apresentar os arquivos** com `present_files` ao final.

---

## 16. Definition of done (checklist único de entrega) *(novo na v5)*

Antes de entregar, conferir:

- [ ] **Transcrição fiel** (quando a questão foi recebida em print).
- [ ] **Classificação** com nó principal + descritores + **"Não é X"** + **campo de trilha** + **nó da grade (Apêndice D)** com caminho completo (ou subnó proposto).
- [ ] **Gabarito verificado de forma independente**; código de verificação quando combinatório/lógico/criptográfico/**autoral**; **verificação persistida** se autoral.
- [ ] **Distratores nomeados** (origem de cada um) no comentário.
- [ ] **"Responder o que foi perguntado"** conferido (todo × parte, final × intermediário).
- [ ] **Comentário no modelo §5** (presente, 1ª pessoa do plural, contas em linha própria, conferência, "A lição que vale guardar", fecho do gabarito).
- [ ] **SVGs** no padrão da casa: render conferido em PNG (render → revisar → corrigir → re-render), anti-sobreposição, **setas/vistos/X desenhados** como formas, acentos OK.
- [ ] **Exemplo inventado verificado** (§13/§14): valores substituídos em **todas** as pistas; unicidade conferida; intermediários não-únicos **não** expostos.
- [ ] **Par de figura** (quando aplicável): `_enunciado` sem solução nem dica + versão resolvida (§9a, §15); leitura de gráfico ancorada à grade (§2, §4).
- [ ] **Nomes de arquivo** na convenção (§15); arquivos em `outputs` e apresentados com `present_files`.
- [ ] **Estilo do texto de aluno (§14, §10) — v5.5:** passou no teste do "ninguém fala assim" (lido em voz alta); definição antes do exemplo; sem travessão (—) antes de aposto, sem ponto e vírgula, sem dois-pontos de suspense; abertura em frase comum (nem pomposa nem com pausa dramática); perguntas, quando houver, são âncoras respondidas no texto; sem as palavras abstratas/pomposas da lista do §14.
- [ ] Convenções editoriais (§10) aplicadas; **registro adequado por trecho** (expositivo impessoal nas definições/propriedades; guiado pode falar com o aluno na resolução); sem hype, auto-elogio nem retórica vazia (§14) em texto de aluno.

---

# Apêndice A — Árvore canônica (outline)

Ramo **Matemática › Aritmética** e ramos vizinhos. Nó principal + descritores; usar a redação oficial quando a metadata "Assunto" existir (§3).

- **Problemas com Algarismos e Criptografia Aritmética**
  - Conta armada cifrada por **soma** (análise de colunas e transportes / vai-um)
  - **Multiplicação cifrada** (restrição de tamanho do resultado + algarismo fixo)
  - Recuperar dígito / número sob regra de algarismos; manchas numa conta armada
- **Valor Posicional**
  - Montar **maior / menor** número (cuidado do zero que não abre)
  - Pedir um **algarismo específico** de um resultado
  - **Formação por colagem** de algarismos (soma cresce 9 × algarismo da esquerda)
  - Peso das casas; forma decomposta; troca/inversão de algarismos (desfaz trocando de novo)
- **Operações com Números Naturais**
  - Multiplicação e Divisão
  - Adição e Subtração
    - Adição com reagrupamento (vai-um) e **arredondamento compensado**
  - Sistema monetário e troco
  - Medidas de tempo (sexagesimal) e de capacidade
  - Problemas de Mínimo e Máximo
  - Aplicações no Cotidiano *(só como principal se a amplitude for real)*
  - **Expressão numérica com ordem das operações** (parênteses; × ÷ antes de + −; papel do zero; máximo por posição de parênteses)
- **Operações com Frações** (e subnós)
- **Grandezas e Medidas** (balança, conversões)
- **Problemas com Pontuação, Torneios e Máximos sob Restrições**
- **Problemas com Restrições de Soma (Linhas e Colunas / Matrizes)**
- **Tratamento da Informação › Leitura de gráficos** (soma ponderada por frequências; total = Σ valor × frequência)
- **Raciocínio Lógico** *(irmão de Aritmética)*
  - Distribuições com Condições
  - Problemas com Restrições e Dedução
  - *(técnica, não nó: análise/eliminação de casos em tabela)*
- **Álgebra pré-algébrica — uma ou mais incógnitas por tradução e teste** *(sempre etiquetar "pré-algébrico")*
  - Uma incógnita por **operação inversa** (inclui **máquina ao contrário**, marcha ré)
  - Uma incógnita por **cancelamento em balança**
  - Duas ou mais condições / incógnitas
- **Nós-padrão de estrutura (transversais)**
  - Contagem dupla / elemento compartilhado entre somas
  - Saldo / "entra e sai" com total constante
  - Otimização travada por viabilidade
  - Comparação de dois cenários (real × hipotético), resultado na diferença *(sub-caso: fatoração da diferença Δ × Δ)*
- **Descritores (micro-motores, secundários)**
  - Porcentagem complementar
  - Achar a parte que falta de um total
  - Raciocínio temporal em linha do tempo (idade ↔ ano de nascimento)
  - Paridade como motor de dedução
  - Limite de 9 por casa (máximo da soma de algarismos)
  - Inversão / troca de posição de algarismos
  - Soma ponderada (Σ valor × quantidade)
  - Processo iterativo / máquina (ida, marcha ré, iteração)

---

# Apêndice B — Biblioteca de helpers de SVG (cairosvg)

Snippet reutilizável. Mantém a paleta e desenha setas/vistos/X como formas (nunca glifos). Renderiza em PNG para revisão antes de entregar.

```python
import cairosvg, math
# Paleta de trabalho (confirmar hex na Bíblia de Ilustração)
NAVY="#14365A"; ORANGE="#E0701B"; BLUE="#2F80C4"; YELLOW="#F6C445"
GREEN="#3E9B6B"; RED="#C0392B"; PURPLE="#7A5CC0"; GREY="#8A97A6"
FILL_BLUE="#E6F0FA"; FILL_ORG="#FCEBD9"; FILL_YEL="#FCEFC2"
FILL_GREEN="#E2F2EA"; FILL_PURPLE="#EEE8FA"; FILL_GREY="#EEF3F8"; BORDER="#CBD5DF"
FONT="DejaVu Sans"; MONO="DejaVu Sans Mono"   # acentos OK; trocam pela fonte da casa no pipeline

def T(x,y,t,fs=16,col=NAVY,w="normal",anchor="start",fam=FONT):
    return (f'<text x="{x}" y="{y}" font-family="{fam}" font-size="{fs}" '
            f'font-weight="{w}" fill="{col}" text-anchor="{anchor}">{t}</text>')

def box(x,y,w,h,fill,stroke,rx=10,sw=2):
    return f'<rect x="{x}" y="{y}" width="{w}" height="{h}" rx="{rx}" fill="{fill}" stroke="{stroke}" stroke-width="{sw}"/>'

def chip(x,y,txt,fill,stroke,w=58,h=42,fs=21):
    return box(x,y,w,h,fill,stroke,9,2.5)+T(x+w/2,y+h/2+fs//3,txt,fs,NAVY,"bold","middle",MONO)

# equação multicolor: um token por <text> posicionado (nunca tspan em sequência)
def eq(x,y,spans,fs=20):
    s=f'<text x="{x}" y="{y}" font-family="{MONO}" font-size="{fs}">'
    for t,c,b in spans:
        s+=f'<tspan fill="{c}" font-weight="{"bold" if b else "normal"}">{t}</tspan>'
    return s+'</text>'   # use só se NÃO houver troca de cor adjacente problemática; senão, T() token a token

def arrow(x1,y1,x2,y2,color=ORANGE,label=None,sub=None):
    head=8; dx,dy=x2-x1,y2-y1; L=math.hypot(dx,dy) or 1; ux,uy=dx/L,dy/L
    ex,ey=x2-ux*head,y2-uy*head; px,py=-uy,ux
    s=(f'<line x1="{x1}" y1="{y1}" x2="{ex:.1f}" y2="{ey:.1f}" stroke="{color}" stroke-width="2.4"/>'
       f'<polygon points="{x2},{y2} {ex-px*5:.1f},{ey-py*5:.1f} {ex+px*5:.1f},{ey+py*5:.1f}" fill="{color}"/>')
    if label: s+=T((x1+x2)/2,y1-21,label,14,color,"bold","middle",MONO)
    if sub:   s+=T((x1+x2)/2,y1-7,sub,10,GREY,"normal","middle")
    return s

def check(cx,cy,s=11,color=GREEN):
    return (f'<polyline points="{cx-s},{cy} {cx-s/3:.1f},{cy+s*0.7:.1f} {cx+s},{cy-s*0.8:.1f}" '
            f'fill="none" stroke="{color}" stroke-width="3.2" stroke-linecap="round" stroke-linejoin="round"/>')

def xmark(cx,cy,s=10,color=RED):
    return (f'<line x1="{cx-s}" y1="{cy-s}" x2="{cx+s}" y2="{cy+s}" stroke="{color}" stroke-width="3" stroke-linecap="round"/>'
            f'<line x1="{cx-s}" y1="{cy+s}" x2="{cx+s}" y2="{cy-s}" stroke="{color}" stroke-width="3" stroke-linecap="round"/>')

def gear(cx,cy,r,col):
    s=''
    for i in range(8):
        a=i*math.pi/4
        s+=(f'<line x1="{cx+r*math.cos(a):.1f}" y1="{cy+r*math.sin(a):.1f}" '
            f'x2="{cx+(r+4)*math.cos(a):.1f}" y2="{cy+(r+4)*math.sin(a):.1f}" stroke="{col}" stroke-width="2"/>')
    return s+f'<circle cx="{cx}" cy="{cy}" r="{r}" fill="none" stroke="{col}" stroke-width="2"/><circle cx="{cx}" cy="{cy}" r="2.5" fill="{col}"/>'

def save(fn,W,H,parts):
    svg=(f'<svg viewBox="0 0 {W} {H}" xmlns="http://www.w3.org/2000/svg">'
         f'<rect width="{W}" height="{H}" fill="white"/>'+''.join(parts)+'</svg>')
    open(fn.replace('.png','.svg'),'w').write(svg)
    cairosvg.svg2png(bytestring=svg.encode(), write_to=fn, output_width=W*2)  # render p/ revisão
```

Regras de uso embutidas: setas/vistos/X via `arrow/check/xmark` (formas, não glifos); equação colorida por tokens posicionados; sempre `save` em PNG e **revisar** antes de entregar; folga horizontal/vertical conforme o checklist anti-sobreposição (§9a).

---

# Apêndice C — Changelog (histórico de novidades)

**Novidades da v5.5.** Régua de estilo do texto de aluno (§14, §10), sem tocar em classificação, verificação ou SVG: **teste do "ninguém fala assim"** como crivo geral, acima de todas as regras de voz (§14); **ordem definição-antes-do-exemplo**, invertendo o antigo "concreto primeiro" — o exemplo confirma a regra já enunciada (§14, item 5 da arquitetura); **frase de fôlego livre**, sem a noção de "uma ideia por frase" (§10, §14); proibição de **travessão (—)** antes de aposto e como pausa, de **ponto e vírgula** e de **dois-pontos de suspense**, com o hífen de palavra preservado (§10, §14); **abertura em frase comum**, proibindo o pomposo ("o fio que atravessa o capítulo") e o falso-simples com pausa dramática ("uma ideia volta sempre: X"), com a frase-espinha que não se anuncia (§14, itens 1 e 2 da arquitetura); distinção **pergunta-âncora × gancho retórico** (§14); lista de **palavras abstratas ou pomposas demais para a faixa** ("invariância", "fragmentada", "segmentos", "desdobra-se", "atravessa o capítulo" e metáforas literárias densas) com regra de substituição pela palavra concreta (§14); checkbox de estilo no §16. Origem: releitura do capítulo "Reta numérica e distâncias" e calibragem de voz para 10 anos. Nada removido; numeração preservada.

**Novidades da v5.3.** **Grade oficial de Matemática embutida** como Apêndice D, com regra de mapear ao nó real (caminho completo) e propor subnó nomeado quando faltar (§3, §16); **verificação numérica de exemplo inventado** — substituir os valores em todas as pistas (§13, §14, §16); **teste de unicidade** com proibição de expor intermediários não-únicos (§13, §9a); **contrato de exemplo fechado** com pergunta em negrito antes das contas (§14); **rotação de verbos por capítulo** (§14); **convenção de figura enunciado × comentário** e sufixo `_enunciado` (§9a, §15); **leitura de barras ancorada à linha de grade** com atenção a valores entre linhas (§2, §4); **Leva 3** no registro de motores e novos blocos de teoria validados (§3, §12). Origem das regras: leva de classificação e capítulos de relações/grades/grupos.

**Novidades da v5.** Cobertura de **criação de questão original** (§13) e **redação/revisão de teoria** (§14); **convenção de nomes** (§15) e **definition of done** (§16); **desenho de setas/vistos/X como formas** promovido a primário (§9); **campo de trilha** na classificação (§3); família de distratores **erro de procedimento** (§6, §4); descritor **processo iterativo / máquina** (§3); **início rápido** (§0); **árvore canônica** (Apêndice A) e **biblioteca de helpers** (Apêndice B); histórico de novidades movido para este apêndice; Bíblia de Ilustração fixada como fonte canônica de cor.

**Novidades da v4** (consolidadas a partir de uma leva de 10 questões: Q1 moedas, Q4 ladrilhos, Q6 Marina, Q6 feira, Q17 bombons, Q20 ano invertido, Q11 multiplicação cifrada, Q18 sinais de adição, Q9 número par/soma 89, Q3 divisão manchada):
- **novos descritores e motores validados**: paridade como motor de dedução; limite de 9 por casa (máximo da soma de algarismos) com déficit pequeno forçando um único algarismo menor; comparação de dois cenários (real × hipotético) com o resultado na diferença, incluindo o sub-caso fatoração da diferença (Δ × Δ); inversão/troca de posição de algarismos (desfazer trocando de novo); formação de números por valor posicional (colar algarismos cresce a soma em 9 × o algarismo da esquerda); cryptaritmética por multiplicação resolvida por restrição de tamanho do resultado;
- **verificação (§4)**: contagem de figura por análise de imagem em código elevada a procedimento explícito; passo fixo de sanidade do enunciado (conferir coerência interna antes de resolver);
- **SVG (§9)**: padrão fixo de conta armada de divisão em escada (restos recuam uma casa à direita; barra da chave curta) com modelo reutilizável; reforço anti-sobreposição com exemplo de caixa-resultado de rótulo curto;
- **comentário (§5)**: registro Expandido documentado (mais didático sob pedido, mantendo todas as travas);
- **operacional**: numeração repetida de prints tratada por desambiguação interna; novo padrão de distratores "menu completo de uma categoria"; registro de motores (§12) atualizado.

**Novidades da v3** (mantidas): dois nós novos validados na árvore — **Tratamento da Informação › Leitura de gráficos** e **Raciocínio Lógico**; nó pré-algébrico **generalizado para uma ou mais incógnitas**; novos descritores recorrentes (**porcentagem complementar**, **achar a parte que falta**); campo **"Não é X (e por quê)"** na classificação; uso da **metadata oficial "Assunto"** como verdade-base; **verificação por enumeração em código** para lógica/criptografia/contagem; engenharia reversa de distratores como **rotina** (não só na transformação); passo fixo **"responder o que foi perguntado"**; correção das regras de SVG (**acentos são OK**; só setas/check viram quadradinho), **token posicionado como padrão**, **checklist anti-sobreposição**, **mapa semântico de cor**, padrão **"estrutura + cálculo"**; regra dos **separadores de milhar em três contextos**.

**Novidades da v2** (mantidas): comentário em **presente**; seção própria para **transformar questões**; seção própria para **SVG renderizado**; **verificação reforçada** contra fonte oficial; nós de classificação validados.

---

# Apêndice D — Árvore de Classificação (Grade de Matemática)

Referência canônica do passo de classificação (§3). Toda questão é mapeada a um nó **existente** desta grade, com o **caminho completo**; quando nenhum nó servir, propor um **subnó nomeado** (com justificativa) em vez de forçar encaixe. Nós marcados `[+]` estavam recolhidos na captura e têm filhos ainda não transcritos (expandir numa próxima captura).

## Sistemas de Numeração `[+]`

## Operações Básicas
- Soma
- Subtração
- Multiplicação
- Divisão
- Potenciação
- Propriedades das operações
- Expressões numéricas
- Cálculo mental
- Relação inversa entre multiplicação e divisão
- Problemas envolvendo as operações básicas

## Conjuntos Numéricos `[+]`

## Aritmética
- Grandezas e Medidas `[+]`
- Operações com Números Naturais `[+]`
- Média Aritmética `[+]`
- Operações com Frações
  - Interpretação de Frações como Parte de um Conjunto
  - Comparação e Ordenação de Frações e Decimais
  - Frações Mistas e Impróprias
  - Adição e Subtração de Frações
  - Problemas com Frações Sucessivas
  - Multiplicação de Frações
  - Divisão de Frações
  - Simplificação de Frações
- Razão e Proporção `[+]`
- Porcentagem
  - Conceitos Introdutórios
  - Porcentagem Relativa
  - Porcentagem Sucessiva
  - Juros Simples
  - Aumento e Desconto
- Valor Posicional `[+]`
- Problemas com Algarismos e Criptografia Aritmética
- Crescimento por operações sucessivas (adição ou multiplicação)
- Conversão de Fração em Decimal
- Quadrados Perfeitos
- Problemas com Pontuação, Torneios e Máximos sob Restrições
- Problemas com Restrições de Soma (Linhas e Colunas / Matrizes)
- Problemas com Interseção de Conjuntos (Apenas um, os dois, nenhum)

## Análise Combinatória `[+]`

## Raciocínio Lógico
- Problemas com Princípios de Existência / Princípio da Casa dos Pombos
- Problemas com Visualização Espacial `[+]`
- Problemas com Restrições e Dedução
  - Decodificação de Idiomas / Sistemas Simbólicos
  - Restrições Temporais e Dias da Semana
  - Restrição de Quantidade em Linhas e Colunas (Matrizes / Tabuleiros)
  - Grupos e Posicionamento com Pistas
  - Distribuições com Condições
  - Quem é Quem / Identidades Ocultas
  - Dedução com Pistas Numéricas
  - Lógicas de Movimento ou Trajetos
- Sequências e Padrões Numéricos `[+]`
- Problemas com Relações Familiares
- Problemas de Otimização e Estratégia de Mínimos/Máximos
- Problemas com Regras de Transformação e Algoritmos
- Problemas com Verdadeiros e Mentirosos
- Problemas de Contagem com Condições Lógicas
- Problemas com Tabelas-Verdade / Lógica Proposicional
- Jogos de Estratégia e Raciocínio
- Problemas com Pontuação, Torneios e Máximos sob Restrições
- Problemas com Conjuntos e Diagramas de Venn

## Geometria `[+]`

## Álgebra
- Sistemas de Equações
  - Sistemas com 2 variáveis
  - Sistemas com 3 variáveis
  - Problemas com Restrições Inteiras (Otimização Discreta)
  - Sistemas com 4 ou mais variáveis
- Equações
  - Equações do 1º Grau
  - Equações do 2º Grau
  - Equações com Frações
- Expressões Algébricas
  - Problemas de Idade e Relações Algébricas
  - Operações com Expressões Algébricas
  - Fatoração de Expressões Algébricas
  - Problemas de Mínimos e Máximos
  - Problemas de Aplicação de Fórmulas e Proporções
- Inequações
- Funções `[+]`

## Probabilidade `[+]`

## Progressões `[+]`

## Geometria Analítica `[+]`

## Teoria dos Números `[+]`

## Estatística
- Probabilidade e Estatística Descritiva
  - Distribuição de Frequência
  - Construção de Gráficos
  - Organização de Dados
- Medidas de Tendência Central `[+]`
- Estatística Aplicada a Problemas do Cotidiano `[+]`
- Medidas de Dispersão `[+]`
- Interpretação de Gráficos e Tabelas
  - Gráficos combinados de barras e linhas
  - Leitura de Gráficos de Radar (Teia / Aranha)
  - Noções básicas de estatística
  - Leitura de Gráficos de Dispersão
  - Leitura de Tabelas de Frequência
  - Análise de Gráficos de Linha
  - Gráficos de Setores (Pizza)
  - Leitura de Gráficos de Barras

### Notas de uso
- A classificação informa o **caminho completo** do nó (ex.: `Álgebra › Sistemas de Equações › Problemas com Restrições Inteiras (Otimização Discreta)`), mais 2–3 nós-irmãos descartados com o porquê (campo "Não é X", §3).
- **Mapa árvore ↔ Trilha:** cada nó usado registra o Caminho/Bloco da Trilha correspondente (campo de trilha, §3), para manter classificação e currículo sincronizados.
- O **Apêndice A** (outline de motores cognitivos) descreve o *raciocínio*; este **Apêndice D** (grade da plataforma) descreve o *lugar de arquivamento*. As duas faces do mesmo item.
- Nós `[+]` precisam ser expandidos e transcritos numa próxima captura para completar o apêndice.
