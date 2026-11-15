# Zhongyuan Hu · 胡中远

**MSc Data Science @ Lingnan University (2026–27)** · Hong Kong  
I build LLM agents that can be supervised — constrained by design, auditable after the fact — and forecasting systems where evaluation gets as much attention as the model.

> **Open to 2026–27 internships** in agent governance / trustworthy ML.  
> [Email](mailto:zhongyuanhu@ln.hk) · [GitHub](https://github.com/pzzzannnlvvv) · [LinkedIn](https://linkedin.com/in/zhongyuanhu)

---

## Research

**Constraint Engineering as Human Oversight** — *TAIG 2026, Paper 0045*  
A four-layer framework (workflow · tool · knowledge · output) for controllable LLM agents. On eight audited tasks: constrained system completed **8/8** with **zero unsupported numeric claims** out of ~1,400 checked; baseline completed none and fabricated ~100 values; two prohibited tool calls intercepted at the tool boundary.  
`Human oversight` `Agent governance` `EU AI Act Art. 14`

**Income Assessment of Poor Families in Latin America Based on Machine Learning** — *ACM CMNM 2025, first author*  
23 interpretable features across 12 countries; Bagging over 9 base models: **90.49% accuracy** (+19.6 pts over PMT proxy), **94.8% recall**. [DOI](https://doi.org/10.1145/3757110.3757170)

## Projects

**iron-ore-agent** — [code](https://github.com/pzzzannnlvvv/iron-ore-agent)  
LangGraph + MCP research agent for iron-ore inventory analysis: `coordinator → planner → human check → research team → reporter`, 8 MCP tools, FastAPI + SSE. One question triggers ~18 tool calls and returns a structured report.

**iron-ore-inventory-forecast** — [code](https://github.com/pzzzannnlvvv/iron-ore-inventory-forecast)  
Weekly port-inventory forecasting: 27 series × 705 multi-frequency factors → ~3,200 features; LightGBM + Optuna (200 trials), 4-stage feature compression, ADF/KPSS checks. Built as a data science intern at Sublime China Information Group.  
> Earlier 0.849 directional accuracy / 2.87% MAPE had publication-lag look-ahead bias; re-benchmarking with release-date alignment.

## Toolbox

`Python` `SQL` `pandas/scikit-learn` `LightGBM` `Optuna` `LangGraph` `MCP` `FastAPI` `Spark/Hive` `Django` `Tableau`  
Currently building an AWS serverless pipeline (S3 + Lambda + Athena + DynamoDB + CDK) to productionise the forecasting model.

## More

<details>
<summary>Experience & undergraduate work</summary>

- **Codemao Technology** — Data analytics intern (user growth), 2025. Layered warehouse, RFM 5-tier segmentation, funnel/retention analysis, Tableau reporting.
- **Undergraduate thesis** — Network traffic detection with ensemble learning: 196K records, 12 derived features, two-stage selection cutting dimensionality by 73%, Bagging over 9 base learners, Django interface.
</details>

## Contact

- Email: [zhongyuanhu@ln.hk](mailto:zhongyuanhu@ln.hk)
- GitHub: [github.com/pzzzannnlvvv](https://github.com/pzzzannnlvvv)
- LinkedIn: [linkedin.com/in/zhongyuanhu](https://linkedin.com/in/zhongyuanhu)
- Based in Hong Kong · 中文 / English
