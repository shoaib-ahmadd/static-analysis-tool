<div align="center">

# 🔍 Static Code Analysis Tool

**Detect bugs, bad practices, and code smells in Python — without executing a single line.**

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-Backend-000000?style=flat-square&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![HTML CSS](https://img.shields.io/badge/HTML%2FCSS-Frontend-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Status](https://img.shields.io/badge/Status-Active-22c55e?style=flat-square)]()
[![License](https://img.shields.io/badge/License-MIT-f59e0b?style=flat-square)]()

</div>

---

## What is this?

A lightweight web-based tool that analyzes your Python source code for common issues — **no execution required**. Upload a `.py` file, get a quality score, and see a breakdown of detected problems instantly.

Great for beginners learning clean code practices, or anyone wanting a quick sanity check before a code review.

---

## Features

- 🔍 Detects missing docstrings, unused imports, long lines & formatting issues
- 🐞 Flags potential bugs before they cause problems
- ⚡ Instant static analysis — no code is ever executed
- 📊 Code quality score with a clear issues breakdown
- 🧠 Simple, beginner-friendly codebase — easy to read and extend

---

## Tech Stack

| Layer | Technology |
|---|---|
| **Backend** | Python + Flask |
| **Frontend** | HTML, CSS |
| **Core Logic** | Custom static analyzer |

---

## Project Structure

```
project/
├── analyzer.py     # Core static analysis logic
├── app.py          # Flask web server & API routes
├── index.html      # Frontend UI
├── static.css      # Styling
└── README.md       # Documentation
```

---

## Getting Started

**1. Install the dependency**

```bash
pip install flask
```

**2. Start the server**

```bash
python app.py
```

**3. Open in browser**

```
http://127.0.0.1:5000
```

Upload any `.py` file and get your analysis instantly.

---

## How It Works

```
Upload .py File
      ↓
Analyzer reads source code
      ↓
Checks for:
  • Missing docstrings
  • Unused imports
  • Lines exceeding length limit
  • Formatting issues
      ↓
Quality Score + Issue Report
      ↓
Displayed in Browser UI
```

---

## Use Cases

- 🎓 Academic / mini projects
- 📚 Learning how static analysis works
- 🧹 Quick code quality checks before reviews
- 🐍 Improving Python code hygiene

---

## Roadmap

- [ ] Multi-language support (JavaScript, Java, C++)
- [ ] AST-based deep analysis
- [ ] AI-powered code improvement suggestions
- [ ] Improved UI/UX with syntax highlighting
- [ ] Exportable PDF reports

---

## Author

<div align="center">

**Shoaib Ahmad**

[![GitHub](https://img.shields.io/badge/GitHub-shoaib--ahmadd-181717?style=flat-square&logo=github)](https://github.com/shoaib-ahmadd)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-shoaib--ahmadd-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/shoaib-ahmadd)

If this project helped you, drop a ⭐ on GitHub — it genuinely helps!

</div>
