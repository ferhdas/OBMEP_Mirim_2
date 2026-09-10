# Regras condicionais

> Trilha Mirim 2 · Caminho 5 · Bloco 4 · Regras condicionais. Nó da grade: Raciocínio Lógico › Problemas com Tabelas-Verdade / Lógica Proposicional (ver `Classificacao_Logica_SeEntao.md`).

Este capítulo é sobre regras do tipo "se acontece isto, então acontece aquilo". Quando uma regra dessas é verdadeira, e um caso satisfaz a primeira parte, o que podemos garantir sobre esse caso? E quando alguém afirma que uma regra vale sempre, como provar que ela é falsa com um único exemplo? E se duas regras se encaixam, uma entregando a condição da outra, o que dá para deduzir juntando as duas? As três perguntas giram em torno da mesma ideia: uma regra condicional só é útil se soubermos exatamente o que ela garante, e o que ela não garante.

***Uma regra condicional garante a consequência sempre que a condição é verdadeira***

Uma regra do tipo "se P, então Q" diz que, toda vez que P acontece, Q também acontece. Quando um caso concreto satisfaz a condição P, a regra garante que esse caso também satisfaz a consequência Q, sem precisar verificar Q de novo, contanto que a regra seja verdadeira e o caso realmente satisfaça P.

**Exemplo 1:** Numa turma, vale a regra: se um número é múltiplo de $4$, então ele é par. O número $28$ é múltiplo de $4$. **O número $28$ é par?**

[Inserir aqui a figura `cond_aplicar_estrutura.svg`.]

Primeiro, conferimos que o caso satisfaz a condição da regra. O número $28$ é múltiplo de $4$, porque $28 \div 4 = 7$, uma divisão exata.

Em seguida, aplicamos a regra. Como a regra diz que todo múltiplo de $4$ é par, e $28$ é múltiplo de $4$, a regra garante que $28$ é par.

Sim, $28$ é par. Conferimos de outra forma, olhando direto para o algarismo das unidades de $28$, que é $8$, um algarismo par, confirmando o que a regra já garantia.

[Inserir aqui a figura `cond_aplicar_resultado.svg`.]

**Guarde. Quando uma regra "se P, então Q" é verdadeira, e um caso satisfaz P, a regra garante Q para esse caso, sem precisar de nenhuma verificação extra.**

***Um único contraexemplo derruba uma regra que deveria valer sempre***

Quando alguém afirma que uma regra vale para **todo** caso que satisfaz uma condição, essa afirmação só é verdadeira se não existir nenhuma exceção. Para provar que ela é falsa, basta achar **um** caso que satisfaz a condição, mas não satisfaz a consequência. Esse caso se chama ***contraexemplo***, e ele sozinho já derruba a afirmação inteira, por mais que ela pareça valer em muitos outros casos.

**Exemplo 2:** Uma pessoa afirma: toda fruta vermelha é uma maçã. **Qual das frutas a seguir mostra que essa afirmação é falsa: banana, morango, uva verde ou pera?**

[Inserir aqui a figura `cond_contraexemplo_estrutura.svg`.]

Primeiro, identificamos o que a afirmação promete: toda fruta que é vermelha também tem que ser uma maçã. Para derrubar isso, precisamos de uma fruta vermelha que não seja maçã.

Em seguida, testamos cada opção contra as duas partes da afirmação. Banana não é vermelha, então nem entra na condição. Uva verde não é vermelha, pelo próprio nome. Pera costuma ser verde ou amarela, não vermelha. O morango é vermelho, e não é uma maçã.

O morango é o contraexemplo. Conferimos porque ele satisfaz a condição (é vermelho) e não satisfaz a consequência (não é maçã), exatamente o que é preciso para derrubar a afirmação "toda fruta vermelha é maçã".

[Inserir aqui a figura `cond_contraexemplo_resultado.svg`.]

**Guarde. Para derrubar uma afirmação do tipo "todo P é Q", procure um caso que satisfaça P mas não satisfaça Q. Um só já basta, e casos que satisfazem P e também satisfazem Q não provam nada sobre a regra valer sempre.**

***Duas regras encadeadas entregam uma conclusão que nenhuma delas dá sozinha***

Quando a consequência de uma regra condicional é exatamente a condição de outra regra, as duas se encadeiam: se P leva a Q, e Q leva a R, então P leva a R, mesmo que nenhuma regra sozinha ligue P diretamente a R. É a mesma ideia da transitividade usada para ordenar comparações, agora aplicada a regras condicionais.

**Exemplo 3:** Valem duas regras: se um número é múltiplo de $9$, então ele é múltiplo de $3$. Se um número é múltiplo de $3$, então a soma dos seus algarismos é múltiplo de $3$. O número $45$ é múltiplo de $9$. **A soma dos algarismos de $45$ é múltiplo de $3$?**

[Inserir aqui a figura `cond_encadeada_estrutura.svg`.]

Primeiro, aplicamos a primeira regra ao caso dado. Como $45$ é múltiplo de $9$, a primeira regra garante que $45$ também é múltiplo de $3$.

Em seguida, usamos esse resultado como entrada da segunda regra. Como $45$ é múltiplo de $3$, a segunda regra garante que a soma dos algarismos de $45$ é múltiplo de $3$.

Sim, a soma dos algarismos de $45$ é múltiplo de $3$. Conferimos calculando direto: $4 + 5 = 9$, e $9$ é múltiplo de $3$, confirmando o que as duas regras encadeadas já garantiam, sem que nenhuma delas sozinha falasse da soma dos algarismos de um múltiplo de $9$.

[Inserir aqui a figura `cond_encadeada_resultado.svg`.]

**Guarde. Quando a consequência de uma regra é a condição de outra, encadeie as duas: o que a primeira regra garante vira a entrada da segunda, e a conclusão final vale mesmo sem nenhuma regra ligando direto o começo ao fim.**

Este capítulo reuniu três formas de raciocinar com regras "se... então". Aplicar uma regra verdadeira a um caso que satisfaz a condição, para garantir a consequência. Achar um contraexemplo, um caso que satisfaz a condição mas não a consequência, para derrubar uma afirmação que deveria valer sempre. E encadear duas regras, quando a consequência de uma é a condição da outra, para chegar a uma conclusão que nenhuma delas entrega sozinha. Nos três casos, o cuidado é o mesmo: saber exatamente o que a regra garante, e não confundir isso com o que ela não garante.

---

***Ilustrações***

| Arquivo | Onde entra | O que mostra |
|---|---|---|
| `cond_aplicar_estrutura.svg` | Após o problema fechado do múltiplo de $4$ | A regra "se múltiplo de 4, então par" e o número $28$, sem a conclusão marcada |
| `cond_aplicar_resultado.svg` | Ao final da resolução do exemplo do múltiplo de $4$ | A cadeia $28$ é múltiplo de $4$ → $28$ é par, com a seta da regra em destaque |
| `cond_contraexemplo_estrutura.svg` | Após o problema fechado das frutas | As quatro frutas listadas, sem nenhuma marcada como contraexemplo |
| `cond_contraexemplo_resultado.svg` | Ao final da resolução do exemplo das frutas | O morango marcado como contraexemplo, com um X sobre a afirmação derrubada |
| `cond_encadeada_estrutura.svg` | Após o problema fechado do múltiplo de $9$ | As duas regras separadas e o número $45$, sem a cadeia montada |
| `cond_encadeada_resultado.svg` | Ao final da resolução do exemplo do múltiplo de $9$ | A cadeia completa múltiplo de $9$ → múltiplo de $3$ → soma dos algarismos múltiplo de $3$ |
