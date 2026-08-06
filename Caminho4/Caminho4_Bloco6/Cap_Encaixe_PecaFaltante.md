# Achar a peça que encaixa

> Trilha Mirim 2 (4º e 5º anos) · Caminho 4 · Bloco 6 · Achar a peça que encaixa. Nó da grade: Geometria › Percepção Espacial no Plano › Encaixe e Complemento de Formas (subnó proposto, ver `Classificacao_Encaixe_PecaFaltante.md`).

Este capítulo é sobre achar a peça certa para um buraco, uma fechadura ou um quebra-cabeça. O que faz um pedaço ser exatamente o que falta numa figura? Por que uma chave só abre uma fechadura entre várias parecidas? Duas peças de quebra-cabeça, encaixadas do jeito errado, ainda revelam o desenho certo? E quando forma e cor precisam bater ao mesmo tempo, como contar o que se forma no final? Essas quatro perguntas organizam o capítulo.

***O pedaço que falta tem o contorno exatamente complementar ao buraco***

Quando um pedaço é arrancado de uma figura, o buraco que sobra tem um formato específico. O único pedaço que preenche esse buraco sem sobrar nem faltar nada é o que tem o contorno exatamente complementar: do mesmo tamanho, da mesma curva, virado do jeito certo para encaixar ali.

**Exemplo 1:** O contorno de uma ilha tem uma mordida em formato de meia-lua, arrancada de uma das pontas. Quatro pedaços soltos têm formatos parecidos: um deles é a meia-lua exata do buraco, um é uma meia-lua menor, um é uma meia-lua maior, e um é um pedaço triangular. **Qual desses quatro pedaços preenche o buraco sem sobrar nem faltar nada?**

[Inserir aqui a figura `enc_buraco_estrutura.svg`.]

Comparamos o buraco com cada pedaço candidato, olhando tamanho e formato ao mesmo tempo. O pedaço triangular tem cantos retos que o buraco, arredondado, não tem: não encaixa. A meia-lua menor deixaria uma sobra de buraco vazio ao redor dela: não encaixa. A meia-lua maior não cabe inteira no espaço, e sobraria pedaço para fora: também não encaixa.

Só a meia-lua do tamanho exato do buraco preenche tudo, sem sobrar buraco nem sobrar pedaço.

[Inserir aqui a figura `enc_buraco_resultado.svg`.]

**Guarde. Um pedaço só encaixa quando o formato E o tamanho batem exatamente com o buraco, ao mesmo tempo. Um formato parecido, mas maior ou menor, sempre deixa uma sobra, de um lado ou do outro.**

***Uma chave só abre a fechadura que é o molde exato dela***

O ***contorno*** de uma chave, com seus dentes de alturas diferentes, precisa bater exatamente com o contorno de dentro de uma fechadura para a chave girar. Se algum dente da chave for mais alto ou mais baixo do que o espaço correspondente na fechadura, a chave range ou não entra, e não abre.

**Exemplo 2:** Uma chave tem quatro dentes, com alturas $3$, $1$, $4$ e $2$, nessa ordem da esquerda para a direita. Três fechaduras têm ranhuras de profundidades diferentes: a fechadura A tem profundidades $3$, $1$, $4$, $2$; a fechadura B tem profundidades $2$, $1$, $4$, $3$; e a fechadura C tem profundidades $3$, $1$, $4$, $3$. **Qual fechadura essa chave consegue abrir?**

[Inserir aqui a figura `enc_chave_estrutura.svg`.]

Comparamos as alturas dos dentes da chave, na ordem, com as profundidades de cada fechadura, também na ordem, dente por dente. A fechadura A tem profundidades $3$, $1$, $4$, $2$, exatamente iguais às alturas da chave, uma a uma. A fechadura B troca a primeira e a última profundidade de lugar, e a fechadura C erra a última profundidade.

A chave abre só a fechadura A, porque é a única com as quatro profundidades batendo exatamente, na mesma ordem, com os quatro dentes da chave.

[Inserir aqui a figura `enc_chave_resultado.svg`.]

**Guarde. Não basta a fechadura ter os mesmos números de profundidade da chave: eles precisam estar na mesma ordem, dente por dente. Trocar dois dentes de lugar já é suficiente para a chave não abrir.**

***Peças de quebra-cabeça revelam um símbolo só quando encaixadas do jeito certo***

Duas peças de quebra-cabeça, cada uma com metade de um desenho, revelam o desenho inteiro quando encaixadas na posição certa, pela borda que combina com as duas. Se uma das peças for encaixada virada, mesmo que a borda pareça combinar, o desenho final muda.

**Exemplo 3:** Duas peças de quebra-cabeça, encaixadas pela borda certa, formam uma seta apontando para cima. A peça de baixo tem a haste da seta; a peça de cima tem a ponta. **Se a peça de cima for encaixada de ponta-cabeça (virada $180°$) antes de juntar com a peça de baixo, para onde a ponta da seta acaba apontando?**

[Inserir aqui a figura `enc_seta_estrutura.svg`.]

A peça de cima, de ponta-cabeça, tem a ponta da seta virada para baixo, porque girar $180°$ inverte completamente a direção que a ponta apontava antes.

Encaixando essa peça virada em cima da haste, a ponta fica voltada para dentro da haste, não para longe dela. O desenho final não forma mais uma seta reconhecível apontando para cima: a ponta aponta para baixo, direto para a haste.

[Inserir aqui a figura `enc_seta_resultado.svg`.]

**Guarde. Encaixar uma peça virada muda o resultado final, mesmo que a borda do encaixe pareça a mesma. Antes de montar, é preciso conferir a orientação da peça, não só se a borda combina.**

***Encaixar por forma e cor ao mesmo tempo exige casar as duas coisas***

Quando peças de um quebra-cabeça têm cor além de formato, encaixar direito exige casar as duas coisas ao mesmo tempo: a borda encaixa fisicamente, e as cores dos dois lados combinam do jeito pedido. Duas peças triangulares cinzas, encaixadas pela borda reta, formam um quadrado cinza inteiro. Contar quantos quadrados cinza saem de um monte de peças é dividir o total de peças cinza por $2$, já que cada quadrado usa exatamente duas peças triangulares.

**Exemplo 4:** Uma caixa tem $8$ peças triangulares cinzas, todas do mesmo tamanho, cada uma exatamente metade de um quadrado. Encaixando essas peças duas a duas, pela borda reta, cada par forma um quadrado cinza inteiro. **Quantos quadrados cinza inteiros dá para formar com essas $8$ peças?**

[Inserir aqui a figura `enc_cinza_estrutura.svg`.]

Cada quadrado cinza usa exatamente $2$ peças triangulares, encaixadas pela borda reta. Para saber quantos quadrados dá para formar, dividimos o total de peças por $2$.

$8 \div 2 = 4$

Dá para formar $4$ quadrados cinza inteiros. Conferimos multiplicando de volta: $4$ quadrados, $2$ peças cada, usam $4 \times 2 = 8$ peças, batendo com o total.

[Inserir aqui a figura `enc_cinza_resultado.svg`.]

**Guarde. Quando cada peça de encaixe representa metade de uma figura, contar quantas figuras inteiras dá para formar é dividir o total de peças pelo número de peças que cada figura usa, nunca contar as peças soltas como se já fossem figuras prontas.**

Este capítulo reuniu quatro formas de raciocinar sobre encaixe. Achar o pedaço com contorno exatamente complementar ao buraco. Comparar os dentes de uma chave, na ordem certa, com as profundidades de uma fechadura. Reconhecer que uma peça virada muda o desenho final de um quebra-cabeça. E contar quantas figuras inteiras se formam quando peças de encaixe precisam casar forma e cor ao mesmo tempo. Em todos os casos, encaixar exige conferir mais de uma coisa ao mesmo tempo, nunca só uma.

---

***Ilustrações***

| Arquivo | Onde entra | O que mostra |
|---|---|---|
| `enc_buraco_estrutura.svg` | Após o problema fechado da ilha | O contorno da ilha com o buraco em meia-lua, e os quatro pedaços candidatos, sem indicação de qual encaixa |
| `enc_buraco_resultado.svg` | Ao final da resolução do exemplo da ilha | O pedaço certo encaixado no buraco, e os outros três marcados como errados |
| `enc_chave_estrutura.svg` | Após o problema fechado da chave | A chave com os quatro dentes e as três fechaduras, sem indicação de qual abre |
| `enc_chave_resultado.svg` | Ao final da resolução do exemplo da chave | A fechadura A marcada como a certa, com as profundidades alinhadas às alturas da chave |
| `enc_seta_estrutura.svg` | Após o problema fechado da seta | As duas peças (haste e ponta), com a peça de cima mostrada de ponta-cabeça |
| `enc_seta_resultado.svg` | Ao final da resolução do exemplo da seta | O resultado da montagem errada, com a ponta apontando para baixo, para dentro da haste |
| `enc_cinza_estrutura.svg` | Após o problema fechado das peças cinzas | As $8$ peças triangulares cinzas soltas, sem nenhuma emparelhada |
| `enc_cinza_resultado.svg` | Ao final da resolução do exemplo das peças cinzas | As peças emparelhadas em $4$ quadrados cinza inteiros, com a conta $8 \div 2 = 4$ em destaque |
