# ДЗ 1 — Mart City Top Products (Spark + Zeppelin + Docker)
Домашнее задание по дисциплине "Семинар наставника"

## Стек
- Docker / Docker Compose  
- Apache Zeppelin 0.11.2  
- Apache Spark 3.5.1 (PySpark)

## Запуск

```bash
docker compose up -d --build
```

## Результат

Построена витрина `mart_city_top_products`. Для каждого города определены **top-2 товара по `revenue_sum`**.

Результат сохранён в формате **Parquet (overwrite)**:

- `/tmp/sandbox_zeppelin/mart_city_top_products/`
- `/tmp/sandbox_zeppelin/s3/mart_city_top_products/`

На хосте данные доступны в папке `./output/`.
