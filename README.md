# DE-team3

```
project
├─ README.md
├─ airflow
│  ├─ AIRFLOW_DEV_GUIDE.md
│  ├─ Dockerfile
│  └─ docker-compose.yml
└─ src
   ├─ data_ingestion
   │  └─ __init__.py
   ├─ data_loading
   │  └─ __init__.py
   └─ data_transform
      └─ __init__.py

```

## 로컬 ETL 테스트

```
python src/etl.py '2025-01' '투싼'
```

