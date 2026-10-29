# Módulo 04 — Mercado e economia

> ⏱ Leitura: ~35 min · Pré-requisito: [Módulos 01–03](01-fundamentos.md)

## Objetivos de aprendizado

1. Entender o tamanho, a estrutura e a concentração do mercado.
2. Saber como os preços são formados e por que existe um "preço chinês" e um "preço ocidental".
3. Conhecer os vetores de demanda até 2035.
4. Ler a economia de um projeto: capex, opex, VPL e as fases de estudo até a FID.

---

## 1. Um mercado pequeno em dinheiro e gigante em importância

- A produção mundial de mina foi de ~**390.000 t REO em 2025** (USGS 2026), com a China em ~69%.
- Em valor, o mercado de óxidos é **pequeno** perto de cobre ou minério de ferro: algumas dezenas de bilhões de dólares por ano, conforme o preço (⚠️ as estimativas variam muito por fonte e por elo da cadeia).
- Mas os ETRs **habilitam** cadeias de trilhões: carros elétricos, eólica, defesa, robótica e eletrônicos. A falta de alguns gramas de Dy para um motor para uma linha de montagem inteira, como aconteceu em 2025 com os controles chineses.

> 💡 **A grande ideia econômica:** terras raras são um mercado **pequeno, concentrado e geopolítico**. Um único comprador ou vendedor (o Estado chinês) consegue mover o preço. Isso torna o investimento privado ocidental **arriscado sem apoio estatal**, e explica os pisos de preço e os financiamentos governamentais de 2025–2026.

## 2. Concentração por elo (IEA)

| Elo | Participação da China (2024) | Projeção da IEA para fora da China |
|---|---|---|
| Mineração (terras magnéticas) | ~60% | Capacidade planejada atende ~50% da demanda de 2035 |
| Refino e separação | ~91% (algumas fontes falam em ~85% em 2025) | ~25% da demanda de 2035 |
| Ímãs sinterizados | ~94% (era ~50% em 2005) | **Bem abaixo de 20%** da demanda de 2035 |

**Leitura:** quanto mais a jusante, maior a dependência da China. A IEA estima que a demanda de terras magnéticas **fora da China cresce ~50% até 2035**, puxada sobretudo por veículos elétricos.

## 3. Formação de preços

### 3.1 Não existe "bolsa" de terras raras

Os ETRs **não são negociados em bolsa** como cobre (LME) ou ouro. Os preços vêm de:
- **Agências de preço** (*Price Reporting Agencies*): Shanghai Metals Market (SMM), Asian Metal, Fastmarkets, Benchmark Mineral Intelligence, Argus. Elas coletam negócios e cotações e publicam avaliações.
- **Contratos bilaterais** (offtake) entre minerador e comprador, geralmente indexados a uma dessas avaliações, com descontos e prêmios.
- **Bolsas chinesas regionais** (Baotou, Ganzhou) com liquidez limitada.

### 3.2 Preço chinês × preço "ex-China" (out/2026)

| Referência | Valor |
|---|---|
| Óxido de NdPr, China (SMM, 27/10/2026) | ¥ 720.500/t ≈ **US$ 101/kg** |
| Óxido de NdPr, fora da China (estimativa REEx, out/2026) | ≈ **US$ 125–140/kg** |
| Piso de política dos EUA (DoD–MP; governo dos EUA–Lynas) | **US$ 110/kg** |

Fontes: [tabela de empresas, seção 3](anexos/tabela-empresas.md#3-preços-de-referência-out2026).

**Por que existem dois preços?** Os controles de exportação chineses fragmentaram o mercado. Compradores ocidentais pagam **prêmio por origem não chinesa** (segurança de suprimento, exigências de defesa, regras de conteúdo). Mesmo assim, as fontes divergem bastante sobre o tamanho do prêmio, e houve meses em 2026 em que o preço ex-China ficou **abaixo** do piso de US$ 110/kg por excesso de oferta pontual (Benchmark).

### 3.3 O piso de US$ 110/kg: o "preço de política"

Em jul/2025, o DoD dos EUA garantiu à MP Materials um **piso de US$ 110/kg de NdPr por 10 anos**: o governo paga a diferença quando o mercado fica abaixo e fica com 30% do ganho acima do piso depois que a fábrica 10X atinge a capacidade. Em 2026 o governo americano estendeu um piso semelhante à Lynas (compra de produto). Esse número virou a **premissa padrão** dos estudos de viabilidade ocidentais, Caldeira inclusive. Pergunta crítica para qualquer analista: *o projeto fecha sem o piso?*

### 3.4 Histórico de volatilidade

- **2010–2011:** embargo informal ao Japão, e alguns óxidos sobem mais de 10×.
- **2012–2016:** colapso. A Molycorp quebra.
- **2021–2022:** boom de veículos elétricos, e o NdPr passa dos US$ 150/kg (pico).
- **2023–2024:** queda com a sobreoferta chinesa (cotas crescentes).
- **2025–2026:** controles de exportação, separação de preços China × ex-China e pisos estatais.

> **Lição para empreendedores e investidores:** o preço de ETR é **cíclico e manipulável**. Modelos de negócio que dependem só do preço do óxido são frágeis. Software e serviços que vendem **produtividade e conformidade** sofrem menos com o ciclo (módulo 10).

## 4. Demanda: os vetores até 2035

| Vetor | Peso | Comentário |
|---|---|---|
| **Veículos elétricos** | Maior | Motores síncronos de ímã permanente dominam. Montadoras testam motores sem ETR, mas com perda de eficiência e densidade |
| **Eólica** | Alto | Sobretudo offshore com *direct-drive*. Sensível a leilões e juros |
| **Robótica e humanoides** | Emergente, crescimento explosivo | Cada atuador usa um ímã. É uma "nova perna" de demanda em 2026 |
| **Drones e defesa** | Alto (estratégico) | Pouco volume, prioridade absoluta, base dos pisos estatais |
| **Eletrônicos e industrial** | Estável | Motores eficientes (normas IE4/IE5), HVAC, bombas |
| **Catalisadores, vidro e polimento** | Estável | Consomem La e Ce, os elementos "em excesso" |

**Riscos de demanda:** substituição (motores de indução, de relutância, ímãs de ferrite ou de nitreto de ferro), redução de Dy e Tb por engenharia e reciclagem.

## 5. Economia de um projeto de mineração de ETR

### 5.1 Fases de estudo e precisão

```
Exploração → Estimativa de recurso → Estudo de escopo (±35-50%) → PFS (±20-25%)
→ DFS/FS (±10-15%) → Licenças (LP → LI → LO no Brasil) → Financiamento + offtakes
→ FID (decisão final de investimento) → Construção (2-3 anos) → Ramp-up (1-3 anos)
```
Do primeiro furo à produção plena são tipicamente **10 a 15 anos** no mundo e **5 a 10** nos casos acelerados de argila iônica no Brasil.

### 5.2 Métricas que você precisa saber ler

| Métrica | O que é | Exemplo brasileiro |
|---|---|---|
| **Capex** | Investimento inicial | Caldeira ≈ US$ 498 mi. BRE ≈ US$ 969 mi (escopo) |
| **Opex / custo unitário** | Custo por kg de TREO ou NdPr | Comparar com o preço chinês |
| **VPL (NPV) e taxa** | Valor presente dos fluxos (taxas de 8–10%) | BRE: VPL8 de US$ 6 bi (escopo, ±40%) |
| **TIR (IRR)** | Retorno do projeto | BRE: 90% (escopo). Desconfie de TIR muito alta em estudo preliminar |
| **Payback** | Anos para recuperar o capex | Caldeira: ~2,5 anos (premissa de US$ 110/kg) |
| **Premissa de preço** | Preço de NdPr, Dy e Tb usado | **Sempre verifique.** Muitos estudos usam projeções de agências acima do spot |
| **Pagabilidade do MREC** | % do valor contido que o comprador paga | Decisiva para minas que vendem só intermediário |
| **Intensidade de capex** | Capex por t/ano de capacidade | Comparar projetos de escalas diferentes |

### 5.3 Como uma mina de argila iônica ganha dinheiro (modelo mental)

```
Receita = Toneladas de argila × Teor (ppm TREO) × Recuperação × Cesta (US$/kg) × Pagabilidade
Custos  = Lavra + Reagentes (MgSO₄, carbonato, ácido) + Energia + Água + Rejeito + Pessoal + Logística + Royalties (CFEM)
```
Os grandes "botões" são **recuperação, cesta (proporção de pesados) e pagabilidade**. Uma melhora de 5 pontos percentuais na recuperação pode valer dezenas de milhões de dólares por ano. É aqui que o software de otimização de processo se paga.

### 5.4 Financiamento

| Fonte | Exemplo |
|---|---|
| Equity em bolsa (ASX, TSX) | O caminho das juniores (diluição frequente) |
| Investidor estratégico | OneIM na Viridis, POSCO International (MoU com a Meteoric) |
| **Agências estatais estrangeiras** | **DFC (EUA)**: US$ 565 mi para a Serra Verde. EXIM, JOGMEC (Japão), EFA (Austrália) |
| Bancos de desenvolvimento brasileiros | BNDES/Finep (chamada de minerais estratégicos). O BNDES negocia financiamento e possível participação na Caldeira |
| Offtake pré-pago | A Apple na MP. O SPV americano na Serra Verde |
| Fusões e aquisições | USA Rare Earth → Serra Verde (US$ 2,8 bi). Lynas → Meteoric (A$ 968 mi) |

---

## Pontos-chave

- Mercado **pequeno em valor e crítico em função**, com concentração extrema na China, maior quanto mais a jusante.
- **Não há bolsa.** Os preços vêm de agências e contratos. Em 2026 existem dois mundos de preço: China (~US$ 100/kg de NdPr) e ex-China (prêmio variável).
- O **piso de US$ 110/kg** do governo dos EUA virou a âncora dos projetos ocidentais. Pergunte sempre se o projeto fecha sem ele.
- A demanda cresce com veículos elétricos, eólica, robótica e defesa, com risco de substituição e de reciclagem.
- A economia de mina de argila iônica depende de **recuperação, cesta e pagabilidade**. São os alvos naturais de tecnologia.
- O capital vem cada vez mais de **Estados** (EUA, Japão, Austrália, Brasil) e de M&A estratégico.

## Conexão com MiningTech

- **Inteligência de mercado e preços:** um painel de preços ex-China, de contratos e de pagabilidade. As agências são caras e opacas.
- **Modelagem econômica de projetos:** ferramentas que ligam o modelo geológico e metalúrgico ao VPL, com análise de sensibilidade a preço e recuperação. Útil para juniores, bancos (BNDES) e investidores.
- **Otimização da recuperação:** cada ponto percentual vale milhões.

## Referências

1. USGS — *Mineral Commodity Summaries 2026*. https://www.usgs.gov/centers/national-minerals-information-center/rare-earths-statistics-and-information
2. IEA — *Rare Earth Elements: Pathways…* (2024–2025). https://iea.blob.core.windows.net/assets/88d2b060-4c5b-46cc-8727-c60576cb937d/RareearthelementsPathwaystosecureanddiversifiedsupplychains.pdf
3. IEA — "With new export controls on critical minerals, supply concentration risks become reality". https://www.iea.org/commentaries/with-new-export-controls-on-critical-minerals-supply-concentration-risks-become-reality
4. SMM — Pr-Nd Oxide. https://www.metal.com/rare-earth-oxides/201102250162
5. Rare Earth Exchanges — preços de out/2026. https://rareearthexchanges.com/rare-earth-prices/
6. Benchmark — "Ex-China NdPr prices slip below $110/kg price floor on oversupply". https://source.benchmarkminerals.com/article/ex-china-ndpr-prices-slip-below-110-kg-price-floor-as-oversupply-builds
7. MP Materials — parceria com o DoD. https://mpmaterials.com/news/mp-materials-announces-transformational-public-private-partnership-with-the-department-of-defense-to-accelerate-u-s-rare-earth-magnet-independence/
8. Clarim Araxá / Brasil 247 — BNDES negocia o financiamento da Caldeira. https://www.brasil247.com/negocios/bndes-negocia-financiamento-para-projeto-de-r-26-bilhoes-de-terras-raras-em-minas
9. Dados de projetos: [anexos/tabela-empresas.md](anexos/tabela-empresas.md).

*Acessos em 29/10/2026.*
