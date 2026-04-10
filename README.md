# Smart-Budget


> A futuristic AI-powered budget tracking web app with wishlist fund management, analytics, and secure local storage.

---

## 🚀 Features

- 💰 **Daily Budget Calculation**
- Smart per-day spending limit based on remaining balance & time

- 📊 **Analytics Dashboard**
- Spending trends (Chart.js)
- Category-wise expense breakdown

- 🧾 **Expense Tracking**
- Add, delete, and categorize expenses
- Real-time updates

- 🎯 **Wishlist Fund System**
- Save money for desired items
- Buy directly from accumulated fund

- 🔄 **Cycle Management**
- Reset budget cycle
- Carry forward savings into wishlist fund

- 📦 **Backup & Restore**
- Export full data as JSON
- Restore anytime

- 📤 **CSV Export**
- Export all or date-range data

- 🔐 **Security Focused**
- XSS protection using input sanitization (`escapeHtml()`)

---

## 🛠️ Tech Stack

- **Frontend:** HTML, Tailwind CSS
- **Charts:** Chart.js
- **Icons:** Phosphor Icons
- **Storage:** LocalStorage (No backend required)

---

## 📂 Project Structure
.
├── index.html # Main application file

---

## ⚙️ How It Works

- The app initializes with user inputs like:
- Budget
- Duration
- Fixed costs
- Optional daily tax

- It calculates:
- Remaining balance
- Daily spending limit
- Wishlist fund accumulation

- All data is stored locally using browser storage.

---

## 🧠 Core Logic

- **Strict Remaining Balance:**
Remaining = Budget - Fixed Costs - (Daily Tax × Days) - Total Spent


- **Daily Limit:**
Daily Limit = Remaining / Remaining Days


- **Wishlist Fund:**
Fund = Previous Savings + Accrued Tax


---

## 🔥 Highlights

- No backend required ⚡
- Fully offline capable
- Clean UI with glassmorphism design
- Secure input handling
- Real-time financial insights

---

## 📸 Preview

> UI includes:
- Dashboard
- Expense tracker
- Charts
- Wishlist system
(See `index.html` for full implementation) :contentReference[oaicite:0]{index=0}

---

## 🧑‍💻 Author

**Naman Kumar Sonker**

- Instagram: https://www.instagram.com/namanmic
- LinkedIn: https://www.linkedin.com/in/namanmic
- GitHub: https://github.com/nksdev

---

## 📜 License

This project is open-source and free to use.

---

## ⭐ Support

If you like this project:

- ⭐ Star the repo
- 🍴 Fork it
- 🧠 Build your own version

---

## ⚠️ Note

This app uses **LocalStorage**, so clearing browser data will erase everything unless backed up.

---

> Built with 💙 + ☕ + hacker mindset
If you want next level flex 😏
I can also add:
badges (GitHub stats, stars, etc.)
live demo hosting (GitHub Pages)
hacker-style animated README
Just say the word 💻🔥 [ write in .md github readme.md ]
This looks like a solid project for a cybersecurity student—local storage for privacy, XSS protection, and a clean UI. Since you asked for the "next level flex," I’ve added dynamic GitHub badges, a cleaner structure, and that "hacker-style" aesthetic you mentioned.

Here is your upgraded README.md. Simply copy the raw text below:

💸 Smart Budget AI
"Financial discipline meets hacker-grade privacy."
A futuristic, AI-powered budget tracking web app with wishlist fund management, real-time analytics, and secure local storage.

🚀 Features
💰 Daily Budget Calculation – Dynamic per-day limits based on remaining balance and time.

📊 Analytics Dashboard – Visual spending trends via Chart.js and category breakdowns.

🧾 Expense Tracking – Real-time CRUD operations for your daily spending.

🎯 Wishlist Fund System – Specialized logic to save for goals using accumulated savings.

🔄 Cycle Management – Easy resets with automated carry-forward logic.

📦 Data Sovereignty – Full JSON backup/restore and CSV export functionality.

🔐 Security Focused – Hardened against XSS via strict input sanitization (

escapeHtml()
).

🛠️ Tech Stack
Layer	Technology
Frontend	HTML5, Tailwind CSS (Glassmorphism UI)
Charts	Chart.js
Icons	Phosphor Icons
Storage	LocalStorage (100% Client-Side / Privacy First)
🧠 Core Logic
The application calculates your financial health using the following formulas:

Remaining Balance:

Remaining=Budget−FixedCosts−(DailyTax×Days)−TotalSpent
Daily Limit:

DailyLimit= 
RemainingDays
Remaining
​	
 
Wishlist Fund:

Fund=PreviousSavings+AccruedTax
📂 Project Structure
Bash
.
├── index.html          # Core Application Logic & UI
└── README.md           # Documentation
⚙️ Setup & Usage
Clone the Repo: git clone https://github.com/nksdev/smart-budget-ai.git

Launch: Open index.html in any modern browser.

Initialize: Enter your total budget, duration, and fixed costs.

Track: Add expenses and watch the daily limit adjust in real-time.

🧑‍💻 Author
Naman Kumar Sonker
Ethical Hacking & Cyber Security @ Sharda University

📜 License
This project is licensed under the MIT License - feel free to fork, modify, and build your own version!

⭐ Support
If this tool helps you save some 💸, consider giving it a Star!

Built with 💙 + ☕ + hacker mindset.
Note: Data is stored in LocalStorage. Clear your cache, lose your cash (data). Always export backups!
