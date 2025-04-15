# ⚡ AI Code Editor with Groq API — HACKHAZARDS

An intelligent, collaborative AI-powered code editor featuring real-time code suggestions, voice-command debugging, syntax highlighting, screen sharing, and live cursors — built for the future of pair programming.

<p align="center">
  <img src="https://img.shields.io/badge/Powered_by-Groq_API-blueviolet?style=flat-square"/>
  <img src="https://img.shields.io/badge/Voice_Command-Enabled-success?style=flat-square"/>
  <img src="https://img.shields.io/badge/Live_Sharing-Built_in-orange?style=flat-square"/>
</p>

---

## 🚀 Features

### 💡 AI Auto Code Prediction
- Predicts next line(s) of code using **Groq API**.
- Provides intelligent completions and short, helpful explanations.
- Integrated seamlessly with the editor.

### 🎨 Syntax Highlighting & Code Styling
- Displays line numbers, keyword-based coloring, and indentation.
- Highlights syntax errors in red for quick debugging.
- Helps with cleaner, structured, and readable code.

### 🎙️ AI Voice Assistant (Voice + Text)
- Speak or type commands to:
  - Generate new code
  - Debug existing logic
- Built using Web Speech API for real-time voice recognition.

### 🧠 Hover Tooltips for Code Hints
- Hover over programming keywords to see:
  - Descriptions
  - Syntax
  - Quick examples

### 🖥️ Screen Sharing + Live Cursor (Real-Time Collaboration)
- **Share your screen** and collaborate with others in real time.
- **Live cursor tracking** shows your teammate’s activity as they code.
- Enhances collaboration during coding sessions, interviews, or mentoring.

> ✅ *Code for screen sharing and live cursor is implemented. Deployment in progress.*

---

## 📁 Folder Structure


---

## 🛠️ Tech Stack

- **Frontend**: React, CodeMirror, Web Speech API, Socket.IO
- **Backend**: Node.js, Express
- **AI Engine**: Groq API (OpenAI-compatible)
- **Desktop App**: Electron
- **Live Collab**: WebRTC, Socket.IO
- **Syntax & Parsing**: ESLint, Prettier

---

## ✅ Prerequisites

- Node.js (v18 or higher)
- npm (or yarn)
- Groq API Key ([Get it here](https://console.groq.com))
- (Optional) Electron installed globally for desktop build

---

## 🔧 Installation & Setup Guide

### 1. Clone the Repository

```bash
git clone https://github.com/samriddhitiwary/AIEditorX.git
cd AIEditorX
```

2. Backend Setup (Port: 5000)
```bash
cd backend
npm install
npm start
```
3. Frontend Setup (Port: 3000)
```bash
cd frontend
npm install
npm start
```
