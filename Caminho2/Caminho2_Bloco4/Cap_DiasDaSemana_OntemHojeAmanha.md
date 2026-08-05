# Dias da semana por ontem, hoje e amanhã

> Trilha Mirim 2 (4º e 5º anos) · Caminho 2 · Bloco 4 · Dias da semana por ontem, hoje e amanhã. Nó da grade: Raciocínio Lógico › Problemas com Restrições e Dedução › Restrições Temporais e Dias da Semana, com apoio do subnó Aritmética › Grandezas e Medidas › Medidas de tempo › Dias da semana por resto da divisão por $7$ (aberto no Bloco 3).

Este capítulo é sobre palavras que apontam para um dia sem dizer o nome dele. Se alguém diz que ontem foi terça-feira, que dia é hoje? E se quatro pessoas falam sobre o dia de hoje e uma delas está enganada, como descobrimos quem foi? As duas perguntas usam a mesma ideia, que é andar alguns passos para frente ou para trás a partir de um dia certo.

***Cinco palavras, cinco posições***

Existem palavras que apontam para um dia sem dizer seu nome, e cada uma fica numa posição fixa em relação a hoje. ***Anteontem*** é $2$ dias antes de hoje. ***Ontem*** é $1$ dia antes de hoje. ***Hoje*** é o dia em que estamos, o meio da linha. ***Amanhã*** é $1$ dia depois de hoje. ***Depois de amanhã*** é $2$ dias depois de hoje. As cinco palavras formam uma linha reta, com hoje bem no centro.

[Inserir aqui a figura `ohj_linha_dias.svg`.]

Cada palavra também é um número de passos na roda da semana que já conhecemos do Bloco 3. Anteontem são $2$ passos para trás. Ontem é $1$ passo para trás. Amanhã é $1$ passo para a frente. Depois de amanhã são $2$ passos para a frente. Para achar o dia que uma dessas palavras aponta, andamos esse tanto de passos a partir de hoje, na direção certa.

Tomemos um caso simples.

⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯
*Ontem foi quinta-feira.* **Que dia é hoje? E que dia será amanhã?**
⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯

[Inserir aqui a figura `ohj_ex_a_estrutura.svg`.]

Ontem foi quinta-feira, e hoje fica $1$ passo depois de ontem na roda da semana. Andando $1$ passo a partir de quinta-feira chegamos a sexta-feira. Hoje é sexta-feira. Amanhã fica mais $1$ passo à frente de hoje, então andamos mais $1$ passo a partir de sexta-feira e chegamos a sábado. Conferimos contando ao contrário, a partir de amanhã. Sábado menos $1$ dia é sexta-feira, que é hoje, e sexta-feira menos $1$ dia é quinta-feira, que é exatamente o que o problema disse ser ontem. Hoje é sexta-feira e amanhã será sábado.

[Inserir aqui a figura `ohj_ex_a_resultado.svg`.]

***A palavra "ontem" não empurra o dia para a frente***

Um erro fácil de cometer é andar na direção errada. Quando o problema diz "ontem foi tal dia", muita gente tenta achar hoje andando para trás a partir de ontem, só que ontem já está para trás, e hoje precisa vir depois dele. Hoje é sempre $1$ passo à frente de ontem, nunca $1$ passo atrás. O mesmo cuidado vale ao contrário. "Amanhã será tal dia" não empurra hoje para a frente, porque hoje é $1$ passo atrás de amanhã.

**Guarde.** Ontem e anteontem ficam para trás de hoje. Amanhã e depois de amanhã ficam para a frente de hoje. Para achar hoje a partir de uma dessas palavras, andamos na direção contrária à direção que a palavra indica.

***Uma fala vira uma conta***

Cada frase que alguém diz sobre o dia pode virar uma pequena conta, trocando a palavra pelo número de passos que ela representa. "Ontem foi segunda-feira" vira "hoje é $1$ dia depois de segunda-feira". "Depois de amanhã será sexta-feira" vira "hoje é $2$ dias antes de sexta-feira". Transformar a fala numa conta assim é útil sobretudo quando mais de uma pessoa fala sobre o mesmo hoje, porque dá para comparar as contas e ver se elas concordam.

Veja o caso de quatro primos conversando durante uma viagem de carro.

⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯
*Ana diz: "Amanhã será sábado." Beto diz: "Hoje é sábado." Carla diz: "Depois de amanhã será domingo." Dudu diz: "Ontem foi quinta-feira." Só um dos quatro está enganado.* **Quem está enganado, e que dia é hoje de verdade?**
⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯ ⋯

[Inserir aqui a figura `ohj_ex_b_estrutura.svg`.]

Imagine que você transforma cada fala numa conta, uma de cada vez.

- Se amanhã é sábado, hoje é sábado menos $1$ dia, ou seja, sexta-feira.
- Beto já deu o hoje direto: sábado.
- Se depois de amanhã é domingo, hoje é domingo menos $2$ dias, ou seja, sexta-feira.
- Se ontem foi quinta-feira, hoje é quinta-feira mais $1$ dia, ou seja, sexta-feira.

Juntando as quatro contas, três delas dão sexta-feira e uma dá sábado. Como só uma pessoa pode estar enganada, o hoje verdadeiro é o dia que mais se repete, sexta-feira, e quem está enganado é Beto, o único que não bate com os outros três.

[Inserir aqui a figura `ohj_ex_b_resultado.svg`.]

***A maioria decide, não a ordem da fala***

Nesse tipo de problema não existe uma pessoa "mais confiável" só por ter falado primeiro. O que decide quem está enganado é a conta, e a conta mostra que três falas apontam para o mesmo dia enquanto uma aponta para outro. Sempre que sobrar uma única fala destoando das demais, ela é a errada.

Este capítulo juntou três tipos de pergunta sobre dias relativos. Descobrir hoje a partir de uma única fala com anteontem, ontem, amanhã ou depois de amanhã. Descobrir uma dessas palavras já sabendo qual é hoje. E, quando várias pessoas falam ao mesmo tempo, transformar cada fala numa conta e comparar os resultados para achar quem está enganado.

---

***Ilustrações***

| Arquivo | Onde entra | O que mostra |
|---|---|---|
| `ohj_linha_dias.svg` | Logo após a definição das cinco palavras | A linha com anteontem, ontem, hoje, amanhã e depois de amanhã, com hoje em destaque no centro |
| `ohj_ex_a_estrutura.svg` | Após o problema fechado de "ontem foi quinta-feira" | A pista dada (ontem = quinta-feira) e as duas perguntas (hoje e amanhã) em aberto, sem resposta |
| `ohj_ex_a_resultado.svg` | Ao final da resolução do exemplo A | A linha resolvida: quinta (ontem), sexta (hoje) e sábado (amanhã) em destaque |
| `ohj_ex_b_estrutura.svg` | Após o problema fechado dos quatro primos | As quatro falas lado a lado, sem indicar quem está certo |
| `ohj_ex_b_resultado.svg` | Ao final da resolução do exemplo B | As quatro falas convertidas em dia, com o dia da maioria em destaque e a fala de Beto marcada como a errada |
