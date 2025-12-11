# Quiz Generator (MindSpark AI)

**Quiz Generator** is a modern, AI-powered web application designed to help users study smarter. By leveraging the **Google Gemini API**, it automatically generates multiple-choice quizzes and flashcards on any topic you choose. It also supports manual study material uploads via JSON.

## 🌟 Key Features

* **🤖 AI-Powered Generation:** Instantly create quizzes or flashcards on any topic (e.g., "Solar System", "ReactJS", "History of Indonesia") using Google Gemini.
* **📝 Two Study Modes:**
    * **Quiz Mode:** Multiple-choice questions with score tracking and a customizable timer.
    * **Flashcard Mode:** Flip cards with "Shuffle" functionality for memorization.
* **💡 AI Explanations:** Stuck on a question? Request an instant AI explanation for why an answer is correct.
* **📂 JSON Support:** Upload your own question banks using a simple JSON format.
* **⏱️ Timer System:** Challenge yourself with countdown timers (Hours/Minutes/Seconds).
* **📱 Responsive Design:** Built with Tailwind CSS, ensuring a great experience on both desktop and mobile.
* **🔒 Client-Side Storage:** Your API Key is stored locally in your browser (`localStorage`) and is never sent to a backend server.

## 🛠️ Tech Stack

* **Frontend:** HTML5, Vanilla JavaScript
* **Styling:** [Tailwind CSS](https://tailwindcss.com/) (via CDN)
* **Icons:** [FontAwesome](https://fontawesome.com/)
* **Markdown Parsing:** [Marked.js](https://marked.js.org/)
* **AI Model:** Google Gemini API (`gemini-2.5-flash`)

## 🚀 Getting Started

Since this project uses CDN links, there is no need to install Node.js or run build commands.

### Prerequisites
1.  A modern web browser (Chrome, Edge, Firefox, Safari).
2.  A **Google Gemini API Key** (Free).

### Installation
1.  **Download** the project files (or just the `index.html` file).
2.  **Open** the `index.html` file directly in your web browser.

## ⚙️ Configuration (API Key)

To use the AI features (Generation and Explanations), you need an API Key:

1.  Go to [Google AI Studio](https://aistudio.google.com/app/apikey).
2.  Click **"Create API Key"**.
3.  Open the **Quiz Generator** in your browser.
4.  Click the **Settings (Gear Icon)** in the top right corner.
5.  Paste your key and click **Simpan** (Save).

## 📄 Custom Question Format (JSON)

You can upload your own questions manually using a `.json` file.

### 1. Quiz Format
```json
[
  {
    "question": "What is the capital of France?",
    "options": ["London", "Berlin", "Paris", "Madrid"],
    "answer": "Paris"
  },
  {
    "question": "What is 2 + 2?",
    "options": ["3", "4", "5", "6"],
    "answer": "4"
  }
]
