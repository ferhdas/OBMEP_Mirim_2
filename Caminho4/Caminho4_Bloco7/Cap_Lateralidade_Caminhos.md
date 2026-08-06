# Achar o caminho

> Trilha Mirim 2 (4º e 5º anos) · Caminho 4 · Bloco 7 · Achar o caminho. Nó da grade: Geometria › Percepção Espacial no Plano › Lateralidade e Rastreamento de Trajetos (subnó proposto, ver `Classificacao_Lateralidade_Caminhos.md`).

Este capítulo é sobre percorrer e comparar trajetos. Entre duas rotas diferentes até um mesmo lugar, como saber qual é mais curta sem se deixar enganar pelo desenho? Depois de várias viradas à esquerda e à direita, para que lado alguém acaba olhando? E quando vários tubos se cruzam no papel, como saber por qual saída cada bola sai? As três perguntas são sobre seguir um trajeto com cuidado, sem se perder nos cruzamentos nem nas aparências.

***O caminho mais curto se acha somando os trechos, não olhando o desenho***

Quando existem duas ou mais rotas diferentes ligando os mesmos dois lugares, cada uma feita de vários trechos retos, a rota mais curta é a que tem a menor soma de trechos. Uma rota que parece mais direta no papel pode, na verdade, ser mais longa do que uma rota com mais curvas.

**Exemplo 1:** Duas rotas ligam a escola ao circo. A rota A tem três trechos, de $40$, $25$ e $30$ metros. A rota B tem três trechos, de $35$, $45$ e $20$ metros. **Qual rota é mais curta?**

[Inserir aqui a figura `cam_rotas_estrutura.svg`.]

Somamos os trechos de cada rota, separadamente.

$40 + 25 + 30 = 95$

$35 + 45 + 20 = 100$

A rota A mede $95$ metros, e a rota B mede $100$ metros. Como $95$ é menor que $100$, a rota A é mais curta, mesmo que as duas rotas tenham o mesmo número de trechos.

[Inserir aqui a figura `cam_rotas_resultado.svg`.]

**Guarde. O número de curvas de uma rota não diz nada sobre o comprimento dela. A única forma segura de comparar duas rotas é somar os trechos de cada uma e comparar os totais.**

***Contar viradas para a esquerda e para a direita mostra para onde alguém termina olhando***

Cada virada à direita gira um quarto de volta ($90°$) num sentido, e cada virada à esquerda gira um quarto de volta no sentido oposto. Para saber para que lado alguém está olhando depois de várias viradas, a régua de ouro é contar quantas viradas foram para cada lado: cada virada à direita cancela uma virada à esquerda. Só a diferença entre as duas contagens decide o resultado final, não importa a ordem em que as viradas aconteceram.

**Exemplo 2:** Uma pessoa caminha de casa até a escola, virando $4$ vezes à esquerda e $2$ vezes à direita ao todo, na ordem que for. Ela começou o percurso olhando para o Norte. **Para que lado ela está olhando quando chega à escola?**

[Inserir aqui a figura `cam_viradas_estrutura.svg`.]

Cada virada à direita cancela uma virada à esquerda. Com $4$ viradas à esquerda e $2$ à direita, $2$ delas se cancelam entre si, e sobram viradas à esquerda sem par.

$4 - 2 = 2$

Sobram $2$ viradas à esquerda sem cancelar, e $2$ viradas de um quarto de volta cada uma somam meia volta.

$2 \times 90 = 180$

Uma meia volta a partir do Norte aponta para o lado exatamente oposto: o Sul.

Ela chega à escola olhando para o Sul. Conferimos porque meia volta, não importa para que lado, sempre aponta para o lado oposto de onde a pessoa começou, do mesmo jeito que uma meia volta numa pista circular leva um ponto para o lado oposto do centro.

[Inserir aqui a figura `cam_viradas_resultado.svg`.]

**Guarde. A ordem das viradas não importa para saber a direção final, só a diferença entre o número de viradas à esquerda e à direita. Cada par de uma virada à esquerda com uma à direita se cancela, e sobra só o que não tem par.**

***Tubos que se cruzam no papel continuam separados de verdade***

Quando vários tubos ou fios são desenhados se cruzando no papel, o cruzamento é só visual: cada tubo continua ligado à sua própria entrada e à sua própria saída, sem trocar de tubo no meio do caminho. Para saber por onde uma bola solta num tubo vai sair, é preciso seguir aquele tubo específico com o olhar, do início ao fim, ignorando os outros tubos que passam por cima ou por baixo dele.

**Exemplo 3:** Três bolas, $1$, $2$ e $3$, são soltas ao mesmo tempo em três tubos que se cruzam no meio do caminho, mas os tubos não se conectam nos cruzamentos: cada bola continua sempre no seu próprio tubo. O tubo da bola $1$ mede $60$ cm, o da bola $2$ mede $45$ cm, e o da bola $3$ mede $75$ cm. Todas as bolas viajam na mesma velocidade. **Em que ordem as três bolas saem dos tubos?**

[Inserir aqui a figura `cam_tubos_estrutura.svg`.]

Como as três bolas viajam na mesma velocidade e partem ao mesmo tempo, quem sai primeiro é quem tem o tubo mais curto para percorrer. Colocamos os três comprimentos em ordem, do menor para o maior.

$45 < 60 < 75$

O tubo da bola $2$ é o mais curto, depois vem o tubo da bola $1$, e por último o tubo da bola $3$, o mais comprido.

A ordem de saída é bola $2$, depois bola $1$, depois bola $3$. Conferimos olhando cada tubo separadamente, do início ao fim, sem deixar o cruzamento no meio do caminho confundir qual bola pertence a qual tubo.

[Inserir aqui a figura `cam_tubos_resultado.svg`.]

**Guarde. Um cruzamento desenhado no papel não é uma troca de caminho. Antes de comparar velocidades ou comprimentos, siga cada trajeto isoladamente, do começo ao fim, para não misturar um tubo com outro.**

Este capítulo reuniu três formas de raciocinar sobre trajetos. Comparar rotas somando os trechos de cada uma, não julgando pela aparência. Contar viradas à esquerda e à direita, cancelando pares, para achar a direção final. E seguir cada tubo separadamente, mesmo quando cruza outros no papel, para não confundir qual bola sai por qual saída. Nos três casos, o cuidado é o mesmo: seguir o trajeto de verdade, com atenção, em vez de confiar só na primeira impressão do desenho.

---

***Ilustrações***

| Arquivo | Onde entra | O que mostra |
|---|---|---|
| `cam_rotas_estrutura.svg` | Após o problema fechado das rotas escola-circo | As rotas A e B desenhadas, com os trechos marcados, sem os totais calculados |
| `cam_rotas_resultado.svg` | Ao final da resolução do exemplo das rotas | As duas rotas com os totais ($95$ e $100$) em destaque, e a rota A marcada como mais curta |
| `cam_viradas_estrutura.svg` | Após o problema fechado das viradas | O percurso de casa até a escola, com as viradas marcadas, sem a direção final indicada |
| `cam_viradas_resultado.svg` | Ao final da resolução do exemplo das viradas | Uma bússola mostrando a direção inicial (Norte) e a final (Sul), com a meia volta em destaque |
| `cam_tubos_estrutura.svg` | Após o problema fechado dos três tubos | Os três tubos cruzados, com as bolas nas entradas, sem a ordem de saída indicada |
| `cam_tubos_resultado.svg` | Ao final da resolução do exemplo dos tubos | Os três tubos com os comprimentos marcados e a ordem de saída ($2$, $1$, $3$) em destaque |
