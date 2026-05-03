# Abhinav Kumar — Portfolio Website

A single-file portfolio site. No build step. No dependencies. Just open `index.html`.

---

## 🚀 Free Hosting Options (Pick One)

All of these are 100% free and give you a public URL you can share on LinkedIn, in your resume, and with recruiters.

### ⭐ Option 1: GitHub Pages (Recommended)

Best for: Permanent URL like `abhinavkblr.github.io`. Most professional.

1. Create a free account at [github.com](https://github.com) if you don't have one.
2. Create a new public repo named exactly: **`abhinavkblr.github.io`** (replace `abhinavkblr` with your actual GitHub username).
3. Upload `index.html` to that repo (drag-and-drop in the browser works).
4. Go to **Settings → Pages**. Under "Branch", select `main` and click Save.
5. Wait 1–2 minutes. Your site is live at: `https://YOUR-USERNAME.github.io`

**Custom URL bonus:** You can later buy a domain (e.g. `abhinavkumar.dev`) on Namecheap (~$10/yr) and point it here.

### ⚡ Option 2: Netlify Drop (Fastest — 30 seconds)

Best for: You want a URL right now with zero setup.

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the folder containing `index.html` onto the page.
3. Done. You get a URL like `https://random-name-123.netlify.app`.
4. Sign up (free) to claim the site and rename it to something like `abhinav-kumar.netlify.app`.

### 🔥 Option 3: Vercel

Best for: Developer credibility. Same as Netlify but Vercel-branded.

1. Sign up at [vercel.com](https://vercel.com) (free, use GitHub login).
2. Click **Add New → Project → Import Git Repository** (or drag-and-drop).
3. Deploy. URL: `https://your-name.vercel.app`.

### 💾 Option 4: Cloudflare Pages

Best for: Fastest global CDN. Free unlimited bandwidth.

1. Sign up at [pages.cloudflare.com](https://pages.cloudflare.com).
2. Connect your GitHub repo or upload directly.
3. URL: `https://your-name.pages.dev`.

---

## 📝 Sharing the Link

Once deployed, add the URL everywhere:

- **LinkedIn:** Profile → Contact Info → Website
- **Resume:** Right under your name, alongside email and phone
- **Email signature:** "Portfolio: yourname.github.io"
- **GitHub bio:** Add the link to your profile README

---

## 🎨 Customizing

Everything is in `index.html`. Open it in VS Code or any text editor.

- **Update content:** Search for the text you want to change (e.g. project descriptions, dates).
- **Change colors:** At the top of the `<style>` block, edit the `:root` CSS variables. The accent color is `--accent: #d4ff3a` — swap in any hex code.
- **Add a project:** Copy any `<div class="project">` block and modify it.
- **Add a photo:** Drop a square image into the same folder, then add `<img src="your-photo.jpg">` somewhere in the hero or about section.

---

## 🧠 Recommended Next Steps

1. **Add real project links.** Each project card should ideally link to a GitHub repo or a live demo. Wrap the project content in `<a href="...">` tags.
2. **Add a favicon.** Create a 32×32 PNG of your initials and save it as `favicon.png`. Add `<link rel="icon" href="favicon.png">` inside `<head>`.
3. **Add Google Analytics or Plausible** (free) to track who's visiting.
4. **Get a custom domain.** `abhinavkumar.dev` looks better than `abhinavkblr.github.io` on a resume.

---

Built clean. Ship fast. Good luck with the job search.
