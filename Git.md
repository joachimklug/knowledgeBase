# Git 

## Commands
```
git config --list --show-origin | awk '{print $1}' | uniq
git config --list --show-origin
git pull --rebase
```

## Alias
```
[alias]
        cm = checkout master
        ac = !git add -A && git commit -m
        pf = !git push --force-with-lease
        p = push
        aa = !git add -A && git commit -a --amend --no-edit && git push --force-with-lease
        c = checkout
        b = branch
        pm = !git checkout master && git pull
```
## Links
[Generating a new SSH key and adding it to the ssh-agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
