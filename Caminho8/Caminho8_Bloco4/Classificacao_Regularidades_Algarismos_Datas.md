Ficha de classificação · Bloco $4$ · Regularidades de algarismos e datas

Ficha de produção (uso interno), no modelo do §$3$ do Protocolo_OBMEP_v$5.5$. Cobre as duas questões de referência do bloco: `2019/Q7` (código `NA19-Q07`) e `2022/F2/Q10` (código `M2-22-F2-Q10`).

***Classificação comum às questões do bloco***

**Motor cognitivo (Apêndice A, uso interno).** Reconhecer uma regularidade que vive nos próprios algarismos de um número (um ano) ou de uma data inteira (dia, mês e ano juntos), seja a soma desses algarismos, que sobe e cai de um jeito previsível ano a ano, seja a simetria deles, quando a sequência de algarismos é igual lida das duas pontas para o centro.

**Nó principal (Apêndice D, grade oficial).** `Aritmética › Problemas com Algarismos e Criptografia Aritmética`.

**Descritores secundários.**
- Soma de algarismos com subida e queda: a soma dos algarismos de um ano sobe $1$ a cada ano, até o último algarismo chegar a $9$, e cai quando esse algarismo volta a $0$ e o algarismo vizinho sobe, o que faz a mesma soma reaparecer depois de um número de anos que precisa ser contado com cuidado, não presumido.
- Palíndromo numérico: uma sequência de algarismos é um palíndromo quando cada algarismo bate com o algarismo que fica na mesma distância da outra ponta, o $1$º com o último, o $2$º com o penúltimo, e assim por diante, até o meio.
- Construção de uma data espelhada: para uma data (dia, mês e ano) formar uma sequência de algarismos que é um palíndromo, o ano precisa ser exatamente a sequência invertida do dia e do mês juntos, o que serve tanto para verificar uma data dada quanto para construir outras datas com essa propriedade.

**Não é X (e por quê).**
- Não são os Blocos $1$, $2$ e $3$ deste Caminho, porque ali a regularidade vive numa figura que cresce ou numa estrutura de posições (um ciclo ou uma grade), enquanto aqui a regularidade vive dentro dos próprios algarismos que escrevem um número ou uma data, sem nenhuma figura envolvida.
- Não é Valor Posicional puro (Aritmética), mesmo quando a questão depende de entender que cada algarismo tem um peso diferente conforme sua posição, porque o núcleo aqui não é calcular o valor de um número a partir dos algarismos, é reconhecer um padrão (soma que se repete, ou simetria) que se repete regularmente.
- Não é Problemas com Restrições Temporais e Dias da Semana (Raciocínio Lógico), mesmo quando a questão envolve datas, porque ali o raciocínio é sobre contar dias ou semanas até um evento, e aqui o raciocínio é sobre a estrutura numérica da própria data escrita por extenso, dia, mês e ano.

**Campo de trilha.** Trilha Mirim 2 › **Caminho 8** › **Bloco 4 · Regularidades de algarismos e datas** › capítulo de teoria "Padrões nos números e no calendário" (`Cap_Regularidades_Algarismos_Datas.md`).

---

***Notas específicas de cada questão de referência***

`2019/Q7` (código `NA19-Q07`)
- **Motor aplicado:** a soma dos algarismos do ano $2019$ é $2+0+1+9=12$. Contando ano a ano, a soma sobe até $2019$ (soma $12$), cai para $4$ em $2020$ (quando o algarismo das dezenas passa de $1$ para $2$), e volta a subir, $5$ em $2021$, $6$ em $2022$, $7$ em $2023$, $8$ em $2024$, $9$ em $2025$, $10$ em $2026$, $11$ em $2027$, até $12$ de novo em $2028$. Gabarito **C ($9$ anos)** ✅, conferido contra a solução oficial (`snA-2019.pdf`, questão $7$).
- **Não é X específico:** não é uma questão de calcular uma soma só, é sobre acompanhar como essa soma muda ano a ano até encontrar de novo o mesmo valor, contando cada ano com cuidado, sem presumir que o intervalo será sempre o mesmo número de anos.

`2022/F2/Q10` (código `M2-22-F2-Q10`)
- **Motor aplicado:** a data $22/02/2022$ forma a sequência $22022022$, um palíndromo de $8$ algarismos. Entre cinco datas candidatas, $12/12/2112$, $23/02/3022$, $13/02/2031$, $21/12/1221$ e $12/21/2121$ (esta última nem é uma data válida, mês $21$ não existe), só `13/02/2031` forma a sequência $13022031$, também um palíndromo (o $1$º algarismo bate com o $8$º, ambos $1$, o $2$º com o $7$º, ambos $3$, e assim por diante). Gabarito **C ($13/02/2031$)** ✅, conferido contra a solução oficial (`sf2m2-2022.pdf`, questão $10$).
- **Não é X específico:** não basta olhar só o primeiro e o último algarismo batendo, é preciso conferir todos os pares de algarismos simétricos, o que elimina candidatas que parecem promissoras à primeira vista mas falham no meio da sequência.

---

***Cobertura nos exercícios autorais***

Os $10$ exercícios de `Lista_Exercicios_Regularidades_Algarismos_Datas.md` seguem a classificação acima:
- Exercícios $1$ a $5$: descobrir depois de quantos anos a soma dos algarismos de um ano volta a se repetir, partindo de anos diferentes, alguns cruzando uma dezena só, outros cruzando mais de uma.
- Exercícios $6$ a $10$: reconhecer, entre datas candidatas, qual forma uma sequência de algarismos igual lida dos dois lados, com exemplos dados diferentes a cada vez.
