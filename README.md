# 🚀 Multi-Agent Deep Researcher (MADR)
### **MCP-Enabled • Autonomous Research • Windows & Linux Compatible**



---

## 🧠 Overview

**Multi-Agent Deep Researcher (MADR)** is an advanced AI framework designed to perform **deep research, long-context reasoning, task decomposition, autonomous tool usage, document analysis, and multi-step workflows** using multiple intelligent agents.

It is built on:

- **Multi-Agent Architecture**
- **MCP (Model Context Protocol)**
- **FastAPI Backend**
- **Cross-platform Windows & Linux Support**
- **LLM-Driven Autonomous Reasoning**

MADR is ideal for **researchers, analysts, engineers, AI developers, and enterprise intelligence systems**.

---

## ⭐ Key Features

### 🔎 **Deep Research Mode**
Performs multi-step research with validation, summarization, citations, and cross-checking.

### 🤖 **Multi-Agent Collaboration**
Includes: Planner Agent, Research Agent, Web Search Agent, Summarizer Agent, Validator, Tool Agent.

### 🔌 **MCP Integration**
Provides tool calling, resource access, and multi-model interoperability.

### 🧩 **Modular Agent Design**
Customize or add new agents easily in `agents.py`.

### ⚡ **FastAPI Backend**
High-performance, async API for instant research queries.

### 💻 **Windows & Linux Compatible**
Fully cross-platform with no OS-specific dependencies.

---

# 🏗 Architecture


                            User Query
                                ↓
                        API Server (FastAPI)
                                ↓
                      Task Router (agents.py)
                                ↓
           ┌─────────────── Multi-Agents ────────────────┐
           │                                             │
           │  Planner Agent → Research Agent → Validator │
           │     ↓                                       │
           │  Web Search Agent → Tool Agent → Summarizer │
           │                                             │
           └─────────────────────────────────────────────┘
                               ↓
             Final Research Report (JSON / Text / Markdown)

---

# 🛠 Installation

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/your-username/Multi-Agent-Deep-Researcher-MCP.git
cd Multi-Agent-Deep-Researcher-MCP
```

### **2️⃣ Install dependencies**
```bash
pip install uv
uv sync
```

### **3️⃣ Run the server**
```bash
python server.py
```

### **📡 API Usage**
##### **POST /ask** 
```bash
{
  "prompt": "Provide a deep research analysis of the future of quantum computing."
}
```
##### **Response Example**
```bash
{
  "result": "Quantum computing is expected to..."
}
```

### **🧪 Example Use Cases**

- **Literature review generation**

- **Academic research**

- **Competitive analysis**

- **Policy analysis**

- **Market intelligence**

- **Technical documentation**

- **Multi-source comparison reports**

### **🔧 Extending Agents**

To add a new agent:

- **Open agents.py**

- **Add a new class for your custom agent**

- **Register it in the routing logic**

- **Test using the /ask endpoint**

### **🗺 Roadmap**

 - **Integrated memory system**

 - **Multi-model support (OpenAI, Anthropic, Llama, Groq)**

 - **Vector database (Qdrant / Chroma)**

 - **Browser automation agent**

 - **Research visualization dashboard**
