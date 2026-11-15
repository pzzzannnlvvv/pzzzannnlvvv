# Zhongyuan Hu · 胡中远

MSc Data Science student at Lingnan University, Hong Kong (2026–27). I build LLM agents that can
be supervised — constrained by design, auditable after the fact — and forecasting systems where the
evaluation gets as much attention as the model.

Looking for 2026–27 internship opportunities in **agent governance** and **trustworthy ML**.

---

## Selected work

**[iron-ore-agent](https://github.com/pzzzannnlvvv/iron-ore-agent)** — a LangGraph + MCP research
agent for iron-ore inventory analysis.
`coordinator → planner → human check → research team → reporter`, with 8 MCP tools wrapping a
forecasting model, served over FastAPI with SSE streaming. One question triggers ~18 tool calls and
returns a structured report. I re-built the research-service architecture I worked with during my
internship, then wrapped it in the constraint layers I write about below.

**[iron-ore-inventory-forecast](https://github.com/pzzzannnlvvv/iron-ore-inventory-forecast)** —
weekly port-inventory forecasting.
27 inventory series × 705 multi-frequency factors (2015–2026) aligned onto one weekly timeline,
~3,200 engineered features, LightGBM + Optuna (200 trials, 9-dim search, TPE with median pruning),
a 4-stage feature-compression pipeline, and ADF/KPSS stationarity checks. Built as a data science
intern at Sublime China Information Group.

> Benchmark note: the first run reported 0.849 directional accuracy / 2.87% MAPE on a 56-week
> hold-out. I later found a publication-lag look-ahead bias in the monthly and quarterly factors,
> so I'm re-benchmarking with release-date alignment instead of quoting that number.

**Network traffic detection with ensemble learning** — undergraduate thesis.
196K traffic records, 12 derived ratio/variation features, two-stage selection (correlation filter +
mutual-information top-K) cutting dimensionality by 73%, Bagging over 9 base learners, wrapped in a
Django interface for parameterised experiments.

## Papers & talks

**Constraint Engineering as Human Oversight: A Four-Layer Framework for Controllable LLM Agents**
TAIG 2026, Paper 0045, Hong Kong (Nov 2026) — accepted for presentation; the full paper follows the
talk. Four constraint layers around an LLM agent — workflow, tool, knowledge, output — trading
flexibility for controllability. On eight audited tasks the constrained system completed 8/8 with
zero unsupported numeric claims out of ~1,400 checked; the unconstrained baseline completed none and
fabricated ~100 values, and two prohibited tool calls were intercepted at the tool boundary.

**Research on Income Assessment of Poor Families in Latin America Based on Machine Learning**
First author, ACM CMNM 2025, pp. 351–356.
[doi:10.1145/3757110.3757170](https://doi.org/10.1145/3757110.3757170)
23 interpretable household features across 12 countries; a Bagging ensemble over 9 base models
reaching 90.49% accuracy (+19.6 points over the traditional PMT proxy) with 94.8% recall.

## Toolbox

Python · SQL · pandas / scikit-learn · LightGBM · Optuna · LangGraph · MCP · FastAPI ·
Hadoop / Hive / Spark · Django · Tableau

## Elsewhere

- **Codemao Technology** — data analytics intern (user growth), 2025. Layered warehouse design,
  RFM segmentation into 5 tiers, funnel and retention analysis, Tableau reporting.
- Currently building an AWS serverless pipeline (S3 + Lambda + Athena + DynamoDB + CDK) to
  productionise the forecasting model — in progress, not deployed yet.

## Contact

- Email: zhongyuanhu@ln.hk
- Based in Hong Kong · 中文 / English
