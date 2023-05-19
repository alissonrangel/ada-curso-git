# Curso Digital: Git e Github

## Estados do Git

- untracked
- unmodified (já está rastreado pelo git)
- modified

## salvando modificações no git

- git diff // para verificar se no estágio modified
- git diff --staged // para verificar após o add
- git commit -m "add subitem"

## git log e git restore
- git log
- na área de Modified: git restore <name> // retorna o arquivo para antes de ser alterado - Unmodified
- na área de Staged: git restore --staged <name> // retorna para área de Modified
  
## git push
- git remote
- git push origin master
- git pull
- git fetch // para verificar quais as modificações foram feitas antes de fazer um pull
  - git diff origin/main
