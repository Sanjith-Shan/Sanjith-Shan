# 👋 About Me

Hey! I'm Sanjith, a **Math-CS major** at **UCSD** with a minor in **Data Science**. 

I build systems across the stack, from CUDA kernels on A100s to production AI pipelines to custom PCBs and embedded firmware. I'm currently a **Forward Deployed Engineer Intern at Paragon (YC W25)** building AI matching pipelines for 300 daily users, and **President of Triton Neurotech** where I lead 70+ developers building brain-computer interfaces. Previously a **Software Engineer Intern at Eigen Labs (a16z-backed)** where I won 1st Place at their Agent Hackathon. I've won **6 hackathons** and I'm always looking for the next thing to build.


## 🚀 Projects

### GPU & Performance
⚡ **[CUDA-SGEMM-Optimization](https://github.com/Sanjith-Shan/CUDA-SGEMM-Optimization)** – High-performance matrix multiply kernels in CUDA C++ on A100. Reached 87.6% of cuBLAS throughput. Benchmarked against CUTLASS (97.7% cuBLAS). Dockerized for reproducible GPU benchmarking.

💰 **[MonteCarloGPU](https://github.com/Sanjith-Shan/MonteCarloGPU)** – GPU-accelerated Monte Carlo option pricing engine. European, Asian, and barrier options with cuRAND Philox. 63x CPU-to-GPU speedup. Neural surrogate pricer at 545K options/sec. Portfolio VaR, delta hedging backtest, and convergence analysis. Containerized with Docker, scaled via Slurm and Kubernetes.

### AI & ML
🔍 **[NotionFlow](https://github.com/Sanjith-Shan/NotionFlow)** – AI knowledge agent for Notion workspaces. RAG pipeline with vector embeddings, semantic chunking, and a Notion Worker with 3 agent tools on the Developer Platform. React dashboard and CLI with a dependency-free TF-IDF fallback.

📊 **[AdRankBench](https://github.com/Sanjith-Shan/AdRankBench)** – CTR prediction benchmark training 5 ranking models (LR, FM, DeepFM, DCN, DNN) on 2M+ Criteo ad impressions. Two-tower DSSM relevance model, budget pacing simulator, and inference optimization across PyTorch, ONNX Runtime, and OpenVINO.

🧪 **[LLM Statistical Reasoning Eval](https://github.com/Sanjith-Shan/LLM_Statistical_Reasoning_Eval)** – Evaluation framework that found a systematic blind spot in frontier LLMs. 0% pass@3 on Gemini Flash across 10 tasks with deterministic verifiers in sandboxed Docker environments.

### Fullstack & Platform
🚀 **[SudoApply](https://sudoapply.vercel.app/)** – Agentic job application platform. 30+ beta testers, 500+ applications weekly. Next.js web app, SwiftUI iOS app, two Python microservices. Auto-apply engine spawning parallel browser agents across 12 ATS platforms.

☁️ **[CloudRelay](https://github.com/Sanjith-Shan/CloudRelay)** – Cloud gaming session orchestration service. Java Spring Boot, Redis cache-aside with pub/sub, MongoDB, Kubernetes with Helm, Prometheus monitoring. 700+ req/s, p99 under 45ms.

### Hardware & Embedded
⚡ **[Jupiter Touch](https://github.com/Sanjith-Shan/Jupiter-Touch)** – Per-finger EMS haptic feedback system for VR. 2 custom PCBs in KiCad, Arduino C++ firmware, I2C digital potentiometers, 12 independent stimulation channels, Python UDP bridge routing 90 Hz hand-tracking from Meta Quest 3.

🔧 **[Forge](https://crates.io/crates/forge-embedded)** – Published Rust CLI on crates.io that generates dependency-ordered C initialization code and Zephyr RTOS devicetree overlays for embedded boards from natural language. Compiler-style pipeline detecting pin conflicts and bus overload.

🤖 **[MiniVLA](https://github.com/Sanjith-Shan/MiniVLA)** – Vision-language-action model for robotic manipulation. Frozen ResNet-18 vision encoder, learned language encoder, multimodal fusion, and action decoder. Trained on 5,000+ simulated demonstrations in PyBullet. 80% pick task success rate.


## 🏆 Hackathon Wins

| Award | Event |
|-------|-------|
| 🥇 1st Place, Hardware+IoT + Best Use of Gemini | UCSD DataHacks |
| 🥇 1st Place, Qualcomm Multi-Device Track | UCSD DiamondHacks |
| 🥇 1st Place Overall | Eigen Labs Agent Hackathon |
| 🥈 2nd Place Overall | United Nations Reboot the Earth |
| 🥈 2nd Place, BCI Competition | California Neurotech Conference |
| 🏅 4th Place | Amgen State Hackathon |


## 💼 Experience

**Current:**  
🔧 Forward Deployed Engineer Intern @ **Paragon (YC W25)** – AI matching pipeline, 300 daily users, 170K products, $60M+ quoted value  
🧠 President @ **Triton Neurotech** – 70+ developers, BCI for assistive tech

**Previous:**  
⚙️ Software Engineer Intern @ **Eigen Labs (a16z-backed)**
🔬 ML Engineer & Research Assistant @ **UCSD Neuroengineering Lab**  
📊 Software Engineering Intern @ Bumper Inc.  
📚 Research Assistant @ Stanford Eberhart Lab  
💼 Research Assistant @ UC Berkeley Even-Tov Lab  
🧪 Research Assistant @ UC Berkeley Critcher Lab  
🛒 Cofounder @ Lagoon AI  
🏥 CEO @ FullCart Incorporated  
📖 President/Founder @ BizTheory Incorporated


## 💻 Tech Stack

### Languages
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![SQL](https://img.shields.io/badge/sql-%2307405e.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white) ![LaTeX](https://img.shields.io/badge/latex-%23008080.svg?style=for-the-badge&logo=latex&logoColor=white)

### Frameworks & Libraries
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Infrastructure & Tools
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) ![MongoDB](https://img.shields.io/badge/mongodb-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![NGINX](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### Hardware & Embedded
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white) ![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white) ![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white)

---

📫 **Contact:** sshanmugavel@ucsd.edu
🌐 **Website:** [sanjith.space](https://sanjith.space)
🔗 **LinkedIn:** [linkedin.com/in/sanjith-shan](https://linkedin.com/in/sanjith-shan)
