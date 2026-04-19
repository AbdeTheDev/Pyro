<div align="center">

<img src="https://avatars.githubusercontent.com/u/236126230?v=4" width="120" height="120" style="border-radius: 50%;" alt="Pyro Logo" />

# Pyro 🔥

**The all-in-one Python developer toolkit that lives in your terminal.**  
Manage packages, environments, projects, databases, AI assistants, EXE builds and more — from a single, beautiful arrow-key interface.

> *One EXE. One window. Turn your machine into a Python forge. ⚡*

[![Status](https://img.shields.io/badge/status-alpha-orange?style=for-the-badge&logo=fire&logoColor=white)](./)
[![Platform](https://img.shields.io/badge/platform-Windows%2011-0078d4?style=for-the-badge&logo=windows&logoColor=white)](./)
[![Python](https://img.shields.io/badge/python-3.10+-3776ab?style=for-the-badge&logo=python&logoColor=white)](./)
[![License](https://img.shields.io/badge/license-Proprietary-red?style=for-the-badge)](./)
[![Stars](https://img.shields.io/github/stars/AbdeTheDev/Pyro?style=for-the-badge&logo=github)](https://github.com/AbdeTheDev/Pyro/stargazers)
[![Issues](https://img.shields.io/github/issues/AbdeTheDev/Pyro?style=for-the-badge&logo=github)](https://github.com/AbdeTheDev/Pyro/issues)

</div>

---

## 📸 Screenshots

<div align="center">

<img src="https://raw.githubusercontent.com/AbdeTheDev/Pyro/refs/heads/main/VideoCapture_20260418-214053.jpg" width="48%" alt="Pyro Main Menu" />
<img src="https://raw.githubusercontent.com/AbdeTheDev/Pyro/refs/heads/main/VideoCapture_20260418-214022.jpg" width="48%" alt="Pyro Package Manager" />

<img src="https://raw.githubusercontent.com/AbdeTheDev/Pyro/refs/heads/main/VideoCapture_20260418-214042.jpg" width="48%" alt="Pyro AI Assistant" />
<img src="https://raw.githubusercontent.com/AbdeTheDev/Pyro/refs/heads/main/VideoCapture_20260418-214013.jpg" width="48%" alt="Pyro Project Builder" />

<img src="https://raw.githubusercontent.com/AbdeTheDev/Pyro/refs/heads/main/VideoCapture_20260327-203109.jpg" width="70%" alt="Pyro Overview" />

</div>

---

## ✨ What's Inside

| # | Feature | Description |
|---|---------|-------------|
| 1 | 📦 **Package Manager** | Install, upgrade, remove, search PyPI, save requirements |
| 2 | 🌿 **Virtual Environments** | Create, inspect, activate, and delete venvs — now with in-Pyro activation |
| 3 | 🐍 **Python Versions** | Auto-detect, install, and set default Python versions system-wide |
| 4 | 🏗 **Project Builder** | Scaffold 7 project types with full lifecycle management |
| 5 | 📚 **Library Builder** | Build wheels, install editable, publish to PyPI |
| 6 | 💥 **EXE Builder** | Wrap any Python script into a standalone Windows `.exe` |
| 7 | 🔧 **Script Tools** | Run, multi-run, debug, analyse, benchmark scripts |
| 8 | 🔍 **Import Fixer** | Auto-detect and install all missing imports in one shot |
| 9 | 🔎 **PyPI Search** | Search PyPI and install directly from results |
| 10 | 📊 **Statistics** | Package charts, ecosystem overview, health dashboard |
| 11 | 🤖 **AI Assistant** | Chat with LM Studio, Ollama, or Google Gemini |
| 12 | 📦 **Dependency Store** | 100+ curated packages in 8 categories |
| 13 | 🛠 **Tools Installer** | Install IDEs, REPLs, AI tools, Git from one menu |
| 14 | ✏ **Vim Editor** | Modal code editor built into the terminal |
| 15 | 🗄 **SQLite Manager** | Full database CRUD, SQL console, CSV export |
| 16 | 📊 **RAM & Memory** | Live memory stats, top processes, Python usage |
| 17 | 🔐 **Script Toolkit** | Encrypt scripts, security scan, enhanced REPL |
| 18 | 🩺 **Environment Doctor** | Diagnose PATH, pip, Python, disk, network |
| 19 | ⚙ **Pyro Settings** | AI config, password lock, version control, auto-update |
| 20 | 📁 **Folder Navigator** | Browse and change directories without leaving Pyro |
| 21 | 🐛 **Bug Report** | Collect logs and open a GitHub issue in one click |
| 22 | ⚡ **Active Venv** | Activate a venv so every Pyro tool uses it automatically *(v1.1.0)* |
| 23 | 🚀 **Active Project** | Activate a project to lock Pyro's context to it *(v1.1.0)* |
| 24 | 🔌 **Pyro API** | Connect your running scripts to Pyro for live monitoring *(v1.1.0)* |
| 25 | 🛡 **Pyro Guard** | Real-time script behaviour and security monitor *(v1.1.0)* |

---

## 🚀 Getting Started

### Option A — Run the EXE *(no Python required)*

1. Download the latest `Pyro.exe` from the [**Releases page**](https://github.com/AbdeTheDev/Pyro/releases).
2. Place it anywhere on your system (e.g. `C:\Tools\Pyro\Pyro.exe`).
3. Double-click or run from CMD:

```cmd
Pyro.exe
```

### Option B — Run from source

Download the installer and follow the on-screen steps.

### Add Pyro to PATH *(recommended)*

Go to **⚙ Pyro Settings → Add Pyro to System PATH**.  
After a terminal restart, launch from anywhere:

```cmd
pyro
```

You can also run any Python script directly:

```cmd
pyro myscript.py
pyro myscript              # .py extension optional
pyro myscript.py --arg value
```

### 🎬 Tutorial

[![Watch Tutorial](https://raw.githubusercontent.com/AbdeTheDev/Pyro/main/thumbnail.png)](https://raw.githubusercontent.com/AbdeTheDev/Pyro/main/tutorial1.mp4)

---

## 🖥 Interface

Pyro runs as a **full-screen arrow-key menu** powered by the [Rich](https://github.com/Textualize/rich) library. Every screen shows the flame banner, current working directory, and a context-aware subtitle.

**Navigation:**

| Key | Action |
|-----|--------|
| `↑` / `↓` | Move selection |
| `Enter` | Confirm |
| `Esc` | Go back |
| `1`–`9` | Quick jump to item by number |
| `Ctrl+C` | Exit anywhere |

**Opening animation:** A flame ignition sequence plays on startup.  
**Exit animation:** Glass-shattering effect when you quit.

---

## 📦 Package Manager

Full pip wrapper with clean fire-themed output.

- **Install** by name, with optional version pinning (`requests==2.31`)
- **Install from requirements.txt** — auto-detects `*requirements*.txt` files in the current folder
- **Uninstall** with confirmation prompt
- **Upgrade** a single package or **upgrade all outdated** at once
- **List installed** packages with a version table
- **Package Info** — fetches PyPI metadata (summary, author, license, recent releases)
- **PyPI Search** — search by keyword, browse results, install directly
- **Save requirements.txt** — runs `pip freeze` and saves to a file of your choice

A background thread checks for outdated packages silently after you select a Python interpreter and shows a badge in the banner when updates are available.

---

## 🌿 Virtual Environments

Discover and manage virtual environments in the current project folder.

- **Auto-detects** `venv`, `.venv`, `env`, `.env`, `virtualenv` directories
- **Create** a new venv using any detected Python version
- **⚡ Use in Pyro** — activate a venv so every tool uses it automatically; a `🌿 Venv: name` badge appears on every screen
- **Activate** in a new CMD window (keeps your current session clean)
- **Inspect** size, Python path, and status
- **Install packages / requirements.txt** directly into a specific venv
- **List / save packages** for a venv
- **Upgrade all** outdated packages in a venv
- **Delete** a venv with confirmation

---

## 🐍 Python Versions & Installer

Pyro scans your system for all Python installations automatically.

**Detection sources:** Windows `py` launcher, `%LOCALAPPDATA%\Programs\Python\*`, `%APPDATA%\Python*`, `C:\` and `D:\` root directories, all entries in `PATH`.

**Actions:**
- View version, executable path, and pip version for any detected Python
- **Set as system default** — rewrites the user `PATH` in the Windows registry
- **Install a new version** — downloads the official installer from python.org directly

Available installers: Python 3.9 · 3.10 · 3.11 · 3.12 · 3.13

---

## 🏗 Project Builder & Manager

Scaffold production-ready Python projects in seconds.

### Project Types

| Type | Entry File | Pre-installed Deps |
|------|-----------|-------------------|
| Simple Script | `main.py` | — |
| Flask Web App | `app.py` | `flask` |
| FastAPI | `main.py` | `fastapi`, `uvicorn` |
| CLI Tool | `cli.py` | `click` |
| Data Science | `analysis.py` | `pandas`, `numpy`, `matplotlib` |
| Machine Learning | `train.py` | `scikit-learn`, `numpy`, `pandas` |
| Automation Script | `run.py` | — |

Each project gets: entry point with starter code, `config.pypip`, `requirements.txt`, `.gitignore`, `README.md`, and an optional virtual environment with dependencies pre-installed.

### Active Project *(v1.1.0)*

Activate a project from **Project Builder & Manager → Open Project → ⚡ Activate Project**. Pyro switches to the project folder and automatically activates the configured venv. The project name appears in the banner on every screen.

### `config.pypip` Format

```json
{
  "pypip_version": "1.1.0",
  "name": "my_project",
  "version": "1.0.0",
  "description": "My Python project",
  "type": "web-flask",
  "python_path": "C:/Python313/python.exe",
  "use_venv": true,
  "venv_name": "venv",
  "entry": "app.py",
  "author": "Your Name",
  "created": "2025-01-01T00:00:00",
  "dependencies": ["flask"],
  "locked": false
}
```

---

## 📚 Library Builder

Build and publish Python packages without touching raw `setup.cfg`.

1. **Create** — scaffolds a `src/` layout with `pyproject.toml`, `__init__.py`, `core.py`, tests, README, and `.gitignore`
2. **Build** — runs `python -m build` to produce `sdist` + `wheel` in `dist/`
3. **Install Editable** — `pip install -e .` so you can import the library immediately
4. **Publish to PyPI** — uses `twine upload dist/*` (requires a PyPI account and API token)

---

## 💥 EXE Builder

Wraps any Python script into a standalone Windows executable using PyInstaller.

- Select the script with the arrow-key file picker
- Choose `--onefile` (single `.exe`) or `--onedir`
- Toggle console window on/off
- Set a custom output name
- Progress shown inline while building
- Opens `dist/` in Explorer when done

---

## 🔧 Script Tools

### Run Script
Select any `.py` file with the file picker, optionally pass arguments.

### Multi-Script Runner
Select multiple scripts. Each one launches in its **own separate CMD window**, running in parallel.

### Smart Debugger
- **Run and capture output** — shows stdout/stderr with syntax highlighting
- **pdb debugger** — opens pdb in a new terminal (`n`=next, `s`=step, `c`=continue, `q`=quit)
- **cProfile** — runs the script through the profiler and shows top functions by cumulative time
- **Syntax check only** — fast `py_compile` check

### Script Analysis
Line count, function and class listing, import listing, cyclomatic complexity estimate, file size, longest line, TODO/FIXME count, and a visual bar chart of line composition.

### Speed Benchmark
Runs 6 standard Python benchmarks (Fibonacci, list comprehension, dict build, string join, sort, math) and produces a visual bar chart plus a **Pyro Score**.

### Import Fixer
Parses any `.py` file with AST, finds all imports, checks which are missing, and installs them in one batch. Includes a 90+ entry map of common import-name → PyPI-package-name differences (e.g. `cv2` → `opencv-python`, `PIL` → `Pillow`, `sklearn` → `scikit-learn`).

---

## 🤖 AI Assistant

Chat with AI models while you code — the AI can read and write files in your project.

### Supported Providers

| Provider | Type | Setup |
|----------|------|-------|
| **LM Studio** | Local | Run LM Studio, load a model, start the server |
| **Ollama** | Local | `ollama serve` then `ollama pull mistral` |
| **Google Gemini** | Cloud | API key from [aistudio.google.com](https://aistudio.google.com/app/apikey) |

### Session Commands

| Input | Action |
|-------|--------|
| Type your question | Send to AI |
| Empty line / Enter | End session |
| `/clear` | Reset conversation history |
| `/files` | List files in current directory |
| `/scan` | Run security scanner on a file |

After any AI reply that contains Python code blocks, Pyro offers to **save them directly to files**.

**Gemini auto-selects** the best available model on your account — no more "model not found" errors.

**Script crash → AI analysis** — when a script exits with an error, Pyro offers to send the traceback to your AI assistant for an instant explanation and fix suggestion.

---

## 🔌 Pyro API — Connect Your Scripts *(v1.1.0)*

Pyro now includes a developer integration system that lets running Python scripts send data to Pyro in real time — logs, errors, performance metrics, dependency information, and more.

### Quick Start

```python
import pyro_api as pyro

pyro.connect("my_app")
```

Get the SDK from **Main Menu → Pyro API → Copy SDK to project…** — Pyro places a `pyro_api.py` file in your project folder.

### Sending Data

```python
# Logs
pyro.log("Server started")
pyro.warn("Disk space low")
pyro.error("Connection failed", exc)

# Performance metrics
pyro.metric("requests_per_second", 342)

# Measure a block of code
with pyro.Timer("database_query"):
    result = db.execute(sql)

# Custom events
pyro.event("user_login", {"user_id": 42})

# Report installed packages
pyro.report_requirements()

# Attach to Python's built-in logging
pyro.attach_logging()
```

Uncaught exceptions are **captured and sent to Pyro automatically** — no extra code needed. If Pyro is not running, events are saved locally and sent the next time the server is available.

### The Dashboard

Open **Pyro API** from the main menu to see:

- **Live Event Log** — all events arriving in real time, auto-refreshes every 2 seconds
- **Sessions** — all connected scripts with connection status and error count
- **Errors & Tracebacks** — browse every error with full traceback
- **Metrics** — performance values charted visually
- **Dependency Reports** — packages installed in each connected environment

You can send any error directly to your AI assistant for analysis with one keypress.

---

## 🛡 Pyro Guard — Script Behaviour Monitor *(v1.1.0)*

Pyro Guard watches a Python script while it runs and shows you exactly what it is doing — what files it opens, what network connections it makes, how much memory it uses, and whether it shows suspicious behaviour.

### What It Monitors

| Category | Details |
|----------|---------|
| **Memory** | Live RAM usage with peak tracking |
| **CPU** | Processor usage percentage |
| **File access** | Every file your script opens |
| **Network** | Every outbound connection your script makes |
| **Security scan** | Automatic check for suspicious patterns in the source code |

### Threat Levels

| Level | Meaning |
|-------|---------|
| `✅ CLEAN` | Nothing suspicious found |
| `⚠ LOW RISK` | Minor indicators worth reviewing |
| `🔴 MEDIUM RISK` | Several indicators found |
| `💀 HIGH RISK` | Multiple serious indicators |

Press **Q** to stop monitoring or **K** to immediately kill the script.

---

## 🗄 SQLite Manager

A complete database management interface — no external tool needed.

- List tables, row counts, and column names
- Create tables with an interactive column builder
- View data in a paginated table
- Insert, edit, and delete rows with WHERE conditions
- Execute free-form SQL in the built-in console
- Export any table to CSV
- View database info (file size, SQLite version, table count)

Supports `.db` and `.sqlite` files. Opens existing databases or creates new ones.

---

## ✏ Vim Editor

A modal code editor built directly into the terminal — no external dependency.

| Mode | How to enter | Purpose |
|------|-------------|---------|
| **NORMAL** | `Esc` | Navigate, delete, yank, paste, search |
| **INSERT** | `i`, `a`, `A`, `I`, `o`, `O` | Type text |
| **COMMAND** | `:` | Save, quit, find/replace, jump to line |

Key shortcuts: `dd` delete line, `yy` yank, `u` undo (60 levels), `/` search, `:s/old/new/` replace, `:%s/old/new/` replace all, `:wq` save and quit.

---

## 📊 RAM & Memory Manager

Live system memory overview powered by `psutil`.

- System memory bar chart — Used / Available / Cached in GB
- Summary table — Total RAM, Used %, Available, Swap usage
- Top 20 processes by RSS — colour-coded by usage percentage
- Current Python process stats — PID, RSS, VMS, thread count
- 10 practical Python memory optimisation tips

---

## 🔐 Script Toolkit

### Script Encryption
Protect your source code with password-based XOR encryption. Encrypt to `.pyc.enc`, decrypt back to `.py`, or generate a self-contained launcher stub that decrypts and runs at runtime.

### Security Scanner
Static analysis using regex patterns and AST inspection.

| Severity | Issues Detected |
|----------|----------------|
| HIGH | `eval()`, `exec()`, `pickle.loads()`, hardcoded passwords, `shell=True` |
| MEDIUM | `os.system()`, MD5/SHA1, bare `except:`, debug mode enabled |
| LOW | Binding to `0.0.0.0`, `assert` in production code |
| INFO | TODO/FIXME/HACK markers |

### Enhanced REPL
Launch a better Python interactive shell — ptpython, ipython, bpython, or standard Python. Auto-installs the selected REPL if missing.

---

## 🩺 Environment Doctor

One-click diagnostics:

- Python interpreter accessibility
- pip version and availability
- `setuptools`, `wheel`, `rich` installation status
- Pending package updates
- PyPI network reachability
- Disk free space and platform info

Results are shown with ✓ / ⚠ / ✗ icons.

---

## ⚙ Pyro Settings

| Setting | Details |
|---------|---------|
| **AI Provider** | Configure endpoint and credentials for LM Studio, Ollama, and Gemini; test connection |
| **Password Protection** | Lock Pyro behind a password at startup (SHA-256 hash stored, plaintext never saved) |
| **Version Lock** | Checks GitHub releases on startup; forces update if a newer version exists |
| **Self-Updater** | Automatically downloads and applies the latest release |
| **Add to PATH** | Adds Pyro's directory to the Windows user PATH via the registry |

---

## 📁 Folder Navigator

Browse your filesystem without exiting Pyro.

- Arrow-key navigation through directories and files
- Files colour-coded by type (`.py` = orange, `.json`/`.toml` = blue, other = grey)
- Shows `config.pypip` project name if one exists in the viewed folder
- **Set Working Directory** — changes `cwd` for the current Pyro session
- **Type path manually** — jump to any absolute path
- **Go Home** — jump to `%USERPROFILE%`

---

## 📦 Dependency Store

Browse and install curated packages organised into 8 categories. Each entry shows whether it's already installed.

| Category | Example Packages |
|----------|-----------------|
| 🤖 AI & Machine Learning | tensorflow, torch, transformers, langchain, openai, anthropic |
| 📊 Data Science | numpy, pandas, matplotlib, plotly, polars, scipy, dask |
| 🌐 Web Development | flask, django, fastapi, aiohttp, httpx, scrapy, playwright |
| 🖥 GUI & Desktop | pyqt6, pyside6, customtkinter, dearpygui, pygame, kivy |
| 🗄 Database | sqlalchemy, psycopg2-binary, pymongo, redis, elasticsearch |
| 🔧 Dev Tools & CLI | rich, click, typer, tqdm, black, ruff, mypy, pytest |
| 🔐 Security & Crypto | cryptography, bcrypt, PyJWT, bandit, safety |
| 📁 Files & System | Pillow, pymupdf, python-docx, python-pptx, psutil, watchdog |

---

## 🛠 Tools Installer

Install external development tools directly from Pyro.

| Category | Tools |
|----------|-------|
| Code Editors | VS Code, PyCharm CE, Cursor AI, Neovim, Notepad++ |
| Python Dev | Git, uv, pipx, Docker, ngrok |
| AI & LLM | LM Studio, Ollama, Jan |
| Python REPLs | ptpython, ipython, Jupyter Lab |

---

## 🐛 Bug Report

Found a bug? Open **Main Menu → Bug Report** (item 21).

Pyro collects the last 50 session events, your Pyro version, Python version, platform, and current directory. Then you can:

- **Open GitHub Issues in browser** — pre-fills the title and body
- **Copy to clipboard** — paste anywhere
- **Save to `.md` file** — for email or attachment

---

## 🔄 Changelog

### v1.1.0 Alpha Fix 1

- **⚡ Active Venv** — activate a virtual environment inside Pyro; every tool uses it automatically
- **🚀 Active Project** — activate a project; Pyro locks its context to that folder and venv
- **🔌 Pyro API** — connect running scripts to Pyro for real-time log, metric, and error streaming
- **🛡 Pyro Guard** — live script behaviour monitor with file, network, CPU, RAM, and security tracking
- **Package installation** now shows a progress bar with percentage instead of just a spinner
- **AI chat** replies are displayed in a clean bordered card layout; code blocks are easier to read
- **AI system prompt** improved — the assistant now understands your project context and creates files directly
- **Gemini AI** now auto-detects available models — no more "model not found" errors
- **Script crash → AI analysis** — Pyro offers to send the traceback to your AI assistant instantly
- **Project Builder back button** fixed
- **Global Import Analyser** promoted to its own main menu entry
- Various stability improvements and minor fixes

---

## 🔒 Security & Privacy

- **No telemetry.** Pyro never sends data anywhere unless you explicitly use the Bug Report feature.
- **No ads.** The tool is clean.
- **API keys** are stored in `pyro_settings.json` in the tool's directory — never transmitted except to the provider you configure.
- **Password hashes** use SHA-256. Plaintext passwords are never written to disk.
- **File tool safety guard** — the AI assistant blocks access to `C:\Windows`, `C:\Program Files`, and `SYSTEMROOT` paths.

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/my-feature`
3. Make your changes and open a pull request

For bugs, use the **built-in Bug Report** (menu item 21) or open an issue at [github.com/AbdeTheDev/Pyro/issues](https://github.com/AbdeTheDev/Pyro/issues).

---

## 📜 License

**Proprietary — All rights reserved.**  
© 2025 Abdelhafid Moussa

This software is provided for personal and professional use. Redistribution, modification, or commercial use without explicit written permission from the author is not permitted.

---

## 🌟 Star History

If Pyro saves you time, give it a ⭐ — it helps a lot.

[![Star History Chart](https://api.star-history.com/svg?repos=AbdeTheDev/Pyro&type=Date)](https://star-history.com/#AbdeTheDev/Pyro&Date)

---

<div align="center">

**Built with 🔥 by [Abdelhafid Moussa](https://github.com/AbdeTheDev)**

[🐛 Report Bug](https://github.com/AbdeTheDev/Pyro/issues) · [✨ Request Feature](https://github.com/AbdeTheDev/Pyro/issues) · [💬 Discussions](https://github.com/AbdeTheDev/Pyro/discussions) · [▶ YouTube](https://www.youtube.com/@pyro-k4n)

</div>
