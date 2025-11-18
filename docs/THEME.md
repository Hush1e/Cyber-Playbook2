# 🎨 Theme Customization – Safe Edits Only

This guide lets you personalize your Playbook without breaking layout or grading structure.

---

## 🧭 Edit Colors
Open `assets/styles.css` → find the top section:
```css
:root{
  --bg:#0b0d10;
  --panel:#0f1319;
  --ink:#e8edf3;
  --muted:#a7b3c2;
  --line:#1f2630;
  --accent:#63e0ff;
  --radius:16px;
}
Change --accent: to any color hex you like (for example):

bash
Copy code
#ff7ab6 (pink)
#00d27a (green)
#ff9a3c (orange)
#00a8ff (sky blue)
🧩 Change Icons (emoji)
Each subject uses an emoji:

html
Copy code
<h2 class="subject-title"><span class="icon">🧩</span> Hardware</h2>
Swap it for your favorite:
🧰 🖥️ 🌐 🔐 ⚙️ 🛰️ 🧠

✏️ Change Corners / Radius
Rounder = --radius:22px;
Sharper = --radius:8px;

🖋 Change Font
Add this line to <head> in index.html:

html
Copy code
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
Then in CSS, update the first font: line to use Inter.

☀️ Light Theme Option
Your CSS already supports system dark/light mode.
Try switching your OS theme to test both views.

⚠️ Keep It Professional
Avoid hard-to-read color combos.

Keep text contrast high.

Don’t make text smaller than 16px.

