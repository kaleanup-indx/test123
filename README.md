echo "# test123" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:kaleanup-indx/test123.git
git push -u origin main
