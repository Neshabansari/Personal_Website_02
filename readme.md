## Portfolio Setup

This project is a cloned portfolio template. Update the following files with your own details before pushing it to GitHub:

1. `data/usersInfo.json` - name, bio, tagline, and GitHub username.
2. `data/socials.json` - your social links and email.
3. `data/projects.json` - your projects, screenshots, and repo links.
4. `public/CV/resume.pdf` - your resume file.

### Push To Your GitHub

After you replace the placeholder content, point `origin` to your own repository and push:

```bash
git remote set-url origin https://github.com/<your-username>/<your-repo>.git
git add .
git commit -m "Personalize portfolio"
git push -u origin main
```

If you want to deploy with `gh-pages`, run `npm run deploy` after the repo URL is updated.



