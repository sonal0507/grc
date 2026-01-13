# GRC Platform with JIRA Integration

## Quick Deploy to Railway

1. Push to GitHub:
```bash
cd sonal
git init
git add .
git commit -m "GRC Platform with JIRA integration"
git remote add origin https://github.com/yourusername/sonal.git
git push -u origin main
```

2. Deploy on Railway:
- Go to railway.app
- New Project → Deploy from GitHub
- Select your repository
- Start command: `node server.js`
- Deploy!

## Local Run
```bash
cd sonal
npm install
npm start
# Open http://localhost:3000
```

## JIRA Settings (Pre-configured)
- URL: https://oswalshobha31-1768193369440.atlassian.net
- Email: oswalshobha31@gmail.com
- Project: SCRUM
- API Token: Already configured

## Files
- server.js - Express server
- index.html - Main application
- jira-integration.js - JIRA integration
- package.json - Dependencies
