# Welcome to Kage Technologies

`@kage-tech/.github` — Global Configuration. 

This repository defines **organization-wide defaults** for all repositories in [`@kage-tech`](https://github.com/kage-tech).

> 🔧 Changes here may affect **dozens of repositories** — please review carefully.

---

## 📁 What This Repo Controls

| Folder/File | Purpose |
|------------|--------|
| `ISSUE_TEMPLATE/` | Standard forms for bugs, features, docs |
| `PULL_REQUEST_TEMPLATE/` | PR description guidance |
| `workflows/stale.yml` | Auto-closes inactive issues/PRs after 60 days |
| `dependabot.yml` | Automatically updates dependencies & security patches |
| `labeler.yml` | Auto-tags PRs (e.g., `area:frontend`, `area:backend`) |

---

## 🧩 How It Works

- ✅ **All repos inherit** these settings unless they override them locally.
- 🔁 Example: A repo can add its own `ISSUE_TEMPLATE/bug.yml` to **override** the global one.
- ➕ Repos can add **extra workflows** (e.g., CI/CD) without removing global ones.

---

## 🚀 Contribution Guidelines

- 📌 Always test changes in a staging repo first.
- 🔄 Open a PR in `.github` for review.
- 🧪 Verify no unintended side effects (e.g., broken templates).

---

## 📞 Need Help?

Contact:

- 🛡️ DevOps Team: `Khalil M.` on Slack
- 🐞 Found a bug in a template? [Open an issue](https://github.com/your-org/.github/issues/new/choose)

---

## 🔗 Related

- [Contribution Guide](CONTRIBUTING.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
