### Hi, I'm Sumant Chakravarty 👋

I work on data science and machine learning projects: collecting and cleaning messy data, testing what it can and cannot support, and turning the results into models, services and business decisions people can use.

**Currently:** building end-to-end machine learning projects in Python and competing on Kaggle.

---

#### Featured projects

Each project states its business problem, the baseline it beats, and whether its impact is measured, backtested or simulated.

| Project | Problem → result (against baseline) | Evidence |
|---|---|---|
| [**Multi-Echelon Inventory**](https://github.com/Sumant-crty/multi-echelon-inventory) | Where to hold safety stock (distribution centre or store) for 17,719 Walmart store-items. LightGBM forecasts 10% more accurate than the best baseline; OR-Tools places stock and sets service levels; **25% less inventory** than a rule of thumb at the same 97% fill rate | **Simulation estimate:** real demand, assumed lead times and costs; held-out test year |
| [**Enterprise AI Data Assistant**](https://github.com/Sumant-crty/enterprise-ai-assistant) | Plain-English questions over 99,000 orders with RAG and text-to-SQL (local LLM or Claude), behind a SQL guard and role-based access. Retrieval raises SQL accuracy **from 44% to 68%** and cuts invented numbers from 21% to 4% of answers; no personal data leaked | **Evaluation** on 59 test questions; no business impact claimed |
| [**Supply Chain ETA**](https://github.com/Sumant-crty/supply-chain-eta) | Delivery-time prediction for 96,000 real orders: **3.6 days error** against 4.9 for the best baseline, turned into delivery promises 3.8 days shorter at the same late rate | **Backtest** on later real orders; money savings use assumed costs |
| [**Spare Parts Inventory**](https://github.com/Sumant-crty/spare-parts-inventory) | Stocking 2,509 intermittent-demand car parts: a global XGBoost policy costs **21.5% less** than a rule of thumb with a higher fill rate | **Simulation estimate:** real demand, assumed costs; held-out test year |
| [**Customer Churn**](https://github.com/Sumant-crty/customer-churn) | Which customers a retention campaign should target: churn risk × value earns **+£3,353** where contacting everyone loses £20,328; SHAP explains the drivers | **Backtest** on real churn outcomes; campaign economics assumed |
| [**Engine Failure Prediction**](https://github.com/Sumant-crty/engine-failure-prediction) | Remaining useful life of jet engines (NASA C-MAPSS): **15–16 cycles error**, 69–75% below a constant baseline, with survival analysis, a FastAPI service and drift monitoring | **Held-out test set** of simulated engines; no money estimate |

#### Other projects

| Project | What it shows |
|---|---|
| [**Falcon 9 Landing Prediction**](https://github.com/Sumant-crty/WinningSpaceRaceWithDataScience) | IBM capstone: SpaceX API and web scraping, SQL, Folium maps, a Plotly Dash app and four tuned classifiers, with an honest look at what 90 launches can support |
| [**Developer Technology Trends 2024**](https://github.com/Sumant-crty/IBM-Data-Analyst-Capstone-Project) | IBM capstone: 65,437 survey responses and 27,005 job postings; includes finding and fixing a counting bug that overstated one skill 30× |
| [**ROGII Wellbore Geology Prediction**](https://github.com/Sumant-crty/rogii-wellbore-geology-detector) | *In progress.* Kaggle competition: predicting geological position along horizontal wells with a particle filter, beam search, k-NN and a cross-validated ensemble |
| [**IARSA: academic research agent**](https://github.com/Sumant-crty/IARSA) | An LLM agent with tool servers built on the Model Context Protocol (schedules, syllabi, arXiv search) |
| [**FIFA World Cup Quiz**](https://github.com/Sumant-crty/fifaQuiz) | Full-stack app: React, Express, MongoDB, JWT authentication and a Gemini-powered assistant |

#### Tools

- **Data and ML:** Python · pandas · NumPy · scikit-learn · LightGBM · XGBoost · CatBoost · SHAP · survival analysis (lifelines, scikit-survival) · time-series and intermittent-demand forecasting · inventory optimisation · multi-echelon inventory · OR-Tools · SQL · Polars
- **Visualization:** Matplotlib · Seaborn · Plotly · Dash · Streamlit · Folium · IBM Cognos
- **GenAI:** RAG (BM25 + embeddings) · text-to-SQL · LLM evaluation · Claude API · Ollama · DuckDB · sqlglot
- **Engineering:** PostgreSQL · MLflow · FastAPI · Flask · Node.js · React · MongoDB · Docker · pytest · GitHub Actions · Git

#### Certifications

IBM Data Science Professional Certificate · IBM Data Analyst Professional Certificate

#### Contact

[LinkedIn](https://www.linkedin.com/in/sumant-chakravarty-b117b539/)
