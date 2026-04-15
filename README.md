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

String para o google acadêmico

```
"large language model" ("financial news") ("stock prediction" OR "stock trading") ("sentiment analysis")
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
| 1 | MARAG-Fin: An Intelligent Multi-agent RAG-LLM Architecture Integrating Financial News Sentiment and Time Series Data for Data-driven Trading Decision-making |Luckianto, M., Gunawan, A.A.S. | 2026 | https://inass.org/wp-content/uploads/2025/10/2026022846-2.pdf 
| 2 | Integrating Taiwan financial BERT sentiment analysis with CNN-BiLSTM-SA model for stock prediction |Chen, G.-W., Hsu, I.-C. | 2025 | https://link-springer-com.ez278.periodicos.capes.gov.br/article/10.1007/s10791-025-09515-3 |
| 3 | A Hybrid Vader-Bert Sentiment Analysis Framework for Real-Time Stock Market Prediction | Ramathulasi, T. , Rajasekharababu, M., Srinivasarao, P. | 2025 | [—](https://doi.org/10.5269/bspm.78547) https://doi.org/10.5269/bspm.78547 |
| 4 | 	Chinese Financial News Analysis for Sentiment and Stock Prediction: A Comparative Framework with Language Models | 	Chuang, H.-M., He, H.-C.,Hu, M.-C. | 2025 | [—](https://doi.org/10.3390/bdcc9100263) https://doi.org/10.3390/bdcc9100263 |
| 5 | Deep Learning Sentiment Analysis of News and Social Media in Geopolitical Crises | Tripathi, N., Rao, D.S. | 2025 | [—](https://iieta.org/journals/isi/paper/10.18280/isi.300825) https://iieta.org/journals/isi/paper/10.18280/isi.300825 |
| 6 | Integrating Financial Knowledge for Explainable Stock Market Sentiment Analysis via Query-Guided Attention | Hong, C., He, Q. | 2025 | [—](https://doi.org/10.3390/app15126893) https://doi.org/10.3390/app15126893|
| 7 | Stock Trend Prediction Using Multi-attention Network on Domain-specific and Domain-general Features in News Headline | Soon, P.C., Tan, T.-P., Chan, H.Y., Gan, K.H. | 2025 | [—](https://doi.org/10.47836/pjst.33.2.13) https://doi.org/10.47836/pjst.33.2.13 |
| 8 | News sentiment and investment risk management: Innovative evidence from the large language models | Liu, T., Shi, Y. | 2025 | [— ](https://doi-org.ez278.periodicos.capes.gov.br/10.1016/j.econlet.2024.112124) https://doi-org.ez278.periodicos.capes.gov.br/10.1016/j.econlet.2024.112124|
| 9 | Does business news sentiment matter in the energy stock market? Adopting sentiment analysis for short-term stock market prediction in the energy industry | Lee, C.-Y., Anderl, E. | 2025 |  https://doi.org/10.3389/frai.2025.1559900 |
| 10 | A deep fusion model for stock market prediction with news headlines and time series data | Chen, P., Boukouvalas, Z., Corizzo, R. | 2025 | [—](https://doi.org/10.1007/s00521-024-10303-1(0123456789().,-volV)(0123456789,-().volV)) https://doi.org/10.1007/s00521-024-10303-1(0123456789().,-volV)(0123456789,-().volV) |
| 11 | Innovative Sentiment Analysis and Prediction of Stock Price Using FinBERT, GPT-4 and Logistic Regression: A Data-Driven Approach | Shobayo, O, Adeyemi-Longe, S., Popoola, O., Ogunleye, B. | 2024 | [—](https://doi.org/10.3390/bdcc8110143) https://doi.org/10.3390/bdcc8110143|
| 12 | Enhancing Stock Market Predictions with Social Media Sentiment and Multi-Headed Attention Mechanisms | Ahire, V., Borase, S. | 2024 |  DOI: 10.47857/irjms.2024.v05i04.01491 |
| 13 | 	Incorporating Multi-Source Market Sentiment and Price Data for Stock Price Prediction | Fu, K., Zhang, Y. | 2024 | [—](https://doi.org/10.3390/math12101572) https://doi.org/10.3390/math12101572|
| 14 | 	Sentiment trading with large language models | Kirtac, K., Germano, G. | 2024 | [—](https://doi-org.ez278.periodicos.capes.gov.br/10.1016/j.frl.2024.105227) https://doi-org.ez278.periodicos.capes.gov.br/10.1016/j.frl.2024.105227|
| 15 | 	Can ChatGPT assist in picking stocks? | Pelster, M., Val, J. | 2024 | [—](https://doi-org.ez278.periodicos.capes.gov.br/10.1016/j.frl.2023.104786) https://doi-org.ez278.periodicos.capes.gov.br/10.1016/j.frl.2023.104786|
| 16 | 	FinBERT and LSTM-based novel model for stock price prediction using technical indicators and financial news | Bathla, G., Gupta, S. | 2024 | DOI: 10.1504/IJEBR.2023.10044437 |
| 17 | 	Developing and testing a custom algorithmic trading strategy using exponential moving average, relative strength index, and sentiment analysis | Mehra, S.D., Shetty, S.D. | 2024 | doi: 10.32629/jai.v7i4.1328|
| 18 | 	Transforming sentiment analysis in the financial domain with ChatGPT | Fatouros, G., Soldatos, J., Kouroumali, K., Makridis, G., Kyriazis, D. | 2023 | [—](https://doi-org.ez278.periodicos.capes.gov.br/10.1016/j.mlwa.2023.100508) https://doi-org.ez278.periodicos.capes.gov.br/10.1016/j.mlwa.2023.100508 |
| 19 | 	Forecasting the S&P 500 Index Using Mathematical-Based Sentiment Analysis and Deep Learning Models: A FinBERT Transformer Model and LSTM | Kim, J., Kim, H.-S. , Choi, S.-Y. | 2023 | [—](https://doi.org/10.3390/axioms12090835)  https://doi.org/10.3390/axioms12090835|
| 20 | 	Stock price movement prediction based on Stocktwits investor sentiment using FinBERT and ensemble SVM | Liu, J.-X., Leu, J.-S., Holst, S. | 2023 | [—](https://doi.org/10.7717/peerj-cs.1403) https://doi.org/10.7717/peerj-cs.1403 |
| 21 | 	Stock trend prediction using deep learning approach on technical indicator and industrial specific information | Prachyachuwong, K., Vateekul, P. | 2021 | [—](https://doi.org/10.3390/info12060250) https://doi.org/10.3390/info12060250 |
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
