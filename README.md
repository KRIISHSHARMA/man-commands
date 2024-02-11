# Search and View manual for all commands
```sh
compgen -c | fzf | xargs man
```
- or creat an alias for the same
```sh
alias <name>="compgen -c | fzf | xargs man"
```
- to make to available on new terminal sessions
``` sh
nvim ~/.zshrc
```

![image](https://github.com/KRIISHSHARMA/man-commands/assets/86760658/c0da7753-f947-4ed3-ad76-043ca0bcfad1)


# install fzf [command-line fuzzy finder](https://github.com/junegunn/fzf?tab=readme-ov-file#installation)
``` sh
sudo apt install fzf
```
- or using git
```sh
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
~/.fzf/install
```

# xargs 
- It converts input from standard input into arguments to a command.
- for more ` man xargs `

# [compgen -c](https://unix.stackexchange.com/a/151120)
- check link 
