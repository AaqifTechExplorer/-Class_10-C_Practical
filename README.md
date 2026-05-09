# 📚 Class 10-C Practical

A clean, fully responsive web app to browse and view **Class 10-C practical files** directly from Google Drive — no backend, no server, just one HTML file.

---

## 🔗 Live Demo

> [Click here to view](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME)

---

## 📸 Preview

| Desktop | Mobile |
|--------|--------|
| Sidebar + Viewer side by side | Bottom nav + slide-in sidebar |

---

## ✨ Features

- 📁 Opens each subject's **own Google Drive folder**
- 🔍 **Search bar** to filter subjects
- 📱 **Mobile** — bottom nav bar + ☰ slide-in sidebar
- 📟 **Tablet** — compact sidebar always visible
- 🖥️ **Desktop** — full sidebar + viewer
- 🔗 "Open in Drive" button for every subject
- ⚡ Zero dependencies — pure HTML/CSS/JS

---

## 🚀 Deploy on GitHub Pages

1. Fork or upload this repo
2. Go to **Settings → Pages**
3. Source: `main` branch → `/ (root)`
4. Save — your site will be live at:
   ```
   https://YOUR-USERNAME.github.io/YOUR-REPO-NAME
   ```

---

## 🛠️ How to Customize

### Add or change subjects

Open `index.html` and find:

```js
const subjects = [
  { name: 'Physics',     icon: '⚡', folderId: 'FOLDER_ID' },
  { name: 'Chemistry',   icon: '🧪', folderId: 'FOLDER_ID' },
  { name: 'Biology',     icon: '🌿', folderId: 'FOLDER_ID' },
  { name: 'Higher Math', icon: '📐', folderId: 'FOLDER_ID' },
  { name: 'ICT',         icon: '💻', folderId: 'FOLDER_ID' }
];
```

Add a new subject:

```js
{ name: 'English', icon: '📝', folderId: 'YOUR_FOLDER_ID' },
```

### Get a Google Drive Folder ID

```
https://drive.google.com/drive/folders/👉THIS_PART👈
```

Make sure the folder sharing is set to **"Anyone with the link → Viewer"**

### Add a logo

Find this in `index.html`:

```html
<div class="header-title">📚 Class 10-C Practical</div>
```

Replace with:

```html
<div class="header-title">
  <img src="YOUR_LOGO_URL" alt="Logo"
    style="height:40px;width:40px;object-fit:contain;border-radius:8px;vertical-align:middle;margin-right:10px;">
  Class 10-C Practical
</div>
```

---

## 📂 File Structure

```
📦 repo
 ┣ 📄 index.html      ← entire app (rename class10c_practical.html → index.html)
 ┗ 📄 README.md
```

> 💡 Rename `class10c_practical.html` to `index.html` for GitHub Pages to work properly.

---

## 🧰 Tech Stack

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=flat&logo=googledrive&logoColor=white)

- Pure HTML / CSS / JavaScript
- Google Drive Embed (no API key needed)
- No frameworks, no npm, no build step

---

## 📄 License

MIT — free to use and modify.

---

<p align="center">Made with ❤️ for Class 10-C</p>
