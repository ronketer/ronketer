# Hi, I'm Ron Keter

**Computer Science student at the Hebrew University of Jerusalem**

I build systems software, computer vision pipelines, backend services, and practical AI tools.  
Open to **student and internship roles** in Software Engineering · Algorithms · AI/ML · Computer Vision · Backend.

---

## Tech Stack

**Languages & Systems:** C · C++ · Python · Java · JavaScript · SQL · Linux  
**AI / ML / CV:** PyTorch · OpenCV · GTSAM · AutoGen · Ollama · LangChain  
**Backend & Infrastructure:** Node.js · PostgreSQL · Docker · Kubernetes · GitHub Actions  
**Frontend & Testing:** React · Vite · pytest · Ruff

---

## Featured Projects

### [Local Anki Agent](https://github.com/ronketer/local-anki-agent)

> Python · AutoGen · Ollama · asyncio · Pydantic · pytest

4-agent study-card pipeline with deterministic state-machine orchestration, Writer–Reviewer reflection, and explicit human approval before Anki writes.

Built idempotent per-card writes, durable run-state persistence, and crash-safe `--resume` recovery to prevent duplicate cards after partial failures.  
**72 automated tests with Ruff/pytest CI. Reduced my study-card creation time from about 2 hours to 30 minutes.**

---

### [Full-Stack Taskboard](https://github.com/ronketer/taskboard-app)

> Node.js · Express · PostgreSQL · React · Docker · Kubernetes · GitHub Actions

Multi-user taskboard built as a modular monolith with separate route, controller, service, and repository layers.

Added board-scoped `OWNER`/`MEMBER` authorization, transactional workflows, versioned migrations, and data-preserving backfills.  
**120 automated backend tests plus real PostgreSQL integration CI.**

---

### [Stereo Visual SLAM Pipeline](https://github.com/ronketer/kitti-visual-slam)

> Python · OpenCV · GTSAM · NumPy

Stereo visual SLAM on KITTI Sequence 05 using AKAZE features, RANSAC-PnP, windowed bundle adjustment, and pose-graph loop closure.

Processed about 2,600 frames and reduced translation error from 3.2 m/100 m to **0.9 m/100 m**, a **3.5× improvement**.

---

### [Multithreaded MapReduce Framework](https://github.com/ronketer/mapreduce-framework)

> C++17 · Linux · pthreads · std::atomic

Multithreaded MapReduce framework with atomic work distribution, per-thread intermediate storage, reusable barriers, and fine-grained synchronization.

Validated concurrent behavior under Valgrind and Helgrind.

---

### [Research Paper RAG](https://github.com/ronketer/research-paper-rag)

> Python · LangChain · ChromaDB · Ollama · sentence-transformers · pytest

Local-first RAG application for academic PDFs with persistent retrieval, page-level citations, and single-paper and cross-paper Q&A.

Built a reproducible 30-question retrieval benchmark measuring **0.299 source-page F1@K** for naive chunking versus **0.260** for section-aware chunking.  
**67 automated tests.**

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

[LinkedIn](https://linkedin.com/in/ronketer) · [GitHub](https://github.com/ronketer)
