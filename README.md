# Hi, I'm Ron Keter

**3rd-year Computer Science student at the Hebrew University of Jerusalem**

I build systems software, computer vision pipelines, backend services, and practical AI tools.
Open to **internship and part-time roles** in SWE · Backend · Systems · ML/CV · DevOps.

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI/CD-2088FF?style=flat&logo=githubactions&logoColor=white)

---

## Featured Projects

### [taskboard-app](https://github.com/ronketer/taskboard-app) — Full-Stack Task Manager
> Node.js · Express · PostgreSQL · React 19 · Docker · Kubernetes · GitHub Actions CI (≥80% coverage)

Production-grade task management app with JWT auth, server-side pagination, multi-stage Docker builds, Kubernetes deployment manifests, and a CI pipeline that blocks merges below 80% backend test coverage.

![taskboard demo](https://raw.githubusercontent.com/ronketer/taskboard-app/main/todo_app_demo%20-%20frame%20at%200m16s.jpg)

---

### [kitti-visual-slam](https://github.com/ronketer/kitti-visual-slam) — Stereo Visual SLAM Pipeline
> Python · OpenCV · GTSAM · NumPy

Stereo visual SLAM processing 2,600+ KITTI frames — AKAZE feature tracking, RANSAC-PnP, windowed bundle adjustment, and pose graph loop closure achieving **0.9 m error per 100 m traveled**.

![trajectory comparison](https://raw.githubusercontent.com/ronketer/kitti-visual-slam/main/results/trajectory_comparison.png)

---

### [paper-qa-agent](https://github.com/ronketer/paper-qa-agent) — RAG System for Academic PDFs
> Python · LangChain · ChromaDB · Ollama · Gradio

Local-first retrieval-augmented generation with exact page-level citations. Dual chunking strategies (naive vs. section-aware) with a 30-question reproducible retrieval benchmark. 56 automated tests.

---

### [Stereo-Mosaicing](https://github.com/ronketer/Stereo-Mosaicing) — Pushbroom Panorama Stitcher
> Python · OpenCV · NumPy

Slit-scan panorama synthesis from panning video — Shi-Tomasi corner detection, Lucas-Kanade optical flow, vertical stabilization, and sub-pixel compositing.

![stereo-mosaicing demo](https://raw.githubusercontent.com/ronketer/Stereo-Mosaicing/main/videos/good_result.gif)

---

### [mapreduce-framework](https://github.com/ronketer/mapreduce-framework) — Multi-Threaded MapReduce
> C++17 · pthreads · std::atomic

MapReduce execution framework with atomic work-stealing, per-thread intermediate storage, two-phase barrier synchronization, and fine-grained locking for concurrent state monitoring.

---

### [uthreads-scheduler](https://github.com/ronketer/uthreads-scheduler) — User-Level Threading Library
> C++11 · POSIX signals · Linux x86-64

Preemptive round-robin thread scheduler in user space — `sigsetjmp`/`siglongjmp` context switching with direct stack/PC manipulation, `SIGVTALRM`-driven preemption, and signal-masked critical sections.

---

<details>
<summary><strong>More Projects</strong></summary>

| Project | Description | Stack |
|---|---|---|
| [Local-anki-agent](https://github.com/ronketer/Local-anki-agent) | Multi-agent LLM pipeline: notes → flashcards via deterministic agent routing, Pydantic validation, human-in-the-loop gate. Fully local with Ollama. | Python · AutoGen |
| [procedural-game-engine](https://github.com/ronketer/procedural-game-engine) | PEPSE: infinite procedural 2D world — Perlin noise terrain, physics, day/night cycle, observer-pattern weather system. | Java |
| [diffusion-membership-inference](https://github.com/ronketer/diffusion-membership-inference) | Membership inference attack on LoRA-finetuned Stable Diffusion to detect training data leakage. | Python · PyTorch |
| [stm32f405-bare-metal](https://github.com/ronketer/stm32f405-bare-metal) | Bare-metal ARM Cortex-M4 peripheral drivers (GPIO, SPI, I2C, UART) — no HAL, register-level. | C · ARM ASM |

</details>

---

## Contact

[![Email](https://img.shields.io/badge/ron.j.keter@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:ron.j.keter@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ronketer-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ronketer/)
[![Portfolio](https://img.shields.io/badge/Portfolio-ronketer.github.io-000000?style=flat&logo=githubpages&logoColor=white)](https://ronketer.github.io)
