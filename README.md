Meu sistema git
git commit -m "Hard apaga alterações e volta para a versão anterior,solf permite fazer alterações para reenviar os commits"
diff ve oq foi alterado------------git diff README.md=seleciona o arquivo que quer vizualizar
git diff --name-only mostra o arquivo/pasta modificado
git checkeout HEAD -- style.css = volta um arquivo especifico


-------------------------------------------main=master------------------------------------------------
echo "# modulogit" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/andrejobbs/modulogit.git
git push -u origin main



git remote add origin https://github.com/andrejobbs/modulogit.git
git branch -M main
git push -u origin main


git push origin :teste =remove o branch q foi adicionado no Github
git revert --no-edit= reverte o ultimo commit 