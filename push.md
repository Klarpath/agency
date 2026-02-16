# Deployment Instructions for https://github.com/Klarpath/agency

Run these commands in your terminal to deploy the latest version.

## 1. Configure Remote (Ensure correct target)
```bash
# Reset remote 'origin' to ensure it points to the correct repo
git remote remove origin
git remote add origin https://github.com/Klarpath/agency.git
git branch -M main
```

## 2. Stage and Commit
git add .
git commit -m "Update LinkedIn links and SEO configuration"
## 3. Push
git push -u origin main

