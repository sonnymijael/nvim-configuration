# nvim from mac and linux with lazy-vim 🤖

Personal configuration of nvim for mac with lazy-vim

## Deployment

Create a backup of our current nvim directory

```bash
cd && mv mv ./config/nvim{,.back}
```

Clone the starter

```bash
git clone url ~/.config/nvim
```

Remove the .git folder

```bash
rm -rf ~/.config/nvim/.git
```

Start Neovim!

```bash
nvim
```

## Extras

Open nvim with vim command

```bash
sudo ln -s $(which nvim) /usr/local/bin/vim
```

In Bash:

```bash
source ~/.bashrc
```

In Zsh:

```bash
source ~/.zshrc
```

Start Neovim!

```bash
vim
```

## Acknowledgements

- [Lazyvim](https://www.lazyvim.org/)

## Authors

- [@sonnymijael](https://www.github.com/sonnymijael)
