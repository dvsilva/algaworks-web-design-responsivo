# algaworks-web-design-responsivo

github commands

```bash
git checkout -b 07-09-adicionando-rotulo-no-plano
git add .
git commit -m "Adicionando rótulo no plano"
git push origin 07-09-adicionando-rotulo-no-plano

git checkout master
git merge --no-ff 07-09-adicionando-rotulo-no-plano
git push

sair da tela de merge
aperte "ESC" depois digite ":wq"
configure other merge tool
git config --global core.editor "'C:/Program Files/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"

// delete branch locally
git branch -d localBranchName

// delete branch remotely
git push origin --delete remoteBranchName
```
