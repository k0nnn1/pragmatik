# Pragmatik — Cybersecurity Lab Blog

Pragmatik is a **static cybersecurity blog** built with **Hugo** and hosted on **GitHub Pages**.  
It serves as a personal space to document labs, walkthroughs, research notes, and practical exercises in DFIR, detection engineering, and security operations.

The site is designed to be:

- 📝 **Markdown-first**
- ⚡ **Fast and lightweight**
- 🔐 **Low attack surface**
- 🧪 **Lab-friendly**
- 🔁 **Automatically deployed via GitHub Actions**

---

## 🌐 Live Site

👉 **https://k0nnn1.github.io/pragmatik/**

---

## 🛠 Tech Stack

This project is built using:

- **Hugo (Extended)** — Static site generator  
- **Markdown** — For all content  
- **GitHub Pages** — Hosting  
- **GitHub Actions** — CI/CD deployment  
- **hugo-theme-terminal** — Dark, console-style theme  

---

## 📁 Repository Structure

```

pragmatik/
├── content/
│   ├── posts/          # Blog posts (labs, walkthroughs, notes)
│   └── who-am-i/       # About / profile page
├── themes/
│   └── terminal/       # Hugo theme (submodule)
├── static/             # Custom assets (CSS, images, etc.)
├── hugo.toml           # Site configuration
└── .github/
└── workflows/
└── github-pages.yml  # Auto-deploy pipeline

````

---

## ✍️ Writing a New Post

Create a new post:

```bash
hugo new posts/my-lab.md
````

Edit it in Markdown:

```bash
nano content/posts/my-lab.md
```

Make sure it includes:

```yaml
draft: false
```

Publish:

```bash
git add .
git commit -m "Add my lab post"
git push origin main
```

Your site will update automatically in ~1 minute.

---

## 🚀 Local Development

Run the site locally:

```bash
hugo server
```

Then open in your browser:

```
http://localhost:1313/
```

---

## 🔁 Deployment

Every push to `main` triggers an automatic deployment via GitHub Actions to GitHub Pages.

You can monitor deployments here:

```
https://github.com/k0nnn1/pragmatik/actions
```

---

## 🎯 Purpose of This Blog

This blog is intended for:

* Documenting hands-on cybersecurity labs
* Sharing DFIR and detection techniques
* Recording learnings from home lab experiments
* Building a technical portfolio
* Practicing clear technical writing

---

## 📬 Contact

You can find me on:

* GitHub: https://github.com/k0nnn1
* LinkedIn: https://linkedin.com/in/andrebanza
* TryHackMe: https://tryhackme.com/p/abnz4

---

## 📄 License

This project is personal and educational. Content is shared for learning purposes unless stated otherwise.

```
```
