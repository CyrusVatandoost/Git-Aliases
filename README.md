# Git-Aliases

- alias.co=checkout
- alias.br=branch
- alias.ci=commit
- alias.st=status
- alias.publish=!git push -u origin $(git rev-parse --abbrev-ref HEAD)
- alias.unstage=reset HEAD --
- alias.ac=!git add . && git commit -m
- alias.l=log --all --pretty=format:'%C(yellow)%h%C(cyan)%d%Creset %s %C(white)- %an, %ar%Creset'
