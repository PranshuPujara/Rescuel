# Rescuel

Rescuel — landing page / frontend static site. Contains `index.html` with styles and assets.

How to push to remote:

1. Create a remote repository (GitHub, GitLab, etc.)
2. Add the remote and push:

```bash
git remote add origin <REMOTE_URL>
git branch -M main
git push -u origin main
```

Or, if you have the GitHub CLI authenticated:

```bash
gh repo create <repo-name> --public --source=. --remote=origin --push
```
