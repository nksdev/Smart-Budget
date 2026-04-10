


# 💸 Smart-Budget AI

<p align="center">
  <img src="https://img.shields.io/badge/Security-XSS_Protected-green?style=for-the-badge&logo=shield" alt="Security Protected">
  <img src="https://img.shields.io/badge/Privacy-Local_Storage-blueviolet?style=for-the-badge&logo=lock" alt="Privacy First">
  <img src="https://img.shields.io/badge/Built_by-Naman_Kumar_Sonker-orange?style=for-the-badge&logo=github" alt="Author">
</p>

> **"Financial discipline meets hacker-grade privacy."** > A futuristic, AI-inspired budget tracking web app featuring wishlist fund management, real-time analytics, and secure client-side storage.

---

## 🚀 Features

* 💰 **Dynamic Daily Limit** – Smart per-day spending limits that adjust in real-time based on your remaining balance and time.
* 📊 **Analytics Dashboard** – High-fidelity spending trends via **Chart.js** and category-wise breakdowns.
* 🎯 **Wishlist Fund System** – Specialized logic to save for goals using accumulated savings and "daily tax" accruals.
* 🔄 **Cycle Management** – Seamlessly reset cycles with automated carry-forward logic into your wishlist.
* 📦 **Data Sovereignty** – Export full data as JSON for backups or CSV for external auditing.
* 🔐 **Security Hardened** – Native XSS protection through strict input sanitization using `escapeHtml()`.

---

## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | HTML5 & Tailwind CSS (Glassmorphism UI) |
| **Charts** | Chart.js |
| **Icons** | Phosphor Icons |
| **Storage** | LocalStorage (100% Client-Side / Offline First) |

---

## 🧠 Core Logic

The application maintains financial integrity using the following mathematical models:

**Remaining Balance:** $$Remaining = Budget - FixedCosts - (DailyTax \times Days) - TotalSpent$$

**Daily Limit:** $$DailyLimit = \frac{Remaining}{RemainingDays}$$

**Wishlist Fund:** $$Fund = PreviousSavings + AccruedTax$$

---

## 📂 Project Structure

```bash
.
├── index.html          # Core Application (Logic, Styles, & UI)
└── README.md           # Documentation
````

-----

## ⚙️ How It Works

1.  **Initialize:** Input your total budget, duration, and fixed costs.
2.  **Calculate:** The engine determines your "Safe-to-Spend" daily limit.
3.  **Track:** Add expenses in real-time; the UI updates instantly without page refreshes.
4.  **Secure:** All data stays in your browser. No server, no tracking, no leaks.

-----

## 🧑‍💻 Author

**Naman Kumar Sonker** *

[](https://www.instagram.com/namanmic)
[](https://www.linkedin.com/in/namanmic)
[](https://github.com/nksdev)

-----

## 📜 License & Support

This project is open-source. If this tool helps you optimize your 💸, give it a **Star**\!

> [\!WARNING]
> **Data Persistence:** This app uses `LocalStorage`. Clearing your browser cache will delete your data. Always use the **Backup** feature to keep your data safe.






