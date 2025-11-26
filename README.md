# 🛒 E-commerce Data Analysis Pipeline

## 📌 Overview

This project is a full end-to-end **E-commerce Data Analysis Pipeline** built by **Eman Mohamed**.  
It covers the complete data lifecycle from raw data ingestion to dashboard visualization using modern data engineering tools.

The project demonstrates skills in:

- ETL pipelines
- Data modeling (ERD)
- Data cleaning & transformation
- Dockerized development
- Business Intelligence dashboards
- Building scalable analytical architecture

---

## 🧱 Architecture

Below is the high-level architecture of the system:

- **Data Source:** E-commerce raw CSV files
- **ETL Pipeline:** Built using **Mage**
- **Database:** SQL Server (running via Docker)
- **Transformation:** SQL + Mage
- **Visualization:** Power BI interactive dashboard
- **Orchestration:** Docker Compose for environment setup

📌 _See `Data pipeline.png` for the full pipeline diagram._

---

## 🗂 Folder Structure

E-commerce-data-analysis-pipeline
│
├── Data/ # Raw input data files
├── MAGE- Data pipeline/ # ETL workflows & transformations
├── Power bi/ # Dashboard files
├── Docker-compose.yaml # Docker environment setup
├── Data pipeline.png # Architecture diagram
├── ER diagram.png # Entity-Relationship diagram
└── README.md # Project documentation

---

## 🧩 ER Diagram (Data Model)

The project uses a relational model suitable for analytical reporting.  
See `ER diagram.png` inside the repository.

---

## ⚙️ ETL Workflow (Mage Pipeline)

The ETL steps include:

1. **Extract**
   - Load raw e-commerce data from CSV files
2. **Transform**
   - Data cleaning
   - Type casting
   - Null handling
   - Feature engineering
3. **Load**
   - Load processed tables into SQL Server
   - Validate relationships & keys
4. **Refresh**
   - Automated pipeline execution
   - Dashboard refresh-ready data

---

## 🐳 Running the Project with Docker

1. Install **Docker Desktop**
2. Navigate to the project folder
3. Run:

```bash
docker-compose up --build

4:Docker will automatically:

.Start SQL Server instance
.Initialize database
.Run Mage pipelines

📊 Power BI Dashboard

The dashboard provides insights such as:

.Sales trends

.Customer segmentation

.Product performance

.Order distribution

.Revenue analysis

```
