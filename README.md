# 📘 AI Agents Lab

*A collection of hands-on projects, experiments, and early-stage MVPs exploring agentic AI systems.*

This repository serves as a structured workspace for building and experimenting with AI agents.
It includes small to medium-scale projects, explorations, and prototypes created while studying modern agentic frameworks, including work inspired by Google’s AI Agents curriculum.

The goal of this repo is to maintain a clear, scalable, and professional environment for experimentation, learning, and future development of production-ready agent systems.

---

## 🚀 What’s Inside

* **Modular projects:** Each project lives in its own folder under `projects/`, with isolated notebooks, code, and documentation.
* **Agentic workflows:** Implementations of planning, tool use, RAG, autonomy loops, and other agent patterns.
* **Experimentation sandbox:** Space for rapid prototypes, proofs-of-concept, and early MVPs.
* **Shared utilities:** Reusable helpers and components under `utils/`.
* **External data storage:** Large datasets and artifacts stored in Google Drive or cloud storage.

---

## 📂 Repository Structure

```plaintext
.
├── projects/               # Individual experiments, prototypes, or MVPs
│   └── project-name/
│       ├── notebooks/      # Colab / Jupyter notebooks
│       ├── src/            # Python modules and scripts
│       ├── data_sample/    # Small sample data for reproducibility
│       └── README.md       # Project-specific overview
│
├── utils/                  # Shared helpers used across projects
│
├── templates/              # Starter templates for new projects
│   └── project_template/
│
├── scripts/                # Automation scripts (e.g., new project generator)
│
├── requirements.txt        # Common dependencies
├── .gitignore
└── README.md
```

---

## 🛠️ How to Use This Repository

### Create a New Project

```bash
./scripts/new_project.sh <project-name>
```

### Work in Google Colab

```python
from google.colab import drive
drive.mount('/content/drive')
```

### Local Development

```bash
git clone https://github.com/pr-rithwik/ai-agents-lab.git
cd ai-agents-lab
pip install -r requirements.txt
```


## 🧠 Learning & Inspiration

This repository includes work influenced by modern agentic AI systems and resources such as:

* Google AI Agents course
* Industry agentic frameworks and design patterns

The repo is **not tied to any specific course** — it is intended to grow into a long-term space for experimentation and MVP development.

---

## 📌 Goals

* Build a strong foundation in **agentic AI engineering**
* Explore planning, tool use, memory, autonomy, and multi-agent systems
* Rapidly prototype ideas and validate concepts
* Maintain a polished, structured agent-focused portfolio

---

## 📄 License

MIT License unless otherwise noted.

---

## 🤝 Contributions

This is primarily a personal workspace, but thoughtful suggestions or issues are welcome.

