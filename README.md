# dbt-snowflake-databricks-lineage-auditor

dbt Snowflake Databricks Lineage Auditor is a Kinetic Gain portfolio proof repo for **dbt, Snowflake, Databricks** across Data Engineering.

It turns analytics lineage, warehouse trust, transformation freshness, and semantic-layer risk into a small board-readable intelligence packet: where risk is building, where money is leaking, what deserves investment, and what story leaders can tell with evidence.

## Platform and company signals

- dbt
- Snowflake
- Databricks

## What it includes

- runnable Node CLI for summarizing synthetic control-plane lanes
- JSON fixture with exposure, savings, and investment lanes
- static proof page in site/index.html
- lightweight CI using Node's built-in test runner
- no production credentials, no customer data, no external API calls

## Local run

`powershell
npm test
npm run demo
npm run build
`

## Output shape

`json
{
  "product": "dbt Snowflake Databricks Lineage Auditor",
  "signals": ["dbt", "Snowflake", "Databricks"],
  "averageScore": 82,
  "priorityLane": "investment"
}
`

## Kinetic Gain fit

This repo supports the Platform and Company Signals layer of the portfolio atlas. It is intentionally small, readable, and evidence-oriented so executives can see the operating pattern without requiring access to live enterprise systems.