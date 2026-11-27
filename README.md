# Zhongyuan Hu · 胡中远

**MSc Data Science @ Lingnan University (2026–27)** · Hong Kong  
I build LLM agents that can be supervised — constrained by design, auditable after the fact — and forecasting systems where evaluation gets as much attention as the model.

> 🎯 **Open to 2026–27 internships** in Agent Governance / Trustworthy ML / Data Science.
> 
> 📬 **Contact:** [zhongyuanhu@ln.hk](mailto:zhongyuanhu@ln.hk) (Email) · [GitHub](https://github.com/pzzzannnlvvv)  
> 💬 **WeChat:** `13612683962` · **WhatsApp:** [+852 5444 1597](https://wa.me/85254441597)
> 💼 **LinkedIn:** [LinkedIn](https://linkedin.com/in/hu-zhongyuan-539560430)

---

## 📄 Research & Publications

**Constraint Engineering as Human Oversight** — *TAIG 2026, Paper 0045*  
A four-layer framework (workflow · tool · knowledge · output) for controllable LLM agents. On eight audited tasks: constrained system completed **8/8** with **zero unsupported numeric claims** out of ~1,400 checked; baseline completed none and fabricated ~100 values.  
`Human oversight` `Agent governance` `EU AI Act Art. 14`

**Income Assessment of Poor Families in Latin America Based on Machine Learning** — *ACM CMNM 2025, First Author*  
23 interpretable features across 12 countries; Bagging over 9 base models: **90.49% accuracy** (+19.6 pts over PMT proxy), **94.8% recall**. [DOI](https://doi.org/10.1145/3757110.3757170)

## 💼 Experience & Projects

**Data Scientist Intern** @ *Sublime China Information Group (卓创资讯)* | 2026.05 – 2026.08  
**[iron-ore-inventory-forecast](https://github.com/pzzzannnlvvv/iron-ore-inventory-forecast)**
- Independently built end-to-end weekly port-inventory forecasting model, achieving **84.91% MDA** (MAPE 2.87%).
- Engineered 3,200+ features from 700+ multi-frequency factors, solving publication-lag look-ahead bias and stationarity (ADF/KPSS).
- Designed a 4-stage feature compression pipeline (LightGBM Gain, Spearman, etc.) reducing ~800 features to ~16, boosting generalization. Built with LightGBM + Optuna (9-dim search, 100% reproducible).

**[iron-ore-agent](https://github.com/pzzzannnlvvv/iron-ore-agent)** | *Personal Project*
- LangGraph + MCP research agent: `coordinator → planner → human check → research team → reporter`. 
- Wrapped 8 MCP tools (based on FastMCP) to decouple model inference from LLM. One question triggers ~18 tool calls and returns a structured report via FastAPI + SSE.

**Data Analyst Intern** @ *Codemao Technology (点猫科技)* | 2025.07 – 2025.09
- Led warehouse architecture design and built RFM models to segment 5 user tiers.
- Diagnosed retention drop via funnel analysis and SQL, directly informing product iteration; built Tableau dashboards for business teams.

## 🛠️ Toolbox

`Python` `SQL` `LightGBM` `Optuna` `LangGraph` `MCP` `FastAPI` `pandas/scikit-learn` `Spark/Hive` `Django` `Tableau`

<details>
<summary><b>More (Undergraduate Thesis & Current Build)</b></summary>

- **Undergraduate Thesis (Network Traffic Detection)**: Processed 196K records, engineered 12 ratio/variation features, two-stage selection cutting dimensionality by 73%. Bagging over 9 base learners, wrapped in a Django interface.
- **In Progress**: Building an AWS serverless pipeline (S3 + Lambda + Athena + DynamoDB + CDK) to productionise the forecasting model.
</details>

---

*Based in Hong Kong · 中文 / 粤语 / English*
