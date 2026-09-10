# Achar a ordem

> Trilha Mirim 2 · Caminho 5 · Bloco 1 · Achar a ordem. Nó da grade: Raciocínio Lógico › Problemas com Restrições e Dedução › Grupos e Posicionamento com Pistas (ver `Classificacao_Ordenar_Comparar.md`).

Este capítulo é sobre montar uma ordem completa a partir de pedaços de informação soltos. Como descobrir o lugar exato de cada pessoa numa fila, só com pistas do tipo "na frente de" ou "atrás de"? Como juntar várias comparações, do tipo "mais alto que", numa única lista do maior para o menor? E o que fazer quando uma pista não diz onde alguém está, só onde ele **não** está? As três perguntas têm a mesma resposta de fundo: juntar todas as pistas até sobrar só um jeito de organizar tudo.

***Pistas de posição fecham um lugar exato na fila***

Numa fila, cada pessoa ocupa um lugar único, contado da frente para trás. Pistas como "está na frente de todos", "está logo atrás de alguém" ou "está no fim da fila" fixam um lugar exato. O caminho mais seguro é aplicar primeiro as pistas mais fortes, as que já dão uma posição fixa (primeiro lugar, último lugar), porque elas encolhem o problema e deixam menos gente para encaixar nas pistas que sobram.

**Exemplo 1:** Quatro amigos, Caio, Beto, Duda e Ana, esperam numa fila para tomar sorvete. Caio está na frente de todos. Beto está logo atrás de Caio. Duda não está no fim da fila. **Qual é a ordem completa da fila, da frente para trás?**

[Inserir aqui a figura `ord_fila_estrutura.svg`.]

Primeiro, aplicamos as pistas mais fortes. Caio está na frente de todos, então ele ocupa o primeiro lugar. Beto está logo atrás de Caio, então ele ocupa o segundo lugar.

Em seguida, olhamos para quem sobrou. Duda e Ana disputam o terceiro e o quarto lugares. Como Duda não está no fim da fila, ele não pode ocupar o quarto lugar, e sobra para ele o terceiro lugar. Ana, então, ocupa o quarto lugar, o único que sobrou.

A ordem completa é Caio, Beto, Duda e Ana. Conferimos cada pista contra essa ordem: Caio está na frente de todos (verdade, é o primeiro), Beto está logo atrás de Caio (verdade, é o segundo) e Duda não está no fim (verdade, ele é o terceiro, quem está no fim é Ana).

[Inserir aqui a figura `ord_fila_resultado.svg`.]

**Guarde. Comece pelas pistas que já dão uma posição fixa, como "primeiro lugar" ou "logo atrás de". Elas encolhem o problema. Só depois use as pistas que sobram para decidir entre as poucas posições que ainda restam.**

***Comparações par a par se encadeiam numa única ordem***

Quando cada pista compara só duas pessoas ou dois objetos de cada vez ("A é mais alto que B"), a forma de juntar tudo numa ordem só é encadear as comparações que têm um nome em comum. Se A é maior que B, e B é maior que C, então A também é maior que C, mesmo sem nenhuma pista dizer isso direto. Essa propriedade se chama ***transitividade***, e ela é o que permite montar uma fila inteira a partir de comparações soltas, duas de cada vez.

**Exemplo 2:** Entre quatro corredores, Rita, Marcos, Júlia e Pedro, sabe-se que Marcos corre mais rápido que Júlia, Júlia corre mais rápido que Pedro, e Rita corre mais rápido que Marcos. **Colocando do mais rápido para o mais lento, quem vem em cada posição?**

[Inserir aqui a figura `ord_ranking_estrutura.svg`.]

O segredo é achar os elos que se repetem entre as pistas. Júlia aparece em duas comparações, ligando Marcos e Pedro. Marcos aparece em duas comparações, ligando Rita e Júlia.

Juntando as pistas pelos nomes repetidos, a cadeia fica assim: Rita é mais rápida que Marcos, que é mais rápido que Júlia, que é mais rápida que Pedro.

A ordem do mais rápido para o mais lento é Rita, Marcos, Júlia e Pedro. Conferimos voltando a cada pista original: Marcos mais rápido que Júlia (posições $2$ e $3$, verdade), Júlia mais rápida que Pedro (posições $3$ e $4$, verdade) e Rita mais rápida que Marcos (posições $1$ e $2$, verdade).

[Inserir aqui a figura `ord_ranking_resultado.svg`.]

**Guarde. Para encadear comparações par a par, procure o nome que se repete em duas pistas diferentes. Ele é o elo que liga as duas comparações numa cadeia só, e a cadeia inteira dá a ordem completa.**

***Uma pista negativa fecha a última posição que sobrou***

Nem toda pista diz onde alguém está. Algumas dizem só onde alguém **não** está, e essas pistas negativas servem para eliminar a única posição errada quando já sobrou pouca coisa para decidir. Elas costumam vir por último no raciocínio, depois que as pistas diretas já resolveram a maior parte da ordem.

**Exemplo 3:** Numa corrida de quatro crianças, Tomás, Bia, Sofia e Léo, Tomás chegou em primeiro lugar, Léo chegou em último lugar, e Sofia não chegou em segundo lugar. **Quem chegou em segundo lugar?**

[Inserir aqui a figura `ord_corrida_estrutura.svg`.]

Antes de julgar a pista negativa, aplicamos as pistas diretas. Tomás chegou em primeiro lugar, e Léo chegou em último lugar, o quarto.

Sobram o segundo e o terceiro lugares para Bia e Sofia. Como Sofia não chegou em segundo lugar, ela só pode ter chegado em terceiro, e o segundo lugar sobra inteiro para Bia.

Bia chegou em segundo lugar. Conferimos porque a única posição livre depois de excluir o primeiro (Tomás), o último (Léo) e o terceiro (Sofia, pela pista negativa) é o segundo lugar, e ele só pode ser de Bia.

[Inserir aqui a figura `ord_corrida_resultado.svg`.]

**Guarde. Uma pista que diz "não é aqui" só é útil depois que sobra pouca coisa para decidir. Aplique primeiro as pistas diretas, e deixe a pista negativa para fechar a última posição em aberto.**

Este capítulo reuniu três formas de reconstruir uma ordem a partir de pistas soltas. Aplicar primeiro as pistas que já travam um lugar fixo, como "primeiro" ou "logo atrás de". Encadear comparações par a par pelo nome que se repete entre elas, usando a transitividade. E guardar a pista negativa para o final, quando ela é a única coisa que decide entre as poucas posições que sobraram. Nos três casos, o raciocínio é o mesmo: juntar as pistas até sobrar só um jeito de organizar tudo.

---

***Ilustrações***

| Arquivo | Onde entra | O que mostra |
|---|---|---|
| `ord_fila_estrutura.svg` | Após o problema fechado da fila do sorvete | Os quatro amigos e as pistas de posição, sem a ordem final marcada |
| `ord_fila_resultado.svg` | Ao final da resolução do exemplo da fila | A fila completa, na ordem Caio, Beto, Duda, Ana, com cada posição numerada |
| `ord_ranking_estrutura.svg` | Após o problema fechado dos corredores | As três comparações par a par soltas, sem a cadeia montada |
| `ord_ranking_resultado.svg` | Ao final da resolução do exemplo dos corredores | A cadeia completa Rita > Marcos > Júlia > Pedro, com os elos em destaque |
| `ord_corrida_estrutura.svg` | Após o problema fechado da corrida | O pódio parcial, com Tomás em primeiro e Léo em último, e Bia/Sofia sem posição |
| `ord_corrida_resultado.svg` | Ao final da resolução do exemplo da corrida | O pódio completo, com Bia no segundo lugar em destaque |
