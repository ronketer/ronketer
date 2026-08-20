# Hi, I'm Ron Keter

**Computer Science student at the Hebrew University of Jerusalem**

I build systems software, computer vision pipelines, backend services, and practical AI tools.

Interested in **Software Engineering, Algorithms, AI/ML, Computer Vision, and Backend** roles.

[LinkedIn](https://linkedin.com/in/ronketer) · [GitHub](https://github.com/ronketer)

---

## Featured Projects

### [Local Anki Agent](https://github.com/ronketer/local-anki-agent)

> Python · AutoGen · Ollama · Pydantic · asyncio · pytest

![taskboard demo](https://github.com/ronketer/taskboard-app/blob/main/todo_app_demo.gif)

---

### [Full-Stack Taskboard](https://github.com/ronketer/taskboard-app)

> Node.js · Express · PostgreSQL · React · Docker · Kubernetes · GitHub Actions

A multi-user taskboard evolved from a CRUD app into a modular monolith with explicit service and persistence boundaries.

- Routes → Controllers → Services → Repositories → PostgreSQL
- Board-scoped `OWNER` / `MEMBER` authorization
- Transactional board creation and Personal-board provisioning
- Versioned migrations and data-preserving backfills
- 120 automated backend tests plus real PostgreSQL integration CI

---

### [Stereo Visual SLAM Pipeline](https://github.com/ronketer/kitti-visual-slam)

> Python · OpenCV · GTSAM · NumPy

Stereo visual odometry and SLAM on KITTI Sequence 05 using AKAZE features, RANSAC-PnP, bundle adjustment, and pose-graph loop closure.

- Processed about 2,600 frames
- Reduced translation error from 3.2 m/100 m to **0.9 m/100 m**
- Achieved about a **3.5× reduction in drift**

---

### [Multithreaded MapReduce Framework](https://github.com/ronketer/mapreduce-framework)

> C++17 · Linux · pthreads · atomics

A multithreaded MapReduce execution framework with atomic work distribution, per-thread intermediate storage, reusable barriers, and concurrent progress tracking.

- Parallel map, shuffle, and reduce stages
- Fine-grained synchronization with atomics and mutexes
- Validated under Valgrind and Helgrind

---

### [Research Paper RAG](https://github.com/ronketer/research-paper-rag)

> Python · LangChain · ChromaDB · Ollama · sentence-transformers · pytest

A local-first RAG system for academic PDFs with page-level citations, single-paper Q&A, and cross-paper comparison.

- Persistent local vector retrieval with ChromaDB
- Deterministic routing and retrieval separated from generation
- 30-question reproducible retrieval benchmark
- Measured 0.299 source-page F1@K for naive chunking vs. 0.260 for section-aware chunking
- 67 automated tests

---

<details>
<summary><strong>More Projects</strong></summary>

| Project | Description | Stack |
|---|---|---|
| [Preemptive User-Level Threading Library](https://github.com/ronketer/uthreads-scheduler) | User-space round-robin scheduler with `SIGVTALRM` preemption and manual context switching | C++11 · Linux |
| [Stereo Mosaicing](https://github.com/ronketer/stereo-mosaicing) | Pushbroom panorama synthesis with optical-flow motion estimation and vertical stabilization | Python · OpenCV |
| [Generative AI Personalization & Forensics](https://github.com/ronketer/diffusion-membership-inference) | Stable Diffusion personalization with LoRA/DreamBooth and reconstruction-based membership inference | Python · PyTorch |
| [Procedural Game Environment](https://github.com/ronketer/procedural-game-engine) | Infinite procedural 2D environment with Perlin-noise terrain and event-driven weather | Java |
| [STM32F405 Bare Metal](https://github.com/ronketer/stm32f405-bare-metal) | Register-level GPIO, SPI, I2C, and UART drivers without a HAL | C · ARM |

</details>

---

## Tech

**Languages & Systems**  
C · C++ · Python · Java · JavaScript · SQL · Linux · pthreads · POSIX signals

**AI / ML / Computer Vision**  
PyTorch · OpenCV · GTSAM · AutoGen · Ollama · LangChain · ChromaDB · Diffusers

**Backend & Infrastructure**  
Node.js · PostgreSQL · REST APIs · Docker · Kubernetes · GitHub Actions

**Frontend & Testing**  
React · Vite · pytest · Ruff

---

## Contact

**LinkedIn:** [linkedin.com/in/ronketer](https://linkedin.com/in/ronketer)  
**GitHub:** [github.com/ronketer](https://github.com/ronketer)
