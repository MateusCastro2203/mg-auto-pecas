# MG Auto Peças — contexto do projeto

Operação de venda de peças e acessórios automotivos no **Mercado Livre**, tocada por dois sócios, saindo do zero rumo a **R$ 10.000 de faturamento acumulado**.

## O que é este repositório

Documentação viva da estratégia e da operação. A fonte de verdade está em `docs/` (leia na ordem 00 → 07, mais o `checklist.md`).

## Contexto essencial

- **Capital:** enxuto (~R$ 1.000 girando). Recomendações precisam caber num orçamento apertado.
- **Meta:** R$ 10.000 de faturamento acumulado.
- **Estratégia (Caminho A):** acessórios de giro rápido, leves e baratos, fornecedor **nacional**, reinvestir 100% do lucro; evoluir depois pra nicho profundo (Caminho C).
- **Vantagem:** conhecimento de carro (usar em compatibilidade e descrição técnica).
- **Prioridade nos primeiros meses:** REPUTAÇÃO no Mercado Livre acima de lucro imediato.

## Regras ao trabalhar aqui

1. **Leia `docs/` antes de aconselhar.** Se contrariar a estratégia documentada, diga e justifique.
2. **Nunca recomendar dropshipping nem revenda via AliExpress** (frete lento destrói reputação).
3. **Nunca inventar compatibilidade técnica** de peça — se não tiver certeza, orientar a confirmar.
4. **Taxas/limites/regras do ML mudam** — sempre orientar a validar no simulador/painel do ML; os valores nos docs são aproximados.
5. **Decisões do dia a dia se tomam pelo lucro líquido**, não pelo faturamento.

## Agente especialista

`.claude/agents/vendas-marketing.md` — especialista em vendas e marketing pra Mercado Livre (anúncios, preço, ads, concorrência, atendimento). Acione para qualquer tarefa comercial.

## Estrutura

```
MG-auto-pecas/
├── README.md                 # visão geral e índice
├── CLAUDE.md                 # este arquivo
├── docs/
│   ├── 00-visao-geral.md     # estratégia e princípios
│   ├── 01-setup.md           # MEI, conta ML, envios, kit
│   ├── 02-produtos.md        # escolha de SKU e fornecedores
│   ├── 03-primeiras-vendas.md# reputação (mês 1)
│   ├── 04-escala.md          # reinvestir, Full, Ads, nicho
│   ├── 05-precificacao.md    # taxas e fórmula de preço
│   ├── 06-divisao-trabalho.md# acordo e papéis dos sócios
│   ├── 07-metas-numeros.md   # 0 a 10k, o poder do giro
│   └── checklist.md          # passo a passo acionável
└── .claude/agents/vendas-marketing.md
```
