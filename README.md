# 🚀 Zain's Dev Portfolio

A personal portfolio website that automatically pulls and displays all my public GitHub repositories — live, via the GitHub API. No manual updates needed; push a new repo to GitHub and it shows up here on next page load.

**🔗 Live site:** _add your Netlify link here after deploying_
**👤 GitHub:** [@ZAINZEEAAA](https://github.com/ZAINZEEAAA)

---

## ✨ Features

- **Live GitHub sync** — fetches profile stats (repos, stars, followers) and all public repositories directly from `api.github.com`
- **Language-coded project cards** — each repo card is color-tagged by its primary language (Python, JavaScript, etc.), just like GitHub's own language colors
- **Sorted by recent activity** — most recently updated repos appear first
- **Zero backend** — pure HTML, CSS, and vanilla JavaScript, no build step or server required
- **Responsive design** — works on mobile, tablet, and desktop
- **Handles edge cases** — shows friendly messages if there are no repos yet or if the GitHub API is temporarily unreachable

## 🛠️ Built With

- HTML5
- CSS3 (custom properties, responsive grid)
- Vanilla JavaScript (Fetch API)
- [GitHub REST API](https://docs.github.com/en/rest)
- Deployed on [Netlify](https://www.netlify.com)

## 📦 Project Structure

```
portfolio/
├── index.html      # Everything — markup, styles, and script in one file
└── README.md        # You're reading it
```

## 🚀 Deployment

This site is deployed on Netlify with continuous deployment connected to this GitHub repo. Any push to the `main` branch automatically triggers a new deployment — no manual redeploy needed.

To deploy your own copy:
1. Fork or clone this repo
2. Open `index.html` and change the `USERNAME` constant in the script section to your own GitHub username
3. Push to your GitHub
4. Connect the repo to [Netlify](https://www.netlify.com) via "Import an existing project"
5. Deploy — no build command needed, it's static HTML

## 📈 Roadmap

- [ ] Add a "featured projects" section for pinned repos
- [ ] Add contact form
- [ ] Add dark/light theme toggle

## 📄 License

Open to use as a template — feel free to fork and adapt for your own GitHub portfolio.

---

<sub>Built while learning Python, data analysis, and web development, one commit at a time.</sub>
