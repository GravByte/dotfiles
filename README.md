 # dotfiles
This repo contains the dotfiles configs for setting up  my personal linux machines.

This is using Chezmoi, the dotfile manager to setup the install.

#How to run
`export GITHUB_USERNAME=gravbyte`
`sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply $GITHUB_USERNAME`
