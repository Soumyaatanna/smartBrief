
# SmartBrief — AI‑Powered Article Summarizer 🚀

**SmartBrief** is a full‑stack web application that converts long articles into concise, easy‑to‑read summaries using RapidAPI’s NLP engine. Built with modern tools, it provides a smooth UI, history tracking, and clipboard support—perfect for busy readers.

---

## ✅ Features

- Paste any article URL to get a **brief summary**
- View and copy your past summaries (saved locally)
- Clean UI built with **React**, **Tailwind**, and **Vite**
- State management via **Redux Toolkit (RTK Query)**
- Summarization powered by **RapidAPI’s NLP endpoint**
- **Responsive design** for mobile and desktop

---

## 📦 Tech Stack

| Layer            | Technologies                                  |
|------------------|-----------------------------------------------|
| Frontend         | React, Vite, Tailwind CSS                     |
| State Management | Redux Toolkit (RTK Query)                     |
| Summarization    | RapidAPI (Article Extractor & Summarizer API) |
| Storage          | `localStorage` for summary history            |
| Deployment       | Vercel / Netlify (Frontend)                   |

---

## ▶️ Live Demo

👉

---

## 🛠️ Installation & Running Locally

### 1. Clone the repo  
```bash
git clone https://github.com/Soumyaatanna/smartBrief.git
cd smartBrief
2. Install dependencies
bash
Copy
Edit
npm install
3. Create your .env
Add a file named .env in the root with your RapidAPI key:

env
Copy
Edit
VITE_RAPID_API_KEY=YOUR_RAPIDAPI_KEY_HERE
👉 Get your key from RapidAPI
```
4. Run the project
bash
Copy
Edit
npm run dev
App will be available at: http://localhost:5173

🎨 Screenshots
![image](https://github.com/user-attachments/assets/94e2e057-0875-4604-9501-7ca1e6d29f58)

💼 Usage Instructions
Paste a valid article URL (e.g., from BBC, NY Times)

Press Enter or click submit

Watch the loader, then view the summary

Click the card to copy URL or view past summaries

⚙️ Configuration
To change summary length, adjust the length parameter in src/services/article.js

Toggle dark/light mode by customizing your Tailwind config or CSS variables

💡 Future Enhancements
🔒 Add authentication to sync across devices

⭐️ Favorite or tag summaries

📚 Import PDF support

🌗 Theme switch (dark / light)

📋 Project Structure
lua
Copy
Edit
src/
├── assets/
├── components/      (Demo.tsx, etc.)
├── services/        (RTK Query API slice)
├── styles/          (global styles + Tailwind overrides)
├── App.jsx
├── main.jsx
.vite.config.js
.tailwind.config.{js,cjs,mjs}
.env
package.json
🤝 Contributing
Contributions are welcome! Feel free to:

Report bugs or request features via GitHub Issues

Fork, create a branch, and send a pull request

📝 License
Distributed under the MIT License. See LICENSE for details.

yaml
Copy
Edit

---
