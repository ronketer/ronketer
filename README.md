# Hi, I'm Ron Keter

**B.Sc. Computer Science student at the Hebrew University of Jerusalem — expected 2028**

I build systems software, computer vision pipelines, backend services, and practical AI tools.

Open to **student and internship roles** in Software Engineering · Algorithms · AI/ML · Computer Vision · Backend.

[LinkedIn](https://linkedin.com/in/ronketer) · [GitHub](https://github.com/ronketer) · [Email](mailto:ron.j.keter@gmail.com)

---

## Tech Stack

**Languages & Systems:** C · C++ · Python · Java · JavaScript · SQL · Linux  
**AI / ML / CV:** PyTorch · OpenCV · GTSAM · AutoGen · Ollama · LangChain  
**Backend & Infrastructure:** Node.js · PostgreSQL · REST APIs · Docker · Kubernetes · GitHub Actions  
**Frontend & Testing:** React · Vite · pytest · Ruff

---

## Featured Projects

### [Local Anki Agent](https://github.com/ronketer/local-anki-agent)

> Python · AutoGen · Ollama · asyncio · Pydantic · pytest

Local-first 4-agent pipeline that turns study notes into reviewed Anki flashcards while keeping workflow control and side effects in deterministic application code.

- Built explicit human approval before Anki writes, durable run-state persistence, and per-card idempotency
- Added crash-safe `--resume` recovery that reconciles interrupted writes before creating missing cards
- **72 automated tests with Ruff/pytest CI** · Reduced my study-card creation time from about 2 hours to 30 minutes

---

### [Full-Stack Taskboard](https://github.com/ronketer/taskboard-app)

> Node.js · Express · PostgreSQL · React · Docker · Kubernetes · GitHub Actions

Multi-user taskboard evolved from a CRUD app into a modular monolith with clear HTTP, application, and persistence boundaries.

- Added board-scoped `OWNER` / `MEMBER` authorization and defense-in-depth task scoping
- Built transactional board creation, versioned migrations, data-preserving backfills, and PostgreSQL-enforced invariants
- **120 automated backend tests plus real PostgreSQL integration CI**

---

### [Stereo Visual SLAM Pipeline](https://github.com/ronketer/kitti-visual-slam)

> Python · OpenCV · GTSAM · NumPy

Stereo visual odometry and SLAM on KITTI Sequence 05 using AKAZE features, RANSAC-PnP, windowed bundle adjustment, and pose-graph loop closure.

- Processed **2,600 frames** and evaluated the full trajectory against KITTI ground truth
- Reduced translation error from **3.2 m/100 m to 0.9 m/100 m**, a **3.5× reduction**

---

### [Multithreaded MapReduce Framework](https://github.com/ronketer/mapreduce-framework)

> C++17 · Linux · pthreads · `std::atomic`

Multithreaded MapReduce execution framework with atomic work distribution, per-thread intermediate storage, reusable barriers, and fine-grained synchronization across map, shuffle, and reduce stages.

---

### [Research Paper RAG](https://github.com/ronketer/research-paper-rag)

> Python · LangChain · ChromaDB · Ollama · sentence-transformers · pytest

Local-first RAG application for academic PDFs with persistent retrieval, page-level citations, deterministic routing, and single-paper and cross-paper question answering.

- Built a reproducible **30-question retrieval benchmark** using the same retrieval policy as the application
- Measured **0.299 source-page F1@K** for naive chunking versus **0.260** for the section-aware implementation
- **67 automated tests** across ingestion, routing, retrieval, generation, persistence, services, and UI handlers

---

<details>
<summary><strong>More Projects</strong></summary>

| Project | Description | Stack |
| --- | --- | --- |
| [Preemptive User-Level Threading Library](https://github.com/ronketer/uthreads-scheduler) | User-space round-robin scheduler with timer preemption and manual context switching | C++11 · Linux |
| [Stereo Mosaicing](https://github.com/ronketer/stereo-mosaicing) | Pushbroom panorama synthesis with optical-flow motion estimation and vertical stabilization | Python · OpenCV |
| [Generative AI Personalization & Forensics](https://github.com/ronketer/diffusion-membership-inference) | Stable Diffusion personalization with LoRA/DreamBooth and reconstruction-based membership inference | Python · PyTorch |
| [Procedural Game Environment](https://github.com/ronketer/procedural-game-engine) | Infinite procedural 2D environment with Perlin-noise terrain and event-driven weather | Java |
| [STM32F405 Bare Metal](https://github.com/ronketer/stm32f405-bare-metal) | Register-level GPIO, SPI, I2C, and UART drivers without a HAL | C · ARM |

</details>

---

## Contact

I'm currently looking for my first software engineering role while completing my degree.

[LinkedIn](https://linkedin.com/in/ronketer) · [GitHub](https://github.com/ronketer) · [Email](mailto:ron.j.keter@gmail.com)
