<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Roboto&size=30&center=true&vCenter=true&width=500&height=70&duration=4000&color=B48CFF&lines=Hi,+I'm+Ryu.;Welcome+to+my+GitHub.;こんにちは,+ラン龍一と申します。" alt="Typing Intro" />
</h1>

<h3 align="center">Software Engineer · AI Agents & Backend</h3>
<h4 align="center">M.S. Computer Science @ University of Southern California (Dec 2026)</h4>

<p align="center">
  I build <b>AI agent systems</b> and the <b>backend infrastructure</b> that keeps them fast and reliable.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open_to-Full--time_roles-4ade80?style=flat-square" alt="Open to full-time roles"/>
  <img src="https://img.shields.io/badge/Graduating-Dec_2026-9b6bff?style=flat-square" alt="Graduating Dec 2026"/>
  <img src="https://img.shields.io/badge/U.S.-Permanent_Resident-60a5fa?style=flat-square" alt="U.S. Permanent Resident"/>
</p>

---

## 🌐 Connect
<p align="center">
  <a href="https://ryuichi-yamafuji-lun.github.io/Portfolio/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-Visit-7c3aed?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"/>
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/ryulun/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  &nbsp;
  <a href="https://docs.google.com/document/d/1LsHdHDT1QlYNuUpqcHDuX9iiHpufoeJY6G4o7vQz6IA/edit?usp=sharing" target="_blank">
    <img src="https://img.shields.io/badge/Résumé-View-111827?style=for-the-badge&logo=googledocs&logoColor=white" alt="Résumé"/>
  </a>
  &nbsp;
  <a href="https://scholar.google.com/citations?user=oITHaT0AAAAJ&hl=en" target="_blank">
    <img src="https://img.shields.io/badge/Google_Scholar-Profile-4285F4?style=for-the-badge&logo=google-scholar&logoColor=white" alt="Google Scholar"/>
  </a>
  &nbsp;
  <a href="mailto:ryuichi.y.lun@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-red?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## 🛠 Tech Stack
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,typescript,java,postgresql,mongodb,linux" /><br>
  <img src="https://skillicons.dev/icons?i=pytorch,fastapi,react,docker,azure,gcp,aws,githubactions" />
</p>

---

## 👤 About Me
- 🤖 **AI agents in production:** At Rakuten I built LLM cost monitoring on self-hosted Claude Managed Agents, metering spend against real usage data from a 10,000+ employee tenant, and rolled out AI code review to every pull request in the team's CI pipeline.
- ⚙️ **Backend and systems:** Concurrency control in C++ for main-memory databases, and duplicate-free message processing across concurrent cloud jobs.
- 🔐 **Research:** Securing the messages LLM agents send each other (MIRROR, NeurIPS 2026 FLMSec Workshop, [paper on arXiv](https://arxiv.org/abs/2610.02349)).
- 🌍 **Bilingual:** Fluent in **English** and **Japanese**. Born in São Paulo, raised in Honolulu, studied in Tokyo, now in Los Angeles.

---

## 💼 Experience

| Role | Where | When |
|:---|:---|:---|
| **AI Engineer Intern** | Rakuten Group (Rakuten AI), Red Queen Team, AI for Business CoE · Tokyo | May – Aug 2026 |
| **Software Engineer Intern** | Tomorrow's AI · Remote | Oct 2024 – Oct 2025 |
| **Systems Research Engineer (Student)** | Data Platform Laboratory, Keio Research Institute (with Mitsubishi UFJ Information Technology) | Mar 2022 – Sep 2024 |
| **Research Engineer Intern** | Japan Science and Technology Agency (JST) · Tokyo | Aug – Sep 2023 |

---

## 🎓 Education

| Degree | School | When |
|:---|:---|:---|
| **M.S. Computer Science** | University of Southern California | Dec 2026 |
| **B.A. Environment & Information Studies** | Keio University | Sep 2024 |

🏆 Outstanding Graduation Project Award (Keio, 2024, one of 12 recipients) · 1999 Mita-kai Scholarship (Keio, 2024, merit-based)

---

## 🚀 Featured Projects & Research

| Project / Research | Description | Stack |
|:---|:---|:---|
| [**MIRROR**](https://github.com/highphysicist/MIRROR-defense-for-aitm-mas) | **Multipath Quorum Integrity for LLM Multi-Agent Communication.** First author, led a 4-person team. NeurIPS 2026 FLMSec Workshop (accepted). [Paper (arXiv)](https://arxiv.org/abs/2610.02349) Protects messages between LLM agents from an intermediary that can read and rewrite them: each message travels over several independent routes and is accepted only when a majority agree, with no extra LLM calls. Evaluated on AutoGen and CAMEL. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Agents](https://img.shields.io/badge/LLM-Multi--Agent-blue?style=flat-square) ![Security](https://img.shields.io/badge/Agent-Security-red?style=flat-square) |
| [**FafnirDT**](https://github.com/Ryuichi-Yamafuji-Lun/FafnirDT) | **Concurrency Control for Main-Memory Databases.** First author, 163rd System Software & OS Symposium (2024). Replaced fixed-size thread structures in 2PL with an elastic reader-writer lock and dynamic timestamp tracker, restoring throughput from **0 to 500,000+ transactions/sec** under heavy multicore contention. | ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Systems](https://img.shields.io/badge/Symposium-2024-green?style=flat-square) |
| [**MediSkinAI**](https://github.com/Ryuichi-Yamafuji-Lun/MediSkinAI) | **Melanoma Screening Agent.** Fine-tuned ResNet50 on 33,126 ISIC 2020 images (56:1 class imbalance), with a LangGraph agent that explains each result in plain language through a Gemini reasoning step. FastAPI on Google Cloud Run; 27+ early users. [Live site](https://mediskinai.vercel.app/) | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![GCP](https://img.shields.io/badge/GCP-Cloud_Run-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-Agent-gray?style=flat-square) |
| [**GenAI vs RL Tetris**](https://github.com/Ryuichi-Yamafuji-Lun/Tetris-Benchmark/tree/main) | **AI Agent Benchmarking.** Custom Gymnasium interface that lets Gemini and GPT models play Tetris head-to-head against a Deep Q-Network baseline. A Chain-of-Thought module improved survival by 8.2%. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=google&logoColor=white) ![RL](https://img.shields.io/badge/RL-DQN-orange?style=flat-square) |
