# hello
мой первый репозиторий
git clone https://github.com/user/my-project.git
cd my-project
echo "# Hello GitHub" > README.md
git add README.md
git commit -m "docs: add initial readme"
git push origin main
git switch -c feature/auth
# правим код, коммитим...
git switch main
git merge feature/auth
# если конфликт → открываем файл, правим маркеры <<<< === >>>>, git add + git commit
