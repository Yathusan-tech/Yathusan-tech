# 👨‍💻 Hi, I'm Yathusan J

**B.Tech Computer Science and Engineering Student** | Software Developer | Tech Explorer

---

### 📌 About Me

I am a passionate Computer Science student dedicated to building high-performance web applications, strengthening computer science fundamentals, and exploring emerging software technologies. 

* 🎓 **Degree:** B.Tech in Computer Science and Engineering
* 💻 **Primary Focus:** Web Development & Software Engineering
* 🧠 **Currently Learning:** Advanced AI Architectures, Large Language Models (LLMs), & Retrieval-Augmented Generation (RAG)
* 🚀 **Current Goals:** Building full-stack production-ready applications and contributing to open-source software.

---

### 🧠 Current Learning Focus: AI & Modern Technologies

To stay ahead in modern software development, I am actively diving into contemporary Artificial Intelligence topics:

* **Retrieval-Augmented Generation (RAG):** Combining Vector Databases (like Chroma/Pinecone) with LLMs to build grounded AI knowledge assistants.
* **Agentic AI Frameworks:** Building autonomous workflows using tools like LangChain and CrewAI.
* **Efficient Fine-Tuning:** Understanding transformer models, prompt engineering, and local model inference (Ollama/Hugging Face).

---

### 📊 GitHub Stats & Overview

<p align="left">
  <img src="https://img.shields.io/badge/GitHub-Yathusan--tech-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile"/>
</p>

* **Focus Areas:** Software Development • Web Engineering • Computer Science
* **GitHub Activity:** Documenting my learning journey, building practical projects, and improving developer skills continuously.

---

### 🤝 Let's Connect

I'm always interested in connecting with fellow developers, students, and tech enthusiasts working on interesting projects.

<p align="left">
  <a href="https://www.linkedin.com/in/yathusan-j/">
    <img src="https://img.shields.io/badge/LinkedIn-Yathusan_J-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:yathusan795@gmail.com">
    <img src="https://img.shields.io/badge/Email-yathusan795%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/Yathusan-tech">
    <img src="https://img.shields.io/badge/GitHub-Yathusan--tech-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
</p>

> 🚀 *"Building software. Strengthening fundamentals. Learning continuously."*

---

### 🎮 Contribution Arcade

#### 🐍 Snake — My Contributions in Motion

![github contribution grid snake animation](https://raw.githubusercontent.com/Yathusan-tech/Yathusan-tech/output/github-contribution-grid-snake.svg)

*Every square represents a day. Every contribution tells part of the journey. 🚀*

---

name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *" # Runs every day at midnight
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3

      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

          *Every square represents a day. Every contribution tells part of the journey. 🚀*
          
