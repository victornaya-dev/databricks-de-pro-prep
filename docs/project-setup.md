# Databricks Data Engineer — Professional Certification Prep

## Project Description
End-to-end Databricks Data Engineering portfolio project built with Colab/PySpark notebooks.
Goal: fully prepare for the Databricks Certified Data Engineer Professional exam.
Covers Delta Lake, Auto Loader, DLT, medallion architecture, Unity Catalog,
streaming, testing, and CI/CD.

> **Note (project spirit):** The idea behind this project is to prepare in an easy
> and enjoyable (gamified/playful) way — using hands-on Colab notebooks for each
> module as the main learning tool to reach a real, job-ready level in Spark and
> Databricks, not just theory.

## Custom Instructions (public version)
```
You are helping me build a Databricks Data Engineering project to prepare for
the Databricks Certified Data Engineer Professional exam.

Rules:
- All code, comments, and docs in English.
- Use PySpark, runnable in Google Colab (no Databricks account required unless noted).
- Every module must include a runnable Google Colab notebook (.ipynb) so the code
  can be tested locally/in-browser, not just explained in text.
- Keep explanations concise, practical, and example-driven — favor learning by doing.
- Prioritize topics by exam relevance and real-world applicability.
- Each module must map to one or more of the 4 exam domains:
  1. Databricks Tooling
  2. Data Processing
  3. Data Modeling
  4. Security, Governance, Monitoring & Testing
```

> Note: the full version of these instructions (including the real
> interview-prep goal) lives in `private/project-instructions-full.md`,
> which is gitignored and never pushed to the repo.

## Build Order

| # | Module | Exam Domain | Notebook |
|---|--------|-------------|----------|
| 1 | Medallion Architecture (Bronze/Silver/Gold) | Data Modeling | `module_1_medallion_architecture.ipynb` |
| 2 | Delta Lake (ACID, MERGE, time travel, optimize/vacuum) | Tooling | `module_2_delta_lake.ipynb` |
| 3 | Batch pipelines + PySpark transformations | Data Processing | `module_3_batch_pipelines.ipynb` |
| 4 | Auto Loader + Structured Streaming | Data Processing | `module_4_autoloader_streaming.ipynb` |
| 5 | Delta Live Tables (DLT) | Data Processing | `module_5_dlt.ipynb` |
| 6 | SCD Type 1/2, schema evolution | Data Modeling | `module_6_scd.ipynb` |
| 7 | Unity Catalog basics (governance concepts) | Security/Governance | `module_7_unity_catalog.ipynb` |
| 8 | Testing (pytest for pipelines) + logging/monitoring | Monitoring/Testing | `module_8_testing.ipynb` |
| 9 | CI/CD (GitHub Actions → Databricks Jobs) | Tooling | `module_9_cicd.ipynb` |
| 10 | Mock exam questions + README/portfolio polish | All domains | `module_10_mock_exam.ipynb` |

## Next Step
Create the Project in claude.ai using the name, description, and instructions above,
then request each module's notebook in order (e.g. "give me the notebook for module 1").
Each notebook opens directly in Google Colab (File → Upload notebook, or drag & drop)
and installs PySpark in its first cell so it runs without a Databricks account.
