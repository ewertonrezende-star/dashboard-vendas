# Dashboard de Vendas por Loja

**Cooperativa Agrícola de Sintra**

Dashboard interativo de vendas líquidas por loja, com comparativo entre 2025 e o ano atual.

## Acesso

🌐 **[Abrir dashboard](https://ewertonrezende-star.github.io/dashboard-vendas/)**

## Funcionalidades

- **KPIs** — YTD do ano atual vs 2025, variação em € e %, total do ano anterior
- **Gráficos** — Vendas YTD por loja e evolução mensal total
- **Tabelas** — Comparativo por loja, por mês e detalhe mês × loja
- **Filtros** — Evolução mensal por loja e detalhe por mês
- **Carregar dados** — Upload de CSV com as vendas do ano atual (botão ⚙️)

## Lojas incluídas

Sintra · Colares · Albarraque · Arneiro · Mem Martins · Sabugo

## Como atualizar os dados

1. Clique no botão **⚙️** (canto superior direito)
2. Descarregue o **modelo CSV** (opcional)
3. Carregue um ficheiro CSV com o formato:

```
Loja;Mês;Líquido
Sintra;1;77698.99
Sintra;Janeiro;102835.80
Colares;3;79870.64
```

- **Loja** — nome da loja  
- **Mês** — número (1–12) ou nome (Janeiro, Fev, Março…)  
- **Líquido** — valor em euros (aceita ponto ou vírgula decimal)

Os dados de **2025** estão fixos. A comparação é feita automaticamente até ao último mês com dados no ficheiro carregado.

## Estrutura do repositório

| Ficheiro       | Descrição                          |
|----------------|------------------------------------|
| `index.html`   | Dashboard completo (HTML + JS)     |
| `README.md`    | Este ficheiro                      |

## Tecnologias

- HTML / CSS / JavaScript
- [Chart.js](https://www.chartjs.org/) — gráficos
- GitHub Pages — publicação

## Contacto

Cooperativa Agrícola de Sintra  
[coopsintra.pt](https://coopsintra.pt)
