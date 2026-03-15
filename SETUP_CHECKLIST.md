# Deployment Setup Checklist

- Platform: **Vercel** (`vercel`)
- Auth method: **TOKEN**
## GitHub Secrets to Add

Add the following secrets at: **Settings > Secrets and variables > Actions**

- [ ] SLACK_WEBHOOK_URL
- [ ] VERCEL_ORG_ID
- [ ] VERCEL_PROJECT_ID
- [ ] VERCEL_TOKEN
## First-Run Reminder- Confirm all secrets are set before dispatching the first workflow run.- Re-run this checklist whenever workflow secret references change.