# Descobrir o escondido

> Trilha Mirim 2 · Caminho 5 · Bloco 6 · Descobrir o escondido. Nó da grade: Raciocínio Lógico › Problemas com Restrições e Dedução › Correspondência Oculta e Padrão Escondido (ver `Classificacao_Deduzir_Oculto.md`).

Este capítulo é sobre descobrir um único valor escondido sem precisar destampar tudo. Qual é a senha que várias pistas numéricas, juntas, deixam determinada? O que está atrás de uma carta ainda fechada, quando outras cartas já confirmaram a mesma regra? E qual peça encaixa numa vaga, quando a regra de encaixe é sempre a mesma? As três perguntas se resolvem do mesmo jeito, juntando o que já sabemos com certeza, as pistas, o padrão confirmado, a regra de correspondência, para apontar direto o valor certo, sem testar cada possibilidade uma por uma.

***Cada pista sozinha deixa dúvida, mas juntas fecham a resposta***

Quando várias pistas falam sobre os mesmos algarismos escondidos, cada pista sozinha costuma deixar várias respostas possíveis. Uma pista de posição fixa um algarismo. Uma pista de soma limita o total dos outros. Uma pista de dobro liga dois algarismos entre si. Nenhuma delas, sozinha, fecha a senha, mas juntas, substituídas uma dentro da outra, sobra uma única combinação possível.

**Exemplo 1:** A senha de um cofre tem $3$ algarismos, nas posições centena, dezena e unidade. O algarismo da dezena é $5$. A soma dos três algarismos é $14$. O algarismo da centena é o dobro do algarismo da unidade. **Qual é a senha do cofre?**

[Inserir aqui a figura `ocul_senha_estrutura.svg`.]

Primeiro, anotamos o que a pista de posição já entrega pronto: o algarismo da dezena é $5$.

Em seguida, juntamos as outras duas pistas, que falam sobre a centena e a unidade. Como a soma dos três algarismos é $14$ e a dezena já vale $5$, sobra para a centena e a unidade juntas.

$14 - 5 = 9$

Agora, você usa a pista do dobro dentro dessa soma. Se a centena é o dobro da unidade, no lugar da centena você pode escrever "duas unidades". Juntando as duas na mesma soma, ficam três unidades ao todo.

$2 \times \text{unidade} + \text{unidade} = 9$

$3 \times \text{unidade} = 9$

$\text{unidade} = 3$

Por fim, a centena é o dobro dessa unidade.

$2 \times 3 = 6$

A senha é $653$. Conferimos substituindo os três algarismos nas pistas originais: $6 + 5 + 3 = 14$, a dezena é $5$, e a centena, $6$, é de fato o dobro da unidade, $3$.

[Inserir aqui a figura `ocul_senha_resultado.svg`.]

**Guarde. Quando cada pista sozinha permite várias respostas, mas juntas sobra só uma combinação, resolvemos substituindo uma pista dentro da outra, uma de cada vez, até restar um único valor para cada algarismo escondido.**

***Um padrão repetido três vezes vale para a próxima carta***

Até aqui, a certeza veio de somar pistas sobre números. Mas há situações em que a certeza vem de outro lugar, um padrão que já se repetiu várias vezes e por isso pode ser aplicado de novo, com confiança, sem conferir cada caso na mão.

**Exemplo 2:** Numa mesa há $4$ cartas. Em $3$ delas, já viradas, vemos os dois lados. A carta de frente $4$ tem verso $11$. A carta de frente $6$ tem verso $9$. A carta de frente $10$ tem verso $5$. A quarta carta, de frente $13$, ainda está fechada. **Sem virar a quarta carta, qual é o número no seu verso?**

[Inserir aqui a figura `ocul_carta_estrutura.svg`.]

Primeiro, procuramos uma regra que ligue a frente e o verso, igual nas três cartas já viradas. Somamos cada par.

$4 + 11 = 15$

$6 + 9 = 15$

$10 + 5 = 15$

As três somas deram o mesmo valor, $15$. Isso confirma a regra: a soma dos dois lados de qualquer carta desse baralho é sempre $15$.

Em seguida, aplicamos essa regra confirmada à quarta carta, mesmo sem virá-la. Se a frente é $13$ e a soma dos dois lados precisa dar $15$, o verso é o que falta para completar.

$15 - 13 = 2$

O verso da quarta carta é $2$. Conferimos porque as três cartas já viradas confirmaram a mesma regra três vezes seguidas, então aplicá-la a mais uma carta do mesmo baralho é seguro, mesmo sem virá-la de verdade.

[Inserir aqui a figura `ocul_carta_resultado.svg`.]

**Guarde. Quando várias cartas já viradas confirmam a mesma regra entre os dois lados, aplicamos essa regra a uma carta ainda fechada com a mesma confiança de quem já virou, sem precisar virá-la de verdade.**

***A mesma regra de encaixe vale para todas as peças***

Nos dois casos anteriores, o alvo era um número. Agora o alvo é uma peça, e a certeza vem de uma regra de correspondência fixa, a mesma para todas as peças do jogo, em vez de pistas soltas sobre cada uma.

**Exemplo 3:** Um brinquedo de encaixe tem uma vaga em formato de estrela, pintada de verde. Entre as peças soltas, há uma estrela azul, um círculo verde, uma estrela verde e um quadrado verde. **Qual peça encaixa nessa vaga?**

[Inserir aqui a figura `ocul_encaixe_estrutura.svg`.]

Primeiro, fixamos a regra de encaixe: uma peça só encaixa numa vaga quando tem a mesma forma e a mesma cor da vaga, as duas condições ao mesmo tempo.

Em seguida, testamos cada peça contra as duas condições juntas, forma de estrela e cor verde. A estrela azul tem a forma certa, mas a cor errada. O círculo verde tem a cor certa, mas a forma errada. O quadrado verde também tem a cor certa, mas a forma errada. Só a estrela verde tem as duas condições ao mesmo tempo.

A peça que encaixa é a estrela verde. Conferimos porque nenhuma outra peça bate as duas condições juntas, cada uma das outras falha em pelo menos uma delas.

[Inserir aqui a figura `ocul_encaixe_resultado.svg`.]

**Guarde. Quando a regra de encaixe é sempre a mesma, comparamos a peça candidata com a vaga pela regra inteira, forma e cor juntas, e não só por uma das duas partes.**

Este capítulo reuniu três formas de descobrir um valor escondido sem testar tudo. Na senha, juntamos pistas diferentes até sobrar uma só combinação possível. Na carta, usamos um padrão já confirmado várias vezes para prever, com confiança, o que ainda está escondido. E no encaixe, aplicamos sempre a mesma regra de correspondência para achar a peça certa, sem comparar uma por uma à toa. Em todos os casos, a ideia de fundo é a mesma, usar o que já sabemos com certeza para apontar direto o valor que falta, em vez de adivinhar.

---

***Ilustrações***

| Arquivo | Onde entra | O que mostra |
|---|---|---|
| `ocul_senha_estrutura.svg` | Após o problema fechado da senha | O cofre de $3$ posições, com a dezena marcada em $5$ e as pistas de soma e dobro escritas ao lado, sem os algarismos de centena e unidade preenchidos |
| `ocul_senha_resultado.svg` | Ao final da resolução do exemplo da senha | O cofre com os $3$ algarismos preenchidos, $6$-$5$-$3$, em destaque |
| `ocul_carta_estrutura.svg` | Após o problema fechado das cartas | As $3$ cartas já viradas, com frente e verso à mostra, e a quarta carta fechada, mostrando só a frente $13$ |
| `ocul_carta_resultado.svg` | Ao final da resolução do exemplo das cartas | A quarta carta virada, com o verso $2$ em destaque, ao lado da conta $15 - 13 = 2$ |
| `ocul_encaixe_estrutura.svg` | Após o problema fechado do encaixe | A vaga em formato de estrela verde, vazia, e as $4$ peças candidatas soltas ao lado, sem indicação de qual encaixa |
| `ocul_encaixe_resultado.svg` | Ao final da resolução do exemplo do encaixe | A vaga com a estrela verde encaixada dentro, em destaque, e as outras $3$ peças descartadas ao lado |
