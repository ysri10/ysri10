<div align="center">

<a href="https://ysri10.github.io/ysri10/?vader=1" title="Click Darth Vader to enter Dark-Side Torch Mode (Hover on Vader ignites his red lightsaber)">
  <img src="./assets/darth-vader-banner.svg" alt="Sri Sai Srivatsa Yerrapragada — Darth Vader Interactive Banner" width="100%" />
</a>

<br/>

[![Interactive Profile](https://img.shields.io/badge/Interactive_Profile-Darth_Vader_Torch_Mode-11151c?style=flat-square&labelColor=090b10&color=8b1e1e)](https://ysri10.github.io/ysri10/?vader=1)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-srivatsa--yerrapragada-11151c?style=flat-square&labelColor=090b10&color=1f2937)](https://www.linkedin.com/in/srivatsa-yerrapragada)
[![Email](https://img.shields.io/badge/Email-sssrivatsa.yerrapragada%40gmail.com-11151c?style=flat-square&labelColor=090b10&color=1f2937)](mailto:sssrivatsa.yerrapragada@gmail.com)
[![Location](https://img.shields.io/badge/Location-Plano%2C_TX-11151c?style=flat-square&labelColor=090b10&color=1f2937)](https://ysri10.github.io/ysri10/)

</div>

---

### Overview

<table>
  <tr>
    <td width="62%" valign="top">
      <p>
        Software Engineer with <b>4+ years of experience</b> building production AI infrastructure and distributed backend services in <code>Python</code>, <code>Go</code>, <code>Java</code>, and <code>C++</code>. I own systems end-to-end from RFC and architecture design to production:
      </p>
      <ul>
        <li><b>Multi-Agent LLM Platforms</b>: Durable multi-day agent orchestration on <b>Temporal</b> and <b>Amazon Bedrock</b> with dynamic cost/complexity routing and persona-based <b>LLM-as-a-Judge</b> quality gates.</li>
        <li><b>Enterprise-Scale RAG</b>: High-throughput vector indexing and retrieval over <b>50M+ embeddings</b> (Snowflake Cortex to Pinecone) serving <b>1M+ daily queries at sub-150ms P99 latency</b>.</li>
        <li><b>Distributed ML &amp; Backend Systems</b>: Multi-GPU <b>PyTorch DDP</b> training/serving pipelines, LoRA fine-tuning, async batching, and high-availability <b>FastAPI / Java / C++</b> microservices.</li>
      </ul>
    </td>
    <td width="38%" valign="top">
      <table>
        <tr>
          <td><b>50M+</b></td>
          <td>Vector Embeddings Indexed</td>
        </tr>
        <tr>
          <td><b>1M+ / day</b></td>
          <td>RAG Queries at <code>&lt;150ms P99</code></td>
        </tr>
        <tr>
          <td><b>2M+ / day</b></td>
          <td>Microservice Transactions (<code>99.95%</code> SLA)</td>
        </tr>
        <tr>
          <td><b>8x GPU DDP</b></td>
          <td>Hyperspectral CNN Training (<code>-50%</code> Time)</td>
        </tr>
        <tr>
          <td><b>3x AWS</b></td>
          <td>ML Specialty, SAA, Developer</td>
        </tr>
      </table>
    </td>
  </tr>
</table>

---

### Experience

**Software Engineer II — Dish Networks** *(Plano, TX | Feb 2026 – Present)*
- Own architecture and RFC process for **AI-LC**, a multi-agent platform on **Temporal** and **Amazon Bedrock** automating the software lifecycle from JIRA ticket to reviewable Git branch with human-approval gates across Dish, Boost Mobile, and Sling.
- Built dynamic LLM model routing (task complexity and token budget scoring with kill-switch fallbacks) and a configurable persona-based **LLM-Judge** layer (manager, architect, developer, tester).

**Software Engineer — Dish Networks** *(Plano, TX | May 2024 – Feb 2026)*
- Architected a RAG support and diagnostics assistant scaling a **50M+ embedding index** (Snowflake Cortex to Pinecone) to **1M+ daily queries at sub-150ms P99 latency**, cutting manual triage time by 40%.
- Improved Context Recall by **25%+** via structure-aware recursive chunking and metadata tagging; reduced P95 inference latency **22%** via LoRA fine-tuning and async batching; built multi-GPU embedding pipelines (+35% ingestion throughput).
- Designed versioned **FastAPI** services with JWT/OAuth and distributed tracing (50K+ daily requests, sub-200ms P95, 99.9% availability).

**Machine Learning Engineer (Research Assistant) — University of Florida** *(Gainesville, FL | Sept 2022 – May 2024)*
- Built **PyTorch DDP** pipelines across 8 GPUs for 10M+ hyperspectral samples (-50% iteration time) and a mixed-precision **MLflow** evaluation framework (-65% evaluation cost, improving spatial-spectral CNN $R^2$ from 0.68 to 0.76).

**Software Developer — Accenture** *(Bengaluru, India | Jun 2021 – Jul 2022)*
- Built high-availability **Java/C++ microservices** processing **2M+ transactions/day** at 99.95% uptime and REST APIs serving 100K+ daily requests (-60% latency via Redis caching and connection pooling).

---

### Technical Stack

| Domain | Technologies |
| :--- | :--- |
| **Languages** | `Python` · `Go` · `Java` · `C / C++` · `C#` · `TypeScript` · `SQL` |
| **AI/ML & LLM Infra** | `PyTorch DDP` · `LoRA Fine-Tuning` · `RAG` · `Amazon Bedrock` · `Temporal` · `LangChain / LangGraph` · `PydanticAI` · `Langfuse` · `MLflow` · `Pinecone` · `FAISS` · `Milvus` |
| **Backend & APIs** | `FastAPI` · `Flask` · `Node.js` · `Spring Boot` · `REST` · `OAuth / JWT` · `Microservices` · `Async/Await` · `Kafka` · `AWS SNS / SQS` |
| **Cloud & DevOps** | `AWS (Bedrock, Lambda, EC2, S3, ECS, SageMaker)` · `GCP` · `Docker` · `Kubernetes` · `Terraform` · `CI/CD (Jenkins, Harness)` · `Observability` |
| **Data & Storage** | `PostgreSQL` · `MongoDB` · `DynamoDB` · `Redis` · `Snowflake` · `Apache Spark` |

---

### Selected Repositories

<table>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/ysri10/Semantic-Search-Analysis">Semantic-Search-Analysis</a></b>
      <p>Multi-document semantic search engine over PDF and TXT files with batched transformer embeddings and FAISS L2 indexing.</p>
      <p><code>DistilBERT</code> · <code>SentenceTransformers</code> · <code>FAISS</code> · <code>Flask</code> · <code>React</code></p>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/ysri10/Cold-Email-Generator">Cold-Email-Generator</a></b>
      <p>Automated career page scraper and outreach email generator matching job requirements against a vector portfolio store.</p>
      <p><code>LangChain</code> · <code>LLaMA 3.1-70B (Groq)</code> · <code>ChromaDB</code> · <code>Streamlit</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/ysri10/camera-view-adjustment">camera-view-adjustment</a></b>
      <p>Pre-capture active camera view adjustment architecture analysis and multi-view composition datasets (FCDB, GAICD, CPC, Pano2Vid).</p>
      <p><code>MobileNet-SPP</code> · <code>Semi-Supervised Learning</code> · <code>PyTorch</code></p>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/ysri10/Movie-Recommendation-System">Movie-Recommendation-System</a></b>
      <p>Content-based movie recommender trained on the TMDB 5000 dataset with cosine similarity ranking and live poster integration.</p>
      <p><code>Scikit-Learn</code> · <code>Cosine Similarity</code> · <code>NLTK</code> · <code>Streamlit</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b><a href="https://github.com/ysri10/Email-Spam-Detector">Email-Spam-Detector</a></b>
      <p>Real-time SMS and Email spam classifier benchmarking 11 ML models and serving a TF-IDF + Multinomial Naive Bayes pipeline.</p>
      <p><code>Scikit-Learn</code> · <code>NLTK</code> · <code>TF-IDF</code> · <code>Streamlit</code></p>
    </td>
    <td width="50%" valign="top">
      <b><a href="https://github.com/ysri10/NoteBook">NoteBook</a></b>
      <p>Full-stack note-taking web application with JWT authentication, auto-refresh interceptors, and protected routes.</p>
      <p><code>Django REST</code> · <code>SimpleJWT</code> · <code>PostgreSQL</code> · <code>React 18</code> · <code>Vite</code></p>
    </td>
  </tr>
</table>

---

### Education & Certifications

- **M.S. in Electrical and Computer Engineering** *(Minor: Computer Science)* — **University of Florida** *(2022 – 2024)*
- **B.Tech in Electronics and Communication Engineering** *(Minor: AI)* — **Jain University** *(2017 – 2021)*
- **Certifications**: AWS Certified Machine Learning – Specialty · AWS Certified Solutions Architect – Associate · AWS Certified Developer – Associate
