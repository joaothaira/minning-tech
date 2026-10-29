# Módulo 03 — Processamento e cadeia de valor: da argila ao ímã

> ⏱ Leitura: ~35 min · Pré-requisito: [Módulos 01](01-fundamentos.md) e [02](02-geologia-e-depositos.md)

## Objetivos de aprendizado

1. Desenhar a cadeia completa: mina → concentrado → separação → metal → liga → ímã.
2. Entender por que a **separação** é o gargalo mundial.
3. Conhecer as tecnologias emergentes que podem mudar o jogo.
4. Identificar onde está o valor econômico e onde estão os riscos (resíduos, tório).

---

## 1. Visão geral da cadeia

```
 MINERAÇÃO      BENEFICIAMENTO      HIDROMETALURGIA       SEPARAÇÃO          METALURGIA        MANUFATURA
 ─────────      ──────────────      ───────────────       ─────────          ──────────        ──────────
 Lavra a céu →  Argila: desagregação → Dessorção/lixiv. →  Extração por    →  Redução a     →  Liga NdFeB   →  Ímã sinterizado
 aberto          e peneiramento        (sal ou ácido)      solvente (SX):     metal (eletró-     (strip casting)   ou bonded
                 Rocha dura: britagem, Purificação         centenas de        lise em sal                        → motor, gerador
                 moagem, flotação      Precipitação        estágios           fundido)
                                       → MREC              → óxidos 99,5%+
                                                             (NdPr, Dy, Tb, La, Ce...)
 ═══════════════════════════════════════════════════════════════════════════════════════════════════════════
 Brasil HOJE:  ████████████  (Serra Verde)  │  quase nada  │  P&D (CIT SENAI)  │  demonstração (MagBras)
 China:        ~60-70%                      │  ~85-91%     │  ~90%+            │  ~94% dos ímãs sinterizados
```
*(Participações da China segundo a IEA: 60% da mineração de terras magnéticas, 91% do refino e 94% dos ímãs sinterizados em 2024.)*

### Onde está o valor (ordem de grandeza)

O preço por kg de ETR contido **sobe a cada elo**. O concentrado misto (MREC) é vendido com **desconto relevante** sobre o valor dos óxidos contidos (pagamento de 50–75% do valor da cesta é uma faixa comum em contratos de MREC: ⚠️ varia muito por contrato). O ímã acabado vale várias vezes o óxido. É por isso que a Lei 15.506/2026 e o MagBras miram a **agregação de valor no Brasil** (módulo 05).

## 2. Etapa por etapa

### 2.1 Mineração

- **Argila iônica:** lavra rasa a céu aberto (escavadeira e caminhão), cavas de poucos metros a dezenas de metros, sem explosivos. Exige reabilitação progressiva: a cava é reaterrada e revegetada.
- **Rocha dura e carbonatito:** lavra convencional, eventualmente com desmonte por explosivos.

### 2.2 Beneficiamento

- **Argila:** desagregação, peneiramento e eventualmente classificação (para remover areia de quartzo que não carrega ETR). Isso reduz a massa que vai para a química.
- **Rocha dura:** britagem, moagem, **flotação** (bastnasita/monazita), separação magnética e gravimétrica. Gera um **concentrado mineral** (30–60% REO).
- **Ore sorting** (triagem por sensores) é uma tecnologia de pré-concentração cada vez mais usada. A BRE planeja triagem em Monte Alto.

### 2.3 Hidrometalurgia: colocar os ETRs em solução

| Rota | Para | Reagentes típicos | Observações |
|---|---|---|---|
| **Dessorção** (troca iônica) | Argila iônica | Sulfato de amônio (China, histórico) ou **sulfato de magnésio** (projetos ocidentais, sem amônio) | pH ~4–5, temperatura ambiente, em tanque (*agitated tank*) ou pilha. Rápida |
| **Cracking ácido** | Monazita, bastnasita | Ácido sulfúrico concentrado a 200–400 °C | Gera resíduos com tório |
| **Cracking alcalino** | Monazita | NaOH a quente | Rota histórica da INB/Orquima |
| **Lixiviação ácida** | Lateritas, rejeitos | HCl ou H₂SO₄ | Alto consumo de reagente quando há muitos carbonatos |

Depois vem a **purificação**: remoção de Al, Fe, U e Th por ajuste de pH. Em seguida, a **precipitação** com carbonato de sódio ou bicarbonato (→ **MREC**) ou com ácido oxálico (→ oxalato, calcinado em óxido misto).

> **MREC** é o produto que a **Serra Verde já vende** e que Caldeira e Colossus planejam vender. É um produto intermediário: quem compra ainda precisa separar.

### 2.4 Separação: o coração (e o gargalo)

**Extração por solvente (SX)** é a tecnologia dominante:
- A solução aquosa com ETRs mistos entra em contato com uma fase orgânica (querosene + um extratante como **P507/PC88A**, **D2EHPA** ou **Cyanex 272**).
- Como os ETRs vizinhos são quimicamente quase idênticos, **cada estágio separa um pouco**. O fator de separação entre lantanídeos adjacentes fica em torno de 1,5 a 5.
- Resultado: **circuitos de centenas a mais de mil misturadores-decantadores** (*mixer-settlers*) em cascata para produzir óxidos de 99,5% a 99,99%.
- O circuito leva **semanas a meses** para entrar em equilíbrio no comissionamento e é extremamente sensível a **pH, vazão, razão orgânico/aquoso, temperatura e composição da alimentação**. Se a alimentação muda (outro lote de minério), o circuito sai do ponto.

**Por que só a China domina?**
1. **Escala e aprendizado:** 40 anos operando centenas de plantas.
2. **Know-how tácito:** ajuste fino de circuitos, receitas de extratantes, controle. Desde **dez/2023 a China proíbe exportar essa tecnologia**.
3. **Custo:** padrões ambientais historicamente frouxos, ácido e energia baratos, cluster de fornecedores.
4. **Capital paciente** estatal que aguenta ciclos de preço baixo.

### 2.5 Metais e ligas

- **Nd, Pr e NdPr:** eletrólise em sal fundido de fluoretos (a ~1.000 °C), a partir do óxido.
- **Dy e Tb:** redução calciotérmica (Ca metálico) ou eletrólise.
- **Liga NdFeB:** fusão em forno de indução + *strip casting* (fitas finas, solidificadas rapidamente).
- É uma etapa de nicho fora da China. Fornecedores ocidentais: Less Common Metals (Reino Unido, hoje da USA Rare Earth), entre outros.

### 2.6 Ímãs

**Sinterizados** (os de alto desempenho):
```
Liga em fitas → decrepitação por hidrogênio (H₂ "quebra" a liga) → moagem a jato (pó de ~3-5 µm)
→ prensagem sob campo magnético (alinha os grãos) → sinterização (~1.050 °C) → tratamento térmico
→ usinagem (corte, retífica) → revestimento (Ni, epóxi, contra corrosão) → magnetização
→ [opcional] difusão de Dy/Tb nos contornos de grão
```
**Bonded** (ligados com polímero): menos potentes, moldáveis, para aplicações menores.

**Capacidade ocidental em construção** (exemplos, ver o [módulo 06](06-players-globais.md)): MP Materials (Texas), USA Rare Earth (Oklahoma), Neo (Estônia), Evolution Metals (Pohang, Coreia), VAC (EUA) e **CIT SENAI ITR** (Lagoa Santa: demonstração de ~100 t/ano).

## 3. Resíduos, tório e urânio

| Resíduo | Origem | Risco | Gestão |
|---|---|---|---|
| Rejeito de argila lixiviada | Argila iônica | Volume enorme, sulfatos e amônio residual, metais | Filtragem + *dry stacking*, retorno às cavas, neutralização |
| Resíduo de purificação (Th, U) | Todas as rotas, sobretudo monazita e carbonatito | **NORM** (material radioativo de ocorrência natural) | Controle **CNEN**. O tório é material nuclear, ligado ao monopólio da União/INB |
| Efluentes ácidos e salinos | Hidrometalurgia | Contaminação de água | Tratamento, reúso de água, circuito fechado |
| Orgânico de SX | Separação | Inflamável, tóxico | Recuperação e controle de incêndio |

A experiência chinesa (Baotou e o lago de rejeitos; contaminação em Jiangxi por lixiviação *in situ*) é o "anti-exemplo" que comunidades e reguladores citam. Licença social é um fator crítico de sucesso (módulo 08).

## 4. Tecnologias emergentes (onde a inovação está acontecendo)

| Tecnologia | Ideia | Estágio | Por que importa |
|---|---|---|---|
| **Troca iônica / cromatografia contínua** | Resinas ou colunas no lugar dos mixer-settlers | Piloto e demonstração (várias empresas nos EUA) | Menos estágios e menos orgânico, possivelmente modular |
| **Extratantes seletivos e ligantes biológicos** | Moléculas como a lanmodulina (proteína) que distinguem lantanídeos | Laboratório e piloto | Separação mais limpa |
| **Extração com membranas** | Membranas suportando o extratante | P&D | Menor inventário de solvente |
| **Recuperação in situ (ISR)** | Injetar solução no solo sem escavar | Testes (Axel REE) | Capex baixo, mas o risco ambiental é crítico (o anti-exemplo chinês) |
| **Eletroquímica e eletrólise direta** | Metal direto de soluções ou óxidos | P&D | Elimina etapas |
| **Reciclagem de ímãs** | HPMS (hidrogênio para separar ímã de sucata), hidrometalurgia de sucata | Comercial inicial (HyProMag, Ionic Technologies, Cyclic Materials, Noveon) | A UE vai exigir conteúdo reciclado (módulo 05). Historicamente menos de ~1% dos ETRs era reciclado |
| **Ímãs sem terras raras** | Nitreto de ferro (Niron), ferrites avançadas, motores de indução e de relutância | Comercial em nichos | Risco de substituição da demanda |
| **Redução de Dy e Tb** | Difusão nos contornos de grão, refino de grão | Comercial | Reduz a demanda por pesados |

---

## Pontos-chave

- A cadeia tem seis elos, e **o valor e o poder estão nos elos do meio para baixo** (separação, metal, ímã).
- O Brasil hoje **minera e produz MREC** (Serra Verde), mas quase não separa nem fabrica ímãs (só P&D e demonstração).
- A **separação por SX** exige centenas de estágios, controle fino e know-how tácito. A China domina e proibiu exportar a tecnologia.
- Tório, urânio e grandes volumes de rejeito tornam o licenciamento e a licença social críticos.
- Inovação em separação (troca iônica, cromatografia), reciclagem e ímãs alternativos pode redesenhar a cadeia na próxima década.

## Conexão com MiningTech

Este é o módulo mais rico em oportunidades de software (detalhes no [módulo 10](10-oportunidades-e-tese-de-startup.md)):
- **Simulação e gêmeo digital de circuitos SX:** projetar, comissionar e operar cascatas de centenas de estágios. Hoje isso é feito com planilhas e know-how chinês.
- **Controle avançado de processo (APC) e analisadores em linha** (XRF/ICP online, espectroscopia) para manter o circuito no ponto quando a alimentação muda.
- **Contabilidade metalúrgica e balanço de massa:** fechar o balanço de 15 elementos por estágio para provar a recuperação a financiadores e compradores.
- **Plataforma de dados de planta-piloto:** todo projeto brasileiro está em piloto (CIT SENAI, CEFET-MG, Aparecida de Goiânia, Camaçari). Os dados são caóticos e ficam em Excel.
- **Gestão de rejeitos e água:** monitoramento contínuo para órgão ambiental, CNEN e comunidade.

## Referências

1. IEA — *Global Critical Minerals Outlook 2026* e *Rare Earth Elements: Pathways…* https://www.iea.org/reports/rare-earth-elements/executive-summary
2. Xie, F. et al. (2014). "A critical review on solvent extraction of rare earths from aqueous solutions". *Minerals Engineering*, 56, 10–28.
3. Gupta, C. K.; Krishnamurthy, N. (2005). *Extractive Metallurgy of Rare Earths*. CRC Press (livro-texto de referência).
4. Ministério do Comércio da China — proibição de exportação de tecnologia de extração e separação (dez/2023), via China Briefing. https://www.china-briefing.com/news/chinas-rare-earth-export-controls-impacts-on-businesses/
5. FIEMG — MagBras e CIT SENAI ITR. https://www.fiemg.com.br/fiemg/noticias/kick-off-reune-28-empresas-e-marca-o-inicio-de-uma-iniciativa-nacional-com-investimento-de-r-73-milhoes-para-consolidar-a-cadeia-produtiva-de-imas-permanentes/
6. Brasil Mineral — "CIT SENAI ITR avança na integração da cadeia brasileira de ímãs". https://brasilmineral.com.br/revistas/460/cit-senai-itr-avanca-na-integracao-da-cadeia-brasileira-de-imas-de-terras-raras
7. Proactive Investors — BRE: triagem em Monte Alto e hidrometalurgia em Camaçari. https://www.proactiveinvestors.com/companies/news/1097159/brazilian-rare-earths-resets-rocha-da-rocha-study-around-monte-alto-with-us-6-billion-npv-1097159.html

*Acessos em 29/10/2026.*
