# 🚀 LoopLogiQ: Business Automation Runner (Hoop Hopper Game)
### Deployment & Hosting Instructions for Claude / Vercel / Netlify / Cloudflare

---

## 📌 Game Overview
**LoopLogiQ: Hoop Hopper** is an interactive, browser-based 2D runner web app created for **LoopLogiQ**.
- **Protagonist**: The Owner of LoopLogiQ (represented by your custom Build with Gemini avatar in `public/avatar.jpg`).
- **Gameplay**: Leap through glowing **LoopLogiQ Infinity Hoops** to automate incoming manual business tasks (`📞 Missed Calls`, `📧 Unread Emails`, `💸 Lead Leakage`, `📝 Manual Entry`, `🗓️ Calendar Chaos`).
- **Business Impact**: Saves thousands of hours (`Hrs`) and dollars (`$$`) for the player's business name entered at launch.
- **Conversion Lead Form**: High-converting lead form on the victory screen for players to schedule a 20-minute automation audit directly on `www.looplogiq.com`.

---

## 🛠️ Step-by-Step Instructions to Hand to Claude / Hosting Developer

### 1️⃣ Option A: Deploy via GitHub (Recommended)
This repository is hosted on GitHub:
👉 **`https://github.com/Seanmorais09/looplogiq-game`**

To host on **Vercel**, **Netlify**, or **Cloudflare Pages**:
1. Go to [Vercel](https://vercel.com) / [Netlify](https://netlify.com).
2. Click **"Add New Project"** -> Import Git Repository `Seanmorais09/looplogiq-game`.
3. Set **Framework Preset**: `Other / HTML` (Root Directory: `./`).
4. Click **Deploy**.
5. Add your custom domain: `game.looplogiq.com` (or `looplogiq.vome`).

---

### 2️⃣ Option B: Give File Directly to Claude for Instant Deployment
If you are asking Claude to host or deploy this game:
1. Provide the main game file: `index.html`
2. Provide the image folder: `public/avatar.jpg` and `public/logo.png`
3. Give Claude this prompt:
> *"Claude, please host this single-page static web application (`index.html`) on my domain. Ensure `public/avatar.jpg` and `public/logo.png` are served from the `./public/` directory."*

---

## 🎨 Asset File Map
| Asset Path | Description |
| :--- | :--- |
| `index.html` | Complete HTML5 Canvas game engine, TailwindCSS UI overlay, Web Audio API sound FX, and lead capture modal. |
| `public/avatar.jpg` | Build with Gemini Owner Avatar sprite. |
| `public/logo.png` | Official LoopLogiQ Logo Badge. |
| `DEPLOYMENT_INSTRUCTIONS.md` | Deployment guide for Claude & hosting. |

---

## 🌐 Lead Form Submission Target
Form submissions trigger instant celebratory confetti and direct users to book an audit at:
`https://www.looplogiq.com`

---
*Created with ❤️ for LoopLogiQ by Google Antigravity.*
