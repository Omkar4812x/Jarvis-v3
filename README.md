# ⚡ Jarvis v3 - Modular System Automation Assistant

> **Modular Python virtual assistant framework featuring automated window management, keyboard/mouse emulation, weather updates, file operations, and Google search integration.**

---

## ✨ Features

- 🖥️ **Windows Desktop Window Controller** (`Jarvis_window_CTRL.py`)
  - Manage active desktop windows, minimize/maximize applications, and switch focus.
- ⌨️ **Keyboard & Mouse Automation** (`keyboard_mouse_CTRL.py`)
  - Automated mouse click positioning, scroll wheel control, and keyboard typing via `pyautogui`.
- 📁 **File System Manager** (`Jarvis_file_opner.py`)
  - Open, search, and manage local files, scripts, and software applications.
- 🌐 **Web Search & Weather Services** (`Jarvis_google_search.py`, `jarvis_get_whether.py`)
  - Real-time Google Search queries and live weather updates.
- 🧠 **Central Agent Orchestrator** (`agent.py`, `Jarvis_prompts.py`)
  - Intelligent prompt routing connecting user intents to specific automation modules.

---

## 🛠️ Tech Stack

- **Language**: Python 3.10+
- **Automation & Control**: `pyautogui`, `psutil`, `pygetwindow`, `pynput`
- **Networking & API**: Requests, BeautifulSoup4

---

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Omkar4812x/Jarvis-v3.git
   cd Jarvis-v3
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Environment Variables**:
   Create a `.env` file in the root directory:
   ```env
   OPENAI_API_KEY=your_openai_api_key_here
   WEATHER_API_KEY=your_weather_api_key_here
   ```

4. **Run Jarvis v3**:
   ```bash
   python agent.py
   ```

---

## 📄 License

Distributed under the MIT License.
