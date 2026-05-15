# Dashboard de Controle de Diárias Pendentes

## Objetivo

Projeto desenvolvido para monitoramento gerencial de diárias pendentes de prestação de contas, utilizando arquitetura Medalhão, Power BI, SharePoint e Power Automate.

O objetivo foi transformar um processo operacional manual em uma solução analítica automatizada com visão gerencial e alertas operacionais.

---

## Problema de Negócio

O ERP institucional não disponibilizava indicadores gerenciais sobre:

- percentual de diárias atrasadas
- gestores com maior volume de pendências
- projetos críticos
- aging de atraso
- alertas automatizados

O acompanhamento era manual e operacional.

---

## Solução Desenvolvida

A solução implementada contempla:

- ingestão automatizada de relatórios ERP
- arquitetura Medalhão (Bronze, Silver e Gold)
- modelagem dimensional
- KPIs executivos
- dashboard gerencial
- atualização automática
- alertas automatizados por e-mail

---

## Arquitetura

ERP → Power Automate Desktop → SharePoint → Power BI → Power Automate → E-mail Gerencial

---

## Camadas Medalhão

### Bronze
Dados brutos do ERP sem transformação.

### Silver
Tratamento, padronização e aplicação de regras de negócio.

### Gold
Modelo dimensional analítico pronto para consumo.

---

## Tecnologias Utilizadas

- Power BI
- DAX
- Power Query
- SharePoint
- Power Automate Desktop
- Power Automate Cloud
- Modelagem Dimensional
- Arquitetura Medalhão

---

## KPIs Implementados

- Total de Diárias
- Diárias em Atraso
- % de Atraso
- Diárias Críticas (+15 dias)
- Ranking de Gestores
- Ranking de Projetos
- Evolução Temporal
- Aging de Pendências

---

## Automação

O projeto possui automação para:

- download automático do relatório ERP
- salvamento no SharePoint
- atualização automática do Power BI
- envio consolidado semanal de alertas por gestor

---

## Dashboard

(INSERIR PRINT)

---

## Resultados Esperados

- maior controle operacional
- redução de pendências
- visão gerencial centralizada
- automatização do acompanhamento
- suporte à tomada de decisão

---

## Autor

Paulo Roberto
