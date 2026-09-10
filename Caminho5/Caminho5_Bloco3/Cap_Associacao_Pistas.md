# Quem tem o quê

> Trilha Mirim 2 · Caminho 5 · Bloco 3 · Quem tem o quê. Nó da grade: Raciocínio Lógico › Problemas com Restrições e Dedução › Quem é Quem / Identidades Ocultas (ver `Classificacao_Associacao_Pistas.md`).

Este capítulo é sobre casar cada pessoa com o que é dela, usando só pistas soltas. Como descobrir qual bicho de estimação é de cada amigo, com poucas frases de pista? E se cada amigo tiver não um, mas dois detalhes escondidos, um bicho e uma cor favorita, por exemplo, como cruzar as pistas de um detalhe com as do outro? E numa grade maior, com mais gente e mais opções, por onde começar? As três perguntas se resolvem com a mesma régua: cada pessoa tem exatamente um item de cada categoria, e cada item pertence a exatamente uma pessoa.

***Uma grade simples se resolve fixando o que já é certo e eliminando o resto***

Quando cada pessoa tem exatamente um item de uma lista, e cada item pertence a exatamente uma pessoa, uma pista que liga uma pessoa a um item de forma direta já fecha aquela casa da grade. Depois de fixar as pistas diretas, sobram poucas pessoas e poucos itens, e uma pista negativa costuma bastar para fechar o resto.

**Exemplo 1:** Três amigos, Ana, Beto e Caio, têm cada um um bicho de estimação diferente: gato, cachorro ou passarinho. Beto tem cachorro. Ana não tem gato. **Qual bicho é de cada amigo?**

[Inserir aqui a figura `assoc_grade_estrutura.svg`.]

Primeiro, aplicamos a pista direta. Beto tem cachorro, então essa casa da grade já fecha, e nem cachorro nem Beto entram em mais nenhuma combinação.

Em seguida, sobram gato e passarinho para Ana e Caio. Como Ana não tem gato, ela só pode ter passarinho, e o gato sobra inteiro para Caio.

A associação completa é Beto com cachorro, Ana com passarinho e Caio com gato. Conferimos voltando às duas pistas: Beto tem cachorro (verdade) e Ana não tem gato (verdade, ela tem passarinho).

[Inserir aqui a figura `assoc_grade_resultado.svg`.]

**Guarde. Numa grade de associação, comece pela pista que já liga uma pessoa a um item direto. Ela fecha uma casa e encolhe o problema, sobrando menos gente e menos itens para a pista seguinte decidir.**

***Uma grade cruzada liga um atributo a outro antes de chegar à pessoa***

Quando cada pessoa tem dois atributos ao mesmo tempo, de duas categorias diferentes, algumas pistas não citam a pessoa, citam só a ligação entre os dois atributos ("quem tem tal coisa usa tal outra"). Para usar essas pistas, primeiro fechamos as casas diretas de cada categoria, separadamente, e só depois cruzamos as duas grades resolvidas para achar a pessoa que a pista realmente aponta.

**Exemplo 2:** Três amigos, Duda, Elis e Fábio, têm cada um um bicho de estimação (gato, cachorro ou peixe) e uma cor favorita (azul, verde ou amarelo), um par diferente para cada um. Duda tem cachorro. Fábio gosta de verde. Elis não gosta de azul. Quem tem o peixe gosta de amarelo. **Quem tem o peixe, e de que cor ele gosta?**

[Inserir aqui a figura `assoc_cruzada_estrutura.svg`.]

Primeiro, fechamos as pistas diretas de cada categoria, separadamente. Duda tem cachorro. Fábio gosta de verde.

Em seguida, sobram gato e peixe para Elis e Fábio, e sobram azul e amarelo para Duda e Elis. Como Elis não gosta de azul, ela gosta de amarelo, e o azul sobra para Duda.

Agora cruzamos a última pista, que liga peixe a amarelo. Como Elis é quem gosta de amarelo, e a pista diz que quem tem peixe gosta de amarelo, o peixe só pode ser de Elis. Sobra o gato para Fábio.

Elis tem o peixe e gosta de amarelo. Conferimos juntando as quatro peças: Duda tem cachorro e azul, Elis tem peixe e amarelo, Fábio tem gato e verde, e a pista "quem tem peixe gosta de amarelo" bate certinho com Elis.

[Inserir aqui a figura `assoc_cruzada_resultado.svg`.]

**Guarde. Numa grade cruzada, resolva primeiro cada categoria separadamente com as pistas diretas. Só depois use a pista que liga uma categoria à outra, porque ela só faz sentido depois que as duas grades já têm menos opções em aberto.**

***Numa grade maior, cada pista resolvida abre caminho para a próxima***

Com mais pessoas e mais itens, a grade fica maior, mas o raciocínio continua o mesmo: aplicar primeiro as pistas diretas, que fecham casas de uma vez, e deixar as pistas negativas para o final, quando já sobra pouca coisa para decidir. Numa grade grande, isso costuma acontecer em cadeia, cada casa fechada tira uma opção do caminho e deixa a próxima pista mais fácil de aplicar.

**Exemplo 3:** Quatro amigos, Léa, Mateus, Nina e Otávio, comeram cada um uma sobremesa diferente numa festa: sorvete, pudim, bolo ou gelatina. Mateus comeu sorvete. Otávio comeu gelatina. Quem comeu bolo não foi a Nina. **Quem comeu pudim?**

[Inserir aqui a figura `assoc_encadeada_estrutura.svg`.]

Primeiro, fechamos as duas pistas diretas. Mateus comeu sorvete, e Otávio comeu gelatina.

Em seguida, sobram pudim e bolo para Léa e Nina. A pista que falta diz que quem comeu bolo não foi a Nina, então o bolo só pode ter sido de Léa, e o pudim sobra para Nina.

Nina comeu pudim. Conferimos porque, das quatro sobremesas, sorvete e gelatina já tinham dono fixo, e entre pudim e bolo, a única forma de respeitar "bolo não foi a Nina" é Léa com bolo e Nina com pudim.

[Inserir aqui a figura `assoc_encadeada_resultado.svg`.]

**Guarde. Numa grade com mais gente, resolva as pistas diretas primeiro, mesmo que sejam poucas. Cada casa fechada empurra a próxima decisão para um espaço menor, até a última pista sobrar só uma forma de fechar tudo.**

Este capítulo reuniu três formas de casar pessoas com atributos por pistas. Numa grade simples, fixar as pistas diretas e fechar o resto com uma pista negativa. Numa grade cruzada, resolver cada categoria em separado antes de cruzar a pista que liga uma categoria à outra. E numa grade maior, deixar cada casa fechada abrir caminho para a próxima, até sobrar uma única combinação possível. Em todas, a régua de fundo é a mesma: cada pessoa tem um item de cada categoria, e cada item pertence a uma só pessoa.

---

***Ilustrações***

| Arquivo | Onde entra | O que mostra |
|---|---|---|
| `assoc_grade_estrutura.svg` | Após o problema fechado dos bichos de estimação | A grade $3 \times 3$ (Ana, Beto, Caio × gato, cachorro, passarinho), com só a casa de Beto marcada |
| `assoc_grade_resultado.svg` | Ao final da resolução do exemplo dos bichos | A grade completa, com as três combinações marcadas em verde |
| `assoc_cruzada_estrutura.svg` | Após o problema fechado dos bichos e cores | As duas grades (bicho e cor), com só as pistas diretas marcadas, sem o cruzamento final |
| `assoc_cruzada_resultado.svg` | Ao final da resolução do exemplo dos bichos e cores | As duas grades completas, com a ligação peixe-amarelo-Elis em destaque |
| `assoc_encadeada_estrutura.svg` | Após o problema fechado das sobremesas | A grade $4 \times 4$, com só Mateus (sorvete) e Otávio (gelatina) marcados |
| `assoc_encadeada_resultado.svg` | Ao final da resolução do exemplo das sobremesas | A grade completa, com Léa (bolo) e Nina (pudim) em destaque como as últimas casas fechadas |
