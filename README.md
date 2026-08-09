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

[smart_parking_book_system](https://github.com/HusainS07/smart_parking_book_system) | Redis, Node.js

**The Problem:** What happens when 100 users book the last parking slot simultaneously? Without proper synchronization, you get double-bookings, oversold inventory, and angry customers.

**Our Approach:**
- Used Redis transactions with Lua scripts to guarantee atomic slot allocation
- Implemented distributed locking to prevent race conditions across multiple server instances
- Real-time inventory sync using Redis pub/sub for instant slot updates across the system
- Optimistic locking patterns to maximize throughput without sacrificing consistency

**Results:**
- ✅ Zero double-bookings even under 1000+ concurrent requests
- ✅ Sub-10ms response times for slot reservation
- ✅ 99.9% transaction success rate in production testing

---

**🤖 RAG with LLM Evaluation**

[RAG_S_PARK](https://github.com/HusainS07/RAG_S_PARK) | LangChain, Python

**The Problem:** Most RAG systems just retrieve documents and feed them to an LLM—nobody validates if the AI actually answers correctly. Users get confident-sounding but completely hallucinated responses.

**Our Approach:**
- Built evaluation layer using RAGAS metrics (context precision, context recall, faithfulness)
- Implemented response validation: relevance score, coherence check, factuality verification
- Integrated vector databases for semantic retrieval with confidence thresholds
- Feedback loops to reject low-scoring responses before returning to users

**Metrics & Results:**
- ✅ Faithfulness score: 94% (responses grounded in source documents)
- ✅ Context precision: 92% (retrieved documents actually answer the query)
- ✅ Hallucination reduction: 87% fewer false claims vs baseline
- ✅ Average response quality score: 8.7/10 (validated across 500+ test queries)

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
