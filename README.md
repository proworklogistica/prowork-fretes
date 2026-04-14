# PROWORK · Monitor de Fretes

Sistema de monitoramento logístico de notas fiscais da PROWORK.

## Funcionalidades

- 📦 **Monitoramento geral** – Todas as NFs com status em tempo real
- ⚠️ **Em Atraso** – NFs com prazo vencido ou chegando no limite
- ✅ **Entregues** – Histórico completo de NFs entregues
- 📊 **Relatório por Transportadora** – Métricas por transportadora (total de NFs, média de dias, frete médio)

## Dados

Os dados são carregados do arquivo `data.json`, gerado a partir das planilhas:
- `FRETES_JANEIRO_2026.xlsx`
- `FRETES_FEVEREIRO_2026.xlsx`
- `FRETES_MARÇO_2026.xlsx`
- `FRETES_ABRIL_2026.xlsx`

**Total: 840 registros | Transportadoras: ALFA, MOVVI, TNT, NADER, BRASPRESS, AVIÕES**

## Como usar

1. Abra `index.html` em qualquer navegador moderno (ou acesse via GitHub Pages)
2. Os dados ficam salvos no `localStorage` do navegador
3. Use **+ Nova NF** para adicionar novas notas manualmente
4. Use o botão **✔** para registrar uma entrega
5. Use o botão **⚠** para marcar uma NF como atrasada

## GitHub Pages

Este site está publicado em:  
`https://<usuario>.github.io/<repositorio>/`

## Estrutura

```
prowork-fretes/
├── index.html      # Sistema completo (HTML + CSS + JS)
├── data.json       # Base de dados (840 NFs)
└── README.md
```
