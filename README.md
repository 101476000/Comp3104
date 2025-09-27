# COMP3104 – Exercise 04 

[![Build Status](https://app.travis-ci.com/101476000/Comp3104.svg?token=izhFLuAuGA5szi2JBVzz&branch=main)](https://app.travis-ci.com/101476000/Comp3104)

This repository contains the setup for **Exercise 04 – Configuring Travis CI**.

---

## Main Files
- `.travis.yml` – Travis CI configuration file.
- `.github/workflows/ci.yml` – GitHub Actions workflow (from previous exercise).
- `package.json` – npm configuration file (scripts, test).
- `build/index.html` – Test file for deployment.
- `hello.txt` – Placeholder file.

---

## Quick Steps (Windows PowerShell / Git Bash)
```powershell
# Clone the repository
git clone https://github.com/101476000/Comp3104.git
cd Comp3104

# Initialize npm and create package.json
npm init -y

# Edit package.json to configure the test script
# "test": "echo \"Warning: No tests created yet.\""

# Create build folder and index.html
mkdir build
cd build
echo "" > index.html
cd ..

# Add and push changes
git add .
git commit -m "Exercise 04: Travis config + build folder"
git push origin main

```