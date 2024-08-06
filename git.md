# Git 

## Commands
```
git config --list --show-origin | awk '{print $1}' | uniq
git config --list --show-origin
git pull --rebase
git log --oneline
git rebase --interactive HEAD~4
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

## GitLeaks
```
docker run -v ./:/path ghcr.io/gitleaks/gitleaks:latest detect --source="/path" --verbose
```

## Links
[Generating a new SSH key and adding it to the ssh-agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
