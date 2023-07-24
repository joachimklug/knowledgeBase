# Git 

## Commands
```
git config --list --show-origin | awk '{print $1}' | uniq
git config --list --show-origin
```

## Alias
```
alias.cm=checkout master
alias.ac=!git add -A && git commit -m
alias.pf=!git push --force-with-lease
alias.p=push
alias.aa=!git add -A && git commit -a --amend --no-edit && git push --force-with-lease
alias.c=checkout
alias.b=branch
alias.pm=!git checkout master && git pull
```
