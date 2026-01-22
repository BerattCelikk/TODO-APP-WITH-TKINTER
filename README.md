<div align="center">

# 📝 TaskForge UI: High-Efficiency Task Management
### *A Lightweight, Event-Driven Desktop Application for Seamless Workflow Orchestration*

---

[![Overview](https://img.shields.io/badge/📖_Overview-blue?style=for-the-badge)](#-project-overview)
[![Key Features](https://img.shields.io/badge/✨_Key_Features-6f42c1?style=for-the-badge)](#-key-features)
[![Tech Stack](https://img.shields.io/badge/🛠️_Tech_Stack-success?style=for-the-badge)](#-tech-stack)
[![Architecture](https://img.shields.io/badge/🏗️_Architecture-orange?style=for-the-badge)](#-technical-architecture)
[![Installation](https://img.shields.io/badge/🚀_Quick_Start-red?style=for-the-badge)](#-getting-started)
[![Contact](https://img.shields.io/badge/📩_Contact-lightgrey?style=for-the-badge)](#-contact)

---

[![Python Version](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Tkinter](https://img.shields.io/badge/GUI-Tkinter-blueviolet?style=flat-square)](https://docs.python.org/3/library/tkinter.html)
[![Software Engineering](https://img.shields.io/badge/Software-Engineering-005850?style=flat-square)](https://en.wikipedia.org/wiki/Software_engineering)
[![Codiom](https://img.shields.io/badge/Powered_By-Codiom-FF4B4B?style=flat-square)](https://codiom.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-4caf50?style=flat-square)](https://opensource.org/licenses/MIT)

**Optimizing personal and professional productivity through a deterministic task management engine.**

</div>

---

## 📖 Project Overview

The **TaskForge UI** is a robust desktop application designed to streamline daily operations and task tracking. Developed as a utility asset within the **Codiom** initiative, this project implements a clean, intuitive interface powered by **Python** and **Tkinter**.

As a Software Engineering student at Istanbul Aydın University, I architected this application to focus on state persistence and responsive UI design—ensuring that every task is managed with maximum reliability and minimal system overhead.

---

## ✨ Key Features

* **⚡ Real-Time Task Tracking:** Instant creation, updates, and deletion of tasks with immediate UI feedback.
* **🛠️ State Persistence:** Integrated logic to ensure that your task list is preserved across application restarts.
* **📱 Clean UX/UI Design:** A minimalist interface focused on reducing cognitive load and maximizing productivity.
* **🔍 Priority Categorization:** Ability to organize tasks based on urgency and operational impact.
* **💾 Data Serialization:** Efficient backend handling for task storage using JSON or local file systems.

---

## 🛠️ Tech Stack

| Category | Technology | Usage |
| :--- | :--- | :--- |
| **Development** | **Python 3.9+** | Core application logic and event orchestration. |
| **GUI Framework** | **Tkinter** | Designing and managing the desktop workspace and widgets. |
| **Data Engine** | **JSON / File I/O** | Handling task persistence and historical data storage. |
| **Paradigm** | **Event-Driven** | Managing user interactions and asynchronous UI updates. |
| **Packaging** | **PyInstaller** | Compiling the script into a standalone executable. |

---

## 🏗️ Technical Architecture

The system utilizes an **Event-Driven Controller Architecture**, ensuring that user inputs are validated and processed before the application state is updated.



### Core Architectural Principles
1. **Modularity:** Separation of concerns between the GUI rendering and the task management logic.
2. **Deterministic State:** Ensuring the application remains in a consistent state even during rapid user interactions.
3. **Input Validation:** Preventing invalid task entries and ensuring data integrity within the persistence layer.

---

## 📂 Project Structure

```bash
.
├── 📄 main.py               # Application entry point and GUI orchestration
├── 📄 task_engine.py        # Core logic for task lifecycle management
├── 📁 data/                 # Local storage for persisted task lists
├── 📁 assets/               # Application icons and custom styles
├── 📄 requirements.txt      # Dependency manifest
└── 📄 README.md             # System Documentation
```

## 🚀 Getting Started

### 1. Installation

```bash
# Clone the repository
git clone [https://github.com/BerattCelikk/TODO-APP-WITH-TKINTER.git](https://github.com/BerattCelikk/TODO-APP-WITH-TKINTER.git)
cd TODO-APP-WITH-TKINTER

# Initialize virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

```

### 2. Dependency Injection

```bash
pip install -r requirements.txt
```

### 3. Execution
To launch the TaskForge UI:
```bash
python main.py

```


## 🗺️ Roadmap

- [ ] Modern Styling: Implementing CustomTkinter for a sleeker, dark-mode-ready interface.
- [ ] Reminder System: Integrating OS-level notifications for high-priority tasks.
- [ ] Cloud Sync: Developing an API connector to sync tasks across multiple devices.
- [ ] Advanced Filtering: Adding search and tag-based filtering for large task volumes.

---

<div align="center" id="contact">

Architected with precision by Berat Erol Çelik Founder of Codiom

Software Engineering @ Istanbul Aydın University

</div>


















