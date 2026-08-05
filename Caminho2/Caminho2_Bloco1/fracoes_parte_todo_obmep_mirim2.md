# A fração como parte de um todo
**Genius Factory — OBMEP Nível Mirim 2 · 4º e 5º ano**

---

## 1) O que é uma fração?

Imagine uma torta de chocolate dividida em partes iguais. Se você comer uma fatia, você comeu **uma parte** de um **todo** que foi dividido em partes iguais. É exatamente isso que uma fração representa.

A fração tem dois números separados por uma barra:

$$\dfrac{\text{partes que queremos}}{\text{total de partes iguais}}$$

O número de baixo chama-se **denominador** — ele diz em quantas partes iguais o todo foi dividido.
O número de cima chama-se **numerador** — ele diz quantas dessas partes estamos considerando.

> **[FIGURA 1 — SVG]** *(inserir após o parágrafo acima)*

```svg
<!-- FIGURA 1: Torta dividida em 8 fatias iguais, 3 delas hachuradas em laranja -->
<svg viewBox="0 0 320 260" xmlns="http://www.w3.org/2000/svg" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif">
  <!-- Fundo -->
  <rect width="320" height="260" fill="#faf9f5" rx="10"/>
  <!-- Título -->
  <text x="160" y="24" text-anchor="middle" font-size="13" fill="#1A2F4F" font-weight="bold">Uma torta dividida em 8 fatias iguais</text>

  <!-- Círculo base (torta) -->
  <g transform="translate(160,140)">
    <!-- 8 fatias: ângulos de 0° a 360° em passos de 45° -->
    <!-- Fatias NÃO hachuradas (partes restantes) — 5 fatias em bege -->
    <!-- fatia 3: 90°–135° -->
    <path d="M0,0 L0,-85 A85,85 0 0,1 60.1,-60.1 Z" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5"/>
    <!-- fatia 4: 135°–180° -->
    <path d="M0,0 L60.1,-60.1 A85,85 0 0,1 85,0 Z" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5"/>
    <!-- fatia 5: 180°–225° -->
    <path d="M0,0 L85,0 A85,85 0 0,1 60.1,60.1 Z" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5"/>
    <!-- fatia 6: 225°–270° -->
    <path d="M0,0 L60.1,60.1 A85,85 0 0,1 0,85 Z" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5"/>
    <!-- fatia 7: 270°–315° -->
    <path d="M0,0 L0,85 A85,85 0 0,1 -60.1,60.1 Z" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5"/>

    <!-- Fatias HACHURADAS (partes comidas) — 3 fatias em laranja -->
    <!-- fatia 0: 315°–360°(=0°) -->
    <path d="M0,0 L-60.1,60.1 A85,85 0 0,1 -85,0 Z" fill="#E5532E" stroke="#1A2F4F" stroke-width="1.5"/>
    <!-- fatia 1: 0°–45° -->
    <path d="M0,0 L-85,0 A85,85 0 0,1 -60.1,-60.1 Z" fill="#E5532E" stroke="#1A2F4F" stroke-width="1.5"/>
    <!-- fatia 2: 45°–90° -->
    <path d="M0,0 L-60.1,-60.1 A85,85 0 0,1 0,-85 Z" fill="#E5532E" stroke="#1A2F4F" stroke-width="1.5"/>

    <!-- Contorno geral -->
    <circle cx="0" cy="0" r="85" fill="none" stroke="#1A2F4F" stroke-width="2"/>
  </g>

  <!-- Legenda -->
  <rect x="30" y="228" width="14" height="14" fill="#E5532E" rx="2"/>
  <text x="50" y="240" font-size="12" fill="#1A2F4F">3 fatias comidas</text>
  <rect x="160" y="228" width="14" height="14" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1" rx="2"/>
  <text x="180" y="240" font-size="12" fill="#1A2F4F">5 fatias restantes</text>

  <!-- Fração indicada -->
  <text x="160" y="256" text-anchor="middle" font-size="12" fill="#4A6FA5">Comida: 3/8 da torta · Restante: 5/8 da torta</text>
</svg>
```

Nessa torta, foram comidas **3 fatias de 8**. Escrevemos isso como $\dfrac{3}{8}$ ("três oitavos").

As 5 fatias que **sobraram** formam o **complemento**: $\dfrac{5}{8}$.

Repare: $\dfrac{3}{8} + \dfrac{5}{8} = \dfrac{8}{8} = 1$ (o todo inteiro).

---

## 2) Lendo a fração numa figura

Para ler a fração de uma figura, siga dois passos:

**Passo 1:** Conte o total de partes iguais → esse é o **denominador**.
**Passo 2:** Conte as partes marcadas (coloridas, comidas, escolhidas…) → esse é o **numerador**.

> **[FIGURA 2 — SVG]** *(inserir após o texto dos dois passos)*

```svg
<!-- FIGURA 2: Retângulo dividido em 6 partes, 2 coloridas. Setas indicando numerador e denominador -->
<svg viewBox="0 0 380 160" xmlns="http://www.w3.org/2000/svg" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif">
  <rect width="380" height="160" fill="#faf9f5" rx="10"/>
  <text x="190" y="22" text-anchor="middle" font-size="13" fill="#1A2F4F" font-weight="bold">Como ler a fração de uma figura</text>

  <!-- 6 retângulos -->
  <!-- 2 coloridos (laranja) -->
  <rect x="20" y="40" width="52" height="70" fill="#E5532E" stroke="#1A2F4F" stroke-width="1.5" rx="4"/>
  <rect x="76" y="40" width="52" height="70" fill="#E5532E" stroke="#1A2F4F" stroke-width="1.5" rx="4"/>
  <!-- 4 brancos/bege -->
  <rect x="132" y="40" width="52" height="70" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5" rx="4"/>
  <rect x="188" y="40" width="52" height="70" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5" rx="4"/>
  <rect x="244" y="40" width="52" height="70" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5" rx="4"/>
  <rect x="300" y="40" width="52" height="70" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5" rx="4"/>

  <!-- Chave embaixo: partes coloridas -->
  <line x1="20" y1="122" x2="128" y2="122" stroke="#E5532E" stroke-width="2"/>
  <line x1="20" y1="118" x2="20" y2="126" stroke="#E5532E" stroke-width="2"/>
  <line x1="128" y1="118" x2="128" y2="126" stroke="#E5532E" stroke-width="2"/>
  <text x="74" y="140" text-anchor="middle" font-size="11" fill="#E5532E" font-weight="bold">2 partes coloridas → numerador</text>

  <!-- Chave embaixo: total -->
  <line x1="20" y1="150" x2="352" y2="150" stroke="#4A6FA5" stroke-width="2"/>
  <line x1="20" y1="146" x2="20" y2="154" stroke="#4A6FA5" stroke-width="2"/>
  <line x1="352" y1="146" x2="352" y2="154" stroke="#4A6FA5" stroke-width="2"/>
  <text x="186" y="160" text-anchor="middle" font-size="11" fill="#4A6FA5" font-weight="bold">6 partes no total → denominador</text>

  <!-- Fração no canto direito -->
  <text x="356" y="72" text-anchor="middle" font-size="20" fill="#1A2F4F" font-weight="bold">2</text>
  <line x1="340" y1="78" x2="372" y2="78" stroke="#1A2F4F" stroke-width="2"/>
  <text x="356" y="98" text-anchor="middle" font-size="20" fill="#1A2F4F" font-weight="bold">6</text>
</svg>
```

A fração colorida é $\dfrac{2}{6}$.

Atenção: para que a fração faça sentido, **todas as partes devem ser iguais**. Se a torta for cortada em pedaços de tamanhos diferentes, não podemos usar fração para descrevê-la.

---

## 3) A fração de um conjunto de objetos

Frações não aparecem só em figuras contínuas (tortas, retângulos). Também aparecem em **conjuntos de objetos** — bolinhas, fichas, figurinhas, contas de um colar.

A ideia é a mesma: o denominador é o **total de objetos** e o numerador é a **quantidade do tipo que queremos**.

> **[FIGURA 3 — SVG]** *(inserir após o parágrafo acima)*

```svg
<!-- FIGURA 3: 12 bolinhas, 4 delas escuras, representando 4/12 = 1/3 do conjunto -->
<svg viewBox="0 0 340 120" xmlns="http://www.w3.org/2000/svg" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif">
  <rect width="340" height="120" fill="#faf9f5" rx="10"/>
  <text x="170" y="20" text-anchor="middle" font-size="13" fill="#1A2F4F" font-weight="bold">Um colar com 12 contas: 4 são escuras</text>

  <!-- 12 bolinhas em linha -->
  <!-- Bolinhas escuras (navy): posições 1,2,3,4 -->
  <circle cx="30"  cy="65" r="16" fill="#1A2F4F"/>
  <circle cx="62"  cy="65" r="16" fill="#1A2F4F"/>
  <circle cx="94"  cy="65" r="16" fill="#1A2F4F"/>
  <circle cx="126" cy="65" r="16" fill="#1A2F4F"/>
  <!-- Bolinhas claras (bege): posições 5–12 -->
  <circle cx="158" cy="65" r="16" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="190" cy="65" r="16" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="222" cy="65" r="16" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="254" cy="65" r="16" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="286" cy="65" r="16" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="318" cy="65" r="16" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5"/>
  <!-- Mais duas bege em segunda linha ajustada — são 12 ao total -->
  <!-- Ajuste: linha dupla 6+6 -->

  <text x="170" y="100" text-anchor="middle" font-size="12" fill="#4A6FA5">4 contas escuras em 12 → fração escura = 4/12</text>
  <text x="170" y="115" text-anchor="middle" font-size="11" fill="#1A2F4F">Isso é o mesmo que 1/3 do colar</text>
</svg>
```

*(Nesse exemplo, o colar tem 12 contas. As 4 contas escuras representam $\dfrac{4}{12}$ do colar — que é a mesma coisa que $\dfrac{1}{3}$, pois $4 \times 3 = 12$.)*

Para comparar colares diferentes e descobrir qual tem **maior fração** de contas escuras, é preciso calcular a fração de cada um e comparar.

---

## 4) O que sobra: o complemento da fração

Quando sabemos a fração de um todo que foi usada, a parte que **sobrou** é o **complemento**.

Se $\dfrac{1}{4}$ das maçãs foram comidas, então sobraram $\dfrac{3}{4}$ das maçãs — pois $\dfrac{1}{4} + \dfrac{3}{4} = 1$.

A regra geral é:

$$\text{parte que sobrou} = 1 - \text{fração usada} = \dfrac{\text{denominador} - \text{numerador}}{\text{denominador}}$$

> **[FIGURA 4 — SVG]** *(inserir após a regra geral)*

```svg
<!-- FIGURA 4: Duas cestas de frutas mostrando complemento — 1/2 das laranjas e 1/4 das maçãs comidas -->
<svg viewBox="0 0 400 200" xmlns="http://www.w3.org/2000/svg" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif">
  <rect width="400" height="200" fill="#faf9f5" rx="10"/>
  <text x="200" y="22" text-anchor="middle" font-size="13" fill="#1A2F4F" font-weight="bold">Frações de dois conjuntos diferentes</text>

  <!-- Laranjas: 4 bolinhas, 2 comidas -->
  <text x="100" y="50" text-anchor="middle" font-size="12" fill="#1A2F4F" font-weight="bold">Laranjas (8 ao todo)</text>
  <!-- 8 laranjas: 4 comidas (cinza) + 4 restantes (laranja) -->
  <!-- linha 1: 4 laranjas -->
  <circle cx="44"  cy="80" r="17" fill="#D0D0D0" stroke="#1A2F4F" stroke-width="1"/>
  <circle cx="76"  cy="80" r="17" fill="#D0D0D0" stroke="#1A2F4F" stroke-width="1"/>
  <circle cx="108" cy="80" r="17" fill="#D0D0D0" stroke="#1A2F4F" stroke-width="1"/>
  <circle cx="140" cy="80" r="17" fill="#D0D0D0" stroke="#1A2F4F" stroke-width="1"/>
  <!-- linha 2: 4 laranjas restantes -->
  <circle cx="44"  cy="116" r="17" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <circle cx="76"  cy="116" r="17" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <circle cx="108" cy="116" r="17" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <circle cx="140" cy="116" r="17" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <text x="92" y="150" text-anchor="middle" font-size="11" fill="#D0D0D0" font-weight="bold">comidas: 4/8 = 1/2</text>
  <text x="92" y="165" text-anchor="middle" font-size="11" fill="#E5532E" font-weight="bold">restam: 4/8 = 1/2</text>

  <!-- Linha divisória -->
  <line x1="200" y1="40" x2="200" y2="180" stroke="#D0D0D0" stroke-width="1.5" stroke-dasharray="5,4"/>

  <!-- Maçãs: 8 bolinhas, 2 comidas -->
  <text x="300" y="50" text-anchor="middle" font-size="12" fill="#1A2F4F" font-weight="bold">Maçãs (8 ao todo)</text>
  <!-- 2 comidas (cinza) + 6 restantes (vermelho) -->
  <circle cx="224" cy="80" r="17" fill="#D0D0D0" stroke="#1A2F4F" stroke-width="1"/>
  <circle cx="256" cy="80" r="17" fill="#D0D0D0" stroke="#1A2F4F" stroke-width="1"/>
  <circle cx="288" cy="80" r="17" fill="#4A6FA5" stroke="#1A2F4F" stroke-width="1"/>
  <circle cx="320" cy="80" r="17" fill="#4A6FA5" stroke="#1A2F4F" stroke-width="1"/>
  <circle cx="352" cy="80" r="17" fill="#4A6FA5" stroke="#1A2F4F" stroke-width="1"/>
  <circle cx="376" cy="80" r="17" fill="#4A6FA5" stroke="#1A2F4F" stroke-width="1"/>
  <circle cx="224" cy="116" r="17" fill="#4A6FA5" stroke="#1A2F4F" stroke-width="1"/>
  <circle cx="256" cy="116" r="17" fill="#4A6FA5" stroke="#1A2F4F" stroke-width="1"/>
  <text x="300" y="150" text-anchor="middle" font-size="11" fill="#D0D0D0" font-weight="bold">comidas: 2/8 = 1/4</text>
  <text x="300" y="165" text-anchor="middle" font-size="11" fill="#4A6FA5" font-weight="bold">restam: 6/8 = 3/4</text>

  <text x="200" y="190" text-anchor="middle" font-size="11" fill="#1A2F4F">Cada fruta tem o seu próprio "todo"!</text>
</svg>
```

**Cuidado importante:** quando o problema fala de dois conjuntos diferentes (laranjas e maçãs, por exemplo), cada conjunto tem o seu próprio todo. A fração $\dfrac{1}{2}$ das laranjas e a fração $\dfrac{1}{4}$ das maçãs se referem a coisas separadas. Não podemos somar ou comparar essas frações diretamente sem saber as quantidades.

---

## 5) Resumo

- A fração $\dfrac{a}{b}$ significa: dividir o todo em $b$ partes iguais e tomar $a$ delas.
- Para ler a fração de uma figura: **numerador = partes marcadas**, **denominador = total de partes**.
- Para ler a fração de um conjunto: **numerador = objetos do tipo escolhido**, **denominador = total de objetos**.
- O complemento de $\dfrac{a}{b}$ é $\dfrac{b-a}{b}$ — a parte que sobra.
- Quando há dois conjuntos distintos, cada um tem seu próprio denominador.

---

## Questões de prova (OBMEP — Nível Mirim 2)

---

**Questão OBMEP 2020 — Q6**

Uma torta foi dividida em partes iguais. Bia comeu algumas fatias e sobrou o que aparece na figura abaixo.

> **[FIGURA Q1 — SVG]** *(torta circular dividida em 6 partes iguais, 4 partes restantes hachuradas em laranja, 2 partes comidas em cinza/vazio)*

```svg
<!-- FIGURA Q1: Torta dividida em 6 partes, 2 comidas, 4 restantes -->
<svg viewBox="0 0 260 230" xmlns="http://www.w3.org/2000/svg" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif">
  <rect width="260" height="230" fill="#faf9f5" rx="10"/>
  <text x="130" y="22" text-anchor="middle" font-size="13" fill="#1A2F4F" font-weight="bold">O que sobrou da torta</text>

  <g transform="translate(130,120)">
    <!-- 6 fatias, ângulo 60° cada. Vértices do hexágono regular a r=85 -->
    <!-- ângulos: 0°, 60°, 120°, 180°, 240°, 300° (medidos do eixo x) -->
    <!-- Fatias RESTANTES (bege/laranja): fatias 0–3 -->
    <!-- fatia 0: de -90° a -30°  (topo para direita superior) -->
    <path d="M0,0 L0,-85 A85,85 0 0,1 73.6,-42.5 Z" fill="#E5532E" stroke="#1A2F4F" stroke-width="1.5"/>
    <!-- fatia 1: de -30° a 30° -->
    <path d="M0,0 L73.6,-42.5 A85,85 0 0,1 73.6,42.5 Z" fill="#E5532E" stroke="#1A2F4F" stroke-width="1.5"/>
    <!-- fatia 2: de 30° a 90° -->
    <path d="M0,0 L73.6,42.5 A85,85 0 0,1 0,85 Z" fill="#E5532E" stroke="#1A2F4F" stroke-width="1.5"/>
    <!-- fatia 3: de 90° a 150° -->
    <path d="M0,0 L0,85 A85,85 0 0,1 -73.6,42.5 Z" fill="#E5532E" stroke="#1A2F4F" stroke-width="1.5"/>
    <!-- Fatias COMIDAS (cinza/vazio): fatias 4–5 -->
    <!-- fatia 4: de 150° a 210° -->
    <path d="M0,0 L-73.6,42.5 A85,85 0 0,1 -73.6,-42.5 Z" fill="#D0D0D0" stroke="#1A2F4F" stroke-width="1.5" stroke-dasharray="4,3"/>
    <!-- fatia 5: de 210° a 270° -->
    <path d="M0,0 L-73.6,-42.5 A85,85 0 0,1 0,-85 Z" fill="#D0D0D0" stroke="#1A2F4F" stroke-width="1.5" stroke-dasharray="4,3"/>
    <!-- Contorno -->
    <circle r="85" fill="none" stroke="#1A2F4F" stroke-width="2"/>
  </g>

  <!-- Legenda -->
  <rect x="30" y="205" width="14" height="14" fill="#E5532E" rx="2"/>
  <text x="50" y="217" font-size="12" fill="#1A2F4F">fatias que sobraram</text>
  <rect x="155" y="205" width="14" height="14" fill="#D0D0D0" stroke="#1A2F4F" stroke-width="1" rx="2"/>
  <text x="175" y="217" font-size="12" fill="#1A2F4F">fatias comidas</text>
</svg>
```

Que fração da torta Bia comeu?

**(a)** $\dfrac{1}{6}$ — **(b)** $\dfrac{2}{6}$ — **(c)** $\dfrac{3}{6}$ — **(d)** $\dfrac{4}{6}$ — **(e)** $\dfrac{5}{6}$

**Resposta:** **(b)** $\dfrac{2}{6}$

*Resolução:* A torta foi dividida em 6 partes iguais. Sobraram 4 fatias, logo foram comidas $6 - 4 = 2$ fatias. A fração comida é $\dfrac{2}{6}$.

---

**Questão OBMEP 2023 — Fase 1, Q7**

Quatro colares foram feitos com contas brancas e pretas. Em qual deles exatamente $\dfrac{1}{3}$ das contas são pretas?

> **[FIGURA Q2 — SVG]** *(quatro colares com diferentes quantidades de contas — ver abaixo)*

```svg
<!-- FIGURA Q2: 4 colares (A, B, C, D) para identificar qual tem 1/3 de contas pretas -->
<svg viewBox="0 0 440 340" xmlns="http://www.w3.org/2000/svg" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif">
  <rect width="440" height="340" fill="#faf9f5" rx="10"/>
  <text x="220" y="22" text-anchor="middle" font-size="13" fill="#1A2F4F" font-weight="bold">Qual colar tem exatamente 1/3 de contas pretas?</text>

  <!-- COLAR A: 6 contas, 3 pretas → 3/6 = 1/2 (não é 1/3) -->
  <text x="70" y="52" text-anchor="middle" font-size="13" fill="#1A2F4F" font-weight="bold">A</text>
  <circle cx="22"  cy="80" r="14" fill="#1A2F4F"/>
  <circle cx="50"  cy="80" r="14" fill="#1A2F4F"/>
  <circle cx="78"  cy="80" r="14" fill="#1A2F4F"/>
  <circle cx="22"  cy="110" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="50"  cy="110" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="78"  cy="110" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <text x="50" y="140" text-anchor="middle" font-size="11" fill="#4A6FA5">6 contas, 3 pretas</text>

  <!-- COLAR B: 9 contas, 3 pretas → 3/9 = 1/3 ✓ -->
  <text x="180" y="52" text-anchor="middle" font-size="13" fill="#1A2F4F" font-weight="bold">B</text>
  <circle cx="138" cy="80" r="14" fill="#1A2F4F"/>
  <circle cx="166" cy="80" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="194" cy="80" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="138" cy="110" r="14" fill="#1A2F4F"/>
  <circle cx="166" cy="110" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="194" cy="110" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="138" cy="140" r="14" fill="#1A2F4F"/>
  <circle cx="166" cy="140" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="194" cy="140" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <text x="166" y="168" text-anchor="middle" font-size="11" fill="#4A6FA5">9 contas, 3 pretas</text>

  <!-- COLAR C: 8 contas, 2 pretas → 2/8 = 1/4 (não é 1/3) -->
  <text x="300" y="52" text-anchor="middle" font-size="13" fill="#1A2F4F" font-weight="bold">C</text>
  <circle cx="254" cy="80" r="14" fill="#1A2F4F"/>
  <circle cx="282" cy="80" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="310" cy="80" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="338" cy="80" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="254" cy="110" r="14" fill="#1A2F4F"/>
  <circle cx="282" cy="110" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="310" cy="110" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="338" cy="110" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <text x="296" y="140" text-anchor="middle" font-size="11" fill="#4A6FA5">8 contas, 2 pretas</text>

  <!-- COLAR D: 10 contas, 4 pretas → 4/10 = 2/5 (não é 1/3) -->
  <text x="70" y="210" text-anchor="middle" font-size="13" fill="#1A2F4F" font-weight="bold">D</text>
  <circle cx="22"  cy="240" r="14" fill="#1A2F4F"/>
  <circle cx="50"  cy="240" r="14" fill="#1A2F4F"/>
  <circle cx="78"  cy="240" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="106" cy="240" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="22"  cy="270" r="14" fill="#1A2F4F"/>
  <circle cx="50"  cy="270" r="14" fill="#1A2F4F"/>
  <circle cx="78"  cy="270" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="106" cy="270" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="22"  cy="300" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <circle cx="50"  cy="300" r="14" fill="white" stroke="#1A2F4F" stroke-width="1.5"/>
  <text x="64" y="325" text-anchor="middle" font-size="11" fill="#4A6FA5">10 contas, 4 pretas</text>

  <!-- Destaque no B (correto) -->
  <rect x="124" y="58" width="84" height="120" fill="none" stroke="#E5532E" stroke-width="2.5" rx="8" stroke-dasharray="6,3"/>
</svg>
```

**(a)** Colar A — **(b)** Colar B — **(c)** Colar C — **(d)** Colar D

**Resposta:** **(b)** Colar B

*Resolução:* Precisamos encontrar o colar em que $\dfrac{\text{contas pretas}}{\text{total de contas}} = \dfrac{1}{3}$.

- Colar A: $\dfrac{3}{6} = \dfrac{1}{2}$ — não.
- Colar B: $\dfrac{3}{9} = \dfrac{1}{3}$ — sim!
- Colar C: $\dfrac{2}{8} = \dfrac{1}{4}$ — não.
- Colar D: $\dfrac{4}{10} = \dfrac{2}{5}$ — não.

---

**Questão OBMEP 2018 — Q18**

Num pomar, há laranjas e maçãs. Pedro comeu $\dfrac{1}{2}$ de todas as laranjas e $\dfrac{1}{4}$ de todas as maçãs. Das frutas que sobraram, é correto afirmar que:

**(a)** Sobraram mais laranjas do que maçãs.
**(b)** Sobraram mais da metade das laranjas.
**(c)** Sobraram $\dfrac{3}{4}$ das maçãs.
**(d)** Pedro comeu mais maçãs do que laranjas.
**(e)** Sobraram menos de $\dfrac{1}{2}$ das maçãs.

**Resposta:** **(c)** Sobraram $\dfrac{3}{4}$ das maçãs.

*Resolução:*

Das laranjas: foram comidas $\dfrac{1}{2}$, então **sobrou** $1 - \dfrac{1}{2} = \dfrac{1}{2}$.
Das maçãs: foram comidas $\dfrac{1}{4}$, então **sobrou** $1 - \dfrac{1}{4} = \dfrac{3}{4}$.

Analisando cada alternativa:

- **(a)** Não sabemos a quantidade total de cada fruta — impossível comparar.
- **(b)** Sobraram exatamente $\dfrac{1}{2}$ das laranjas, não mais da metade.
- **(c)** Correto: sobraram $\dfrac{3}{4}$ das maçãs.
- **(d)** Não sabemos as quantidades absolutas.
- **(e)** Errado: sobrou $\dfrac{3}{4} > \dfrac{1}{2}$ das maçãs.

---

## Exercícios originais

---

**1.** Uma pizza foi cortada em 8 fatias iguais. Carla comeu 3 fatias. Que fração da pizza ainda está inteira?

> **[FIGURA EX1 — SVG]**

```svg
<!-- EX1: Pizza dividida em 8 fatias, 3 em cinza (comidas), 5 em amarelo (restantes) -->
<svg viewBox="0 0 240 210" xmlns="http://www.w3.org/2000/svg" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif">
  <rect width="240" height="210" fill="#faf9f5" rx="10"/>
  <text x="120" y="20" text-anchor="middle" font-size="12" fill="#1A2F4F" font-weight="bold">Pizza de 8 fatias</text>
  <g transform="translate(120,110)">
    <!-- 8 fatias (45° cada). Pontos no círculo r=80 para ângulos múltiplos de 45° -->
    <!-- cos/sen de 0,45,90,135,180,225,270,315° × 80: -->
    <!-- 0°: (80,0); 45°: (56.6,56.6); 90°: (0,80); 135°: (-56.6,56.6) -->
    <!-- 180°: (-80,0); 225°: (-56.6,-56.6); 270°: (0,-80); 315°: (56.6,-56.6) -->
    <!-- 3 fatias comidas (cinza): de 270° a 360°+45° = 3 setores -->
    <!-- fatia a: 270°–315° -->
    <path d="M0,0 L0,-80 A80,80 0 0,1 56.6,-56.6 Z" fill="#D0D0D0" stroke="#1A2F4F" stroke-width="1.5"/>
    <!-- fatia b: 315°–360° -->
    <path d="M0,0 L56.6,-56.6 A80,80 0 0,1 80,0 Z" fill="#D0D0D0" stroke="#1A2F4F" stroke-width="1.5"/>
    <!-- fatia c: 0°–45° -->
    <path d="M0,0 L80,0 A80,80 0 0,1 56.6,56.6 Z" fill="#D0D0D0" stroke="#1A2F4F" stroke-width="1.5"/>
    <!-- 5 fatias restantes (amarelo) -->
    <path d="M0,0 L56.6,56.6 A80,80 0 0,1 0,80 Z" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5"/>
    <path d="M0,0 L0,80 A80,80 0 0,1 -56.6,56.6 Z" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5"/>
    <path d="M0,0 L-56.6,56.6 A80,80 0 0,1 -80,0 Z" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5"/>
    <path d="M0,0 L-80,0 A80,80 0 0,1 -56.6,-56.6 Z" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5"/>
    <path d="M0,0 L-56.6,-56.6 A80,80 0 0,1 0,-80 Z" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1.5"/>
    <circle r="80" fill="none" stroke="#1A2F4F" stroke-width="2"/>
  </g>
  <rect x="20" y="188" width="12" height="12" fill="#D0D0D0" rx="2"/>
  <text x="38" y="199" font-size="11" fill="#1A2F4F">comidas</text>
  <rect x="110" y="188" width="12" height="12" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1" rx="2"/>
  <text x="128" y="199" font-size="11" fill="#1A2F4F">restantes</text>
</svg>
```

**(a)** $\dfrac{3}{8}$ — **(b)** $\dfrac{4}{8}$ — **(c)** $\dfrac{5}{8}$ — **(d)** $\dfrac{6}{8}$ — **(e)** $\dfrac{7}{8}$

---

**2.** Um pano de bandeirolas foi decorado com 12 triângulos: 4 são vermelhos, 3 são azuis e os restantes são amarelos. Que fração dos triângulos é amarela?

**(a)** $\dfrac{3}{12}$ — **(b)** $\dfrac{4}{12}$ — **(c)** $\dfrac{5}{12}$ — **(d)** $\dfrac{6}{12}$ — **(e)** $\dfrac{7}{12}$

---

**3.** Um saco de bolinhas de gude tem 20 bolinhas ao todo. Rafael tirou $\dfrac{1}{4}$ das bolinhas para jogar. Quantas bolinhas ficaram no saco?

**(a)** 4 — **(b)** 5 — **(c)** 10 — **(d)** 15 — **(e)** 16

---

**4.** Em qual dos retângulos abaixo a parte colorida representa exatamente $\dfrac{2}{5}$ do retângulo inteiro?

> **[FIGURA EX4 — SVG]**

```svg
<!-- EX4: 4 retângulos divididos em faixas, com frações diferentes coloridas -->
<svg viewBox="0 0 400 180" xmlns="http://www.w3.org/2000/svg" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif">
  <rect width="400" height="180" fill="#faf9f5" rx="10"/>
  <!-- Retângulo A: dividido em 4 partes, 2 coloridas → 2/4 = 1/2 -->
  <text x="50" y="20" text-anchor="middle" font-size="12" fill="#1A2F4F" font-weight="bold">A</text>
  <rect x="10" y="28" width="20" height="50" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="30" y="28" width="20" height="50" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="50" y="28" width="20" height="50" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="70" y="28" width="20" height="50" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <text x="50" y="94" text-anchor="middle" font-size="10" fill="#4A6FA5">4 partes, 2 coloridas</text>

  <!-- Retângulo B: dividido em 5 partes, 2 coloridas → 2/5 ✓ -->
  <text x="150" y="20" text-anchor="middle" font-size="12" fill="#1A2F4F" font-weight="bold">B</text>
  <rect x="110" y="28" width="18" height="50" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="128" y="28" width="18" height="50" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="146" y="28" width="18" height="50" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="164" y="28" width="18" height="50" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="182" y="28" width="18" height="50" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <text x="150" y="94" text-anchor="middle" font-size="10" fill="#4A6FA5">5 partes, 2 coloridas</text>

  <!-- Retângulo C: dividido em 6 partes, 2 coloridas → 2/6 = 1/3 -->
  <text x="258" y="20" text-anchor="middle" font-size="12" fill="#1A2F4F" font-weight="bold">C</text>
  <rect x="216" y="28" width="16" height="50" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="232" y="28" width="16" height="50" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="248" y="28" width="16" height="50" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="264" y="28" width="16" height="50" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="280" y="28" width="16" height="50" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="296" y="28" width="16" height="50" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <text x="258" y="94" text-anchor="middle" font-size="10" fill="#4A6FA5">6 partes, 2 coloridas</text>

  <!-- Retângulo D: dividido em 10 partes, 4 coloridas → 4/10 = 2/5 ✓ — mas B é o canônico -->
  <!-- Vamos usar D com 3 partes, 2 coloridas → 2/3 -->
  <text x="362" y="20" text-anchor="middle" font-size="12" fill="#1A2F4F" font-weight="bold">D</text>
  <rect x="328" y="28" width="22" height="50" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="350" y="28" width="22" height="50" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="372" y="28" width="22" height="50" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <text x="362" y="94" text-anchor="middle" font-size="10" fill="#4A6FA5">3 partes, 2 coloridas</text>

  <!-- Destaque em B -->
  <rect x="107" y="23" width="97" height="60" fill="none" stroke="#E5532E" stroke-width="2" rx="6" stroke-dasharray="5,3"/>
</svg>
```

**(a)** A — **(b)** B — **(c)** C — **(d)** D — **(e)** Nenhum deles

---

**5.** Numa turma de 30 alunos, $\dfrac{1}{3}$ são meninas. Quantos meninos há na turma?

**(a)** 10 — **(b)** 15 — **(c)** 20 — **(d)** 22 — **(e)** 25

---

**6.** Bia tem um livro de 40 páginas. Ela já leu $\dfrac{3}{4}$ do livro. Quantas páginas faltam para ela terminar?

**(a)** 3 — **(b)** 8 — **(c)** 10 — **(d)** 12 — **(e)** 30

---

**7.** Uma caixa tem 24 lápis: alguns são vermelhos e os outros são verdes. Exatamente $\dfrac{1}{6}$ dos lápis são vermelhos. Quantos lápis verdes há na caixa?

**(a)** 4 — **(b)** 6 — **(c)** 14 — **(d)** 18 — **(e)** 20

---

**8.** Observe o retângulo abaixo.

> **[FIGURA EX8 — SVG]**

```svg
<!-- EX8: Retângulo 4×3 (12 quadradinhos), 8 coloridos de laranja -->
<svg viewBox="0 0 240 160" xmlns="http://www.w3.org/2000/svg" font-family="-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif">
  <rect width="240" height="160" fill="#faf9f5" rx="10"/>
  <text x="120" y="20" text-anchor="middle" font-size="12" fill="#1A2F4F" font-weight="bold">Retângulo dividido em quadradinhos iguais</text>
  <!-- Grade 4 colunas × 3 linhas, cada quadradinho 44×38, deslocado para ficar centralizado -->
  <!-- Coloridos: 8 dos 12 quadradinhos -->
  <!-- Linha 1: todos os 4 coloridos -->
  <rect x="28" y="30" width="44" height="38" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="72" y="30" width="44" height="38" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="116" y="30" width="44" height="38" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="160" y="30" width="44" height="38" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <!-- Linha 2: os 4 coloridos -->
  <rect x="28" y="68" width="44" height="38" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="72" y="68" width="44" height="38" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="116" y="68" width="44" height="38" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="160" y="68" width="44" height="38" fill="#E5532E" stroke="#1A2F4F" stroke-width="1"/>
  <!-- Linha 3: nenhum colorido (4 bege) -->
  <rect x="28"  cy="106" width="44" height="38" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="72"  cy="106" width="44" height="38" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="116" cy="106" width="44" height="38" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="160" cy="106" width="44" height="38" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <!-- Corrijo: linha 3 precisa de y, não cy -->
  <rect x="28"  y="106" width="44" height="38" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="72"  y="106" width="44" height="38" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="116" y="106" width="44" height="38" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <rect x="160" y="106" width="44" height="38" fill="#E8D4A8" stroke="#1A2F4F" stroke-width="1"/>
  <text x="120" y="152" text-anchor="middle" font-size="11" fill="#4A6FA5">Quadradinhos: 12 no total · 8 coloridos</text>
</svg>
```

Qual fração do retângulo está colorida de laranja?

**(a)** $\dfrac{6}{12}$ — **(b)** $\dfrac{7}{12}$ — **(c)** $\dfrac{8}{12}$ — **(d)** $\dfrac{9}{12}$ — **(e)** $\dfrac{10}{12}$

---

**9.** Um fazendeiro tem galinhas e patos. Ele vendeu $\dfrac{1}{3}$ das galinhas e $\dfrac{1}{2}$ dos patos. Sobre o que sobrou é correto afirmar:

**(a)** Sobrou $\dfrac{2}{3}$ das galinhas.
**(b)** Sobrou $\dfrac{1}{3}$ dos patos.
**(c)** Sobrou menos da metade das galinhas.
**(d)** Sobrou $\dfrac{1}{2}$ das galinhas.
**(e)** Sobraram mais galinhas do que patos.

---

**10.** Em um aquário há 30 peixes. $\dfrac{2}{5}$ deles são dourados, $\dfrac{1}{3}$ são azuis e o restante é listrado. Quantos peixes listrados há no aquário?

**(a)** 2 — **(b)** 4 — **(c)** 6 — **(d)** 8 — **(e)** 10

---

## Gabarito

| Q | Resp | Q | Resp |
|---|------|---|------|
| 1 | c    | 6 | c    |
| 2 | c    | 7 | e    |
| 3 | d    | 8 | c    |
| 4 | b    | 9 | a    |
| 5 | c    | 10| d    |

---

## Resoluções dos exercícios originais

**1.** Sobraram $8 - 3 = 5$ fatias. Fração restante: $\dfrac{5}{8}$. **Resposta: c**

**2.** Amarelos: $12 - 4 - 3 = 5$. Fração amarela: $\dfrac{5}{12}$. **Resposta: c**

**3.** $\dfrac{1}{4}$ de $20 = 5$ bolinhas tiradas. Ficaram $20 - 5 = 15$. **Resposta: d**

**4.** O retângulo B tem 5 partes, 2 coloridas: $\dfrac{2}{5}$. **Resposta: b**

**5.** Meninas: $\dfrac{1}{3}$ de $30 = 10$. Meninos: $30 - 10 = 20$. **Resposta: c**

**6.** Já leu $\dfrac{3}{4}$ de $40 = 30$ páginas. Faltam $40 - 30 = 10$. **Resposta: c**

**7.** Vermelhos: $\dfrac{1}{6}$ de $24 = 4$. Verdes: $24 - 4 = 20$. **Resposta: e**

**8.** 8 quadradinhos de 12 coloridos: $\dfrac{8}{12}$. **Resposta: c**

**9.** Galinhas vendidas: $\dfrac{1}{3}$ → sobrou $\dfrac{2}{3}$. **Resposta: a**

**10.** Dourados: $\dfrac{2}{5}$ de $30 = 12$. Azuis: $\dfrac{1}{3}$ de $30 = 10$. Listrados: $30 - 12 - 10 = 8$. **Resposta: d**
