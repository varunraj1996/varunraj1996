## Varun Vavilala

Data Engineer — pipelines, warehouses, SQL and analytics — currently building retrieval and evaluation systems on top of LLMs.

### Recent work

**[10k-rag](https://github.com/varunraj1996/10k-rag)** — a question-answering system over SEC 10-K filings. Answers carry citations or refuse when the source doesn't support them, and correctness is scored automatically against SEC XBRL filings rather than judged by another model: **8/9 in-tolerance numeric accuracy, 3/3 correct refusals**. The README documents the one failure I diagnosed and chose to leave in, with the reasoning.

**warehouse-agent** *(in progress)* — natural-language questions answered over a SQL database, with the access governed rather than trusted: read-only by database grant, a SQL-parsing policy layer that blocks queries touching restricted columns, and a semantic layer so the same question returns the same number every time.

### Toolkit

SQL, Python, dbt-style modeling, Databricks, LangChain/LangGraph, retrieval and evaluation pipelines.

[LinkedIn](https://www.linkedin.com/in/varun-raj-101150156/)
