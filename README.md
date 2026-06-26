# 1. Initialize a fresh local repository
git init

# 2. Add the specific remote URL
git remote add origin https://github.com/marymicy/Pdf-Query-with-Astra-DB.git

# 3. Force push to overwrite all previous files on GitHub
git branch -M main
git push -u origin main --force
