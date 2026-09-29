# Análise de Paradas de Equipamentos Móveis

## Descrição

Projeto desenvolvido em Power BI para análise de ocorrências de manutenção e paradas de equipamentos móveis.

O objetivo é monitorar indicadores de disponibilidade, quantidade de paradas e distribuição das ocorrências por frota, equipamento, turno e período.

---

## Dados Tratados

Os dados foram tratados utilizando Power Query com as seguintes transformações:

- Conversão de datas para formato correto.
- Extração da Frota.
- Identificação do Tipo de Equipamento.
- Classificação por Turno:
  - 06x14
  - 14x22
  - 22x06
- Criação da coluna Quantidade de Paradas.
- Padronização dos campos para análise.

---

## Indicadores Disponíveis

- Quantidade de Paradas
- Paradas por Frota
- Paradas por Tipo de Equipamento
- Paradas por Turno
- Paradas por Mês
- Horas de Avaria
- Pareto de Falhas

---

## Equipamentos Monitorados

- Alimentador
- Martelete
- Rodão

---

## Tecnologias Utilizadas

- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel

---

## Estrutura do Projeto

```
/
├── Relatorio.pbix
├── Dados/
│   └── Base_Paradas.xlsx
├── Documentacao/
│   └── Regras_Negocio.pdf
└── README.md
```

---
Autor
Marcos De Campos Coutinho

Técnico Mecânico Jr.


Marcos De Campos Coutinho

Técnico Mecânico Jr.
