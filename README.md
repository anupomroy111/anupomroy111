<div align="center">
  <a href="https://github.com/anupomroy111">
    <img src="./assets/banner.jpg" alt="Anupom Roy - Software Developer | AI Builder | App Creator" width="100%" style="border-radius: 12px;" />
  </a>

  <br/><br/>

  <p align="center">
    <a href="https://github.com/anupomroy111">
      <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&duration=2500&pause=1000&color=38BDF8&center=true&vCenter=true&width=700&lines=Body-Tracked+AR+Games+%E2%80%94+MediaPipe+%2B+Three.js;RAG+Pipelines+with+Automated+LLM+Evaluation;Flutter+%26+Dart+Mobile+App+Specialist;On-Device+AI+%26+llama.cpp+Innovator;Python+%26+FastAPI+Backend+Architect" alt="Typing SVG" />
    </a>
  </p>

  <p align="center">
    <a href="https://www.linkedin.com/in/anupom-roy-728909401/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:royaa7840@gmail.com">
      <img src="https://img.shields.io/badge/Email-royaa7840%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://github.com/anupomroy111?tab=repositories">
      <img src="https://img.shields.io/badge/Public_Repos-25+-38BDF8?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" />
    </a>
    <img src="https://komarev.com/ghpvc/?username=anupomroy111&label=Profile%20Views&color=0284c7&style=for-the-badge" alt="Profile Views" />
  </p>
</div>

<br/>

### 💡 Professional Summary & Objective

> **Software Developer specializing in mobile application engineering with Flutter & Dart, native Android (Kotlin), Python backends (FastAPI/Django), privacy-first On-Device AI, browser-based AR (MediaPipe + Three.js), and evaluation-driven RAG systems.**
> Certified in **App Development with Flutter & AI (Ostad)** with demonstrated experience engineering memory-constrained apps with **0 MB background Flutter runtime overhead**, low-latency on-device inference on **2GB–4GB Android hardware**, hardware-backed encryption, real-time cloud architectures, and **measurable LLM quality** (faithfulness / hallucination evaluation with ablation studies).

- 📍 **Location:** Kaliyaganj, West Bengal, India
- 🎯 **Open to:** Entry-level Software Engineering Roles, Full-Stack / Mobile / AI Engineering & High-impact Collaborations.
- 📬 **Get in touch:** [royaa7840@gmail.com](mailto:royaa7840@gmail.com) • [LinkedIn](https://www.linkedin.com/in/anupom-roy-728909401/)


<p align="center">
  <a href="https://anupomroy111.github.io/Body-Tracking-AR-Running-Game/">
    <img src="https://img.shields.io/badge/TRY_ROY_SPEED-Live_Body--Tracked_AR_Demo-22d3ee?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Try ROY SPEED live demo" />
  </a>
</p>

---

### 🚀 Featured Engineering Projects

#### 🏃 [ROY SPEED — Body-Tracked AR Endless Runner](https://github.com/anupomroy111/Body-Tracking-AR-Running-Game)

<p>
  <a href="https://anupomroy111.github.io/Body-Tracking-AR-Running-Game/">
    <img src="https://img.shields.io/badge/LIVE_DEMO-Play_in_Browser-22d3ee?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live Demo" />
  </a>
  <a href="https://github.com/anupomroy111/Body-Tracking-AR-Running-Game">
    <img src="https://img.shields.io/badge/Source_Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" />
  </a>
</p>

*`JavaScript (ES Modules)` • `Three.js (WebGL)` • `MediaPipe PoseLandmarker` • `WebAudio API` • `Zero Build Step`*
- **Your Body Is the Controller:** Real-time full-body pose estimation drives gameplay — step sideways = lane change, arms up = jump, squat = slide, T-pose = hoverboard. GPU delegate with automatic CPU fallback, **100% client-side**, no install.
- **Robust Gesture Pipeline:** 2-second height/distance calibration, exponential smoothing, hysteresis lane bands, and per-gesture cooldowns turn noisy landmark streams into reliable real-time game events — with a live gesture coach and graceful touch/keyboard fallback.
- **Complete Game Product:** 4 unlockable runners with gameplay perks, rotating missions, coin-bank progression, 3 difficulty tiers, a fully procedural WebAudio soundtrack (zero audio assets), and a responsive premium dashboard from phone to desktop.

---

#### 🧪 [Custom RAG & Evaluation Pipeline — RAG That Grades Its Own Answers](https://github.com/anupomroy111/custom-rag-evaluation-pipeline)
*`Python` • `Hybrid BM25 + Dense (RRF)` • `LLM Reranking` • `Gemini API` • `LLM-as-Judge`*
- **Self-Evaluating RAG:** Citation-grounded generation with an automated evaluation pipeline measuring **Faithfulness, Hallucination rate, Answer Relevancy, Context Precision/Recall, and Refusal accuracy** — every claim audited against its source passage.
- **Measured Results (12-question golden set):** Faithfulness **1.000** and hallucination **0.000** across all retrieval variants; the ablation study exposes dense-only precision dropping to **0.908** on keyword-heavy queries and RRF fusion recovering it to **1.0**; both unanswerable questions correctly refused — zero fabricated answers.
- **Pure-Python Retrieval Core:** Okapi BM25 + cosine dense search fused with Reciprocal Rank Fusion, listwise LLM re-ranking (relevance grades 0–3), disk-cached embeddings, and one-command 4-variant ablation reports with a per-claim audit trail.

---

#### 🛡️ [ShieldMind AI — Offline AI Notification Firewall & Summarizer](https://github.com/anupomroy111/AI-Notification-Firewall-Context-Summarizer)
*`Flutter (Dart 3)` • `Kotlin` • `Riverpod` • `SQLite (WAL)` • `AES-256-GCM` • `llama.cpp`*
- **Zero-Overhead Architecture:** Engineered an offline Android security app for 2GB–4GB RAM devices with **0 MB background Flutter engine overhead** via native Kotlin background interceptor.
- **Real-Time Threat Classifier:** Built a high-speed Tier-1 security engine (~8 MB RAM, 8–14 ms latency) detecting phishing, OTP harvesting traps, and homograph character spoofing.
- **Privacy & Security:** Implemented hardware-backed **AndroidKeyStore AES-256-GCM** envelope encryption, `Isolate.run()` batch decryption, pure Dart TextRank + `llama.cpp` FFI summarization, and a 60 FPS GPU-optimized UI.

---

#### 🧠 GhostPilot AI — Low-RAM System-Wide Android Screen Copilot
*`Flutter` • `Kotlin` • `Accessibility Service` • `Multi-Process :agent` • `llama.cpp`*
- **Low-Resource Overlay HUD:** Architected a floating copilot operating smoothly on 2GB Android Go hardware (<= 8 MB incremental PSS, <= 50 ms p95 screen text extraction).
- **Play Store Compliant:** Designed strict suggest-only execution (**SafetyGate** confirmation flow) and automated local PII redaction (cards, OTPs, IBANs).
- **Multi-Mode AI Pipeline:** Offline deterministic heuristics, isolated `:agent` native `llama.cpp` inference, and optional BYOK cloud LLM integration.

---

#### 💬 Aora+ — Real-Time Private Android Messenger
*`Flutter` • `Dart` • `Firebase Auth` • `Cloud Firestore`*
- **Zero-Cost Scalable Architecture:** Private real-time messenger built to operate seamlessly on Firebase with Google Sign-In and unique `@username` claims.
- **Optimistic Real-Time Engine:** Implemented optimistic sending (`hasPendingWrites`), message editing, soft deletion, typing indicators, live presence, and lightweight split-ABI APKs (**22.9 MB** arm64-v8a).

---

#### 🔧 AI Mobile Technician & Voice Assistant
*`Kotlin` • `Jetpack Compose` • `Material 3` • `Room` • `SpeechRecognizer` • `Gemini API`*
- **Diagnostic Agent:** Engineered a bounded troubleshooting workflow (*observe → diagnose → consent → verify*) running live DNS/HTTPS probes with strict tool allowlists.
- **Multilingual Voice Engine:** Built multilingual speech dictation supporting **Bengali, Hindi, English, and Banglish** paired with a Gemini structured-output proxy.

---

#### 📚 AI-Powered Quiz & Learning Platform
*`Flutter` • `Go (Chi)` • `PostgreSQL (pgvector)` • `FastAPI` • `NATS JetStream` • `MinIO`*
- **Modular Monolith & Microservices:** Material 3 Flutter client integrated with high-performance Go backend and Python background workers for isolated document ingestion and vector semantic search (`pgvector`).

---

### 🎯 Technical Skills & Arsenal

<div align="center">

#### 💻 Programming Languages
<p align="center">
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
</p>

#### 📱 Mobile Engineering
<p align="center">
  <img src="https://img.shields.io/badge/Flutter_(Dart_3)-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=for-the-badge&logo=android&logoColor=white" alt="Jetpack Compose" />
  <img src="https://img.shields.io/badge/Riverpod-2C3E50?style=for-the-badge&logo=dart&logoColor=white" alt="Riverpod" />
  <img src="https://img.shields.io/badge/Provider-0175C2?style=for-the-badge&logo=flutter&logoColor=white" alt="Provider" />
  <img src="https://img.shields.io/badge/Material_3-7C3AED?style=for-the-badge&logo=materialdesign&logoColor=white" alt="Material 3" />
  <img src="https://img.shields.io/badge/Clean_Architecture-10B981?style=for-the-badge&logo=flutter&logoColor=white" alt="Clean Architecture" />
</p>

#### 🕶️ AR, Graphics & Game Engineering
<p align="center">
  <img src="https://img.shields.io/badge/Three.js_(WebGL)-000000?style=for-the-badge&logo=threedotjs&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/MediaPipe_Pose-0097A7?style=for-the-badge&logo=google&logoColor=white" alt="MediaPipe" />
  <img src="https://img.shields.io/badge/WebAudio_API-FF6F00?style=for-the-badge&logo=javascript&logoColor=white" alt="WebAudio" />
  <img src="https://img.shields.io/badge/Canvas_2D-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="Canvas 2D" />
  <img src="https://img.shields.io/badge/Responsive_Game_UI-7C3AED?style=for-the-badge&logo=css3&logoColor=white" alt="Responsive Game UI" />
</p>

#### 🤖 AI Engineering — On-Device, LLM & RAG
<p align="center">
  <img src="https://img.shields.io/badge/llama.cpp_(On--Device)-FF6F00?style=for-the-badge&logo=cplusplus&logoColor=white" alt="llama.cpp" />
  <img src="https://img.shields.io/badge/LiteRT_/_TFLite-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow Lite" />
  <img src="https://img.shields.io/badge/Google_Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini API" />
  <img src="https://img.shields.io/badge/RAG_Pipelines-4CAF50?style=for-the-badge&logo=python&logoColor=white" alt="RAG" />
  <img src="https://img.shields.io/badge/Hybrid_BM25%2BDense_(RRF)-0284C7?style=for-the-badge&logo=python&logoColor=white" alt="Hybrid Retrieval" />
  <img src="https://img.shields.io/badge/LLM--as--Judge_Evaluation-10B981?style=for-the-badge&logo=checkmarx&logoColor=white" alt="LLM Evaluation" />
  <img src="https://img.shields.io/badge/TextRank_%26_TF--IDF-4CAF50?style=for-the-badge&logo=python&logoColor=white" alt="NLP" />
  <img src="https://img.shields.io/badge/AI_Safety_Gates-E11D48?style=for-the-badge&logo=shield&logoColor=white" alt="AI Safety" />
</p>

#### ⚙️ Backend, Web & Message Brokers
<p align="center">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/REST_APIs-0284C7?style=for-the-badge&logo=fastapi&logoColor=white" alt="REST APIs" />
  <img src="https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white" alt="WebSockets" />
  <img src="https://img.shields.io/badge/NATS_JetStream-27AAE1?style=for-the-badge&logo=natsdotio&logoColor=white" alt="NATS" />
</p>

#### 🗄️ Databases & Storage
<p align="center">
  <img src="https://img.shields.io/badge/Firebase_(Firestore/Auth)-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/PostgreSQL_(pgvector)-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/SQLite_(WAL_Mode)-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Android_Room-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Room" />
  <img src="https://img.shields.io/badge/MinIO-C72C48?style=for-the-badge&logo=minio&logoColor=white" alt="MinIO" />
</p>

#### 🛠️ Developer Tools & DevOps
<p align="center">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white" alt="Android Studio" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
</p>

</div>

---

### 🎓 Certifications & Training

- 🏆 **App Development with Flutter & AI** — *Ostad* (Intensive hands-on training covering Flutter UI architecture, reactive state management [Riverpod, Provider], Firebase, REST APIs, and On-Device/Cloud AI workflows).
- 🏫 **Secondary Education (10th / Madhyamik)** — *Kaliyaganj Parbati Sundari High School (WBBSE)*

---

### 📊 GitHub Activity & Analytics

<div align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=anupomroy111&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Anupom's GitHub Stats" height="165" />
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=anupomroy111&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165" />
</div>

<br/>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=anupomroy111&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

<br/>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=anupomroy111&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Activity Graph" width="100%" />
</div>


<br/>

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=anupomroy111&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8" alt="GitHub Trophies" width="100%" />
</div>

---

### 🌐 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/anupom-roy-728909401/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:royaa7840@gmail.com">
    <img src="https://img.shields.io/badge/Email-royaa7840%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/anupomroy111" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<div align="center">
  <sub>⭐️ Built with precision, code &amp; passion by <a href="https://github.com/anupomroy111">Anupom Roy</a></sub>
</div>
