# 🚀 InnovaHorizon

> **One Platform. Every Language.**

InnovaHorizon is a modern web-based multi-language compiler and online IDE that allows users to write, compile, execute, and manage programs written in multiple programming languages from a single platform.

The goal of this project is to provide a fast, secure, scalable, and user-friendly development environment for students, developers, and programming enthusiasts.

---

## 📖 Table of Contents

- [About](#about)
- [Vision](#vision)
- [Objectives](#objectives)
- [Features](#features)
- [Supported Languages](#supported-languages)
- [Technology Stack](#technology-stack)
- [System Architecture](#system-architecture)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Development Roadmap](#development-roadmap)
- [Future Enhancements](#future-enhancements)
- [Security](#security)
- [Contributing](#contributing)
- [License](#license)
- [Team](#team)

---

# 📌 About

Programming often requires installing different compilers, SDKs, and IDEs for different languages.

**OmniCompile** solves this problem by providing one platform where users can:

- ✍️ Write code
- ⚡ Compile code
- ▶️ Execute programs
- 📄 View output
- 💾 Save projects
- 📂 Upload source files

All from a clean and modern interface.

---

# 🌟 Vision

To build a secure, intelligent, cloud-based compiler platform that supports multiple programming languages while providing an excellent developer experience.

---

# 🎯 Objectives

- Support multiple programming languages
- Provide fast code execution
- Create an intuitive code editor
- Ensure secure sandbox execution
- Build a scalable architecture
- Help students learn programming easily

---

# ✨ Features

## 📝 Code Editor

- Syntax Highlighting
- Auto Indentation
- Line Numbers
- Multiple Themes
- Language Selection
- Auto Save *(Planned)*
- IntelliSense *(Future)*

---

## ⚙️ Compiler Features

- Compile Source Code
- Execute Programs
- Standard Input Support
- Output Console
- Error Console
- Execution Time
- Memory Usage *(Future)*

---

## 👤 User Features

- Create Projects
- Save Code
- Download Files
- Upload Files
- Recent Projects
- Authentication *(Future)*

---

## 🛠 Admin Features *(Future)*

- User Management
- Language Management
- Execution Monitoring
- Analytics Dashboard

---

# 💻 Supported Languages

### Current

- C
- C++
- Java
- Python

### Upcoming

- JavaScript
- TypeScript
- Go
- Rust
- PHP
- C#
- Kotlin
- Swift
- Ruby

---

# 🛠 Technology Stack

## Frontend

- React.js
- Next.js
- Tailwind CSS
- Monaco Editor

## Backend

- Node.js
- Express.js

## Database

- MongoDB

## Compiler Environment

- Docker
- GCC
- G++
- Python
- OpenJDK

## Authentication

- JWT
- bcrypt

## Deployment

- Docker
- Nginx
- GitHub Actions
- Vercel

---

# 🏗 System Architecture

```text
                Client (Browser)
                      │
             React / Next.js Frontend
                      │
                REST API / WebSocket
                      │
             Node.js + Express Backend
                      │
      ┌───────────────┼────────────────┐
      │               │                │
 Database         Compiler API     File Storage
      │               │
   MongoDB      Docker Sandbox
                      │
      GCC | G++ | Java | Python
```

---

# 📁 Project Structure

```text
OmniCompile/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   ├── services/
│   │   └── styles/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── models/
│   ├── compiler/
│   ├── sandbox/
│   ├── config/
│   └── services/
│
├── docker/
├── docs/
├── scripts/
├── tests/
│
├── .env.example
├── README.md
└── package.json
```

---

# ⚡ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/OmniCompile.git
```

Go to the project directory

```bash
cd OmniCompile
```

Install frontend dependencies

```bash
cd frontend
npm install
```

Install backend dependencies

```bash
cd ../backend
npm install
```

Run frontend

```bash
npm run dev
```

Run backend

```bash
npm start
```

---

# 🚀 Usage

1. Open the application.
2. Select a programming language.
3. Write your source code.
4. Click **Run**.
5. View the output.
6. Fix errors if needed.
7. Save your project.

---

# 🗺 Development Roadmap

## Phase 1

- [x] Project Planning
- [ ] UI Design
- [ ] Code Editor
- [ ] Language Selector

---

## Phase 2

- [ ] Backend API
- [ ] Docker Integration
- [ ] Compiler Execution
- [ ] Error Handling

---

## Phase 3

- [ ] User Authentication
- [ ] Project Saving
- [ ] Dashboard

---

## Phase 4

- [ ] AI Code Assistant
- [ ] AI Error Detection
- [ ] Code Formatting
- [ ] Execution History

---

## Phase 5

- [ ] Collaborative Coding
- [ ] Online Judge
- [ ] GitHub Integration
- [ ] Cloud Deployment

---

# 🔒 Security

OmniCompile will execute programs securely using:

- Docker Containers
- Execution Time Limits
- Memory Limits
- CPU Limits
- Network Isolation
- File System Restrictions

---

# 🚀 Future Enhancements

- AI Code Completion
- AI Debugging
- GitHub Integration
- Real-time Collaboration
- Competitive Programming Mode
- Version Control
- Cloud Workspace
- Mobile Support

---

# 🤝 Contributing

Contributions are always welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Team

### Project

**OmniCompile**

### Developed By

- Your Name
- Team Members

---

# 📊 Project Status

**Version:** `v0.1.0`

**Status:** 🚧 Under Development

---

# 💡 Mission

> **Build a modern, secure, fast, and intelligent online compiler that enables developers to write, compile, and execute programs in multiple programming languages from a single platform.**

---

⭐ **If you like this project, don't forget to star the repository!**
