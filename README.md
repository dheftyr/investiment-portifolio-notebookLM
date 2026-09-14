# Caderno Temático: Planejamento Estratégico de Renda Passiva na B3 com IA

Repositório desenvolvido como parte do Desafio de Projeto da **DIO**, utilizando o **Google NotebookLM** como ferramenta de aprendizagem ativa, curadoria de fontes e organização do conhecimento em investimentos.

---

## 1. Contexto e Objetivos

* **Assunto de Interesse:** Construção de carteira de investimentos focada em geração de renda passiva recorrente na B3 (Bolsa de Valores do Brasil), através de ações pagadoras de dividendos consistentes e Fundos Imobiliários (FIIs).
* **Objetivos de Estudo:**
  * Compreender os fundamentos de alocação de ativos para investidores de perfil moderado.
  * Simular matematicamente o crescimento de patrimônio e a velocidade de alcance de uma meta de renda passiva (R$ 1.600,00/mês).
  * Analisar calendários de proventos para identificar oportunidades táticas com base em fontes abertas.
  * Aliar o uso ético e estratégico de Inteligência Artificial (NotebookLM) com rigor técnico financeiro.

---

## 2. Curadoria de Fontes

Para alimentar o NotebookLM, foram selecionadas 4 fontes abertas em texto e PDF:
1. **Agenda de Dividendos de Ações - 2026/2027** (Calendário oficial de datas Com e pagamentos).
2. **Agenda de Dividendos de Fundos Imobiliários - FIIs - 2026/2027** (Mapeamento de rendimentos mensais).
3. **COMO MONTAR UMA CARTEIRA DE DIVIDENDOS PARA VIVER DE RENDA** (Guia metodológico de alocação e setores perenes).
4. **Luiz Barsi Filho - O Rei dos Dividendos - YouTube** (Transcrição/resumo de conceitos fundamentais de valorização de longo prazo e reinvestimento).

---

## 3. Engenharia de Prompts e Respostas Completas

### Prompt 1: Planejamento Estratégico e Simulação de Carteira

**Texto do Prompt Enviado:**
> Atue como um Consultor Financeiro Sênior e Especialista em Alocação de Ativos na B3 (Bolsa de Valores do Brasil).
> Objetivo
> Sua tarefa é criar um planejamento estratégico e simulação de carteira voltada exclusivamente para a geração de renda passiva recorrente através de investimentos em ativos geradores de dividendos (Ações pagadoras de dividendos consistentes e Fundos Imobiliários - FIIs).
> Contexto do Usuário
> Valor inicial disponível para investimento: 1.000,00
> Aporte mensal planejado: 100,00
> Objetivo de renda passiva mensal desejada: 1.600,00
> Horizonte de tempo (Prazo): 10 anos
> Perfil de Risco: Moderado
> Diretrizes e Restrições Técnicas
> NUNCA invente dados de cotação atual ou rendimentos passados específicos de empresas. Caso mencione exemplos clássicos de ativos da B3 para fins didáticos, faça ressalvas claras de que o investidor deve checar as cotações atuais.
> Foque em diversificação inteligente (dividir entre setores perenes como energia, saneamento, bancos e fundos imobiliários de tijolo/papel).
> Mantenha total rigor matemático nas estimativas de juros compostos, considerando uma taxa média hipotética e conservadora de longo prazo (ex: 8% a 10% ao ano de retorno total reinvestido), detalhando as premissas usadas.
> Mantenha a moeda estritamente em Reais (R$).
> Formato de Saída Esperado
> Estruture sua resposta final utilizando o seguinte formato:
> Premissas e Hipóteses: Explique claramente as premissas matemáticas e de retorno utilizadas.
> Estratégia de Alocação (Sugestão de Divisão Percentual): Apresente em tabela ou tópicos a divisão ideal da carteira (ex: % FIIs de Tijolo, % FIIs de Papel, % Ações do Setor Elétrico, etc.).
> Simulação de Crescimento: Mostre a projeção do patrimônio e da renda passiva estimada ao final do horizonte de tempo.
> Próximos Passos Educacionais: Orientações práticas e alertas de risco fundamentais (como a importância da reserva de emergência).

**Resposta Completa Obtida:**
Como Consultor Financeiro Sênior e Especialista em Alocação de Ativos na B3, apresento o planejamento estratégico de investimentos e a simulação matemática detalhada para a construção da sua carteira de renda passiva.

**1. Premissas e Hipóteses**
Para garantir rigor matemático e realismo financeiro, a simulação foi construída sobre as seguintes premissas:
* Aporte Inicial ($PV$): R$ 1.000,00.
* Aporte Mensal ($PMT$): R$ 100,00.
* Prazo do Investimento ($n$): 10 anos (120 meses).
* Taxa de Retorno Total Hipotética ($r$): Consideramos uma taxa nominal média e conservadora de 9,0% ao ano (composta por valorização dos ativos e proventos reinvestidos), situando-se na faixa de 8% a 10% a.a. Isso equivale a uma taxa equivalente de ~0,7207% ao mês ($r_{mensal} = (1 + 0,09)^{1/12} - 1$).
* Reinvestimento Integral dos Proventos: Na fase de acúmulo, 100% dos dividendos e JCP recebidos são reinvestidos na compra de novas cotas e ações, acionando o efeito "bola de neve" dos juros compostos.
* Dividend Yield (DY) Estimado da Carteira na Fase de Usufruto: Adotamos um Dividend Yield médio estimado de 0,65% ao mês (~7,8% ao ano), padrão condizente com uma carteira equilibrada entre Ações e FIIs.

**2. Estratégia de Alocação (Sugestão de Divisão Percentual)**
Para o seu Perfil Moderado, a alocação é dividida em duas grandes classes de ativos para equilibrar previsibilidade mensal de aluguéis e crescimento sustentável com dividendos corporativos:

| Classe de Ativo | Subcategoria / Setor | Alocação (%) | Justificativa Estratégica |
| :--- | :--- | :--- | :--- |
| Fundos Imobiliários (FIIs) | FIIs de Tijolo (Logística, Shoppings, Lajes) | 30% | Imóveis físicos com contratos atrelados à inflação (IPCA/IGP-M) e fluxo constante de aluguéis. |
| Fundos Imobiliários (FIIs) | FIIs de Papel / Recebíveis (CRIs) | 20% | Títulos de dívida imobiliária que oferecem retornos mensais elevados e previsíveis. |
| Ações de Dividendos | Setor Financeiro (Bancos) | 15% | Instituições sólidas, com alta lucratividade e histórico consistente de proventos. |
| Ações de Dividendos | Setor Elétrico (Transmissão e Geração) | 15% | Contratos de longo prazo com receita previsível e corrigida por índices inflacionários. |
| Ações de Dividendos | Setor de Saneamento / Utilidades | 10% | Serviços essenciais com demanda inelástica e geração de caixa estável. |
| Ações de Dividendos | Setor de Telecomunicações / Perenes | 10% | Modelo de negócios baseado em receita recorrente por assinaturas. |

*Nota Didática e Educacional:* Empresas e fundos pertencentes a esses setores (como Itaú, Banco do Brasil, Taesa, Engie, Copasa, HGLG11, KNCR11 e MXRF11) são citados frequentemente no mercado apenas para ilustrar conceitos de setores perenes e diversificação. O investidor deve sempre verificar cotações atuais, relatórios de RI e dados oficiais da B3/CVM antes de realizar qualquer operação.

**3. Simulação de Crescimento e Análise de Metas**
* **Projeção do Patrimônio e Renda em 10 Anos (120 meses):**
  * Total de Capital Aportado do Bolso: R$ 1.000,00 + (120 × R$ 100,00) = **R$ 13.000,00**.
  * Patrimônio Final Estimado (a 9% a.a. retorno total): R$ 21.339,23. (Caso o retorno médio seja de 8,0% a.a., o patrimônio acumulado será de R$ 20.171,35; a 10,0% a.a., alcançará R$ 22.580,13).
  * Renda Passiva Mensal Estimada no Final de 10 Anos: Entre R$ 138,70 e R$ 158,00 por mês (considerando DY mensal entre 0,65% e 0,70%).
* **Análise do Objetivo de Renda Passiva (R$ 1.600,00/mês):**
  * Para obter uma renda passiva mensal de R$ 1.600,00 com um Dividend Yield médio de 0,65% ao mês, é necessário acumular um patrimônio focado em renda de aproximadamente R$ 246.153,85 (R$ 1.600,00 / 0,0065).
* **Ajustes de Sensibilidade para Atingir a Meta:**
  * *Ajuste do Aporte Mensal (para manter o prazo de 10 anos):* Para atingir o patrimônio de ~R$ 246 mil em 10 anos (considerando a taxa de 9% a.a.), o aporte mensal necessário seria de aproximadamente R$ 1.285,00 por mês.
  * *Ajuste do Prazo (mantendo o aporte de R$ 100,00/mês):* Mantendo R$ 1.000,00 iniciais e R$ 100,00 mensais com retorno de 9% a.a. totalmente reinvestido, seriam necessários cerca de 33 anos para acumular o capital necessário de R$ 246 mil.

**4. Próximos Passos Educacionais e Alertas de Risco**
* **Construção da Reserva de Emergência:** Antes de realizar aportes em Ações ou FIIs, aloque de 6 a 12 meses do seu custo de vida em ativos de alta liquidez e baixo risco (como Tesouro Selic ou CDB 100% do CDI).
* **Critérios Seleção de Ativos:**
  * *Em Ações:* Busque empresas com histórico de lucro líquido recorrente, payout sustentável (abaixo de 100% do lucro), endividamento controlado ($\text{Dívida Líquida / EBITDA} < 3\text{x}$) e valuation atrativo em relação aos dividendos projetados.
  * *Em FIIs:* Observe a lei que exige a distribuição de no mínimo 95% dos lucros semestrais, analisando a liquidez do fundo, a diversificação de inquilinos/imóveis e o histórico da gestão.
* **Disciplina no Reinvestimento:** Durante a fase de acumulação, a regra de ouro é nunca gastar os proventos recebidos, mas sim reutilizá-los imediatamente na compra de mais ativos, impulsionando a velocidade do crescimento patrimonial.
* **Acompanhamento e Rebalanceamento:** Realize aportes mensais direcionados aos ativos ou setores que estiverem abaixo do percentual estabelecido na sua meta de alocação.

---

### Prompt 2: Análise Fundamentalista de Calendário de Dividendos (2026/2027)

**Texto do Prompt Enviado:**
> Atue como um Analista de Renda Fixa e Variável especializado em análise fundamentalista de fluxo de caixa e dividendos na B3.
> Objetivo
> Sua tarefa é analisar as fontes carregadas ("Agenda de Dividendos de Ações - 2026/2027", "Agenda de Dividendos de Fundos Imobiliários - FIIs - 2026/2027", e "COMO MONTAR UMA CARTEIRA DE DIVIDENDOS PARA VIVER DE RENDA" e "Luiz Barsi Filho - O Rei dos Dividendos - YouTube") para identificar e recomendar oportunidades de compra estratégicas de curto, médio e logo prazo baseadas estritamente no calendário de pagamentos e datas "Com" informadas nos documentos.
> Instruções de Execução (Baseadas Exclusivamente nas Fontes)
> Varredura do Calendário: Analise as agendas fornecidas para os anos de 2026 e 2027. Identifique quais ativos (Ações e FIIs) apresentam histórico ou previsão de pagamentos recorrentes e robustos no horizonte de tempo coberto pelas fontes.
> Critérios de Seleção para Compra: Dentre os ativos listados nas fontes, selecione aqueles que: Possuem alta previsibilidade ou constância de distribuição de proventos. Apresentam datas "Com" (data limite para ter direito ao dividendo) próximas ou táticas dentro da programação do calendário.
> Análise Cruzada: Agrupe as oportunidades separando-as em duas categorias claras: Fundos Imobiliários (FIIs) (focados em fluxo de caixa mensal previsível). Ações (focadas em dividendos trimestrais, semestrais ou anuais informados nas fontes).
> Formato de Saída Obrigatório
> Apresente a sua resposta estruturada exatamente da seguinte forma:
> Visão Geral das Fontes: Um breve resumo do que foi mapeado nas agendas de 2026/2027 carregadas no notebook.
> Top Oportunidades em Fundos Imobiliários (FIIs): Ativo: [Nome do FII retirado da fonte] | Período/Data de Pagamento ou Data Com: [Informação estrita da fonte] | Justificativa baseada no documento: [Por que este FII se destaca na agenda de dividendos?]
> Top Oportunidades em Ações: Ativo: [Nome da Ação retirada da fonte] | Período/Data de Pagamento ou Data Com: [Informação estrita da fonte] | Justificativa baseada no documento: [Por que esta ação é um destaque de dividendos na agenda?]
> Alerta Crítico: Reforce obrigatoriamente que a análise acima restringe-se aos dados das agendas fornecidas nas fontes de 2026/2027 e que o investidor deve checar o preço atual de mercado do ativo antes de efetuar qualquer compra (evitando comprar na máxima se o preço disparou).

**Resposta Completa Obtida:**
As agendas de dividendos de ações e fundos imobiliários mapeadas para os anos de 2026 e 2027 organizam os anúncios oficiais, datas "Com", datas de pagamento e os valores de proventos distribuídos por ativos negociados na B3. Os Fundos Imobiliários (FIIs) são voltados ao fluxo de caixa recorrente, sendo obrigados por lei a distribuir no mínimo 95% dos lucros auferidos aos cotistas, com pagamentos predominantemente mensais decorrentes de aluguéis ou títulos imobiliários. Por sua vez, as ações que pagam dividendos ou Juros sobre Capital Próprio (JCP) concentram-se fortemente em setores com receitas previsíveis e lucro líquido constante, com destaque para os setores financeiro (bancos), energia elétrica, saneamento e telecomunicações. A análise fundamentalista presente nos documentos reforça que o investidor deve buscar ativos com lucros recorrentes, payout sustentável (abaixo de 100%), endividamento controlado e preço de compra adequado em relação ao dividend yield almejado.

**Top Oportunidades em Fundos Imobiliários (FIIs)**
* **Ativo:** RECR11 (FII Rec Recebíveis Imobiliários)
  * **Período/Data de Pagamento ou Data Com:** Data Com em 08/09/2026 e Data de Pagamento em 15/09/2026 (Valor: R$ 0,74 por cota).
  * **Justificativa baseada no documento:** O fundo é destacado entre os FIIs mais buscados da plataforma Investidor10 e mantém pagamentos mensais confirmados na agenda oficial de proventos. Além disso, é citado historicamente como um dos destaques em distribuição de dividendos aos cotistas.
* **Ativo:** MCCI11 (Mauá Capital Recebíveis Imobiliários)
  * **Período/Data de Pagamento ou Data Com:** Data Com em 11/09/2026 e Data de Pagamento em 18/09/2026 (Valor: R$ 1,00 por cota).
  * **Justificativa baseada no documento:** Destaca-se no segmento de recebíveis imobiliários com renda mensal previsível e distribuição expressiva confirmada no calendário de setembro de 2026.
* **Ativo:** RBRR11 (RBR Rendimento High Grade)
  * **Período/Data de Pagamento ou Data Com:** Data Com em 10/09/2026 e Data de Pagamento em 17/09/2026 (Valor: R$ 0,90 por cota).
  * **Justificativa baseada no documento:** Apresenta distribuição constante de rendimentos catalogada na agenda, atuando no segmento de títulos de dívida imobiliária que oferecem fluxo previsível aos investidores.
* **Ativo:** FLMA11 (Continental Square Faria Lima)
  * **Período/Data de Pagamento ou Data Com:** Data Com em 04/09/2026 e Data de Pagamento em 15/09/2026 (Valor: R$ 1,22 por cota).
  * **Justificativa baseada no documento:** Representa uma oportunidade confirmada em FIIs de tijolo focados em empreendimentos imobiliários corporativos, garantindo o recebimento de aluguéis no período informado.
* **Ativo:** KNRI11 (Kinea Renda Imobiliária) / MXRF11 (Max Renda)
  * **Período/Data de Pagamento ou Data Com:** Distribuição mensal recorrente mapeada no histórico e nas orientações do calendário.
  * **Justificativa baseada no documento:** As fontes apontam esses fundos como referências consolidadas no mercado para investidores que buscam renda passiva recorrente por meio do pagamento mensal consistente de dividendos.

**Top Oportunidades em Ações**
* **Ativo:** BBAS3 (Banco do Brasil S.A.)
  * **Período/Data de Pagamento ou Data Com:** Data Com em 01/09/2026 e Data de Pagamento em 11/09/2026 (JSCP nos valores de R$ 0,10 e R$ 0,03 por ação).
  * **Justificativa baseada no documento:** Integra o setor financeiro/bancário, classificado pelas fontes como um dos setores essenciais de maior constância de lucro líquido e estabilidade de proventos. Na análise de valuation, é apontado como um ativo com margem de desconto expressiva em relação ao preço teto estimado por dividend yield e com payout controlado.
* **Ativo:** CSMG3 (Copasa - Cia de Saneamento de Minas Gerais)
  * **Período/Data de Pagamento ou Data Com:** Data Com em 21/09/2026 e Data de Pagamento em 09/11/2026 (JSCP no valor de R$ 0,26 por ação).
  * **Justificativa baseada no documento:** Pertence ao setor de saneamento, enquadrado nos documentos como um setor de demanda inelástica e lucros recorrentes ao longo dos anos.
* **Ativo:** MDIA3 (M. Dias Branco S.A.)
  * **Período/Data de Pagamento ou Data Com:** Data Com em 22/09/2026 e Data de Pagamento em 30/09/2026 (Dividendos de R$ 0,03 por ação).
  * **Justificativa baseada no documento:** O documento cita expressamente a M. Dias Branco como uma das companhias que apresentam histórico de consistência no pagamento mensal de dividendos.
* **Ativo:** ITUB4 / ITUB3 (Banco Itaú Unibanco S.A.)
  * **Período/Data de Pagamento ou Data Com:** Data Com em 30/09/2026 e Data de Pagamento em 03/11/2026 (JSCP no valor de R$ 0,02 por ação).
  * **Justificativa baseada no documento:** Apresenta elevada previsibilidade no setor bancário, ostentando histórico de lucros líquidos recorrentes sem registro de prejuízos anuais e com pagamentos periódicos confirmados no calendário.
* **Ativo:** JHSF3 (JHSF Participações S.A.)
  * **Período/Data de Pagamento ou Data Com:** Data Com em 30/09/2026 e Data de Pagamento em 09/10/2026 (Dividendos no valor de R$ 0,07 por ação).
  * **Justificativa baseada no documento:** A empresa é destacada no documento como uma das ações com histórico recente de regularidade na distribuição mensal de proventos.

**Alerta Crítico**
Reforça-se obrigatoriamente que a análise acima restringe-se estritamente aos dados fornecidos nas agendas de dividendos de 2026/2027 e nos materiais explicativos carregados nas fontes do notebook. O investidor deve checar obrigatoriamente o preço atual de mercado do ativo na B3 antes de efetuar qualquer compra, verificando o valor da cotação e a margem de segurança para evitar comprar ativos na máxima histórica ou com dividend yield distorcido caso os preços tenham disparado.

---

## 4. Miniguia de Estudo (Consolidação Final)

### Resumos Estruturados
* **Fase de Acumulação:** Foco total no reinvestimento de 100% dos proventos recebidos para ativar os juros compostos.
* **Setores Perenes:** Prioridade para ativos de energia elétrica, saneamento, bancos e fundos imobiliários.

### Glossário de Conceitos Aprendidos
* **Data "Com":** Último dia em que o investidor precisa ter o ativo em custódia para ter direito ao próximo provento.
* **Dividend Yield (DY):** Rentabilidade dos dividendos pagos em relação ao preço de mercado atual da cota/ação.
* **Juros Sobre Capital Próprio (JCP):** Forma de remuneração acionária no Brasil sujeita a 15% de IR na fonte.
* **Payout:** Percentual do lucro líquido distribuído aos acionistas.

### Prompts Reutilizáveis para Futuras Revisões
> *Prompt para Análise Setorial:* *"Atue como um analista fundamentalista da B3. Analise o setor [INSERIR SETOR] sob a ótica de endividamento (Dívida Líquida/EBITDA), consistência de lucros nos últimos 5 anos e histórico de payout. Liste os principais riscos regulatórios e operacionais."*
