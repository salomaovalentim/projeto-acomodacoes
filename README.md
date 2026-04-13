#  Expansão para locação de quartos em Nova York

##  Contexto do Projeto

A empresa Tudo Aqui possui planos estratégicos de expansão para o segmento de locação de quartos e acomodações. Para apoiar essa decisão, foi solicitada uma análise exploratória utilizando dados públicos do Airbnb da cidade de Nova York, abrangendo o período de 2011 a 2018.

O projeto tem como objetivo fornecer suporte analítico para auxiliar a diretoria na tomada de decisões estratégicas.

---

##  Objetivo da Análise

- Identificar padrões de preços das acomodações
- Avaliar comportamento das hospedagens ao longo do tempo
- Analisar distribuição geográfica dos imóveis
- Classificar acomodações por faixa de preço
- Fornecer indicadores estratégicos para expansão do negócio

---

## 🛠️ Ferramentas Utilizadas

- Power BI
- Power Query
- DAX
- Modelagem de Dados

---

##  Estrutura do Projeto

- dataset → Base de dados utilizada  
- dashboard → Arquivo Power BI (.pbix)  
- imagens → Prints dos dashboards  
- documentacao → Detalhamento técnico do projeto  

---

##  Tratamento dos Dados

Foram realizadas as seguintes etapas:

- Remoção de registros duplicados
- Exclusão de linhas em branco
- Padronização de textos
- Ajuste de espaços indevidos
- Validação dos tipos de dados

---

##  Modelagem Temporal

Foi criada uma tabela calendário contendo:

- Data
- Dia
- Mês
- Nome do mês
- Ano
- Semana do mês
- Trimestre
- Nome do trimestre

A tabela foi relacionada com a coluna Last Review da tabela principal.

---

##  Dashboards Desenvolvidos

### Dashboard Estratégico
- Indicadores gerais de preços
- Distribuição geográfica das acomodações
- Análise temporal das hospedagens
- Segmentação por padrão de preço

### Dashboard Analítico
- Comparação entre tipos de acomodações
- Análise detalhada por bairros
- Visualização de comportamento dos preços

---

##  Visualizações

![image-alt](https://raw.githubusercontent.com/salomaovalentim/projeto-acomodacoes/69c1d50079d29c58a9fa70b9289691988a1df0ad/visao-geral.png)
(![visao-detalhes](https://raw.githubusercontent.com/salomaovalentim/projeto-acomodacoes/a017d5996c18e1558d27be6efef77972fc910dd1/visao-detalhes.png)
---

##  Principais Insights

###  Análise de Pareto
Entre os 100 principais bairros analisados, apenas 21 bairros representam aproximadamente 80% do preço total das acomodações, demonstrando forte concentração financeira.

###  Distribuição Geográfica
Foi possível identificar regiões com maior concentração de acomodações e compreender padrões estratégicos de localização.

###  Crescimento de Acomodações
Comparando 2017 e 2018, foi observado crescimento superior a 110% em determinados períodos, com média superior a 60% nos demais meses.

###  Crescimento do Preço Final
O ano de 2018 apresentou crescimento acumulado de 226,36% no preço final das acomodações em relação a 2017.

###  Classificação de Acomodações
A categoria Baixo Padrão concentra a maior quantidade de acomodações, indicando predominância de imóveis com valores mais acessíveis.

---

##  Recomendações Estratégicas

###  Foco em Bairros Estratégicos
Priorizar investimentos nos bairros que concentram 80% do valor total das acomodações.

###  Foco em Baixo e Médio Padrão
Investir em acomodações com maior volume de oferta e demanda.

###  Monitoramento do Crescimento do Mercado
Acompanhar tendências e sazonalidade para otimizar estratégias comerciais.

### Tipo de produto — quartos privativos lideram em demanda relativa

---

##  Resultados do Projeto

O dashboard permite visão estratégica do mercado de hospedagem, auxiliando na análise de viabilidade da expansão do negócio.

---

##  Aprendizados

- Desenvolvimento de modelagem dimensional
- Aplicação de DAX
- Construção de dashboards estratégicos
- Aplicação de regras de negócio
