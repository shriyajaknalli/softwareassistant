<!-- Banner -->
![DevFlow Banner](https://files.catbox.moe/8y56pm.png)

# 🚀 **DevFlow: Software Development Assistant** [UNDER DEVELOPMENT]

---

## 🔧 About DevFlow

**DevFlow** is an all-in-one software development assistant that streamlines the **entire SDLC** — from UML design and unit test generation to documentation management and validation — all inside a secure, Linux-based virtual workspace.

---


https://github.com/user-attachments/assets/9e8f4586-fbe9-4c6b-8e81-3c8e76721a0e




## ✨ Key Features

### 🧩 UML Generation
- Use commands like `@SEQUENCE`, `@ACTIVITY`, `@CLASS` to generate UML diagrams from SRS or chat input.
- Visual and downloadable diagrams.

![UML Generation](https://files.catbox.moe/7wmdas.jpg)
![Generated Sequence Diagram](https://files.catbox.moe/b98ki3.svg)

---

### 🧪 Unit Test Generation
- `@gitclone` – Mount a Git repo inside a secure VM.
- `@TESTGENERATE` – Generate test for current file.
- `@TESTALL` – Generate test files for entire codebase.

**Includes:**
- 📁 Virtual File System
- 🖥️ Linux VM
- 🖱️ IDE + Terminal combo like AWS EC2

![Unit Test](https://files.catbox.moe/w23iog.png)

---

### 📄 Documentation RAG
- Upload SRS/docs → Ask questions directly about your codebase using RAG.
- Navigate in-app PDF reader and get contextual insights.

![Documentation](https://files.catbox.moe/4kexn4.png)

---

SRS Document Generation
DevFlow introduces a powerful document generation assistant that enables seamless creation of Software Requirements Specification (SRS) documents using natural language prompts and context-aware understanding.

🚀 Current Capabilities
Use the @DOCGEN command in the chatbot to generate a complete SRS document with just a single line of input.
For example:
![DOCGEN](https://files.catbox.moe/eyxp6m.png)

---

### ✅ Verify & Validate
- Auto-run test cases, score software quality, and suggest improvements.

![Verify & Validate](https://files.catbox.moe/xxxd04.png)

---

## 🛠 Tech Stack

- **Frontend**: React + Tailwind CSS  
- **Backend**: FastAPI  
- **Environment**: Alpine Linux VM  
- **Custom Commands**: `@SEQUENCE`, `@TESTGENERATE`, `@gitclone`, etc.

---

## Installation
To run **DevFlow** locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/umarocks/DevFlow.git
   ```

2. Navigate into the project directory:
   ```bash
   cd DevFlow
   ```

3. Docker Compose:
   ```bash
   docker compose up --build
   ```
## Contact
For any inquiries, you can reach out via email:
Shriya.jaknalli@gmail.com
