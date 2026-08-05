# Databricks Data Engineer — Professional Certification Prep

End-to-end portfolio project in PySpark/Colab to prepare for the
**Databricks Certified Data Engineer Professional** exam.

## Project Architecture

```
databricks-de-pro-prep/
├── README.md
├── .gitignore
├── docs/
│   ├── project-setup.md          # project instructions and build order
│   └── calendario-databricks.md  # study plan (~5-6 weeks)
├── private/                      # NOT pushed to git (see .gitignore)
│   └── interview-questions/      # interview question bank, personal use
└── notebooks/
    ├── module_1_medallion_architecture.ipynb   # Bronze/Silver/Gold
    ├── module_2_delta_lake.ipynb               # (pending)
    ├── module_3_batch_pipelines.ipynb          # (pending)
    ├── module_4_autoloader_streaming.ipynb     # (pending)
    ├── module_5_dlt.ipynb                      # (pending)
    ├── module_6_scd.ipynb                      # (pending)
    ├── module_7_unity_catalog.ipynb            # (pending)
    ├── module_8_testing.ipynb                  # (pending)
    ├── module_9_cicd.ipynb                     # (pending)
    └── module_10_mock_exam.ipynb               # (pending)
```

## Modules (build order)

| # | Module | Exam Domain |
|---|--------|--------------|
| 1 | Medallion Architecture | Data Modeling |
| 2 | Delta Lake (ACID, MERGE, time travel) | Tooling |
| 3 | Batch pipelines + PySpark | Data Processing |
| 4 | Auto Loader + Streaming | Data Processing |
| 5 | Delta Live Tables (DLT) | Data Processing |
| 6 | SCD Type 1/2 | Data Modeling |
| 7 | Unity Catalog | Security/Governance |
| 8 | Testing + monitoring | Monitoring/Testing |
| 9 | CI/CD | Tooling |
| 10 | Mock exam + portfolio | All domains |

Each notebook runs standalone in Google Colab (installs PySpark/Delta in the first cell).

See `docs/calendario-databricks.md` for the study plan and `docs/project-setup.md`
for the full instructions used to build this project.
