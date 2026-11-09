# my-project
git remote set-url origin https://github.com/romanov48/my-project.git
git init
git add .
git commit -m "Первый коммит"
git branch -M main
gh auth login
gh repo create my-project --public --source=. --remote=origin --push
git init
git add .
git commit -m "Первый коммит"
git branch -M main
git remote remove origin 2>/dev/null
git remote add origin https://github.com/romanov48/my-project.git
git push -u origin main
