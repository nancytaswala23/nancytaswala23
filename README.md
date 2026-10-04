

# Hi, I'm Nancy Taswala

I'm a **Full-Stack AI Engineer** who builds AI that understands connected data. My work sits where knowledge graphs meet large language models: designing Neo4j graphs, building GraphRAG pipelines, and shipping the APIs and interfaces around them.

Most recently I was an **AI Engineer at Cernuvo**, where I built knowledge graph and GraphRAG features for a live platform serving thousands of users. I'm completing my **MS in Information Systems at Northeastern University** (December 2026) and I'm open to full-time roles in AI, ML and full-stack AI engineering from January 2027.

---

## Featured projects

### Satellite infrastructure series
*Personal projects exploring the distributed systems behind LEO satellite networks.*

**[GroundLink: Distributed Ground Station Task Scheduler](https://github.com/nancytaswala23/groundlink)**
Fault-tolerant scheduler that allocates satellite downlink windows across 4 ground stations using an O(log n) priority queue. Detects station failures in real time, reassigns tasks automatically with zero task loss, and keeps a full PostgreSQL audit trail of every scheduling decision.
`Python` `FastAPI` `PostgreSQL` `Docker` `GitHub Actions`

**[OrbitOps: AI Satellite Operations Agent](https://github.com/nancytaswala23/kuiperops)**
LLM agent that ingests satellite telemetry, detects 6 types of failure (signal loss, latency, packet loss, power and thermal anomalies), and generates incident diagnoses and runbooks, cutting diagnosis time by 80%. Structured JSON output, retry logic and a fallback diagnosis path mean every request returns a usable result.
`Python` `Llama 3 (Groq)` `FastAPI` `AWS DynamoDB` `Docker`

**[EdgeSync: Offline-First Remote Device Sync](https://github.com/nancytaswala23/edgesync)**
Lets remote devices in places like schools and hospitals keep working through connectivity outages by queuing 1,000+ records locally in SQLite and syncing to AWS DynamoDB on reconnect. Three conflict-resolution strategies and exponential backoff retry ensure zero data loss.
`Python` `FastAPI` `SQLite` `AWS DynamoDB` `Docker`

**[TrafficWatch: Real-Time Satellite Network Monitor](https://github.com/nancytaswala23/trafficwatch)**
Three-stage streaming pipeline (validate, enrich, store) monitoring 5 satellite nodes across 4 continents. Per-node Z-score anomaly detection flags warning (2σ) and critical (3σ) deviations in bandwidth, latency and packet loss, with live alerts over Server-Sent Events.
`Python` `FastAPI` `SSE` `Anomaly Detection` `Docker`

### AI and knowledge graphs

**[AI-Powered Crime Investigation with Knowledge Graphs](https://github.com/nancytaswala23/Crime-Investigation-Graph-Using-Neo4j)**
Ask questions in plain English over a Neo4j knowledge graph built from 30K+ multi-source crime records. LangChain RAG pipeline with automated entity extraction, data lineage tracking, retrieval evaluation and output guardrails, plus a React frontend.
`Python` `Neo4j` `LangChain` `RAG` `NLP` `React`

**[BookShelf: Book Recommendation System](https://github.com/nancytaswala23/BookShelf---A-Book-Recommendation-System)**
Collaborative filtering recommendation engine using SVM, Random Forest and matrix factorisation to handle sparse rating data, improving accuracy by 35% over baseline. Published in IJSREM.
`Python` `Scikit-learn` `Flask` `Recommender Systems`

**[MediHive: Healthcare Management Platform](https://github.com/nancytaswala23/Hospital-Management-System)**
Role-based hospital platform for administrators, doctors, patients and staff, with a HIPAA-aware data governance framework and star schema models that reduced query latency by 60%.
`Java` `SQL` `Power BI` `Data Modelling`

---

## Research

**[BookShelf: A Book Recommendation System Using Collaborative Filtering](https://ijsrem.com/download/bookshelf-a-book-recommendation-system-using-collaborative-filtering/)**
*International Journal of Scientific Research in Engineering and Management (IJSREM), SJIF 8.659*
Collaborative filtering with SVM and Random Forest models on sparse user data, improving recommendation accuracy by 35% over baseline.

---

## Tech stack

| Area | Tools |
|---|---|
| Languages | Python, TypeScript, JavaScript, SQL, Cypher, Java, R |
| AI and ML | LLMs, GraphRAG, RAG, LangChain, Hugging Face Transformers, PyTorch, Scikit-learn, NLP |
| Graphs and databases | Neo4j, PostgreSQL, MySQL, SQL Server, SQLite, AWS DynamoDB |
| Backend and frontend | FastAPI, Flask, React |
| Cloud and DevOps | AWS (DynamoDB, Lambda, SQS), Docker, GitHub Actions CI/CD |
| Analytics | Power BI, Tableau, AWS QuickSight, Excel |

---

## Experience

**AI Engineer, Knowledge Graphs & GraphRAG** | Cernuvo | Jan 2026 to Jul 2026
Built Neo4j knowledge graphs, GraphRAG pipelines and FastAPI microservices for a live platform, working directly with the technical co-founder on architecture.

**Research Assistant** | Dept. of Data Science, University of Mumbai | Jun 2023 to Apr 2024
Led a recommendation systems study from scoping to peer-reviewed publication.

## Education

**Northeastern University** | MS Information Systems | Aug 2024 to Dec 2026
Application Engineering, Data Management, Generative AI and LLMs with Graph Databases, UX Design

**University of Mumbai** | BS Data Science | 2021 to 2024
Machine Learning, Artificial Intelligence, Big Data, Business Intelligence, Agile Software Engineering

---

## Let's connect

Open to conversations about knowledge graphs, GraphRAG, AI engineering and distributed systems.

[Portfolio](https://nancytaswala23.github.io/) · [LinkedIn](https://www.linkedin.com/in/nancytaswala23/) · [Email](mailto:taswalan@gmail.com)
