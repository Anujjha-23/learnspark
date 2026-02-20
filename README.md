# LearnSpark – EdTech Website

A modern, multi-page educational technology website built with pure HTML, CSS, and JavaScript. No frameworks or build tools required.

## 📄 Pages

| File | URL | Description |
|------|-----|-------------|
| `index.html` | `/` | Homepage with hero, features & course preview |
| `courses.html` | `/courses.html` | Course catalog with category filter |
| `about.html` | `/about.html` | About us, mission, team & values |
| `blog.html` | `/blog.html` | Blog posts & articles |
| `contact.html` | `/contact.html` | Contact form & info |
| `signup.html` | `/signup.html` | Sign up & login page |

## 🚀 Hosting on GitHub Pages (Free)

### Step 1 – Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in
2. Click **New repository** (+ button top right)
3. Name it: `learnspark` (or anything you like)
4. Set it to **Public**
5. Click **Create repository**

### Step 2 – Upload Files
**Option A – Drag & Drop (easiest):**
1. Open your new repo
2. Click **Add file → Upload files**
3. Drag all 7 files (`index.html`, `courses.html`, `about.html`, `blog.html`, `contact.html`, `signup.html`, `README.md`) into the upload area
4. Click **Commit changes**

**Option B – Using Git (for developers):**
```bash
git init
git add .
git commit -m "Initial commit: LearnSpark website"
git remote add origin https://github.com/YOUR_USERNAME/learnspark.git
git push -u origin main
```

### Step 3 – Enable GitHub Pages
1. Go to your repo → **Settings** tab
2. Scroll to **Pages** section (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Choose branch: **main**, folder: **/ (root)**
5. Click **Save**

### Step 4 – Access Your Site
After ~2 minutes, your site will be live at:
```
https://YOUR_USERNAME.github.io/learnspark/
```

## ✏️ How to Edit

All styles are inside `<style>` tags in each HTML file. To change:

- **Colors** – Edit CSS variables at the top of each file:
  ```css
  --accent: #f0c040;   /* Gold/Yellow */
  --accent2: #e05aff;  /* Purple */
  --bg: #0a0a0f;       /* Dark background */
  ```
- **Text content** – Edit directly in the HTML
- **Course cards** – Copy/paste `.course-card` divs in `courses.html`
- **Team members** – Edit `.member-card` divs in `about.html`
- **Blog posts** – Edit `.post-card` divs in `blog.html`
- **Contact email** – Find `hello@learnspark.io` in `contact.html`
- **Site name** – Search & replace "LearnSpark" across all files

## 🎨 Customization Tips

- **Logo name:** Find `Learn<span>Spark</span>` in every `<nav>` and replace it
- **Google Fonts:** The site uses `Syne` (headings) + `DM Sans` (body). Change in the `<link>` tag
- **Add a page:** Copy any existing page, change the content, and link to it in all nav menus

## 📁 File Structure

```
learnspark/
├── index.html      ← Homepage
├── courses.html    ← Courses catalog
├── about.html      ← About us
├── blog.html       ← Blog
├── contact.html    ← Contact form
├── signup.html     ← Auth page
└── README.md       ← This file
```

---
Built with ❤️ using pure HTML, CSS & JavaScript — no dependencies needed.
