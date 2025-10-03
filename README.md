# 🚀 InterviewAI

**InterviewAI** is a modern **AI-powered interview preparation platform** built with **React + Vite**. It helps students and professionals practice interviews, receive instant AI feedback, and track progress. Powered by **Google Gemini AI**, it delivers real-time mock interview experiences with voice and video analysis.

---

## 📌 Features

* 🎤 **Interview Practice** – Mock sessions in Technical, HR, Aptitude, or Group Discussion formats
* 🤖 **AI Feedback** – Real-time, detailed feedback and motivational tips using Gemini AI
* 🎥 **Voice & Video Analysis** – Evaluate communication skills like confidence, clarity, and engagement
* 📊 **Performance Dashboard** – Visual reports with scores, strengths, and weaknesses
* 📂 **Session Management** – Review and manage past interview sessions
* ⚙️ **Customization** – Choose domain, job role, and experience level for tailored questions

---

## 🏗️ System Architecture

* **Frontend:** React (JSX), Vite, Tailwind CSS
* **Routing:** React Router
* **State Management:** React Context API
* **Icons:** Lucide React
* **Charts:** Recharts
* **Speech Recognition:** Web Speech API
* **AI Integration:** Google Gemini AI API (with Mock AI fallback)

---

## 📂 Modules

* **Authentication & User Context** – Manage user sessions and preferences
* **Interview Module** – Question selection, answering (text/voice), AI-driven feedback
* **Feedback & Analysis Module** – Suggestions, motivational insights, and voice analysis
* **Dashboard Module** – Track performance, view history, and delete sessions
* **Admin/Customization Module** – Manage job roles, domains, and AI feedback prompts

---

## ⚡ Getting Started

### ✅ Prerequisites

* Node.js v18+
* npm

### 🔧 Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/dineshuniq-creator/interviewAI.git
   cd interviewAI
   ```

2. **Install dependencies:**

   ```sh
   npm install
   ```

3. **Setup environment variables (.env):**

   ```env
   VITE_API_BASE_URL=http://localhost:5000/api
   VITE_GEMINI_API_KEY=your-google-gemini-api-key
   ```

4. **Run Development Frontend:**

   ```sh
   npm run dev
   ```

5. **Run Development Backend/Server:**

   ```sh
   npm run server
   ```

6. **Access Application:**

   ```sh
   http://localhost:5173/
   ```

---

## 📁 File Structure

```
src/
  components/        # React components (Dashboard, InterviewSession, ResultsPage, etc.)
  contexts/          # Context providers (UserContext)
  utils/             # Helper functions, AI services
  index.css          # Tailwind CSS styles
  App.jsx            # Main app component
  main.jsx           # Entry point
```

---

## 🎯 Customization

* **AI Model:** Change in `src/utils/geminiAI.js` (`gemini-pro` recommended)
* **Domains & Roles:** Editable in `src/types/interview.js`
* **Feedback Prompts:** Modify templates in `geminiAI.js`

---

## 🛠️ Challenges & Solutions

* **AI response delays** → Implemented Mock AI fallback for offline usage
* **Speech recognition inconsistencies** → Optimized for Chrome/Edge with microphone permission handling

---

## ✅ Expected Outcomes

* Simulate **real interview experiences**
* Get **instant AI-driven feedback**
* Track and improve systematically with **progress dashboards**
* Offer a **cost-effective, scalable interview training solution**

---

## 💻 Tech Stack

* **Frontend:** React, Vite, Tailwind CSS
* **AI:** Google Gemini AI
* **Charts & Visualization:** Recharts
* **Voice Analysis:** Web Speech API
* **Icons:** Lucide React
* **Version Control:** GitHub

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use and modify.

---

## 🙌 References

* [Google Gemini AI](https://ai.google.dev/)
* [Recharts](https://recharts.org/)
* [Tailwind CSS](https://tailwindcss.com/)
* [Lucide Icons](https://lucide.dev/)

