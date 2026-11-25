# 🚀 End-to-End Data Engineering Project using dbt & Databricks

![dbt](https://img.shields.io/badge/dbt-Core-orange)
![Databricks](https://img.shields.io/badge/Databricks-Platform-red)
![SQL](https://img.shields.io/badge/SQL-Language-blue)
![Jinja](https://img.shields.io/badge/Jinja-Templating-green)
![Git](https://img.shields.io/badge/Git-Version%20Control-orange)

## 📌 Project Overview

This project demonstrates an end-to-end Analytics Engineering workflow using **dbt Core** and **Databricks** following the Medallion Architecture (Bronze → Silver → Gold).

The project covers data transformation, testing, reusable SQL development with Jinja macros, snapshots for Slowly Changing Dimensions (SCD Type 2), Git version control, and deployment best practices.

---

# 🛠️ Tech Stack

- dbt Core
- Databricks
- SQL
- Jinja
- YAML
- Git & GitHub

---

# 📂 Project Structure

```
dbt_youtube/
│
├── analyses/
├── macros/
├── models/
│   ├── bronze/
│   ├── silver/
│   ├── gold/
│   └── source/
├── seeds/
├── snapshots/
├── tests/
├── dbt_project.yml
├── README.md
└── .gitignore
```

---

# 🏗️ Architecture

```
Raw Data
     │
     ▼
 Bronze Layer
     │
     ▼
 Silver Layer
     │
     ▼
 Gold Layer
```

### Bronze Layer

- Raw ingestion
- Minimal transformations
- Source data preservation

### Silver Layer

- Data cleaning
- Business transformations
- Derived columns
- Joins

### Gold Layer

- Business-ready datasets
- Reporting tables
- Analytics layer

---

# ✨ Features Implemented

## ✅ Models

- Bronze Models
- Silver Models
- Gold Models

---

## ✅ Jinja

- Variables
- Loops
- Conditions

---

## ✅ Macros

Created reusable SQL macros including:

- Multiply Macro
- Schema Generation Macro

---

## ✅ Tests

Implemented both generic and custom tests.

### Generic Tests

- unique
- not_null
- accepted_values

### Custom Generic Test

- non_negative

### Singular Test

- Custom SQL validation

---

## ✅ Snapshots

Implemented SCD Type 2 using dbt Snapshots.

Snapshot Strategy:

- Timestamp Strategy

---

## ✅ Seeds

Loaded static mapping data using CSV seed files.

---

# 📊 Workflow

```
Raw Data

↓

Bronze Models

↓

Tests

↓

Silver Models

↓

Gold Models

↓

Snapshots

↓

Analytics
```

---

# 🧪 Common dbt Commands

### Parse Project

```bash
dbt parse
```

### Build Everything

```bash
dbt build
```

### Run Models

```bash
dbt run
```

### Run Tests

```bash
dbt test
```

### Run Snapshots

```bash
dbt snapshot
```

### Generate Documentation

```bash
dbt docs generate
dbt docs serve
```

---

# 🔄 Git Workflow Used

- Feature Branch
- Merge to Main
- Git Commit
- Git Push
- GitHub Repository

---

# 📚 Concepts Covered

- dbt Project Structure
- Models
- Materializations
- Sources
- Jinja
- Macros
- Generic Tests
- Singular Tests
- Custom Generic Tests
- Seeds
- Snapshots
- Git Integration
- Development vs Production Targets

---

# 📸 Screenshots

> Screenshots will be added soon.

Suggested screenshots:

- Databricks Workspace
- dbt Build Output
- Test Results
- Snapshot Execution
- GitHub Repository
- Catalog Explorer

---

# 🎯 Learning Outcomes

Through this project I learned:

- Building modular SQL transformations using dbt
- Organizing projects using Medallion Architecture
- Writing reusable SQL with Jinja Macros
- Implementing data quality tests
- Managing Slowly Changing Dimensions with Snapshots
- Version controlling analytics projects using Git & GitHub
- Working with Databricks as the execution platform

---

# 📖 Reference

This project was built while learning dbt and Databricks concepts through the excellent tutorial series by **Ansh Lamba**, with additional experimentation and customization during implementation.

---

## 👨‍💻 Author

**Muhammed Sahil R M**

Computer Science Engineer

Aspiring Data Engineer

GitHub: https://github.com/Sahilzackriya