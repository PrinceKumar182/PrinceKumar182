# Hi 👋, I'm Prince Kumar

### Software Engineer | Backend Engineering · Java · Spring Boot · Distributed Systems

[🌐 Portfolio](https://princekumar182.github.io) · [💼 LinkedIn](https://linkedin.com/in/princekumar182) · [📧 Email](mailto:princekumar182@gmail.com) · [📄 Resume](https://princekumar182.github.io/resume.pdf)

I build **backend systems, APIs, and data-driven applications**, with a primary focus on **Java and Spring Boot**.

My work spans production backend engineering, distributed systems, cloud deployment, machine learning, and AI-powered applications. I enjoy taking a problem from **system design → implementation → testing → deployment**.

---

## 🚀 What I Work With

**Backend:** Java · Spring Boot · Python · Node.js · REST APIs
**Databases:** PostgreSQL · MongoDB · Redis
**Distributed Systems:** Concurrency Control · Distributed Locking · Idempotency · Kafka · Transactions
**Cloud & DevOps:** AWS · Docker · Linux · Git · CI/CD
**AI / ML:** Python · Scikit-learn · LLM APIs · RAG · AI Agents
**Frontend:** React · Next.js · TypeScript · Thymeleaf

---

## 💼 Experience

### Software Engineer — HCLTech

**Jul 2025 – Present**

Working on enterprise healthcare and clinical-instrument software using **Java, Spring Boot, PostgreSQL, Hibernate, Docker and microservices**.

Some of the backend work I've contributed to:

* Optimized an N+1 query flow using Hibernate batch fetching, targeted joins/fetch queries, and in-memory mapping, reducing PostgreSQL round-trips from **8,000+ to ~50**.
* Reduced a report-generation workflow from approximately **5 minutes to 30 seconds**.
* Implemented audit-trail improvements across **14 Java/Spring Boot microservices**, including capturing the actual Windows user on shared laboratory workstations.
* Fixed client notification leakage by moving events from shared-account destinations to **client/session-scoped destinations**.
* Investigated and resolved **50+ P1/P2 production issues** involving memory leaks, API timeouts, and integration failures.
* Improved automated test coverage from approximately **45% to 81%** using JUnit and SonarQube-driven analysis.

---

# 🧩 Featured Projects

### 🚗 InstaPart — Hyperlocal Vehicle Spare Parts Marketplace

**Java · Spring Boot · PostgreSQL · Redis · Docker · AWS · Razorpay**

A vehicle spare-parts marketplace designed around **local inventory, multi-vendor operations, vehicle fitment, and location-aware fulfillment**.

* Built backend services for product, inventory, orders, vendors, and store operations.
* Implemented inventory concurrency controls using **database locking** to prevent conflicting stock updates.
* Tested inventory flows with **100+ concurrent requests** without inventory inconsistencies in the test scenario.
* Added Redis-based caching and distributed coordination for frequently accessed operations.
* Built SKU import validation and quarantine workflows to prevent invalid inventory data from entering the system.
* Containerized backend services with Docker and deployed services using **AWS EC2/RDS**.
* Integrated Razorpay for online payments.

🔗 **Repository:** https://github.com/PrinceKumar182/InstaPart

---

### 💳 High-Throughput Distributed Transaction Engine

**Java 17 · Spring Boot · PostgreSQL · Redis · Kafka · Docker**

A concurrent banking backend focused on preventing **double-spending and duplicate transaction execution**.

* Used PostgreSQL `SELECT FOR UPDATE` to serialize balance updates at the database level.
* Added Redis-based distributed locking for request coordination.
* Implemented **idempotency handling** to prevent duplicate transaction execution.
* Kept balance updates and ledger entries inside a single transactional workflow.
* Used Kafka to asynchronously process audit and notification events.
* Tested concurrent transfer scenarios with **100+ simultaneous requests** without duplicate transfers in the test scenario.

🔗 **Repository:** https://github.com/PrinceKumar182

---

### 🧵 India Textile Connect

**Java 21 · Spring Boot · MongoDB · Spring Security · Razorpay · Firebase**

An e-commerce backend focused on **transactional checkout, inventory consistency, authentication security, and payment validation**.

* Implemented MongoDB multi-document transactions for checkout workflows.
* Added checkout idempotency to handle duplicate requests.
* Implemented inventory reservation and restoration for failed, expired, or cancelled payments.
* Added Razorpay payment validation against the server-calculated order amount.
* Designed an order state flow around `PAYMENT_PENDING → PAID / CANCELLED`.
* Implemented USER/ADMIN RBAC with Spring Security.
* Added authentication abuse protection including brute-force controls and token-bucket rate limiting.

🔗 **Repository:** https://github.com/PrinceKumar182

---

### 🤖 Awaaz Billing

**Python · Llama 3.3 · Groq · Web Speech API · PostgreSQL**

A voice-based billing application designed for small retail businesses, supporting **code-mixed Hindi voice interactions**.

* Built voice-driven product and billing workflows.
* Integrated Llama 3.3 through Groq for natural-language processing.
* Used PostgreSQL for product and transaction data.
* Designed the system around a real-world kirana-store catalogue and credit (`udhaar`) workflows.

---

### 🏏 IPL Score Predictor

**Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn**

A machine learning project for predicting final IPL first-innings scores from ball-by-ball match state.

* Worked with **76,000+ ball-by-ball records**.
* Engineered features around current score, wickets, overs, and recent 5-over performance.
* Compared Linear Regression, Decision Tree, and Random Forest models.
* Used cross-validation and GridSearchCV for model tuning.
* Random Forest achieved a reported **94.03% test R²**.

---

# 🏆 Achievements

* 🥇 **AIR 1 — Smart India Hackathon 2024**, Hardware Domain
* 🥇 **AIR 1 — Microsoft Clash of Codes**
* 🥇 **Top 100 — Amazon ML Challenge**, among 72,000+ teams
* 🥈 **AIR 2 — ACM HackData**
* 🏅 **Top 10 — Pitchcafe**

---

# 🏗️ What I Like Building

```text
Backend APIs
     ↓
Databases & Transactions
     ↓
Concurrency & Distributed Systems
     ↓
Caching & Event-Driven Architecture
     ↓
Cloud Deployment
     ↓
AI / ML-powered Applications
```

I'm particularly interested in problems involving:

* High-concurrency backend systems
* Distributed transactions
* Database performance
* Microservices
* API design
* Cloud-native applications
* AI/LLM-powered products
* Early-stage products where engineering decisions matter

---

# 🛠️ Technical Stack

### Languages

**Java · Python · JavaScript · TypeScript · C++ · SQL**

### Backend

**Spring Boot · Spring MVC · Spring Data JPA · Hibernate · Node.js · Express.js · REST APIs**

### Databases & Messaging

**PostgreSQL · MongoDB · Redis · Apache Kafka**

### Cloud & DevOps

**AWS · Docker · Linux · Git · CI/CD**

### AI / Machine Learning

**Scikit-learn · NumPy · Pandas · LLM APIs · RAG · AI Agents**

### Frontend

**React · Next.js · TypeScript · Thymeleaf · Bootstrap**

---

# 🎓 Education

### Indraprastha Institute of Information Technology, Delhi (IIIT-Delhi)

**B.Tech — Electronics & Communication Engineering**
**Minor — Entrepreneurship**
2021 – 2025

---

# 📫 Let's Connect

I'm interested in **Software Engineer / SDE1 / Backend Engineering** opportunities where I can work on real production systems, backend architecture, distributed systems, cloud applications, or AI-enabled products.

[LinkedIn](https://linkedin.com/in/princekumar182) · [GitHub](https://github.com/PrinceKumar182) · [Portfolio](https://princekumar182.github.io) · [Email](mailto:princekumar182@gmail.com)
