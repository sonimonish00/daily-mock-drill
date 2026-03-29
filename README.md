# Daily Practice Hub 🎯
### 10-Module AI-Powered Daily Practice System

A fully offline-capable web app that generates fresh, applied, randomised practice problems daily across 10 subject modules. All you need is an internet connection to call the AI API.

---

## How to Run

1. **Unzip** this folder anywhere on your computer.
2. **Double-click** `index.html` to open it in any modern browser (Chrome, Edge, Firefox, Safari).
   - No server needed. No installation needed. No Node.js needed.
3. On first launch, enter your API key and you're ready to go.

---

## Getting a Free API Key

Choose any one provider — all have generous free tiers:

### Option 1 — Google Gemini (Recommended)
- Visit: https://aistudio.google.com/app/apikey
- Sign in with Google → click **Create API Key**
- Free tier: **1,500 requests/day**, 15 req/min
- Default model: `gemini-2.0-flash`

### Option 2 — Groq (Fastest responses)
- Visit: https://console.groq.com/keys
- Sign up free → click **Create API Key**
- Free tier: generous daily limits
- Default model: `llama-3.3-70b-versatile`

### Option 3 — OpenRouter (Most flexible)
- Visit: https://openrouter.ai/keys
- Sign up free → generate a key
- Many free models available, e.g.:
  - `meta-llama/llama-3.1-8b-instruct:free`
  - `google/gemini-2.0-flash-exp:free`
  - `mistralai/mistral-7b-instruct:free`

---

## Features

| Feature | Details |
|---|---|
| **10 Modules** | Exercise, SQL, Excel, Power BI/Tableau, Python, Quant Aptitude, LR & DI, General Science, Current Affairs & GK, GATE CS |
| **AI-generated problems** | Fresh, randomised, applied problems every session |
| **Auto difficulty scaling** | Score ≥ 80% on a module → level increases automatically |
| **AI evaluation** | Your answers are graded with partial credit, specific feedback, and tips |
| **Progress saved** | All progress stored in browser localStorage — persists across sessions |
| **Multi-provider** | Switch between Gemini / Groq / OpenRouter anytime in settings |
| **Zero install** | Pure HTML + CSS + JS — runs directly in any browser |

---

## Modules & What to Expect

| # | Module | Problem Type |
|---|---|---|
| 1 | Exercise & Mental | Workout plans, chess puzzles, riddles |
| 2 | SQL | CREATE TABLE + INSERT data → write a query |
| 3 | Excel | Data table → write a formula or evaluate one |
| 4 | Power BI / Tableau | Business scenario → write DAX or LOD formula |
| 5 | Python | Problem + examples → write complete code |
| 6 | Quant Aptitude | Word problem MCQ (A/B/C/D) — CAT/SSC/UPSC style |
| 7 | LR & Data Interpretation | Logic puzzles or DI tables with MCQ |
| 8 | General Science | Numerical/applied MCQ — 10th to JEE/NEET level |
| 9 | Current Affairs & GK | MCQ — UPSC/GPSC/RPSC/GSSSB/RSMSSB level |
| 10 | GATE CS | Computational MCQ — COA, OS, CN, DSA |

---

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl + Enter` | Submit your answer |

---

## Tips for Best Results

- **Attempt daily** — the streak counter motivates consistency
- **Use the hint button** if stuck — it nudges without giving away the answer
- **Avoid Skip** — use it only when you truly cannot proceed; it resets your streak
- **Level 1 = Beginner, Level 10 = Master** — score ≥80% consistently to level up
- **Change the model** in settings if responses are slow or poor quality

---

## Privacy

- Your API key is stored only in your browser's `localStorage`
- No data is sent anywhere except directly to your chosen AI provider
- No tracking, no accounts, no servers

---

## Troubleshooting

**"Error generating problem"**
→ Check your API key is correct in Settings (⚙ icon)
→ Check your internet connection
→ Try a different provider or model

**Slow responses**
→ Switch to Groq (fastest) or a smaller model

**JSON parse errors**
→ Try again — occasionally the AI response has formatting issues

---

*Built for daily competitive exam and skill practice. Good luck! 🎯*
