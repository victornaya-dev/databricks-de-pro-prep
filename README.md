# Databricks Data Engineer — Professional Certification Prep

Proyecto portfolio end-to-end en PySpark/Colab para preparar el examen
**Databricks Certified Data Engineer Professional**.

## Arquitectura del proyecto

```
databricks-de-pro-prep/
├── README.md
├── .gitignore
├── docs/
│   ├── project-setup.md          # instrucciones y build order del proyecto
│   └── calendario-databricks.md  # plan de estudio (~5-6 semanas)
├── private/                      # NO se sube a git (ver .gitignore)
│   └── interview-questions/      # banco de preguntas de entrevista, uso personal
└── notebooks/
    ├── module_1_medallion_architecture.ipynb   # Bronze/Silver/Gold
    ├── module_2_delta_lake.ipynb               # (pendiente)
    ├── module_3_batch_pipelines.ipynb          # (pendiente)
    ├── module_4_autoloader_streaming.ipynb     # (pendiente)
    ├── module_5_dlt.ipynb                      # (pendiente)
    ├── module_6_scd.ipynb                      # (pendiente)
    ├── module_7_unity_catalog.ipynb            # (pendiente)
    ├── module_8_testing.ipynb                  # (pendiente)
    ├── module_9_cicd.ipynb                     # (pendiente)
    └── module_10_mock_exam.ipynb               # (pendiente)
```

## Módulos (orden de build)

| # | Módulo | Dominio examen |
|---|--------|-----------------|
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

Cada notebook corre standalone en Google Colab (instala PySpark/Delta en la primera celda).

Ver `docs/calendario-databricks.md` para el plan de estudio y `docs/project-setup.md`
para las instrucciones completas usadas en este proyecto.
