# Project 1 — End-to-End Data Engineering with Microsoft Fabric

## 📌 Overview

This project demonstrates the design and implementation of an **end-to-end data engineering solution using Microsoft Fabric**, following modern lakehouse and analytics engineering best practices.

The goal is to build a complete data pipeline — from raw data ingestion to analytics-ready datasets — using **public datasets**, with a strong focus on:
- Data architecture
- Transformation logic
- Analytics readiness
- Documentation and maintainability

This is a **portfolio project**, but intentionally structured to resemble a real-world data platform scenario.

---

## 🎯 Objectives

- Design a scalable **lakehouse architecture** using Microsoft Fabric
- Implement data ingestion and transformation pipelines
- Apply the **Medallion Architecture** (Bronze / Silver / Gold)
- Prepare clean, analytics-ready datasets for consumption
- Demonstrate engineering reasoning and best practices

---

## 📊 Dataset

- **Source:** Public datasets (as defined during the project design phase)
- **Type:** Structured data
- **Purpose:** Chosen to allow realistic transformations, modeling, and analytics use cases

The dataset selection prioritizes **clarity of transformations and architectural decisions** rather than domain complexity.

---

## 🏗️ Architecture

The solution is built entirely on **Microsoft Fabric**, using a lakehouse-centric approach.

### Core Components
- **OneLake** — unified storage layer
- **Lakehouse** — central data storage and processing
- **Data Pipelines** — orchestration and ingestion
- **Notebooks (PySpark)** — data transformations and enrichment


### Architectural Pattern
- **Medallion Architecture**
  - **Bronze:** Raw, ingested data
  - **Silver:** Cleaned and standardized data
  - **Gold:** Analytics-ready, business-focused datasets

---

## 🔄 Data Flow

1. **Ingestion**
   - Raw data is ingested from public sources into the Bronze layer
   - Minimal transformations applied

2. **Transformation**
   - Data is cleaned, standardized, and validated in the Silver layer
   - Business rules and enrichments applied using PySpark and SQL

3. **Analytics Layer**
   - Gold layer designed for analytical consumption
   - Optimized for semantic modeling and reporting

---

## 🧰 Tech Stack

- **Platform:** Microsoft Fabric
- **Storage:** OneLake, Lakehouse
- **Processing:** PySpark, SQL
- **Orchestration:** Data Pipelines
- **Transformation:** Notebooks
- **Version Control:** Git & GitHub

---

## 📁 Repository Structure

```text
fabric-project-1/
├── README.md
├── docs/          # Architecture diagrams and documentation
├── notebooks/     # PySpark notebooks
├── pipelines/     # Data pipeline definitions
└── images/        # Images used in documentation
