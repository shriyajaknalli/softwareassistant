<!-- Banner -->
![DevFlow Banner](https://files.catbox.moe/8y56pm.png)

# 🚀 **DevFlow: Software Development Assistant** [UNDER DEVELOPMENT]

🔒 **Codebase is Private**  
> *If you wish to review the codebase, please schedule a virtual meeting.*  

**Project Timeline**: Ongoing for ~1.5 months  
[Connect with me on LinkedIn](https://www.linkedin.com/in/shriyaj)

---

## 🔧 About DevFlow

**DevFlow** is an all-in-one software development assistant that streamlines the **entire SDLC** — from UML design and unit test generation to documentation management and validation — all inside a secure, Linux-based virtual workspace.

---

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

## 📦 Local Installation (Preview Only)

> For preview purpose only — full codebase not available.

```bash
git clone https://github.com/umarocks/DevFlow.git
cd DevFlow
docker compose up --build
