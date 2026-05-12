# Batch ETL Pipeline

Airflow + Spark + dbt 기반의 배치 ETL 파이프라인 학습 프로젝트입니다.

---

# 프로젝트 목표

- Airflow DAG 구성
- Spark 기반 데이터 변환
- dbt 모델링
- S3 + RDS 연동
- Parquet 기반 배치 처리 이해

---

# Tech Stack

- Python
- Apache Airflow
- Apache Spark
- dbt
- PostgreSQL (RDS)
- AWS S3
- Terraform

---

# 디렉토리 구조

```text
batch-etl-pipeline/
├── airflow/
├── dbt/
├── terraform/
├── spark/
├── tests/
└── README.md
```

---

# Pipeline Flow

1. Raw 데이터 수집
2. Spark Transform 수행
3. Parquet 저장
4. dbt 모델링
5. Warehouse 적재

---

# 핵심 학습 내용

## Airflow
- DAG 작성
- Task Dependency
- Retry 정책
- XCom 기초

## Spark
- DataFrame 처리
- Join
- Shuffle 이해
- Partition 관리

## dbt
- staging / mart 구조
- dbt test
- 모델 분리

## Terraform
- S3 구성
- RDS 연결
- 변수 관리
- backend 구성

---

# 테스트

- Airflow DAG test
- Spark transform test
- pytest 기반 검증

---

# CI

- Python lint
- pytest
- dbt test
- terraform validate

---

# 학습 목표

- 안정적인 배치 ETL 구조 이해
- Spark 기반 대용량 처리 감각 습득
- 데이터 파이프라인 문서화 경험
