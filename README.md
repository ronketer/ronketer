# Hi, I'm ronketer 👋

I’m a developer interested in systems programming, concurrency, distributed systems, and applied algorithms. I like building small, focused projects to learn fundamentals—especially around threading, MapReduce-style data processing, REST APIs, and SLAM.

- Languages: C, C++, Python, JavaScript
- Tooling: Linux, Make, Git
- Currently: Exploring SLAM concepts in Python and sharpening systems skills with C/C++

## Featured projects

###  [Deep Learning Diagnostic Dashboard](https://github.com/ronketer/mnist-variational-inference)
**Stack:** Python, PyTorch, JavaScript, Chart.js
* **What it is:** A research pipeline for Variational Auto-Encoders (VAE) and CNNs.
* **Key Feature:** Engineered a custom **JavaScript visualization dashboard** to automate the reporting of diagnostic metrics (MSE reconstruction vs. KL divergence) during training.
* **Result:** Achieved >97% accuracy on classification benchmarks and reduced metric analysis time.

###  [Vision Aided Navigation (SLAM)](https://github.com/ronketer/SLAM-VN)
**Stack:** Python, OpenCV, GTSAM
* **What it is:** A stereo visual SLAM pipeline built from scratch on the KITTI dataset.
* **Key Feature:** Implemented AKAZE tracking, stereo triangulation, and outlier rejection (RANSAC).
* **Result:** Reduced relative translation error by 3x using windowed bundle adjustment and pose-graph optimization.

###  [Multithreaded MapReduce Framework](https://github.com/ronketer/map-reduce)
**Stack:** C++, pthreads, Linux
* **What it is:** A high-performance concurrency framework managing N worker threads.
* **Key Feature:** Thread-safe barrier synchronization and atomic counters.
* **Result:** Deterministic output with optimized per-thread intermediate sorting.

###  [User-Level Threads (UThreads)](https://github.com/ronketer/user-level-threads)
**Stack:** C++, Assembly
* **What it is:** A user-space threading library (green threads).
* **Key Feature:** Implemented round-robin scheduling, context switching, and signal handling to manage cooperative concurrency.

###  [Secure RESTful API](https://github.com/ronketer/todo-list-api)
**Stack:** Node.js, Express, MongoDB
* **What it is:** A secure backend service for task management.
* **Key Feature:** Implemented JWT authentication, Helmet/XSS protection, and centralized error handling for production safety.

## What I’m into

- Systems programming: threads, schedulers, synchronization, memory
- Distributed/data processing patterns (MapReduce-style)
- Backend fundamentals and API design
- Visual computing/SLAM experimentation

## Get in touch

- GitHub: https://github.com/ronketer
