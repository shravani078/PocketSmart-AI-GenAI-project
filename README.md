# PocketSmart AI v2 — Enhanced Edition

## 🚀 Quick Start (3 Steps)

### Step 1 — Install Dependencies
```bash
cd pocketsmart-v2
python -m venv venv

# Activate venv:
# Windows:  venv\Scripts\activate
# Mac/Linux: source venv/bin/activate

pip install -r requirements.txt
```

### Step 2 — Add Your Gemini API Key
Open `.env` and replace `YOUR_GEMINI_API_KEY_HERE` with your actual key.
Get a FREE key at: https://aistudio.google.com/app/apikey

```
GEMINI_API_KEY=AIza...your_key_here
```

### Step 3 — Run
```bash
python app.py
```

Open your browser at: **http://localhost:5000**

---

## ✨ What's New in This Version

### 🔐 Enhanced Login / Signup
- **Name + Email** fields on both sign in and sign up
- **Monthly Income** field to personalize your dashboard
- **Monthly Savings Target** to track your goals
- **Currency Selector** — INR ₹, USD $, EUR €, GBP £, AED, SGD, CAD, AUD
- All dashboard values update based on your selected currency

### 🗂 Proper Section Navigation
- Clicking a sidebar item ONLY opens that section
- All other sections stay hidden (no overlapping)

### 🧠 AI Analysis Studio (6 Powerful Modes)
1. **😊 Financial Mood Meter** — Animated gauge showing your financial wellness
2. **🧬 Spend DNA Profile** — Your unique spender type with donut charts
3. **🔮 30-Day Forecast** — Timeline prediction of end-of-month balance
4. **🚨 Smart Alerts** — Personalized budget warnings and opportunities
5. **🏆 Savings Challenges** — Gamified challenges with progress bars
6. **📊 Full Report** — Comprehensive AI spending analysis

