# Sri Sai Srivatsa Yerrapragada

**Software Engineer II @ Dish Networks** | **Production AI Infrastructure, Multi-Agent LLM Platforms & Distributed Backend Systems**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-srivatsa--yerrapragada-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/srivatsa-yerrapragada)
[![Email](https://img.shields.io/badge/Email-sssrivatsa.yerrapragada%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sssrivatsa.yerrapragada@gmail.com)
[![Location](https://img.shields.io/badge/Location-Plano%2C%20TX-2ea44f?style=for-the-badge)](https://github.com/ysri10)

---

### 👨‍💻 About Me

Software Engineer with **4+ years of experience** building production AI infrastructure and distributed backend services in Python, Go, Java, and C++. I own systems end-to-end from RFC/design doc to production:
- **Multi-Agent LLM Platforms**: Durable multi-day agent orchestration on **Temporal** and **Amazon Bedrock** with dynamic cost/complexity model routing and persona-based LLM-as-a-Judge guardrails.
- **Enterprise-Scale RAG**: High-throughput vector indexing and retrieval over **50M+ embeddings** (Snowflake Cortex $\rightarrow$ Pinecone) serving **1M+ daily queries at sub-150ms P99 latency**.
- **Distributed ML & Backend Systems**: Multi-GPU **PyTorch DDP** training/serving pipelines, LoRA fine-tuning, async batching, and high-availability **FastAPI / Java / C++** microservices.

---

### 💼 Experience Highlights

- **Software Engineer II** — **Dish Networks** *(Plano, TX | Feb 2026 – Present)*
  - Own architecture and RFC process for **AI-LC**, a multi-agent platform on **Temporal** + **Amazon Bedrock** automating the dev lifecycle from JIRA ticket to reviewable Git branch with human-approval gates across Dish, Boost Mobile, and Sling.
  - Built dynamic LLM model routing (task complexity & token budget scoring with kill-switch fallbacks) and a configurable persona-based **LLM-Judge** layer (manager, architect, developer, tester).
- **Software Engineer** — **Dish Networks** *(Plano, TX | May 2024 – Feb 2026)*
  - Architected a RAG support & diagnostics assistant scaling a **50M+ embedding index** (Snowflake Cortex $\rightarrow$ Pinecone) to **1M+ daily queries at sub-150ms P99 latency**, cutting manual triage time by 40%.
  - Improved Context Recall by **25%+** via structure-aware recursive chunking & metadata tagging; reduced P95 inference latency **22%** via LoRA fine-tuning & async batching; built multi-GPU embedding pipelines (+35% ingestion throughput).
  - Designed versioned **FastAPI** services with JWT/OAuth and distributed tracing (50K+ daily requests, sub-200ms P95, 99.9% availability).
- **Machine Learning Engineer (Research Assistant)** — **University of Florida** *(Gainesville, FL | Sept 2022 – May 2024)*
  - Built **PyTorch DDP** pipelines across 8 GPUs for 10M+ hyperspectral samples (-50% iteration time) and a mixed-precision **MLflow** evaluation framework (-65% evaluation cost, improving spatial-spectral CNN $R^2$ from 0.68 to 0.76).
- **Software Developer** — **Accenture** *(Bengaluru, India | Jun 2021 – Jul 2022)*
  - Built high-availability **Java/C++ microservices** processing **2M+ transactions/day** at 99.95% uptime and REST APIs serving 100K+ daily requests (-60% latency via Redis caching and connection pooling).

---

### 🛠️ Technical Skills

| Category | Technologies |
| :--- | :--- |
| **Languages** | `Python` · `Go` · `Java` · `C/C++` · `C#` · `TypeScript/JavaScript` · `SQL` |
| **AI/ML & LLM Infra** | `PyTorch` · `LoRA Fine-Tuning` · `RAG` · `Amazon Bedrock` · `Temporal` · `LangChain / LangGraph` · `PydanticAI` · `Langfuse` · `MLflow` · `Pinecone` · `FAISS` · `Milvus` |
| **Backend & APIs** | `FastAPI` · `Flask` · `Node.js` · `Spring Boot` · `REST` · `OAuth / JWT` · `Microservices` · `Async/Await` · `Kafka` · `AWS SNS/SQS` |
| **Cloud & DevOps** | `AWS (Bedrock, Lambda, EC2, S3, ECS, SageMaker)` · `GCP` · `Docker` · `Kubernetes` · `Terraform` · `CI/CD (Jenkins, Harness)` · `Observability` |
| **Data & Storage** | `PostgreSQL` · `MongoDB` · `DynamoDB` · `Redis` · `Snowflake` · `Apache Spark` |

---

### 🎓 Education & Certifications

- **M.S. in Electrical and Computer Engineering** *(Minor: Computer Science)* — **University of Florida** *(2022 – 2024)*
- **B.Tech in Electronics and Communication Engineering** *(Minor: AI)* — **Jain University** *(2017 – 2021)*
- **Certifications**:
  - ☁️ **AWS Certified Machine Learning – Specialty**
  - ☁️ **AWS Certified Solutions Architect – Associate**
  - ☁️ **AWS Certified Developer – Associate**

---

### 🚀 Featured Open-Source Repositories

| Repository | Overview | Stack |
| :--- | :--- | :--- |
| **[Semantic-Search-Analysis](https://github.com/ysri10/Semantic-Search-Analysis)** | Multi-document semantic search engine over PDF & TXT files with batched transformer embeddings and FAISS L2 indexing (Full-Stack + Streamlit). | `DistilBERT` · `SentenceTransformers` · `FAISS` · `Flask` · `React` · `Streamlit` |
| **[Cold-Email-Generator](https://github.com/ysri10/Cold-Email-Generator)** | Automated career page scraper and personalized outreach email generator matching job requirements against a vector portfolio store. | `LangChain` · `LLaMA 3.1-70B (Groq)` · `ChromaDB` · `Streamlit` |
| **[Movie-Recommendation-System](https://github.com/ysri10/Movie-Recommendation-System)** | Content-based movie recommender trained on the TMDB 5000 dataset with cosine similarity ranking and live poster integration. | `Scikit-Learn` · `Cosine Similarity` · `NLTK` · `Streamlit` · `TMDB API` |
| **[Email-Spam-Detector](https://github.com/ysri10/Email-Spam-Detector)** | Real-time SMS & Email spam classifier benchmarking 11 ML models and serving a TF-IDF + Multinomial Naive Bayes pipeline. | `Scikit-Learn` · `NLTK` · `TF-IDF` · `Streamlit` |
| **[NoteBook](https://github.com/ysri10/NoteBook)** | Full-stack note-taking web application with JWT authentication, auto-refresh interceptors, and protected routes. | `Django REST` · `SimpleJWT` · `PostgreSQL` · `React 18` · `Vite` |
| **[LLM-web](https://github.com/ysri10/LLM-web)** | Document ingestion and web scraping workflows (`TextLoader`, `CSVLoader`, `WebBaseLoader`, `UnstructuredURLLoader`) for RAG pipelines. | `LangChain` · `Unstructured` · `NLTK` · `Jupyter` |
