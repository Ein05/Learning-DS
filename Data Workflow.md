# Hệ sinh thái dữ liệu theo quy mô doanh nghiệp

## Doanh nghiệp lớn

```text
ERP / CRM / Website / App
            ↓
        Data Lake
            ↓
    ETL / ELT Pipeline
            ↓
     Data Warehouse
            ↓
    ┌───────────────┐
    ↓               ↓
Data Analyst   Data Scientist
    ↓               ↓
Dashboard      ML Model / AI
    ↓               ↓
    └───────┬───────┘
            ↓
      Business Decision
```


---

## Doanh nghiệp vừa

```text
ERP / CRM
      ↓
 Database
      ↓
 SQL + Python
      ↓
 ┌───────────┐
 ↓           ↓
DA          DS
 ↓           ↓
BI      ML Model
```

Nhiều doanh nghiệp vừa không tách biệt hoàn toàn DA và DS. Một người có thể đảm nhiệm cả hai vai trò.

---

## Doanh nghiệp nhỏ

### Mô hình 1

```text
Excel / Google Sheets
        ↓
      Power BI
        ↓
    Data Analyst
```

### Mô hình 2

```text
Excel / CSV
      ↓
 Pandas
      ↓
 Data Scientist
      ↓
 Scikit-learn
      ↓
 Prediction
```

### Mô hình 3

```text
MISA / Odoo
      ↓
 Export Excel
      ↓
 Power BI
```

---

## Hệ sinh thái dữ liệu hoàn chỉnh

```text
Data Source
     ↓
Data Engineer
     ↓
Data Warehouse
     ↓
 ┌───────────────┬───────────────┐
 ↓               ↓               ↓
DA              BI              DS
 ↓               ↓               ↓
Dashboard    Reporting      ML/AI Model
```

### Trách nhiệm chính

| Vai trò        | Công việc                                         |
| -------------- | ------------------------------------------------- |
| Data Engineer  | Xây dựng pipeline, ETL, Data Lake, Data Warehouse |
| Data Analyst   | Dashboard, KPI, phân tích dữ liệu                 |
| BI Analyst     | Reporting, Business Intelligence                  |
| Data Scientist | Machine Learning, AI, dự báo                      |

---

## Lộ trình học Data Analyst

```text
Excel
  ↓
SQL
  ↓
Power BI
  ↓
Python
  ↓
Data Warehouse
```

---

## Lộ trình học Data Scientist

```text
Python
  ↓
NumPy
  ↓
Pandas
  ↓
Matplotlib
  ↓
Statistics
  ↓
Machine Learning
  ↓
Deep Learning
  ↓
MLOps
```
