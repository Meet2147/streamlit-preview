<p align="center">
  <img src="128_1.png" alt="Streamlit Preview" height="60">
</p>

<p align="center">
  <b>Preview Streamlit apps directly inside VS Code.</b><br/>
  No more context switching between editor and browser.
</p>

<p align="center">
  <img src="https://img.shields.io/visual-studio-marketplace/v/mjethwa-streamlit.streamlit-preview?label=Version&style=for-the-badge">
  <img src="https://img.shields.io/visual-studio-marketplace/i/mjethwa-streamlit.streamlit-preview?label=Installs&style=for-the-badge">
  <img src="https://img.shields.io/visual-studio-marketplace/r/mjethwa-streamlit.streamlit-preview?label=Rating&style=for-the-badge">
</p>

---

# ✨ Streamlit Preview (VS Code)

**Streamlit Preview** lets you open and preview your Streamlit application **inside a VS Code tab**, similar to an embedded browser.

Stop switching between your editor and browser — stay focused in one window.

---

# 🚀 Features

### 🔁 One-click Preview
Run your current `app.py` (or any Streamlit script) and open it instantly in VS Code.

### 🔄 Auto Hot-Reload
Write → Save → Instantly see updates via Streamlit’s built-in reload.

### 🧭 Port 8501 (Default)
Automatically waits for the Streamlit server to start — fewer errors, smoother workflow.

### 🪟 Clean UI Layout
Side panel for app URL & controls, main panel displays the Streamlit UI.

---

# 🧪 Streamlit Preview **Pro** (Gumroad)

A separate **Pro edition** will be available via **Gumroad** as a downloadable package (no license activation flow inside VS Code).

Planned premium features:

### ⚙️ Choose Python Environment
Run Streamlit using any virtual environment or Conda environment.

### 🔌 Custom Ports & Auto-Retry
Run multiple Streamlit previews in parallel (8501, 8502, 8503…).

### 📌 Workspace Profiles
Automatically remember:
- Script path
- Environment
- Port
- Auto-start settings

### 📜 Built-In Log Panel
View Streamlit stdout & stderr logs in a dedicated VS Code panel.

### 🌍 Share via Tunnel
One-click sharing using:
- `ngrok`
- `cloudflared`

> Pro will be distributed directly via Gumroad (separate download).

---

# 🧰 Requirements

- **Python 3.x** in PATH  
  - Windows → `python`  
  - macOS/Linux → `python3`  
- Install Streamlit:

```bash
pip install streamlit
````

-----

# 📦 Installation

## From Marketplace

1.  Open VS Code
2.  Go to Extensions
3.  Search for: Streamlit Preview
4.  Click Install

## Or install via VSIX

```bash
code --install-extension streamlit-preview.vsix
```

-----

# 🛠 Usage

### ▶️ 1. Open Your Streamlit Script

Open `app.py` or any file that runs Streamlit.

### ▶️ 2. Start Preview

**Command Palette** →

`Streamlit: Preview Current File`

### ▶️ 3. Edit & Save

Every save triggers a reload. **No restart required.**

### ⏹ 4. Stop Preview

`Streamlit: Stop Preview`

-----

# ⚙️ Settings

| Setting | Description |
| :--- | :--- |
| `streamlitPreview.port` | Default Streamlit port (8501) |
| `streamlitPreview.autoStart` | Auto-start preview when opening a Streamlit file |
| `streamlitPreview.openInSidePanel` | Open preview inside sidebar panel |

-----

# 🖼 Screenshots

### 📌 Streamlit Preview inside VS Code

<p align="center">
  <img src="S4.png" width="80%">
</p>

-----
