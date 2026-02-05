#  Metodologia e Desenvolvimento Técnico

##  Tratamento dos Dados

Foram realizadas as seguintes etapas:

- Remoção de duplicidades
- Exclusão de linhas em branco
- Padronização textual
- Ajustes de espaçamento
- Validação dos tipos de dados

---

##  Criação da Tabela Calendário

Foi criada uma tabela calendário para permitir análises temporais avançadas contendo:

- Data
- Dia
- Ano
- Mês
- Nome do mês
- Semana do mês
- Trimestre
- Nome do trimestre

Foi criado relacionamento entre:

Tabela Calendário[Data]  
Airbnb[Last Review]

---

##  Regras de Negócio

- Price considerado como valor da diária
- Implementação de filtros por tipo de acomodação

---

##  Classificação de Acomodações

```DAX
Classificação Tipo de Acomodação =
SWITCH(
    TRUE(),
    Airbnb[Preço Mínimo Final] <= 1000, "Baixo Padrão",
    Airbnb[Preço Mínimo Final] > 1000 && Airbnb[Preço Mínimo Final] <= 10000, "Médio Padrão",
    Airbnb[Preço Mínimo Final] >= 10000 && Airbnb[Preço Mínimo Final] <= 100000, "Alto Padrão",
    Airbnb[Preço Mínimo Final] >= 100000, "Altíssimo Padrão"
)
