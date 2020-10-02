# dotfiles
Personal config files

To install:
```bash
git clone --bare <git-repo-url> $HOME/.cfg
alias config='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'
config checkout
```

https://www.atlassian.com/git/tutorials/dotfiles
