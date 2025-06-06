# 🤖 CodeBuddy – AI-Powered Code Reviewer

**CodeBuddy** is a full-stack AI-driven web application that helps developers review code with the help of Google Gemini AI. It analyzes code snippets, identifies problems, and suggests improvements in real-time.

Built using the **MERN stack**, **Gemini 2.0 Flash API**, and enhanced with **PrismJS** for elegant syntax highlighting.

---

## 🚀 Features

- 🔍 Instant AI-Powered Code Review
- 💡 Suggests Better, Cleaner, and More Efficient Code
- 🎯 Feedback Based on Real Development Practices
- 🌈 Beautiful Code Rendering with PrismJS
- 🧠 Gemini 2.0 Flash Model Integration
- 🔐 Secure API Key via `.env` setup
- 💬 Developer-Friendly UI with React.js

---

## 🛠️ Tech Stack

| Frontend | Backend | AI/Utilities |
|----------|---------|--------------|
| React.js | Node.js + Express | Google Gemini AI (2.0 Flash) |
| PrismJS | MongoDB (optional) | dotenv |
| Tailwind CSS / CSS |             | CORS, Axios |

---

## 📦 Setup Instructions

### 🔑 Environment Variables

#### Backend: `Backend/.env`
```env
PORT=5000
GOOGLE_GEMINI_KEY=your_gemini_api_key
```

### 📁 Install Dependencies
#### Backend:
```bash
cd Backend
npm install
```
#### Frontend:
```bash
cd ../Frontend
npm install
```

### ▶️ Run the App
#### Start Backend:
```bash
cd Backend
npm run dev
```
#### Start Frontend:
```bash
cd ../Frontend
npm run dev
```
### 🧪 Example Usage
Paste a code snippet in the input area and click "Review". The AI will return:

- Identified problems

- Suggestions

- Possible improvements

- Cleaned-up alternative code (if applicable)

