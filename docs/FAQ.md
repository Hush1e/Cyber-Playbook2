# ❓ Cyber Playbook FAQ – Hocking College Edition

This FAQ covers everything students break, forget, or ask about most often.  
If you follow this document, you will not need to ask for help 99% of the time.

---

## 🧱 Basic Site Questions

### 💡 What is this site?
Your **Cyber Playbook** is a personal, professional portfolio.  
You’ll document labs (Hardware, Networking, Security) by adding “Topic” blocks to `index.html`.  
Your GitHub Pages site will serve as both your graded deliverable and a long-term resume piece.

### 🌐 What’s my site link?
After enabling Pages:

https://<your-username>.github.io/<repo-name>/

Example:  
`https://claytonholden.github.io/Cyber-playbook2/`

### 🧑‍💻 What files am I allowed to edit?
You can edit **index.html** and add screenshots in **assets/images/** only.  
Everything else (CSS, docs, templates) should remain as-is.

---

## 🧱 Topic & Editing Issues

### 🧩 How do I add a new Topic?
Copy the block from `templates/topic-block.html`, open `index.html`, paste it under your correct subject section, and fill it out.  
See `docs/HTML_EDITING.md` for the exact steps.

### ❌ My page shows raw HTML or text.
You deleted or forgot a closing `</section>` or `<div>`.  
Copy a fresh Topic block from `templates/topic-block.html` and re-add it properly.

### 🖼 My images don’t show.
- Make sure they’re uploaded to `assets/images/`
- Use lowercase filenames (`2025-11-lab-01.png`)
- Link properly:  
  ```html
  <a href="assets/images/2025-11-lab-01.png" target="_blank">Screenshot</a>

🎨 My colors or icons don’t look right.

You can safely change accent colors, icons, and font using docs/THEME.md.

⚙️ The sidebar or top bar disappeared.

You accidentally removed a <header> or <aside> tag.
Revert to a previous commit:

Open index.html → History

Click the last working commit

Choose Revert this commit

🖥 GitHub Pages & Repo Problems
🕓 My site hasn’t updated.

Wait ~1–2 minutes. GitHub Pages rebuilds automatically after every commit.
Then hard-refresh (Ctrl/Cmd + Shift + R).

🚫 My site says “404 Not Found.”

Check that Pages is enabled:
Settings → Pages → Build & Deployment → Deploy from branch → Branch: main, Folder: / (root)

If it’s already enabled, your last commit might not have built yet — wait a minute and refresh.

🧭 I can’t find my images folder.

It’s inside assets/images/.
If it’s missing, recreate it exactly (lowercase).

🔄 I made a mistake and pushed it.

That’s fine — go to the file → History → click the last good version → Revert.

📄 Submissions & Grading
📦 What do I turn in for class?

Your live Pages URL (primary deliverable)

If your instructor asks, a PDF export (Ctrl + P → Save as PDF)

Make sure your site link shows your new Topic block

🧾 What will be graded?

Correct structure (Overview / Approach / Evidence / Reflection)

1–3 working screenshots

Clear reflection (not copy/paste from instructions)

Proper filenames (lowercase, hyphenated)

🎨 Customization & Personality
💅 How do I change colors?

Open assets/styles.css, find the section:

:root{
  --accent:#63e0ff;
}


Change --accent: to any hex color (examples: #ff7ab6, #00d27a, #ff9a3c).

🧠 Can I change icons?

Yes! In index.html, look for:

<span class="icon">🧩</span>


Replace the emoji (🧰 🔧 🖥️ 🌐 🔐 ⚙️ 🛰️).

🖋 Can I use a different font?

Add this inside <head> (above your stylesheet):

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">


Then update the font: rule in assets/styles.css to use Inter.

🧯 Emergencies
😭 I broke everything.

Don’t panic.

Go to index.html → History

Find a version that worked

Click Revert

Redo your edits carefully following docs/HTML_EDITING.md

🔒 I deleted files or folders.

Check the GitHub trash bin (under repo → commits → browse files).
If needed, clone the template repo again and re-copy missing folders.

🧩 Still Need Help?

Before asking:

Read this FAQ fully

Check docs/HTML_EDITING.md

Check your site’s History tab

Revert if you made a major error

If it’s still broken, contact your instructor with:

A link to your repo

A link to your live site

Screenshot of the issue
