# SECP3843-SPECIAL-TOPIC-IN-DATA-ENGINEERING

# ⚙️ Special Topic in Data Engineering (SECP3843-02) - Learning Portfolio & Project Reflection

Welcome to my portfolio for the **Special Topic in Data Engineering (SECP3843)** course.

---

## 📑 Overall Course Reflection

Special Topic in Data Engineering has completely redefined how I view enterprise-scale computation and data pipelines. Moving past isolated databases, this course built an engineering mindset focused on extreme scalability, structural throughput efficiency, and the seamless convergence of distributed computing with modern cloud environments.

Key personal and technical takeaways include:
* **Decoupled Architecture & Cloud Orchestration:** Transitioning from localized operations to multi-layered cloud-native systems showed me how to securely decouple compute from storage using ecosystems like Azure Data Factory, Databricks, and Synapse Analytics.
* **Distributed Computing In-Memory Performance:** Exploring distributed processing frameworks like Apache Spark and PySpark fundamentally changed my approach to massive datasets. Overcoming memory constraints, tuning shuffle fractions, and utilizing vectorized formats like Parquet proved how optimized architecture mitigates processing bottlenecks.
* **The Fusion of AI and Modern Data Pipelines:** Data engineering does not end with delivery; it sets the stage for downstream intelligence. Integrating advanced convolutional neural networks (CNNs) for image classification and leveraging AI agents for low-code ETL pipelines demonstrated that the modern analytics engineer must understand both data architecture and intelligent transformation logic.

---

## 🛠️ Specialized Technical Analysis & Practice Tutorials

### 🔹 [Technical Analysis Report: Apache Spark for Data Engineering]
* **Concepts Focused:** Resilient Distributed Datasets (RDDs), DAG Engine Optimization, Driver-Executor Topology, and Memory Management Tuning.
* **Implementation Details:** Conducted a comprehensive structural deep-dive into Apache Spark as the premiere alternative to legacy disk-bound Hadoop systems. Analyzed core architecture mappings (Driver Program, Cluster Manager, Executors) and researched mitigations for critical execution barriers, proving that proper allocation fixes GC spikes and broadcast joins optimize shuffle bottlenecks.
* **Reflection:** This analytical exercise emphasized that blindly scaling up compute cannot substitute for rigorous pipeline tuning. Uncovering why distributed shuffles can exhaust up to 50% of runtime provided me with the diagnostic foresight required to configure modern distributed computation clusters defensively.

### 🔹 [Tutorial Portfolio: Enterprise Cloud Architecture, Distributed Big Data & AI Engines]
* **Concepts Focused:** Medallion Data Architecture (Bronze/Silver/Gold), ETL Pipelines, Containerized Ecosystems via Docker Compose, Deep Learning Image Networks (CNNs), and Low-Code AI Agents.
* **Implementation Details:** Engineered a diverse suite of technical data workflows:
  * **Microsoft Azure End-to-End Workflow:** Built a complete enterprise stack extracting data from SQL Server to Azure Data Lake via Azure Data Factory, processing layers via Databricks, and establishing SQL views inside Azure Synapse.
  * **Big Data Apache Spark Lab:** Processed a 2.2 GB Brazilian Education Census dataset by containerizing an architecture utilizing Docker Compose, PostgreSQL, and Parquet formatting.
  * **AI Image Classification Network:** Developed a Convolutional Neural Network (CNN) in Python to normalize pixel streams and execute image classification benchmarks.
  * **AI-Assisted ETL Orchestration:** Configured a low-code automated ingestion pipeline feeding OpenWeather API payloads directly into a Snowflake Data Warehouse using an AI Agent.
* **Reflection:** Navigating these diverse exercises bridged the gap between legacy processes and modern AI-driven cloud automation. Successfully troubleshooting localized network connection timeouts inside Docker containers and engineering robust validation tracks to handle null payloads from APIs taught me how to design self-healing pipelines ready for production environments.

---

## 🌐 Industry Engagement & Professional Insights

| Activity / Topic | Organizer / Company | Resource Link |
| :--- | :--- | :--- |
| Industrial Visit to PPG | PPG Coatings Malaysia | [View LinkedIn Post](https://www.linkedin.com/posts/safiyanursyahadah_on-7-april-i-visited-ppg-for-our-special-activity-7450576897131872257-Sapk?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAEfmQUgB8bcPMjlQCvfVg7DNZ4erBSHeeJk) |
| Industry Talk | iZeno | [View LinkedIn Post](https://www.linkedin.com/posts/safiyanursyahadah_industry-talk-by-izeno-13-may-2026-activity-7474768546061803521-rt5v?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAEfmQUgB8bcPMjlQCvfVg7DNZ4erBSHeeJk) |
| Industry Talk | Telekom Malaysia (TM) | [View LinkedIn Post](https://www.linkedin.com/posts/safiyanursyahadah_industry-talk-by-tm-20-may-2026-had-activity-7474769167959629824-Bx10?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAEfmQUgB8bcPMjlQCvfVg7DNZ4erBSHeeJk) |

---

## 🏭 Final Group Project Reflection: Recoverable Assets (RA) & Inventory Risk Management (IRM)

### 📄 [Medallion Pipeline Ingestion & Business Rule Cleansing]
* **Concepts Covered:** Azure Data Lake Storage (ADLS Gen2), Multi-Source Schema Blending, PySpark Transformations, and Deduplication Tracks.
* **Core Design:** Ingested 6 fragmented enterprise operational repositories (Materials, Inventory Snapshots, Purchase Orders, Suppliers, Production, and Sales) for paint-manufacturer PPG. Built a disciplined, reproducible 4-layer Medallion Pipeline on Microsoft Azure. Cleaned raw structural properties inside the **Bronze-to-Silver** track by synchronizing date alignment standards, managing missing fields, and ensuring referential constraints.
* **Reflection:** This foundational step proved that engineering clean data assets is the single most valuable phase of the industrial BI pipeline. Converting manual spreadsheets into reliable, programmatically validated data arrays taught our team how crucial systematic normalization is when detecting material obsolescence and mitigating supply chain risk.

### 📺 [Gold-Layer Star Schemas & Executive Dashboard Delivery]
* **Implementation Victory:** Engineered business-centric analytics rules inside the **Silver-to-Gold** Databricks notebooks. Programmed dynamic tracking parameters including a 12-month trailing consumption comparison, reorder flags, and material expiration calculators. Formulated an optimized Star Schema modeling 1 Fact Table (`fact_inventory_status`) interconnected across 4 Dimension tables, casting them as 9 scalable SQL Views inside Azure Synapse Analytics.
* **Mechanics Validation:** Successfully exposed the multi-layered Azure Synapse views to Power BI, designing a unified executive interactive command hub answering 7 core cross-functional inventory risk questions at a glance.
* **Reflection:** Seeing our curated gold layer completely replace slow, manual checks with real-time automated visual tracking was extremely rewarding. Designing distinct operational modules—mapping critical stock shortfalls against production fulfillment schedules rather than relying on historical summaries—demonstrated how modern data engineering directly saves working capital and optimizes industrial supply chains.
