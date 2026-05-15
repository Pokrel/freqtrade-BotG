# ⚙️ GitHub Workflows Overview — freqtrade-BotG

This directory contains all automation pipelines for the project.  
Each YAML file defines a GitHub Action that runs automatically to keep the bot healthy, updated, and secure.

---

## 🧩 Workflow Summary

| Workflow File | Purpose |
|----------------|----------|
| **ci.yml** | Runs tests, linting, and type checks to ensure code quality. |
| **docker-build.yml** | Builds Docker images for deployment. |
| **docker-update-readme.yml** | Updates Docker documentation automatically. |
| **deploy-docs.yml** | Publishes updated documentation to the site. |
| **devcontainer-build.yml** | Builds the development container environment. |
| **pre-commit-update.yml** | Updates pre-commit hooks and dependencies. |
| **pre-commit-types-update.yml** | Refreshes type-checking tools for pre-commit. |
| **binance-lev-tier-update.yml** | Updates Binance leverage tier data. |
| **packages-cleanup.yml** | Removes old or unused GitHub packages. |
| **zizmor_action.yml** | Runs Zizmor security scans for vulnerabilities. |

---

## 🧭 Visual Diagram

![Workflow Diagram](path/to/your/diagram.png)

> Replace `path/to/your/diagram.png` with the actual relative path to your saved image.

---

## 💡 Quick Tip
To view this file directly on GitHub:
- Navigate to `.github/workflows/README.md`
- I, Gyan created this readme for my reference.

---

**Maintainer:** Gyan
**Last Updated:** May 2026
