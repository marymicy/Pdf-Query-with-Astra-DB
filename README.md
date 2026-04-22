# 1. Initialize a fresh local repository
git init

# 2. Add the specific remote URL
git remote add origin https://github.com/marymicy/Pdf-Query-with-Astra-DB.git

# 3. Force pull the professional README first to keep documentation consistent
git pull origin main

# 4. Add your new PDF_QUERY.py script
git add PDF_QUERY.py

# 5. Commit the new architecture
git commit -m "Complete repository reset: Implementing PDF Query system with Astra DB and LangChain"

# 6. Force push to overwrite all previous files on GitHub
git branch -M main
git push -u origin main --force
