# Módulo 09 — MiningTech: panorama global e brasileiro

> ⏱ Leitura: ~35 min · Pré-requisito: [Módulos 03](03-processamento-e-cadeia.md), [06](06-players-globais.md) e [08](08-regulacao-licenciamento-esg.md)

## Objetivos de aprendizado

1. Mapear as categorias de tecnologia em cada etapa da cadeia mineral.
2. Conhecer os incumbentes globais (e o que eles **não** cobrem em terras raras).
3. Entender o ecossistema de inovação e capital no Brasil.
4. Ter noção de tamanho de mercado e da dinâmica de vendas no setor.

---

## 1. O que é MiningTech

**MiningTech** é o conjunto de software, hardware, dados e serviços tecnológicos aplicados à cadeia mineral: exploração, lavra, processamento, logística, ESG e comercialização. É um setor **antigo**, com softwares de modelagem geológica desde os anos 1980, mas que passa por uma onda de **IA, sensores baratos, nuvem e automação**.

### Tamanho de mercado (ordens de grandeza; as estimativas divergem muito)

| Segmento | Estimativa | Fonte |
|---|---|---|
| Software de mineração (geral) | ~US$ 12–13 bi (2025–2026), crescimento de ~8%/ano | Fortune Business Insights |
| Soluções de mina digital | ~US$ 7 bi (2024) → ~US$ 15 bi (2031) | QYResearch |
| Gêmeo digital em mineração | US$ 0,2 a 2,5 bi (2025–2026), conforme a definição | TBRC / Bosson |
| Smart mining (amplo) | ~US$ 20 bi (2026) | Futurebridge |

> ⚠️ Relatórios de mercado pagos costumam inflar números e usam definições diferentes. **Não use TAM de relatório como argumento principal de um pitch.** Construa o mercado de baixo para cima: número de clientes × ticket (módulo 10).

## 2. Mapa de tecnologia por etapa da cadeia

| Etapa | Categoria | Incumbentes globais (exemplos) | Lacuna em terras raras |
|---|---|---|---|
| **Exploração** | Modelagem geológica 3D | **Seequent** (Leapfrog; Bentley), **Datamine**, **Dassault GEOVIA**, **Micromine**, Maptek | Ferramentas genéricas, pouco adaptadas a depósitos rasos e espalhados de argila |
| | Banco de dados de sondagem e QAQC | acQuire, MX Deposit (Seequent), Datashed (Datamine) | Juniores pequenas ainda usam Excel |
| | IA de prospectividade | **KoBold Metals**, Earth AI, VerAI e outras | Pouco foco em ETR e argila iônica |
| | Geofísica e sensoriamento | Fornecedores de aerolevantamento, satélite (Planet, Sentinel), hiperespectral | Mapeamento de regolito e tipo de argila |
| **Planejamento de lavra** | Sequenciamento e otimização | **Deswik** (Sandvik), Hexagon, Datamine, GEOVIA | Lavra rasa em tiras com reabilitação simultânea: nicho |
| **Operação de mina** | Gestão de frota, despacho | **Hexagon**, Modular Mining (Komatsu), Wenco (Hitachi), Caterpillar MineStar | Minas de argila são pequenas em frota. Baixa prioridade |
| | Drones e levantamentos | Propeller, Skycatch, DJI Enterprise, Emesent | Volume de pilhas e cavas: **muito comoditizado** |
| | Automação e robótica | Sandvik, Epiroc, Komatsu, Caterpillar | Pouco relevante para lavra rasa |
| **Processamento** | Historiador de dados (PI) | **AVEVA PI** (antigo OSIsoft), Honeywell, Emerson | Infraestrutura genérica |
| | Simulação de processo | METSIM, SysCAD, HSC Chemistry (Metso), Aspen, IDEAS | **SX de ETR com centenas de estágios: pouca ferramenta comercial madura; know-how na China** |
| | Otimização com IA | IntelliSense.io, Petra Data Science, Metso, ABB, Rockwell | Focadas em cobre, ouro e ferro |
| | Sensores e triagem de minério | MineSense, TOMRA, Steinert | Triagem para ETR em rocha dura (BRE) |
| | Contabilidade metalúrgica | Módulos de AVEVA, Hexagon, Datamine. Código AMIRA P754 | Balanço de 15 elementos por estágio: complexo |
| | LIMS (laboratório) | LabWare, Thermo, CCLAS (Datamine) | Química de ETR (ICP-MS) gera muitos dados |
| **ESG e conformidade** | Gestão ambiental e condicionantes | Enablon (Wolters Kluwer), Intelex, Sphera, Cority | **Nenhum incumbente forte com foco em ANM + SEMAD + CNEN** |
| | LCA e carbono | **Minviro**, Sphera, Ecoinvent | ETR tem poucos dados de LCA públicos |
| **Cadeia e comercialização** | Rastreabilidade | **Circulor**, **Minespider**, RCS Global (Better Mining) | Foco em baterias (cobalto, lítio). **Ímãs e ETR são a próxima fronteira** (CRMA) |
| | Inteligência de preço | Benchmark, Fastmarkets, Argus, SMM, Adamas | Caras e opacas |

### O que esse mapa revela

1. Os **incumbentes são fortes em geologia, planejamento e frota**, as etapas "genéricas" da mineração. Competir ali é difícil.
2. As **lacunas específicas de terras raras** estão em: **(a)** simulação, controle e gêmeo digital de **separação por SX**; **(b)** dados de **planta-piloto e metalurgia** de argila iônica; **(c)** **conformidade regulatória brasileira** (ANM + estado + CNEN); **(d)** **rastreabilidade de ímãs** para o CRMA e o DFARS.
3. Consolidação: os grandes compraram as startups do passado (Bentley → Seequent, Sandvik → Deswik, Weir → Micromine, Hexagon com várias aquisições). **A saída por M&A é um caminho real** para startups de nicho.

## 3. Modelos de referência (o que aprender com quem deu certo)

| Empresa | Modelo | Lição |
|---|---|---|
| **KoBold Metals** | IA + **compra direitos e opera exploração** (vira dona do ativo) | Em exploração, o valor de IA se captura sendo **dono do ativo**, não vendendo software. Isso exige capital de centenas de milhões |
| **Seequent (Leapfrog)** | Software de modelagem 3D implícita, muito melhor que o legado | Um produto **10× melhor** num fluxo de trabalho central vira padrão de mercado. Vendido à Bentley por ~US$ 1 bi |
| **Minviro** | Consultoria de LCA → software | Começar como **serviço especializado** e produtizar depois funciona em nicho regulatório |
| **Circulor / Minespider** | Rastreabilidade puxada por regulação (passaporte de baterias) | **Regulação cria o comprador.** Vender para OEMs, não para mineradoras |
| **IntelliSense.io** | IA para otimização de planta, vendida por resultado | Prova de valor em **% de recuperação** ou em throughput |

## 4. Ecossistema de inovação no Brasil

| Ator | O que é | Como usar |
|---|---|---|
| **Mining Hub** (BH) | Inovação aberta das mineradoras (Vale, Anglo, Usiminas, CBMM, Kinross e outras). **M-Start** (aceleração por PoCs; ~45 startups já passaram), **M-Spot** (desafios exclusivos) | Porta de entrada para PoCs pagas com grandes mineradoras |
| **Minex Hub / Inova+ Mineração** (BA) | Programa da CBPM com PoCs de até **R$ 25 mil** por solução (inscrições até 20/10/2026 no ciclo atual). Desafios: dados históricos, governança de IA, inteligência para pesquisa mineral | Bom para quem mira a BRE e a Bahia |
| **IBRAM** | Instituto Brasileiro de Mineração. Promove o **Mining Innovation Summit** (jun/2026, BH) e a **Exposibram** | Rede e vendas |
| **CIT SENAI ITR** (Lagoa Santa) | P&D em terras raras e ímãs, MagBras, pilotos | Parceiro técnico. Dados de piloto. Coautoria de projetos de fomento |
| **CETEM** (RJ), **CDTN** (BH), **IPT** (SP) | Centros públicos de tecnologia mineral e nuclear | Parceria científica |
| **ITV** (Instituto Tecnológico Vale) | P&D da Vale | Pesquisa aplicada e talentos |
| **Universidades** | UFMG, UFOP (Escola de Minas), USP (Poli), UNICAMP, UFRGS, CEFET-MG, PUC Minas | Talento, laboratórios, spin-offs |
| **Fomento** | **Finep** (subvenção, Mais Inovação, Centelha), **BNDES** (Garagem, chamada de minerais estratégicos), **Embrapii**, **FAPEMIG**, FAPESP (PIPE) | Capital não diluidor |
| **Lei 15.506/2026** | Obrigação de destinar receita a P&D (⚠️ regulamentação pendente) | **Novo orçamento de inovação nas mineradoras** |
| **Lei do Bem** | Incentivo fiscal a P&D para empresas no lucro real | Argumento de venda para clientes grandes |

## 5. A dinâmica de vender tecnologia para mineração

| Característica | Implicação |
|---|---|
| **Aversão a risco** (segurança, produção contínua) | Pilotos longos. Ninguém quer ser o primeiro |
| **Ciclos de venda de 6 a 24 meses** | É preciso caixa para aguentar. Comece com PoCs pagas |
| **Comprador fragmentado** (operação, TI/TO, ESG, suprimentos) | Mapeie o *champion* técnico e o dono do orçamento |
| **Juniores têm pouco caixa** e gastam em sondagem e estudos | Venda **serviço + software** ligado a um marco (DFS, LI) que destrava capital |
| **Produtores têm caixa e dor operacional** | Venda **resultado** (recuperação, disponibilidade, conformidade) |
| **Engenharia (EPCM) influencia a escolha de tecnologia** | Parceria com engenharias e laboratórios como canal |
| **Mercado brasileiro de ETR é pequeno** (1 produtor, ~5 desenvolvedores) | **Pense globalmente desde o início**: argila iônica existe também no Chile, em Uganda, Madagascar, Malásia e Austrália, e a conformidade com o CRMA vale para qualquer origem |

---

## Pontos-chave

- MiningTech é maduro em geologia, planejamento e frota (incumbentes fortes) e **imaturo em separação de ETR, metalurgia de argila, conformidade brasileira e rastreabilidade de ímãs**.
- Os números de mercado de relatórios pagos divergem até 10×. Construa o mercado de baixo para cima.
- Há saída por M&A: grandes grupos compram startups de nicho com frequência.
- O Brasil tem um ecossistema de inovação aberta real (Mining Hub, Inova+, CIT SENAI) e fomento não diluidor. A Lei 15.506 pode criar orçamento obrigatório de P&D.
- Vender para mineração é **lento e baseado em confiança**. PoCs pagas, parceria com engenharias e foco em resultado mensurável.

## Conexão com o próximo módulo

O [módulo 10](10-oportunidades-e-tese-de-startup.md) cruza as **lacunas** (seção 2) com as **dores brasileiras** (módulos 07 e 08) para pontuar e priorizar teses de negócio.

## Referências

1. Fortune Business Insights — Mining Software Market. https://www.fortunebusinessinsights.com/mining-software-market-116898
2. The Business Research Company (via GII) — Digital Twin in Mining. https://www.giiresearch.com/report/tbrc2133598-digital-twin-mining-global-market-report.html
3. Futurebridge — "Software-defined mining". https://www.futurebridge.com/software-defined-mining-the-next-competitive-advantage-for-mining-leaders/
4. Berkeleyside — KoBold Metals. https://www.berkeleyside.org/2026/10/05/kobold-metals-berkeley
5. DeepLearning.AI (The Batch) — "How KoBold Metals Uses AI". https://www.deeplearning.ai/the-batch/how-kobold-metals-uses-ai-to-find-rare-earth-minerals
6. Mining Hub — M-Start. https://mininghub.com.br/m-start/
7. Brasil Mineral — Inova+ Mineração (BA). https://brasilmineral.com.br/noticias/inova-mineracao-esta-com-inscricoes-abertas
8. Portal RCD — desafios do Inova+ Mineração. https://www.portalrcd.com/post/hub-de-minera%C3%A7%C3%A3o-lan%C3%A7a-programa-de-inova%C3%A7%C3%A3o-aberta-para-o-segmento-mineral-na-bahia
9. IBRAM — Mining Innovation Summit 2026. https://ibram.org.br/noticia/mining-innovation-summit-2026-liderancas/
10. Geoscan — "Startups na mineração". https://geoscan.com.br/startups-na-mineracao/

*Acessos em 29/10/2026. As aquisições citadas (Bentley–Seequent em 2021, Sandvik–Deswik em 2022, Weir–Micromine em 2024) vêm de conhecimento setorial: confirme valores e datas antes de uso formal.*
