echo "# github" >> README.md
git init
git add README.md
git commit -m "second commit"
git branch -M main
git remote add origin https://github.com/github/github.git
git push -u origin main
