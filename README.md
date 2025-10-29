# # 🎧 Spotify End-to-End Data Engineering Project on Azure

This project is inspired by the **Spotify Data Engineering Pipeline** using **Microsoft Azure**.  
It demonstrates how to build and automate a complete **data engineering workflow** for processing and analyzing streaming data.

---

## 🚀 Project Overview
Built an **end-to-end data pipeline** on Azure to extract, transform, and load (ETL) Spotify data.  
The pipeline follows the **Medallion Architecture** for structured, layered data processing.

Implemented dynamic pipelines using **Jinja templating**, **Git integration**, and **asset bundles** for deployment and configuration management.

---

## 🧩 Architecture Diagram

<p align="center">
  <img src="https://github.com/user-attachments/assets/258a7c21-0484-4c25-bb78-3acbd128e193" alt="architecture" width="700"/>
</p>

---

## ⚙️ Tech Stack & Tools
- **Azure Data Factory** – Pipeline orchestration and automation  
- **Azure Data Lake** – Centralized storage for all data layers  
- **Azure Databricks (PySpark)** – Data transformation and cleaning  
- **Jinja Templating** – Dynamic configuration for pipelines  
- **Asset Bundles** – Versioned pipeline packaging  
- **Git Integration** – Version control for notebooks and pipelines  
- **Python & SQL** – Data manipulation and transformations  

---

## 🛠️ Project Workflow
1. **Data Ingestion (Bronze Layer)** – Raw data stored in Azure Data Lake.  
2. **Data Transformation (Silver Layer)** – Cleaning and formatting with Databricks (PySpark).  
3. **Data Aggregation (Gold Layer)** – Curated data ready for analytics.  
4. **Automation & Deployment** – Managed via ADF with Jinja templates and asset bundles.  
5. **Version Control** – Integrated Git to track and manage changes.

---

## 📂 Project Structure

📦 azureproject  
 ┣ 📂 dataset/              # Contains dataset definitions and metadata  
 ┣ 📂 factory/              # Azure Data Factory configuration files  
 ┣ 📂 linkedService/        # Linked service connections (e.g., Data Lake, Databricks)  
 ┣ 📂 pipeline/             # Data pipeline definitions  
 ┣ 📜 publish_config.json   # Deployment and configuration details  
 ┗ 📜 README.md             # Project documentation

---

🧠 Key Learnings

- Implemented Medallion architecture in Azure Data Lake.

- Used PySpark for efficient data transformation and cleaning.

- Applied Jinja templating for flexible, reusable pipeline configuration.

- Understood asset bundle deployment and Git-based workflow in Azure.

---

📜 Author

Hemang Rathod
📧 hemangrathod71@gmail.com

---
⭐ If you like this project, don’t forget to star the repo!
