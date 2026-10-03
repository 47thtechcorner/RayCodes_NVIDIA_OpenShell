<div align="center">
  <a href="https://youtu.be/_NowPIXZ6Yo">
    <img src="https://img.youtube.com/vi/_NowPIXZ6Yo/0.jpg" alt="NVIDIA OpenShell: Stop Agents Stealing Your Local System Secrets!">
  </a>
  <h3>📺 <a href="https://youtu.be/_NowPIXZ6Yo">Watch the full tutorial on YouTube</a></h3>
</div>

# NVIDIA OpenShell: Stop Agents Stealing Your Local System Secrets!

A zero-trust local AI agent security testing lab powered by NVIDIA OpenShell and Ollama to safely analyze code, prevent secret leaks, and isolate agent execution.

---

## ⚡ 3-Step Execution Workflow

| Step 1: Target Input 📥 | Step 2: OpenShell Security Engine 🛡️ | Step 3: Verified Report 📊 |
| :--- | :--- | :--- |
| Run `python main.py` (automatically initializes target `inputs/` folder if needed). | Performs static pattern scanning & sandbox attack vector simulations. | Generates structured security reports in the `outputs/` folder. |

---

## 🛠️ Tool Installation Commands

Install NVIDIA OpenShell, local Ollama engine, and python dependencies using these single-line PowerShell commands:

### 1. Install NVIDIA OpenShell & Dependencies (Single Command)
```powershell
pip install -r requirements.txt; python main.py
```

### 2. Install Local Ollama AI Engine (Single Command)
```powershell
winget install Ollama.Ollama
```

### 3. Setup WSL2 Container Subsystem for Windows (Single Command)
```powershell
wsl --install -d Ubuntu; wsl --set-default-version 2
```

> 💡 **WSL2 Setup:** Windows requires WSL2 container configuration. Run `wsl --install -d Ubuntu` in PowerShell (Admin) to initialize kernel isolation for NVIDIA OpenShell.

---

## 🌟 Key Features

* 🔒 **Kernel Isolation:** Contains local AI agent file and process access inside strict container boundaries.
* 🛡️ **Default-Deny Networking:** Blocks unapproved socket connections and external credential leaks.
* ⚡ **100% Offline Autonomy:** Pairs with local Ollama models for zero cloud API costs and total privacy.
* 📊 **Automated Report Generation:** Automatically audits scannable files and outputs executive Markdown & HTML security reports.

---

## 🎯 5 Practical Use Cases

1. **Untrusted Code Inspection:** Safely test third-party open-source AI scripts before executing them on host machines.
2. **Secret Leakage Prevention:** Verify local AI agents cannot access environment variables or private host API keys.
3. **Network Exfiltration Audit:** Ensure code agents do not make unapproved outbound web requests.
4. **Local Model Evaluation:** Benchmark how local Ollama models perform when restricted by security policies.
5. **CI/CD Security Gate:** Run automated security checks on agent code inside containerized build pipelines.

---

## 📁 Repository Structure

```text
NVIDIA OpenShell/
├── main.py
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📄 License & Attribution

Built with NVIDIA OpenShell policy engine principles and Ollama local model inference.

---

## 🏷️ Keywords & SEO
`NVIDIA OpenShell` `Ollama` `AI Agent Security` `Kernel Sandbox` `Zero Trust AI` `LLM Safety` `WSL2 Container` `Code Execution Sandbox` `Data Leak Protection` `Local LLM Isolation`
