<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:050816,50:0B1220,100:0F172A&height=240&section=header&text=Jo%C3%A3o%20Victor%20Poloniato%20Buss&fontSize=42&fontColor=E5F3FF&fontAlignY=38&desc=Data%20Engineer%20%7C%20AWS%20%7C%20Airflow%20%7C%20Spark%20%7C%20Databricks&descAlignY=63&descSize=20&animation=fadeIn" alt="João Victor Poloniato Buss banner" />
</p>

<h1 align="center">Hi there 👋 I'm João Victor</h1>
<h3 align="center">Building reliable data platforms, one pipeline at a time.</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/jo%C3%A3o-victor-poloniato-buss-908177164/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/joaovictorPoloniato">
    <img src="https://img.shields.io/badge/GitHub-Portfolio-111827?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="mailto:poloniato155@gmail.com">
    <img src="https://img.shields.io/badge/Email-Let's%20Talk-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=joaovictorPoloniato&style=for-the-badge&color=0ea5e9&label=PROFILE+VIEWS" alt="Profile views" />
</p>

---

## 🌑 About Me

I'm **João Victor Poloniato Buss**, a **Data Engineer with 3+ years of experience** across software engineering, enterprise integrations, data platforms, and analytics workflows.

I specialize in **cloud-based data engineering**, with strong hands-on experience in **AWS, Apache Airflow, Databricks, Apache Spark, SQL, Python, dbt, Apache Hop, Amazon Athena, Amazon Redshift, Apache Iceberg, and Parquet**.

My focus is to build **scalable, reusable, and reliable data solutions** that reduce rework, automate workflows, and make high-quality data easier to deliver to downstream applications and analytics teams.

### 🔎 Quick Highlights

- ☁️ **Current focus:** AWS data platforms, lakehouse architectures, and analytics engineering.
- ⚙️ **What I do:** Design and orchestrate ETL/ELT pipelines, centralize integrations, and automate enterprise data flows.
- 🔄 **Orchestration:** Apache Airflow, scheduled workflows, dependency management, and reusable integration patterns.
- 📦 **Data stack:** Amazon S3, Amazon Athena, Amazon Redshift, Spark/PySpark, Databricks, Iceberg, Parquet, dbt, Apache Hop.
- 🤝 **Business mindset:** Reduce duplicated work, cut manual effort, simplify maintenance, and accelerate reliable data delivery.
- 🤖 **Also experienced in:** Backend APIs, Machine Learning, NLP, and Generative AI.
- 🎓 **Education:** B.Sc. in Information Systems (UNEMAT) + Postgraduate specialization in Data Engineering in progress.
- 🌍 **Based in:** Brazil | English: Professional Working Proficiency.

> **Engineering philosophy:** Build once, standardize well, orchestrate cleanly, and deliver trusted data at scale.

---

## 🚀 Featured Engineering Project

# Centralized AWS Data Platform for Multi-Client Integrations

One of my most relevant recent projects focused on **centralizing data integrations from multiple customers into a single AWS-based architecture**.

We had around **40 customers** using the same source system. Instead of maintaining duplicated integrations and repeated transformation logic for each one, the goal was to **standardize the flow, reduce rework, and create a scalable architecture** for reliable data delivery.

### 🧱 Architecture Overview

```mermaid
flowchart LR
    A[Source Systems<br/>~40 customers] --> B[Amazon S3<br/>raw CSV data]
    B --> C[Apache Spark / PySpark<br/>distributed processing]
    C --> D[Parquet + Apache Iceberg<br/>analytical datasets]
    D --> E[Amazon Athena + dbt<br/>layered transformations]
    E --> F[Amazon Redshift<br/>centralized data warehouse]
    F --> G[Downstream systems<br/>and analytics]
    H[Apache Airflow<br/>workflow orchestration] -.-> B
    H -.-> C
    H -.-> E
    H -.-> F
```

### 🛠️ Technologies Used

| Layer | Technologies | Purpose |
| --- | --- | --- |
| Landing & Storage | Amazon S3, CSV | Centralized ingestion and raw data storage |
| Processing | Apache Spark, PySpark | Distributed data transformation and processing |
| Lakehouse Structure | Apache Iceberg, Parquet | Standardized analytical file/table structure |
| Transformation | Amazon Athena, dbt | Layered, reusable SQL transformations |
| Serving | Amazon Redshift | Centralized warehouse for downstream consumption |
| Orchestration | Apache Airflow | Pipeline automation, scheduling, and dependency control |
| Integration Workflows | Apache Hop | Additional integration and ETL workflows |

### ✅ Business Impact

- Reduced **integration rework** by reusing common patterns across customers.
- Reduced **manual execution effort** through orchestration and automation.
- Improved **maintainability** by standardizing transformation layers and data structures.
- Accelerated **data delivery** for downstream systems and analytics use cases.
- Created a more **scalable and reliable cloud data foundation**.

> Note: I intentionally describe the solution at a high level to avoid exposing proprietary implementation details.

---

## 🛠️ Tech Stack & Tools

### ☁️ Cloud & Data Platforms
<p>
  <img src="https://img.shields.io/badge/AWS-0F172A?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" />
  <img src="https://img.shields.io/badge/Amazon%20S3-0F172A?style=for-the-badge&logo=amazons3&logoColor=66BB6A" />
  <img src="https://img.shields.io/badge/Amazon%20Athena-0F172A?style=for-the-badge&logo=amazonaws&logoColor=F59E0B" />
  <img src="https://img.shields.io/badge/Amazon%20Redshift-0F172A?style=for-the-badge&logo=amazonredshift&logoColor=A78BFA" />
  <img src="https://img.shields.io/badge/Databricks-0F172A?style=for-the-badge&logo=databricks&logoColor=FF3621" />
</p>

### 🔄 Data Engineering & Orchestration
<p>
  <img src="https://img.shields.io/badge/Apache%20Airflow-0F172A?style=for-the-badge&logo=apacheairflow&logoColor=38BDF8" />
  <img src="https://img.shields.io/badge/Apache%20Spark-0F172A?style=for-the-badge&logo=apachespark&logoColor=FB923C" />
  <img src="https://img.shields.io/badge/dbt-0F172A?style=for-the-badge&logo=dbt&logoColor=FB7185" />
  <img src="https://img.shields.io/badge/Apache%20Kafka-0F172A?style=for-the-badge&logo=apachekafka&logoColor=ffffff" />
  <img src="https://img.shields.io/badge/Apache%20Hop-0F172A?style=for-the-badge&logo=apache&logoColor=93C5FD" />
  <img src="https://img.shields.io/badge/Apache%20Iceberg-0F172A?style=for-the-badge&logo=apache&logoColor=60A5FA" />
  <img src="https://img.shields.io/badge/Parquet-0F172A?style=for-the-badge&logo=apache&logoColor=CBD5E1" />
  <img src="https://img.shields.io/badge/Pentaho-0F172A?style=for-the-badge&logoColor=ffffff" />
  <img src="https://img.shields.io/badge/ETL%20%2F%20ELT-0F172A?style=for-the-badge&logoColor=ffffff" />
</p>

### 🐍 Programming, Databases & APIs
<p>
  <img src="https://img.shields.io/badge/Python-0F172A?style=for-the-badge&logo=python&logoColor=FACC15" />
  <img src="https://img.shields.io/badge/SQL-0F172A?style=for-the-badge&logoColor=ffffff" />
  <img src="https://img.shields.io/badge/Java-0F172A?style=for-the-badge&logo=openjdk&logoColor=F59E0B" />
  <img src="https://img.shields.io/badge/JavaScript-0F172A?style=for-the-badge&logo=javascript&logoColor=FACC15" />
  <img src="https://img.shields.io/badge/PostgreSQL-0F172A?style=for-the-badge&logo=postgresql&logoColor=60A5FA" />
  <img src="https://img.shields.io/badge/MySQL-0F172A?style=for-the-badge&logo=mysql&logoColor=7DD3FC" />
  <img src="https://img.shields.io/badge/Oracle-0F172A?style=for-the-badge&logo=oracle&logoColor=EF4444" />
  <img src="https://img.shields.io/badge/FastAPI-0F172A?style=for-the-badge&logo=fastapi&logoColor=2DD4BF" />
</p>

### 🧰 DevOps, Automation & AI
<p>
  <img src="https://img.shields.io/badge/Docker-0F172A?style=for-the-badge&logo=docker&logoColor=38BDF8" />
  <img src="https://img.shields.io/badge/Kubernetes-0F172A?style=for-the-badge&logo=kubernetes&logoColor=60A5FA" />
  <img src="https://img.shields.io/badge/Linux-0F172A?style=for-the-badge&logo=linux&logoColor=FACC15" />
  <img src="https://img.shields.io/badge/Git-0F172A?style=for-the-badge&logo=git&logoColor=F97316" />
  <img src="https://img.shields.io/badge/n8n-0F172A?style=for-the-badge&logo=n8n&logoColor=FB7185" />
  <img src="https://img.shields.io/badge/PyTorch-0F172A?style=for-the-badge&logo=pytorch&logoColor=FB923C" />
  <img src="https://img.shields.io/badge/Scikit--learn-0F172A?style=for-the-badge&logo=scikitlearn&logoColor=F59E0B" />
  <img src="https://img.shields.io/badge/Pandas-0F172A?style=for-the-badge&logo=pandas&logoColor=C084FC" />
</p>

---

## 💼 Professional Experience

### **Data Engineer · JMJ Sistemas e Consultoria**  
**2025 – Present**

- Designed and orchestrated **ETL/ELT workflows** using Apache Airflow, Spark, Python, and SQL.
- Contributed to a **centralized AWS-based data platform** using S3, Athena, dbt, Iceberg, Parquet, and Redshift.
- Built enterprise data integration workflows with **Apache Hop** and **n8n**.
- Developed **REST APIs and microservices** using FastAPI and Java.
- Worked on applied **Machine Learning / NLP** solutions in enterprise contexts.

### **Data Engineer · Alfameta**  
**2024 – 2025**

- Developed data pipelines with **Pentaho PDI, Apache Hop, Python, and SQL**.
- Worked with **Kafka, Spark, and Databricks** for integrations and distributed processing.
- Improved SQL transformations, data models, and integration routines.

### **Junior Software Engineer · Porto Tech**  
**2021 – 2024**

- Developed Python applications, REST APIs, and relational-database integrations.
- Worked with SQL optimization, data processing routines, and ETL/ELT support tasks.

---

## 🎓 Education & Learning

| Program | Institution | Status |
| --- | --- | --- |
| B.Sc. in Information Systems | UNEMAT | Graduated 2026 |
| Postgraduate Specialization in Data Engineering | — | In progress |

### Selected Learning
- Databricks for Data Engineering  
- AWS Machine Learning Engineer Associate preparation *(course/training)*  
- AI Engineer Core Track *(LLMs, RAG, QLoRA & Agents)*  
- Advanced SQL & Data Processing  
- Advanced Machine Learning  
- Advanced Python  

---

## 📈 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=joaovictorPoloniato&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=joaovictorPoloniato&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=joaovictorPoloniato&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</p>

---

## 🤝 Let's Connect

I'm always open to connecting with professionals working on:

- Cloud Data Engineering
- Workflow Orchestration
- Lakehouse & Data Platform Architecture
- Analytics Engineering
- Scalable Data Solutions
- Applied AI in data-driven environments

<p>
  📬 <strong>Email:</strong> <a href="mailto:poloniato155@gmail.com">poloniato155@gmail.com</a><br/>
  💼 <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/jo%C3%A3o-victor-poloniato-buss-908177164/">João Victor Poloniato Buss</a><br/>
  🧑‍💻 <strong>GitHub:</strong> <a href="https://github.com/joaovictorPoloniato">@joaovictorPoloniato</a>
</p>

<p align="center">
  <strong>Thanks for visiting — let’s build better data platforms.</strong>
</p>

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:0B1220,100:050816&height=120&section=footer" alt="Footer" />
</p>
