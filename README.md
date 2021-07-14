# proddy-hacks
Dot files for various tools to create the illusion of productivity. JK, it helps you with ADHD.

*Do you lose track of which k8s context you are in? Which directory were you in again?
This repo was made with the intention to add dotfiles for various CLI tools to make us spend slightly less time in remebering contexts and more in remembering birthdays, anniversaries of fellow humans. Or cats. Or dogs.*

Currently the dotfile(s) are for: 
1. Starship (a nice command prompt customizer, written in Rust).

## Steps to setup:

1. Follow the simple [installation.](https://starship.rs/guide/#%F0%9F%9A%80-installation)
2. Clone this repo.
3. Run the following command from the location where you cloned the repo:
```zsh
mkdir -p ~/.config && cp starship-config/starship.toml ~/.config/
```
4. That's all !

## Currently configured prompt configs :

*Starship*:

    1. Kubernetes context and namespace
    2. Directory
    3. Currently checked out git branch
    4. Current gcloud project


### TO DO:

Creating a script to automate this setup.
Adding dotfiles for more tools:
1. oh-myzsh/zshrc

Till then, enjoy!



