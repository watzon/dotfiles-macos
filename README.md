# macOS Dotfiles

This repository contains my personal dotfiles for macOS. I use chezmoi to manage my dotfiles, so I can easily update them.

## Installation

1. Install chezmoi

```shell
brew install chezmoi
```

2. Use chezmoi to install the dotfiles

```shell
chezmoi init git@github.com:watzon/macOS-dotfiles.git
```

3. Check what changes chezmoi will make to your home directory

```shell
chezmoi diff
```

4. Apply the changes

```shell
chezmoi apply
```

## What's included?

- zsh
  - oh-my-zsh
  - p10k
  - zinit
  - aliases
  - config
  - init
- nvim (astronvim)


