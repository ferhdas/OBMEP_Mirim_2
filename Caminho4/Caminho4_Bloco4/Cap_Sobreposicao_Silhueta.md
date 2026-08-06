# O que fica por cima

> Trilha Mirim 2 (4º e 5º anos) · Caminho 4 · Bloco 4 · O que fica por cima. Nó da grade: Geometria › Percepção Espacial no Plano › Sobreposição, Transparência e Silhueta (subnó proposto, ver `Classificacao_Sobreposicao_Silhueta.md`).

Este capítulo é sobre figuras desenhadas umas em cima das outras. Quando vários cartões ficam empilhados, dá para descobrir a ordem deles só olhando quais bordas aparecem cortadas? Quando duas folhas com buraquinhos brancos ficam uma em cima da outra, como saber se o resultado final fica todo preto? E quando colamos vários adesivos exatamente no centro uns dos outros, sem girar nenhum, que forma sobra na silhueta de fora? As três perguntas são sobre a mesma ideia: o que está por cima esconde parte do que está por baixo.

***Quem aparece inteiro está por cima de tudo***

Quando várias figuras ficam empilhadas, cada uma cobrindo parte da anterior, a figura que aparece inteira, sem nenhuma borda cortada, é sempre a que está mais em cima. Uma figura com a borda cortada por outra está embaixo dela. Quanto mais bordas cortadas uma figura tem, mais embaixo na pilha ela está.

**Exemplo 1:** Três cartões quadrados, um vermelho, um azul e um amarelo, estão empilhados, cada um deslocado dos outros. O cartão vermelho aparece inteiro, sem nenhuma borda cortada. O cartão azul tem uma borda cortada, coberta pelo vermelho. O cartão amarelo tem duas bordas cortadas, uma coberta pelo vermelho e outra coberta pelo azul. **Qual é a ordem dos cartões, de cima para baixo?**

[Inserir aqui a figura `sobrep_cartoes_estrutura.svg`.]

O cartão vermelho aparece inteiro, então nada o cobre: ele está no topo da pilha. O cartão amarelo tem a borda cortada pelos outros dois cartões, então ele está embaixo dos outros dois: ele está no fundo da pilha. O cartão azul, cortado só pelo vermelho, fica no meio.

$\text{vermelho (topo)} \rightarrow \text{azul (meio)} \rightarrow \text{amarelo (fundo)}$

A ordem, de cima para baixo, é vermelho, azul, amarelo. Conferimos olhando o número de bordas cortadas de cada um: vermelho tem $0$, azul tem $1$, amarelo tem $2$, e quanto mais bordas cortadas, mais embaixo a figura está.

[Inserir aqui a figura `sobrep_cartoes_resultado.svg`.]

**Guarde. A ordem de uma pilha de figuras se descobre contando quantas bordas de cada uma estão cortadas por outra figura. Zero cortes significa estar no topo; quanto mais cortes, mais embaixo na pilha.**

***Uma folha com buraco deixa a cor de baixo aparecer***

Uma folha preta com buraquinhos brancos é transparente só nesses buraquinhos: em qualquer lugar onde a folha é preta, ela tapa o que está atrás. Quando duas dessas folhas ficam uma sobre a outra, um ponto do resultado final só fica branco se as duas folhas tiverem um buraco exatamente naquele mesmo ponto. Se pelo menos uma das duas folhas for preta ali, o resultado fica preto.

**Exemplo 2:** Duas folhas quadriculadas, cada uma com uma malha de $4$ por $4$ casinhas, são sobrepostas exatamente alinhadas. A primeira folha tem buraquinhos brancos em $4$ casinhas específicas. A segunda folha tem buraquinhos brancos em outras $4$ casinhas, nenhuma delas na mesma posição das casinhas brancas da primeira folha. **O resultado final, com as duas folhas sobrepostas, fica todo preto?**

[Inserir aqui a figura `sobrep_transp_estrutura.svg`.]

Uma casinha só fica branca no resultado se ela for branca nas duas folhas ao mesmo tempo. Como os buraquinhos da primeira folha e os buraquinhos da segunda folha estão em casinhas diferentes, não existe nenhuma casinha branca nas duas folhas ao mesmo tempo. Toda casinha da malha é preta em pelo menos uma das duas folhas.

Como não sobra nenhuma casinha branca nas duas folhas ao mesmo tempo, o resultado final fica todo preto.

[Inserir aqui a figura `sobrep_transp_resultado.svg`.]

**Guarde. Duas folhas com buraco só deixam uma casinha branca aparecer se as duas tiverem um buraco na mesma casinha. Buraquinhos em posições diferentes, de folhas diferentes, nunca se somam: eles só tapam um ao outro.**

***A silhueta de duas figuras coladas é a soma dos dois contornos***

Quando duas figuras são coladas exatamente no mesmo centro, sem girar nenhuma delas, a ***silhueta*** final (o contorno de fora, olhando as duas figuras como uma só sombra) segue sempre a figura que está mais longe do centro, em cada direção. Onde uma figura se estica mais do que a outra, a silhueta segue essa figura mais comprida; onde é o contrário, ela segue a outra.

**Exemplo 3:** Dois retângulos idênticos são colados exatamente no centro, um deitado (mais largo do que alto) e um em pé (mais alto do que largo), sem girar nenhum dos dois. **Qual é a silhueta resultante, olhando os dois retângulos como uma sombra só?**

[Inserir aqui a figura `sobrep_silhueta_estrutura.svg`.]

Na direção horizontal, o retângulo deitado se estica mais longe do centro do que o retângulo em pé, então a silhueta segue a borda do retângulo deitado nessa direção. Na direção vertical, é o contrário: o retângulo em pé se estica mais longe, então a silhueta segue a borda dele.

Nos quatro cantos, onde nenhum dos dois retângulos cobre sozinho, a silhueta faz um degrau, entrando para dentro. O resultado tem quatro braços salientes, dois deitados (do retângulo deitado) e dois em pé (do retângulo em pé): a silhueta final é uma cruz.

[Inserir aqui a figura `sobrep_silhueta_resultado.svg`.]

**Guarde. A silhueta de duas figuras coladas no mesmo centro nunca é só uma das duas figuras. Em cada direção, ela segue quem se estica mais longe naquela direção, e por isso pode ganhar pontas ou braços que nenhuma das duas figuras sozinha tinha.**

Este capítulo reuniu três formas de raciocinar sobre figuras sobrepostas. Descobrir a ordem de uma pilha contando bordas cortadas. Descobrir se duas folhas com buraco, sobrepostas, tapam tudo ou deixam algum ponto branco. E descobrir a silhueta de duas figuras coladas no centro, seguindo sempre quem se estica mais longe em cada direção. Nos três casos, a régua é a mesma: o que está por cima ou o que se estica mais longe é o que aparece no resultado final.

---

***Ilustrações***

| Arquivo | Onde entra | O que mostra |
|---|---|---|
| `sobrep_cartoes_estrutura.svg` | Após o problema fechado dos três cartões | Os três cartões empilhados, com as bordas cortadas visíveis, sem a ordem indicada |
| `sobrep_cartoes_resultado.svg` | Ao final da resolução do exemplo dos cartões | Os três cartões separados, em ordem vertical de cima para baixo, com o número de cortes de cada um |
| `sobrep_transp_estrutura.svg` | Após o problema fechado das duas folhas | As duas folhas de $4\times 4$ lado a lado, com os buraquinhos brancos marcados, sem o resultado sobreposto |
| `sobrep_transp_resultado.svg` | Ao final da resolução do exemplo das folhas | A malha resultante da sobreposição, toda preta, com uma nota confirmando que nenhuma casinha coincide |
| `sobrep_silhueta_estrutura.svg` | Após o problema fechado dos dois retângulos | Os dois retângulos, deitado e em pé, sobrepostos no centro, sem o contorno final destacado |
| `sobrep_silhueta_resultado.svg` | Ao final da resolução do exemplo da silhueta | A silhueta final em formato de cruz, com o contorno de fora destacado |
