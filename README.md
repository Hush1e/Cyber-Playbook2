# 🚀 Cyber Playbook – Hocking College Template

A student-friendly, employer-ready portfolio for documenting hands-on labs across **Hardware**, **Networking**, and **Security**.  
Everything is stored in one page (`index.html`) with consistent **Topic blocks** that instructors can grade easily and employers can scan quickly.

---

## 🎯 Purpose

This playbook exists to:
- Provide students with a **professional showcase** of technical work.
- Give instructors a **consistent grading structure**.
- Teach real-world **Git and GitHub skills**.
- Build a lasting personal portfolio hosted on **GitHub Pages**.

---

## 🧱 Core Concept

Each **Topic** = one lab, project, or task.  
Every Topic follows the same 4-part structure:

| Section | Description |
|--------|-------------|
| **Overview** | One short paragraph explaining what the lab was and why it mattered. |
| **Approach** | A bullet list of key steps, tools, or commands used. |
| **Evidence** | 1–3 screenshots or artifacts uploaded to `assets/images/` and linked. |
| **Reflection** | 2–4 sentences on what you learned and what you’d improve next time. |

---

## 🪜 Quick-Start Guide

### Option A — GitHub Web (easiest)
1. Turn on Pages once:  
   Settings → Pages → Build & Deployment → Source = **Deploy from branch** → Branch = `main`, Folder = `/(root)` → **Save**
2. Add screenshots:  
   **Add file → Upload files** → target folder `assets/images/`
3. Add a Topic:  
   Open `templates/topic-block.html` → click **Raw** → Copy All  
   Open `index.html` → **Edit** → Scroll to the right subject (Hardware / Networking / Security)  
   Paste the block **below the last Topic**, fill in your text, update screenshot links, **Commit changes**
4. Wait ~1–2 minutes and open your site:  
   `https://<username>.github.io/<repo-name>/`

### Option B — Command Line
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
# edit index.html and add images under assets/images/
git add .
git commit -m "Added Week 3 Networking Lab"
git push

✅ Turn-In Checklist

 Topic added under correct subject

 Overview / Approach / Evidence / Reflection complete

 1–3 screenshots uploaded & linked correctly

 Live site opens with no broken links

 (If required) PDF exported and submitted to LMS

🛡 Guardrails

Do NOT delete or rename: index.html, assets/, templates/, docs/

Use lowercase filenames only (case-sensitive hosting).

Add content only by copying templates/topic-block.html (never freestyle HTML).

If broken: index.html → History → Revert to last good commit.

Don’t edit CSS unless following docs/THEME.md.

🎨 Customization (safe creativity)

You can personalize without breaking structure:

Colors / accent tones

Rounded corners / minimalistic tweaks

Icons (emoji in subject titles)

Optional fonts (Google Fonts via docs/THEME.md)

See docs/THEME.md for exact steps.

💬 Why This Works

For students: Shows your technical journey visually — a mini-portfolio proving hands-on skill.
For instructors: One URL per student, identical structure, faster grading.
For employers: A clean, public showcase of your applied IT and cybersecurity work.

📚 Reference Docs
File	Purpose
docs/HTML_EDITING.md	Exact copy/paste editing steps for index.html
docs/FAQ.md	Fixes for common mistakes
docs/THEME.md	Safe theme customization (colors, icons, font)
templates/topic-block.html	Copy block for new Topics
