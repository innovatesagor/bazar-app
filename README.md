# Bazar Receipt Pro - Troubleshooting Guide

## Resolving Push Conflicts
If VS Code says "Can't push refs", run:
`git pull origin main --rebase && git push origin main`

## Fixing Billing Lock
- Ensure the repository is **Public**.
- Check [GitHub Billing Settings](https://github.com/settings/billing) for overdue balances.
- Once cleared, the 'Actions' tab will allow APK generation.

## Build Commands
- Local Sync: `npx cap sync android`
- Build APK: Managed automatically via `.github/workflows/build.yml`