# Seguir, inverter e o que não muda

> Trilha Mirim 2 (4º e 5º anos) · Caminho 6 · Bloco 5 · Processos passo a passo. Nó da grade: Raciocínio Lógico › Problemas com Regras de Transformação e Algoritmos (ver `Classificacao_Processos_Passo_a_Passo.md`).

Este capítulo é sobre acompanhar um processo que muda passo a passo, e descobrir alguma coisa sobre ele sem precisar ver cada passo escrito. Um robô que segue sempre a mesma regra de virar termina num lugar que dá para calcular só de seguir a regra com cuidado. Uma transformação que se repete enquanto for possível para sozinha num estado final, mesmo sem saber a ordem exata dos passos. Um processo que soma sempre que alguém mente e volta ao início sempre que alguém fala a verdade guarda, no resultado final, uma pista sobre qual passo foi verdade com certeza. E às vezes o mais importante não é o resultado final, é o que nunca muda enquanto o processo acontece, uma paridade que se mantém, ou uma ordem que não se embaralha. Essas quatro ideias organizam o capítulo.

***Seguir a regra, um passo de cada vez***

Quando um processo segue uma regra fixa de movimento, "ande até a parede, depois vire à direita", o jeito mais seguro de achar o resultado final é percorrer a regra devagar, um trecho de cada vez, sem tentar adivinhar o final de uma vez só.

**Exemplo 1:** Um robô começa no ponto de entrada de um labirinto, olhando para o Leste, e segue esta regra, andar reto até bater numa parede, depois virar à direita. **Em que ponto do desenho abaixo o robô sai do labirinto?**

[Inserir aqui a figura `labirinto_estrutura.svg`.]

Seguimos a regra corredor por corredor. O robô anda $3$ casas para o Leste, bate na parede, e vira à direita, passando a olhar para o Sul.

Andando para o Sul, ele percorre $2$ casas até bater na próxima parede, e vira à direita de novo, passando a olhar para o Oeste.

Para o Oeste, ele percorre $4$ casas até bater na parede seguinte, e vira à direita, passando a olhar para o Norte.

Para o Norte, ele percorre $1$ casa e sai do labirinto.

$3 \to 2 \to 4 \to 1$

O robô sai no ponto A, que é onde termina o último trecho do trajeto. Conferimos percorrendo o desenho de novo, do início ao fim, contando cada trecho reto entre duas viradas.

[Inserir aqui a figura `labirinto_resultado.svg`.]

**Guarde. Num processo que segue uma regra fixa de movimento, percorra a regra passo a passo, trecho reto por trecho reto, marcando cada virada no momento em que ela acontece. Tentar adivinhar o final sem seguir cada trecho é o erro mais comum nesse tipo de questão.**

***Repetir a transformação até não dar mais***

Quando uma regra transforma um grupo de itens em outro, e essa transformação pode se repetir enquanto houver itens suficientes, o processo sempre para no mesmo lugar, não importa em que ordem as transformações aconteceram, contanto que a regra seja sempre aplicada enquanto for possível.

**Exemplo 2:** Um mágico transforma $3$ moedas de prata em $1$ moeda de ouro, e transforma $3$ moedas de ouro em $1$ moeda de prata. Sempre que uma das duas transformações é possível, ele a faz. Ele começa com $2$ moedas de ouro e $4$ moedas de prata. **Com o que ele fica ao final?**

Olhamos o que ele tem, $2$ moedas de ouro e $4$ de prata. Como há $4$ moedas de prata, e $4$ é pelo menos $3$, ele transforma $3$ delas numa moeda de ouro.

$2 \text{ ouro} + 4 \text{ prata} \to 3 \text{ ouro} + 1 \text{ prata}$

Agora ele tem $3$ moedas de ouro e só $1$ de prata. Como há $3$ moedas de ouro, ele transforma essas $3$ numa moeda de prata.

$3 \text{ ouro} + 1 \text{ prata} \to 0 \text{ ouro} + 2 \text{ prata}$

Agora ele tem $0$ moedas de ouro e $2$ de prata, e nenhuma das duas transformações é mais possível, porque nem $3$ moedas de ouro nem $3$ de prata estão disponíveis.

$0 \text{ ouro}, \ 2 \text{ prata}$

Ele fica com $0$ moedas de ouro e $2$ de prata. Conferimos refazendo as duas transformações na ordem que aconteceram, e nenhuma outra transformação sobra para fazer.

**Guarde. Numa transformação que se repete enquanto for possível, aplique a regra um passo de cada vez, sempre conferindo depois de cada passo se alguma das transformações ainda cabe. O processo só termina quando nenhuma transformação é mais possível, e é nesse ponto que mora a resposta.**

***Reconstruir de trás para frente***

Alguns processos escondem a ordem exata dos passos, mas o resultado final ainda revela alguma coisa que precisa ter acontecido com certeza. Quando uma regra "reseta" o processo para um valor conhecido, e outra regra o afasta desse valor, o resultado final aponta exatamente quantos passos consecutivos de afastamento aconteceram por último, e isso obriga o passo logo antes desses a ter sido um reset.

**Exemplo 3:** O termômetro mágico de Aurora marca $20$ graus quando ninguém mente por perto. Toda vez que alguém conta uma mentira, o termômetro sobe $4$ graus. Toda vez que alguém fala a verdade, o termômetro volta direto para $20$ graus. Cinco pessoas falaram, uma de cada vez, e ao final o termômetro marcava $32$ graus. **Qual das cinco falas com certeza foi verdade?**

A diferença entre o valor final e o valor de descanso é $32-20=12$, e $12$ dividido por $4$ dá $3$.

$12 \div 4 = 3$

Isso quer dizer que as últimas $3$ falas, a terceira, a quarta e a quinta, formaram uma sequência de mentiras sem nenhuma verdade no meio, porque só assim o termômetro sobe $12$ graus seguidos a partir de $20$.

Se a segunda fala também tivesse sido mentira, a sequência de mentiras teria $4$ falas, não $3$, e o termômetro teria subido $16$ graus, chegando a $36$, não a $32$. Por isso, a segunda fala precisa ter sido verdade, resetando o termômetro para $20$ bem antes da sequência final de $3$ mentiras começar.

$20 \to 24 \to 28 \to 32$

A segunda fala com certeza foi verdade. Conferimos passo a passo, a segunda reseta para $20$, e a terceira, a quarta e a quinta somam $4$ cada, $20+4+4+4=32$.

**Guarde. Quando um processo tem uma regra que reseta para um valor fixo e outra que se afasta dele, calcule quantos passos de afastamento cabem entre o valor de descanso e o valor final. O passo logo antes desses é o único que precisa ter sido um reset, mesmo sem saber o que aconteceu antes dele.**

***O que não muda enquanto o processo continua***

Às vezes a pergunta mais útil não é "qual é o resultado", é "o que nunca muda, não importa como o processo aconteça". Duas ideias de invariante aparecem com frequência, uma paridade que se mantém sempre igual, e uma ordem que nunca se embaralha.

**Exemplo 4:** Usando os números $1$, $2$, $3$, $4$ e $5$, cada um exatamente uma vez, separe-os num grupo de $3$ números e num grupo de $2$ números. **O valor (soma do grupo de $3$) menos (soma do grupo de $2$) pode ser qual desses números, $4$, $5$, $6$ ou $11$?**

A soma de todos os cinco números é $15$.

$1+2+3+4+5=15$

Se o grupo de $3$ soma $S$, o grupo de $2$ soma $15-S$, e a diferença pedida é $S-(15-S)=2S-15$. Como $2S$ é sempre par, e $15$ é ímpar, essa diferença é sempre um número ímpar, não importa quais números formem cada grupo.

$2S-15 \ \text{é sempre ímpar}$

Entre as opções, $4$ e $6$ são pares, então nunca podem ser essa diferença. Falta conferir se $5$ ou $11$ são realmente alcançáveis. Testando o grupo $\{1,4,5\}$ contra o grupo $\{2,3\}$,

$(1+4+5)-(2+3)=10-5=5$

o valor $5$ é alcançável, e ele é a resposta.

**Guarde. Antes de testar grupos ao acaso, pergunte se existe uma paridade que nunca muda, seja qual for a separação escolhida. Uma soma total ímpar dividida em duas partes sempre dá uma diferença ímpar, e uma soma total par sempre dá uma diferença par, isso descarta metade das opções sem nenhuma conta.**

**Exemplo 5:** Um colar tem $7$ contas nesta ordem, da esquerda para a direita, bolinha, estrela, estrela, coração, bolinha, coração, estrela. Ana quer retirar $2$ contas, algumas pela ponta esquerda do cordão e outras pela ponta direita, nunca pelo meio. **Qual dessas sequências pode ser o que sobrou no colar, "estrela, estrela, coração, bolinha, coração" ou "bolinha, estrela, estrela, bolinha, coração"?**

[Inserir aqui a figura `colar_ordem_estrutura.svg`.]

Como as contas só saem pelas pontas, o que sobra é sempre um pedaço contínuo do colar original, sem pular nenhuma conta e sem trocar a ordem entre elas. Retirando $2$ contas pela esquerda, sobra da terceira até a sétima conta, estrela, coração, bolinha, coração, estrela. Retirando $1$ de cada ponta, sobra da segunda até a sexta, estrela, estrela, coração, bolinha, coração. Retirando $2$ pela direita, sobra da primeira até a quinta, bolinha, estrela, estrela, coração, bolinha.

A sequência "estrela, estrela, coração, bolinha, coração" é exatamente o pedaço que sobra retirando $1$ conta de cada ponta, então ela pode ter sobrado.

$\text{estrela, estrela, coração, bolinha, coração}$

Já a sequência "bolinha, estrela, estrela, bolinha, coração" tem as contas na ordem errada, ela não aparece em nenhum pedaço contínuo do colar original, então não pode ter sobrado.

[Inserir aqui a figura `colar_ordem_resultado.svg`.]

**Guarde. Quando itens só podem sair pelas pontas de uma fila, o que sobra é sempre um pedaço contínuo da sequência original, na mesma ordem de sempre. Uma sequência com os itens certos mas na ordem errada nunca pode ser o resultado, porque a ordem entre os itens que ficam nunca se embaralha.**

---

## Ilustrações

- `labirinto_estrutura.svg` / `.png` — um labirinto com corredores em formato de espiral, entrada marcada, e cinco pontos rotulados de A a E nas posições possíveis de saída, sem o trajeto desenhado ainda.
- `labirinto_resultado.svg` / `.png` — o mesmo labirinto com o trajeto do robô desenhado em verde, do início ao ponto A, com os quatro trechos retos e as três viradas marcadas.
- `colar_ordem_estrutura.svg` / `.png` — o colar de Ana com as $7$ contas na ordem descrita, sem nenhuma retirada ainda.
- `colar_ordem_resultado.svg` / `.png` — o mesmo colar com as $2$ contas retiradas (uma de cada ponta) esmaecidas, e as $5$ contas restantes destacadas em verde.
