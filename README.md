# Development Tools That I Use

> **As a solo developer primarily focusing on AI/ML based projects, Data Structures & Algorithms (DSA) using Python, I understand the friction of solo development. I feel the same pain many do: the need for a helping hand in complex projects and daily workflows. Here is my curated working environment, structured to optimize local resources, system architecture, and code efficiency. This might help you set up your own.**

---

## Tools I Use

### 1. Aider
* **Overview:** Aider is an AI pair programming tool that operates directly in your terminal, allowing you to edit code in your local repositories seamlessly alongside an LLM.
* **Workflow:** Operates purely via the Command Line Interface (CLI) and supports the Model Context Protocol (MCP) for tool integration.
* **Flexibility:** Works with both local inference (via Ollama) and cloud APIs.
* **Advantage:** It provides almost all the capabilities of Cursor at minimal to zero cost, while keeping you grounded in the terminal.
* **My Use Case:** I use it primarily for heavy code completions, architectural corrections, and general coding assistance, mostly hooked up to the OpenRouter API.

### 2. Continue.dev
* **Overview:** Continue.dev is an open-source AI code assistant built directly into your IDE.
* **Workflow:** Operates as a VS Code extension, featuring a rich GUI and full support for MCP.
* **Flexibility:** Seamlessly switches between local inference (Ollama) and cloud APIs.
* **Advantage:** Provides an excellent, free alternative to Cursor's interface right inside your existing editor.
* **My Use Case:** I rely on it for `tabAutoComplete` and contextual linting, powered mostly by Ollama running `qwen-coder-3:1.5b` locally.

### 3. Open WebUI
* **Overview:** Open WebUI is an extensible, feature-rich, and user-friendly self-hosted interface designed to operate entirely offline. 
* **Features:** Full support for MCP and multimodal AI models.
* **Flexibility:** Works brilliantly with both local inference (Ollama) and remote cloud APIs.
* **Advantage:** Provides robust chat and context management with local embedding. It serves as a highly capable, private alternative to the default ChatGPT or Gemini web interfaces.

### 4. Git
* **Overview:** The industry-standard distributed version control system.
* **Advantage:** Absolutely essential for tracking project history, managing code revisions, and branching experimental AI features without breaking the core codebase.

### 5. uv
* **Overview:** `uv` is an incredibly fast Python package and project manager written in Rust.
* **Advantage:** It serves as a drop-in replacement for `pip`, dramatically speeding up dependency resolution and virtual environment creation. It removes the bottleneck of managing complex Python environments.

### 6. Anaconda / Miniconda
* **Overview:** Robust environment managers tailored for data science.
* **Advantage:** Perfect for isolating complex dependencies. They are particularly beneficial for AI/ML workflows where heavy mathematical libraries, deep learning frameworks, and C++ bindings (like CUDA toolkits) need to be strictly managed without conflicting with system-level Python.

---

## Services I Use

### 1. Ollama
* **Purpose:** Core engine for local inference.
* **My Use Case:** Handles lightweight, rapid-response tasks like inline code autocomplete, ensuring zero latency and complete privacy for local development.

### 2. OpenRouter
* **Purpose:** Unified gateway for cloud API services.
* **Advantage:** Features a generous free tier and supports state-of-the-art multimodal models. 
* **Workflow:** Requires only one API key to access hundreds of models on the platform, following the standard OpenAI API endpoint architecture for easy integration.

### 3. Google AI Studio
* **Purpose:** Prototyping and evaluation.
* **My Use Case:** Perfect for testing and evaluating prompts, as well as leveraging free API credits for the latest Gemini models.

### 4. Anthropic MCP and MCPO Proxy
* **Overview:** The Model Context Protocol (MCP) standardizes how AI models interact with external tools, file systems, and databases.
* **The Proxy:** Services like Open WebUI and various IDE extensions often expect an OpenAI-style API endpoint. The `mcpo` proxy solves this compatibility issue by translating standard OpenAI API requests into MCP/Anthropic formats, bridging the gap between different model architectures and standardized tool workflows.

### 5. Docker
* **Overview:** The unsung hero of open-source projects and system deployment.
* **Advantage:** Turns complex, heavy infrastructure setups into a simple "download and run" process. Essential for spinning up databases, containerized applications, and isolated development environments.

---

## IDE I Use

### Visual Studio Code
Nothing beats its versatility, massive extension ecosystem, and lightweight nature.

* **Primary Extension:** Continue.dev
* **Linter:** A linter (like Ruff or Flake8) statically analyzes code to flag syntax errors, bugs, stylistic deviations, and suspicious constructs. It ensures code remains clean, readable, and strictly adheres to standard formatting rules before runtime.

---

## Knowledge Management

### Obsidian
* **Overview:** A literal "second brain" that lives on your local machine, operating entirely on plain text Markdown files. It is perfect for structuring academic documentation, tracking learning progress, and storing custom typography layouts.
* **MAKE.md:** This extension transforms the default Obsidian experience into a more fluid workspace (similar to Notion), adding spaces, inline editing, and enhanced folder organization without sacrificing the benefits of local markdown.
* **Excalidraw:** An infinite canvas extension that is absolutely invaluable. I use it directly within my notes for sketching out algorithmic visualizations, mapping database schemas, and designing architectural flowcharts.

## Start your Setup now
### Aider: [text](https://aider.chat/#getting-started)
### Open WebUI: [text](https://github.com/open-webui/open-webui#how-to-install-)
### uv: [text](https://docs.astral.sh/uv/getting-started/installation/)
### Obsidian: [text](https://obsidian.md/download)
### Openrouter: [text](https://openrouter.ai/)
### Ollama: [text](https://ollama.com/)
