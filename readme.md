-- création du répertoire
git init
--
touch readme.md
--
git add *
git commit -m "first commit"
git remote add origin https://github.com/dbeauseigneur/gitquest.git
git push -u origin master

-- après modification du fichier readme.md

git add *
git commit -m "commit complet"
git push -u origin master

