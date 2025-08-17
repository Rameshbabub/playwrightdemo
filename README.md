[README.md](https://github.com/user-attachments/files/21821089/README.md)
# 🎭 Playwright MCP Automation Framework + PWA Docs

This repository contains a **modern Playwright-based automation framework** with **PWA-powered documentation**.  
It’s designed as a **reference project** for teams to learn, adopt, and extend.

---

## 🚀 Features
- ✅ **Playwright + TypeScript** automation framework
- ✅ Clear structure (`tests`, `pages`, `fixtures`, `utils`)
- ✅ **Environment config** via `.env`
- ✅ **Reporters**: HTML, Traces, Screenshots, Videos
- ✅ **CI/CD ready** with GitHub Actions
- ✅ **Documentation** powered by VitePress + PWA
- ✅ Easy deployment to **GitHub Pages**

---

## 📂 Project Structure
```
e2e/
 ├── tests/        # Test specs
 ├── pages/        # Page objects
 ├── fixtures/     # Shared test data/fixtures
 ├── utils/        # Helpers
 └── env/          # .env configs

docs/              # Documentation site (VitePress + PWA)
.github/workflows/ # CI/CD pipelines
playwright.config.ts
package.json
```

---

## 🛠 Setup

### 1. Install dependencies
```bash
pnpm install
```

### 2. Configure environment
```bash
cp e2e/env/.env.example e2e/env/.env
```
Edit `.env` file with your `BASE_URL` and credentials.

---

## ▶️ Running Tests
```bash
pnpm e2e:test
```

Generate and open report:
```bash
pnpm e2e:report
```

---

## 📖 Running Docs
Start docs locally:
```bash
pnpm docs:dev
```

Build docs for deployment:
```bash
pnpm docs:build
```

---

## ⚡ CI/CD
- On every push/PR, GitHub Actions will:
  - Run Playwright tests
  - Upload test reports + traces
- Docs auto-deploy to **GitHub Pages**

---

## 🌟 Contributing
Feel free to fork this repo, raise issues, and submit PRs.  
The goal is to **educate and enable QA teams** to adopt modern automation practices.

---

## 📜 License
MIT License © 2025
