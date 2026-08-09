<h2 align="center">👋 Hi, I'm Husain Sakarwala</h2>

<p align="center">
  🎓 Computer Engineering @ <b>VJTI, Mumbai</b><br>
  💻 Full-Stack Developer | AI/ML Engineer | Robotics Enthusiast<br>
  🏆 <b>Grand Finalist, Smart India Hackathon 2025</b>
</p>

---

### 🔧 What I Do

- **🔴 Redis & Concurrent Booking Systems** – Solving race conditions and high-concurrency challenges using distributed caching and atomic operations for real-time slot management
- **🤖 RAG with LLM Evaluation** – Building production-grade retrieval-augmented generation pipelines with RAGAS/DeepEval frameworks to ensure reliability and accuracy in AI responses
- **⚡ Next.js & React** – Full-stack web applications
- **🔐 ML Cybersecurity** – Phishing detection, malware classification
- **🤖 Robotics & IoT** – ESP32 firmware, embedded systems
- **🏗️ SIH Backend** – Smart India Hackathon solutions

---

### 💼 Deep Dives

**🔴 Redis & Concurrent Booking Systems**

[smart_parking_book_system](https://github.com/HusainS07/smart_parking_book_system) | Next.js, PostgreSQL, Upstash Redis

**The Problem:** Thousands of users booking limited parking slots simultaneously. Without proper synchronization, double-bookings and race conditions destroy data integrity. Standard databases alone can't handle millisecond-level concurrency.

**Our Approach:**
- ACID transaction booking using PostgreSQL to prevent race conditions
- Upstash Redis for serverless edge-level rate limiting (10 attempts per 15 min per IP)
- Transaction-safe slot booking flow with database locking
- Client-side caching to eliminate redundant queries
- Parameterized SQL queries to prevent injection attacks

**Results:**
- ✅ Zero double-bookings under concurrent load
- ✅ OWASP-hardened: 100% parameterized queries, edge brute-force protection, IDOR safeguards
- ✅ Secure admin dashboard with role-based access control

---

**🤖 RAG with LLM Evaluation**

[RAG_S_PARK](https://github.com/HusainS07/RAG_S_PARK) | FastAPI, Pinecone, OpenRouter, Llama 3.3

**The Problem:** Most RAG systems skip validation. They retrieve documents and feed them to an LLM without checking if the answer is actually correct. Users get confident-sounding hallucinations.

**Our Approach:**
- Pinecone vector database for high-efficiency semantic retrieval with adaptive top-K scanning
- FastAPI asynchronous backend with health monitoring and debug endpoints
- Multi-phase evaluation (Simple, Medium, Complex) across 150 curated questions
- LLM-Judge scoring: Faithfulness, Answer Relevancy, Context Recall, Context Precision
- Deterministic statistical scoring: ROUGE-L, BERTScore, Cosine Similarity

**Evaluation Metrics (150 Test Questions):**
- ✅ **Overall Score:** 0.838/1.0
- ✅ **Faithfulness:** 0.818 (answers grounded in source documents)
- ✅ **Answer Relevancy:** 0.888 (responses directly address queries)
- ✅ **Context Precision:** 0.915 (retrieved docs are highly relevant)
- ✅ **Context Recall:** 0.736 (comprehensive context coverage)
- ✅ **BERTScore F1:** 0.777 (semantic similarity with ground truth)

---

### 📁 Other Projects

| Project | Tech | Description |
|---------|------|-------------|
| [ai-fitness-nutrition-coach](https://github.com/HusainS07/ai-fitness-nutrition-coach) | LangChain, Next.js | AI chatbot with personalized coaching |
| [PORTFOLIO](https://github.com/HusainS07/PORTFOLIO) | Next.js, React | Professional web showcase |
| [Phishing-Detect](https://github.com/Shree21941/Phishing-Detect) | Scikit-learn, Python | ML-based threat detection (95%+ accuracy) |
| [ROBOTICS_OTA](https://github.com/HusainS07/ROBOTICS_OTA) | C++, ESP32 | Firmware over-the-air updates for robots |

---

### 🛠️ Tech Stack

**Languages:** Python • JavaScript • C++

**Frontend:** Next.js • React • Tailwind CSS

**Backend:** Node.js • FastAPI • Express

**Databases:** MongoDB • MySQL • PostgreSQL

**AI/ML:** LangChain • Scikit-learn

**Tools:** Redis • Git • VS Code

---

### 📬 Connect

<p align="left">
  <a href="https://www.linkedin.com/in/mohamed-husain-sakarwala-b9b0b2226" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/HusainS07" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="mailto:mhs.sakarwala@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

⭐ *Building scalable, intelligent systems.*
