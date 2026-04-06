# Omar Shakeel Ahmed Attar — Digital Portfolio

Personal portfolio website for **Omar Shakeel Ahmed Attar**, B.Tech CSE (AIML) student at MIT Vishwaprayag University.

## 🌐 Live Site
> Add your GitHub Pages URL here after deployment: `https://omer10ahmed47-ai.github.io/portfolio`

---

## 📁 Folder Structure

```
portfolio/
├── index.html                  ← Main portfolio page
├── style.css                   ← All styles (dark/light mode)
├── script.js                   ← Interactions & animations
├── README.md
└── assets/
    ├── images/
    │   └── profile.jpg         ← Your profile photo ✅
    ├── certificates/
    │   ├── cisco_modern_ai.pdf ← Cisco / Netcad cert ✅
    │   ├── yuva_ai_for_all.pdf ← Yuva AI for All cert ✅
    │   └── coursera.pdf        ← ⬅ ADD: Upload your Coursera certificate here
    └── projects/
        ├── ai4a.jpg            ← ⬅ ADD: Screenshot of AI4A project
        ├── design_thinking.jpg ← ⬅ ADD: Screenshot of Design Thinking project
        └── ace.jpg             ← ⬅ ADD: Screenshot of ACE project
```

---

## 🚀 How to Upload to GitHub

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and log in as `omer10ahmed47-ai`
2. Click **New Repository**
3. Name it: `portfolio`
4. Set to **Public**
5. Click **Create Repository**

### Step 2 — Upload Files
**Option A — GitHub Web Interface (easiest):**
1. Open your new repo
2. Click **Add file → Upload files**
3. Upload ALL files maintaining the folder structure above
4. Click **Commit changes**

**Option B — Git CLI:**
```bash
cd portfolio/
git init
git add .
git commit -m "Initial portfolio commit"
git remote add origin https://github.com/omer10ahmed47-ai/portfolio.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repo → **Settings → Pages**
2. Under **Source**, select **Deploy from branch**
3. Branch: `main`, Folder: `/ (root)`
4. Click **Save**
5. Your site will be live at: `https://omer10ahmed47-ai.github.io/portfolio`

---

## ✏️ What Still Needs to Be Updated

| Item | Status | How to Fix |
|------|--------|------------|
| Coursera certificate | ⬅ Pending | Upload to `assets/certificates/coursera.pdf` |
| AI4A project screenshot | ⬅ Pending | Add to `assets/projects/ai4a.jpg` |
| Design Thinking screenshot | ⬅ Pending | Add to `assets/projects/design_thinking.jpg` |
| ACE project screenshot | ⬅ Pending | Add to `assets/projects/ace.jpg` |
| AI4A project description | ⬅ Edit in index.html | Update the text in the Projects section |
| Design Thinking description | ⬅ Edit in index.html | Update the text in the Projects section |
| ACE project description | ⬅ Edit in index.html | Update the text in the Projects section |
| Coursera cert details | ⬅ Edit in index.html | Fill in the Achievements section |
| LinkedIn URL | ⬅ Edit in index.html | Replace `#` in Contact section |
| GitHub project links | ⬅ Edit in index.html | Add actual repo URLs |

---

## ✨ Features
- Dark / Light mode toggle (persists across sessions)
- Smooth scroll with offset nav
- Scroll-triggered reveal animations
- Gallery filter (All / Certificates / Projects / Photos)
- Active nav link tracking
- Responsive mobile layout
- Direct PDF links to certificates

---

Built with HTML, CSS & vanilla JavaScript. No frameworks, no dependencies.
