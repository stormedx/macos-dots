# My macOS dotfiles

This repo contains my macOS dotfiles configurations for primarily zshrc, yabai & skhd!

## Requirements

I'm managing my dotfiles using GNU Stow, it can be installed using

```
brew install stow
```

I'm also using the following:

zsh, yabai, skhd (more to come)

Afterwards, you can use GNU stow to create symlinks for the dotfiles


### Installation

First, it's probably a good call to rename files such as .zshrc to another name, that way GNU Stow doesn't create conflict issues.

copy the repository into your $HOME directory

```
git clone git@github.com/stormedx/macos-dots.git
cd dotfiles
```

Then use GNU stow to create symlinks

```
stow .
```
