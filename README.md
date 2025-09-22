# COMP3104 – Exercise 03 Starter

This starter gives you a minimal repository structure so you can complete Exercise 03 quickly using **GitHub Actions** (no credit card needed).

## Files
- `.github/workflows/ci.yml` – Minimal CI workflow that runs on every push.
- `.travis.yml` – Placeholder if you decide to activate Travis CI instead.
- `hello.txt` – Just a placeholder file so the repo isn't empty.

## Quick Steps (Windows PowerShell)
```powershell
# From inside your local clone of https://github.com/101476000/Comp3104
Copy-Item -Recurse -Force .\comp3104_ex03_starter\* .

git add .
git commit -m "Exercise 03: add CI workflow and placeholders"
git push origin main   # or 'master' if that's your default
```

## What to screenshot
- **S1.jpg** – Your terminal showing the `git add`, `git commit`, and `git push` commands.
- **S2.jpg** – The commit list page on GitHub showing your commit.
- **S3.jpg** – The **Actions** tab with the CI run **(or)** your TravisCI dashboard, **and** your Azure for Students account page.
```