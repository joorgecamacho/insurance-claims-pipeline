# insurance-claims-pipeline
# Insurance Claims Data Pipeline

This project simulates a real-world big data ingestion and processing pipeline for insurance claims, designed to practice the skills required for a Big Data Developer role.

##  Project Goals

- Simulate ingestion of raw insurance claims data.
- Clean and transform the data using PySpark.
- Perform analytical queries using Spark SQL.
- Store processed data in efficient formats (Parquet).
- Build unit and integration tests for data transformations.
- Document the pipeline end-to-end.

---

##  Stack

| Layer            | Technology             |
|------------------|------------------------|
| Ingestion        | PySpark (Spark)        |
| Processing       | PySpark / Spark SQL    |
| Storage (raw)    | CSV files              |
| Storage (output) | Parquet files          |
| Orchestration    | (Optional) Airflow     |
| Testing          | Pytest + custom utils  |
| Docs             | Markdown               |

---

##  Project Structure

```bash
insurance-claims-pipeline/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── pipeline/
│   ├── ingest.py
│   ├── transform.py
│   ├── utils.py
├── tests/
│   ├── test_transform.py
├── README.md
├── requirements.txt
└── spark-submit.sh
