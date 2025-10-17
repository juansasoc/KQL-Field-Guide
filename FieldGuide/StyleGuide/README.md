# KQL Style Guide

- Put `let` parameters at the top
- Comment the intent, data sources, and expected output
- Use `project`/`project-away` early to reduce columns
- Summarize early; join summarized sets
- Use `materialize()` for heavy reused subqueries
- Always time-bound queries (e.g., `ago(24h)`)
