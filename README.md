Hey , This is for practice.

# 🚀 My First CI/CD Portfolio Site

> A personal portfolio website deployed automatically using a full CI/CD pipeline with GitHub Actions.

🌐 **Live Site:** [kalpana-w.github.io/MyFirstRepository](https://kalpana-w.github.io/MyFirstRepository/)

---

## 📌 What This Project Does

- Displays a personal portfolio page with HTML, CSS, and JavaScript
- Automatically deploys to GitHub Pages on every `push` to `main`
- Runs a CI check on every `pull_request` before merging
- Demonstrates a real end-to-end DevOps pipeline

---

## ⚙️ CI/CD Pipeline

This project uses **GitHub Actions** to automate the full build and deployment process.

### CI — Continuous Integration (`ci.yml`)
- Triggered on: `pull_request` to `main`
- Checks out the code
- Runs automated validation before any merge

### CD — Continuous Deployment (`deploy.yml`)
- Triggered on: `push` to `main`
- Automatically deploys the latest code to GitHub Pages
- Live site updates within seconds of every push

```
Push code → CI runs → CD deploys → Live site updated ✅
```

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML / CSS / JavaScript | Frontend website |
| Git | Version control |
| GitHub | Code hosting & repository management |
| GitHub Actions | CI/CD pipeline automation |
| YAML | Workflow configuration |
| GitHub Pages | Free hosting & deployment |

---

## 📁 Project Structure

```
MyFirstRepository/
├── .github/
│   └── workflows/
│       ├── ci.yml        # CI pipeline - runs on pull_request
│       └── deploy.yml    # CD pipeline - deploys on push to main
├── css/
│   └── style.css
├── js/
│   └── script.js
├── index.html
├── about.html
└── README.md
```

---

## 💡 What I Learned

- How to set up a GitHub Actions workflow from scratch
- Writing and debugging YAML configuration files
- Understanding CI vs CD and when each triggers
- Fixing real deployment errors (404 branch/root issues)
- Connecting version control to automated deployment

---

## 👩‍💻 About Me

**Kalpana** — Azure Administrator & DevOps Learner
| [GitHub](https://github.com/Kalpana-w)

---

*Built with 💙 and a lot of YAML debugging*