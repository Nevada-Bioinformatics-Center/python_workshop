# Python Workshops 


Welcome! This repository contains a **teaching workshop** for beginners who want a gentle, hands-on introduction to Python using Jupyter notebooks. No prior Python experience is required. Then, we take it a step further by going into our intermediate workshop to learn more skills.

---

## What’s inside

- **PythonCrashCourse_Notebook_beginner.ipynb** — the main workshop notebook you can run in your browser via Google Colab.
- Step-by-step exercises covering:
  - Basic Python syntax (variables, types, lists)
  - Control flow (if/else, loops)
  - Modules
  - Working in notebooks (cells, markdown, code)
  - Light data wrangling and plotting (intro level)

---

## Run in your browser (recommended)

Click the badge to launch the notebook in Colab:

**Beginner** - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nevada-Bioinformatics-Center/python_workshop/blob/main/PythonCrashCourse_Notebook_beginner.ipynb)

Tips:
- To keep your own copy: **File → Save a copy in Drive** (or **Save a copy to GitHub**).

---

## Run locally (optional)

If you prefer running on your machine:

### Using conda (mamba/conda)
```bash
mamba create -n pyworkshop python=3.10 jupyterlab numpy pandas matplotlib -y
mamba activate pyworkshop   # or: conda activate pyworkshop
jupyter lab
