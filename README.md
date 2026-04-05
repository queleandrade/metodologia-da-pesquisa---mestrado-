# Análise de Sentimento em Notícias Financeiras com Large Language Models para Apoio à Decisão de Compra e Venda de Ações de Empresas Brasileiras (Petrobras, Vale, Itaú e Bradesco)

> Trabalho de Conclusão de Mestrado — Repositório de Revisão Sistemática da Literatura

---

## 📌 Sobre o trabalho

Este TCC investiga o uso de **Large Language Models (LLMs)** — como GPT, BERT e modelos generativos derivados — na análise automatizada de notícias financeiras para geração de sinais de compra e venda de ações. O estudo tem como objeto quatro das principais empresas listadas na B3:

| Empresa | Ticker |
|---|---|
| Petrobras | PETR3 / PETR4 |
| Vale | VALE3 |
| Itaú Unibanco | ITUB4 |
| Bradesco | BBDC4 |

A hipótese central é que LLMs, por sua capacidade de compreensão contextual do texto, são capazes de extrair sinais de sentimento de notícias financeiras com qualidade superior a abordagens tradicionais de NLP, contribuindo para decisões mais informadas de trading.

---

## 🔍 String de busca — Scopus

A busca foi realizada na base **Scopus**, restrita a artigos científicos de acesso aberto publicados entre 2021 e 2026.

```
TITLE-ABS-KEY (
  ( "large language model*" OR "LLM" OR "GPT" OR "BERT" OR "ChatGPT"
    OR "generative AI" OR "pre-trained language model*" OR "transformer-based model*" )
  AND
  ( "financial news" OR "news sentiment" OR "financial sentiment"
    OR "market sentiment" OR "news-based prediction" OR "stock news"
    OR "earnings announcement*" )
  AND
  ( "stock market prediction" OR "stock price prediction" OR "buy sell signal*"
    OR "trading decision*" OR "stock trading" OR "equity prediction" OR "stock return*" )
)
AND PUBYEAR > 2020
AND PUBYEAR < 2027
AND ( LIMIT-TO ( OA , "all" ) )
AND ( LIMIT-TO ( DOCTYPE , "ar" ) )
```

### Critérios de filtragem

| Critério | Valor |
|---|---|
| Base de dados | Scopus |
| Tipo de documento | Artigo científico (`ar`) |
| Acesso | Somente Open Access |
| Período | 2021 – 2026 |
| Campo de busca | Título, Resumo e Palavras-chave |

---

## 📚 Artigos selecionados

| # | Título | Autores | Ano | Link |
|---|---|---|---|---|
| 1 | Using ChatGPT to Predict Stock Price Movements Based on Financial News | Lopez-Lira, T.; Tang, Y. | 2023 | [doi.org/10.2139/ssrn.4412788](https://doi.org/10.2139/ssrn.4412788) |
| 2 | FinBERT: Financial Sentiment Analysis with Pre-trained Language Models | Araci, D. | 2021 | [arxiv.org/abs/1908.10063](https://arxiv.org/abs/1908.10063) |
| 3 | *(adicione aqui)* | — | — | — |

---

## 🗂️ Estrutura do repositório

```
/
├── README.md               # Este arquivo
├── /artigos/               # PDFs dos artigos selecionados (open access)
├── /planilhas/             # Planilha de rastreamento da RSL
└── /notas/                 # Fichamentos e anotações por artigo
```

*Repositório mantido como parte do processo de Revisão Sistemática da Literatura (RSL) do TCC.*
