# My Courseworks

Self-study courses on data engineering, data science and AI agent systems, written for interview preparation. Each course is organised into chapters or modules, and its examples have been run against the real system rather than copied from documentation.

## Courses

| Course | What it covers | Stack |
|---|---|---|
| [**bigquery-revision**](https://github.com/My-Courseworks/bigquery-revision) | 18 chapters of BigQuery SQL, from essentials through joins, window functions, arrays and structs, JSON, scripting, performance and cost, ending with a cheatsheet of gotchas. Includes scripts that seed a scratch dataset and a runner that checks every example against BigQuery. | BigQuery · Standard SQL · GCP |
| [**pyspark-coursework**](https://github.com/My-Courseworks/pyspark-coursework) | 5 modules of PySpark for data scientists, built around one running example (a churn model over a clickstream), plus a lab that runs the pipeline on 2 billion events locally and on Dataproc Serverless, with per-step metrics for shuffle and skew. | PySpark · Dataproc · BigQuery · GCP |
| [**Harness-Engineering**](https://github.com/My-Courseworks/Harness-Engineering) | 17 modules on designing the systems around AI agents: model failure modes, context engineering, the instruction layer, memory, tool interfaces and MCP, orchestration, evaluation, reliability, security, guardrails and observability. Every module ends with a design exercise, and the material is grounded in published research and the official ADK docs. | Google ADK · LiteLLM · MCP |

## How the courses are built

- **Built around interview questions.** Every chapter or module is organised around the questions an interviewer asks, such as what happens to unmatched rows, or why a job is slow.
- **Examples that run.** The SQL and Spark code can be executed, and each repo contains the scripts to run it yourself.
- **Gotchas stated plainly.** NULL handling, fan-out from duplicate keys, data skew and similar issues are pointed out where they come up.

## Start here

- Preparing for a SQL or analytics interview: start with the [BigQuery cheatsheet and gotchas](https://github.com/My-Courseworks/bigquery-revision/blob/main/chapters/18-cheatsheet-gotchas.md).
- Preparing for a Spark or data-science interview: start with the [PySpark interview talk-track](https://github.com/My-Courseworks/pyspark-coursework/blob/main/modules/05-interview-talk-track/README.md).
- Designing or reviewing an AI agent system: start with the [Harness Engineering syllabus](https://github.com/My-Courseworks/Harness-Engineering/blob/main/syllabus.md), then [M1 · What Is a Harness](https://github.com/My-Courseworks/Harness-Engineering/blob/main/modules/01-what-is-a-harness/README.md).
