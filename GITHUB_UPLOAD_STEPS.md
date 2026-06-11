# GitHub Upload Steps

## Option 1 — Upload from browser

1. Create a new GitHub repository called `ai-automation-projects`.
2. Click **Add file → Upload files**.
3. Drag the folders and files from this ZIP.
4. Commit with: `Initial AI automation portfolio`.

## Option 2 — Upload with Git

```bash
git init
git add .
git commit -m "Initial AI automation portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/ai-automation-projects.git
git push -u origin main
```

## Before publishing

- Replace placeholder emails, Slack channels, Google Sheet IDs and API keys.
- Never commit real API keys.
- Add screenshots from your real n8n canvas later if you want stronger proof.
