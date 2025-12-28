# trading_app
Tracking trading, creating models, and displaying results

trading_app/
├── .env.template
├── .gitignore
├── README.md
├── pyproject.toml
├── requirements.txt
│
├── data/
│   ├── external/
│   ├── processed/
│   ├── raw/
│   ├── real_time/
│   └── trade_logs/
│
├── docs/
│   ├── planning/
│   │   ├── architecture_decisions.md
│   │   ├── backlog.md
│   │   ├── glossary_finance_terms.md
│   │   ├── roadmap.md
│   │   └── weekly_log.md
│   ├── references/
│   │   ├── causal_ml_notes.md
│   │   ├── financial_microstructure.md
│   │   ├── papers_to_read.md
│   │   ├── resources.md
│   │   └── time_series_models.md
│   └── system_design/
│       ├── agent_system_design.md
│       ├── backtester_arch.md
│       ├── dashboard_design.md
│       ├── data_flow.md
│       ├── execution_pipeline.md
│       └── diagrams/
│           └── backtester_flow.png
│
├── notebooks/
│   ├── backtesting/
│   ├── causal/
│   ├── dashboard/
│   ├── exploration/
│   └── modeling/
│
├── src/
│   ├── agents/
│   │   ├── filings_agent.py
│   │   ├── multi_agent_system.py
│   │   ├── news_agent.py
│   │   ├── risk_agent.py
│   │   ├── sentiment_agent.py
│   │   └── synthesis_agent.py
│   ├── analysis/
│   │   ├── causal_analysis.py
│   │   ├── feature_importance.py
│   │   ├── post_trade_analysis.py
│   │   ├── regime_analysis.py
│   │   └── slippage_analysis.py
│   ├── backtesting/
│   │   ├── event_engine.py
│   │   ├── performance.py
│   │   ├── portfolio.py
│   │   ├── position_sizing.py
│   │   ├── slippage.py
│   │   ├── transaction_costs.py
│   │   └── vectorized_backtester.py
│   ├── core/
│   │   ├── config.py
│   │   ├── logging.py
│   │   └── utils.py
│   ├── dashboard/
│   │   ├── alerts.py
│   │   ├── app.py
│   │   ├── portfolio.py
│   │   ├── positions.py
│   │   ├── recommendations.py
│   │   ├── risk.py
│   │   ├── trades.py
│   │   ├── components/
│   │   │   ├── charts.py
│   │   │   ├── indicators.py
│   │   │   └── tables.py
│   │   └── pages/
│   ├── data/
│   │   ├── causal_features.py
│   │   ├── clean.py
│   │   ├── feature_engineering.py
│   │   ├── ingest.py
│   │   ├── preprocess.py
│   │   ├── real_time_ingest.py
│   │   └── storage.py
│   ├── execution/
│   │   ├── live_trading.py
│   │   ├── paper_trading.py
│   │   ├── real_time_signals.py
│   │   └── brokers/
│   │       ├── alpaca.py
│   │       ├── ccxt_client.py
│   │       └── ibkr.py
│   ├── modeling/
│   │   ├── baseline_models.py
│   │   ├── evaluation.py
│   │   ├── model_monitoring.py
│   │   ├── model_registry.py
│   │   ├── training.py
│   │   └── advanced_models/
│   │       ├── hybrids.py
│   │       ├── nbeats.py
│   │       ├── patchtst.py
│   │       ├── tft.py
│   │       └── tide.py
│   ├── risk/
│   │   ├── kill_switch.py
│   │   ├── portfolio_risk.py
│   │   └── trade_risk.py
│   └── tools/
│       ├── email_alerts.py
│       ├── news_api.py
│       ├── sec_filings.py
│       ├── sentiment_api.py
│       └── vectorstore.py
│
└── tests/
    ├── test_agents.py
    ├── test_backtester.py
    ├── test_dashboard.py
    ├── test_data_pipeline.py
    ├── test_models.py
    └── test_risk.py
