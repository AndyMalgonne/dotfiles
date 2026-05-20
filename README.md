# dotfiles

install config on new machines: 

public machine:
curl https://mise.run | sh
mise use --global chezmoi@
chezmoi init --apply https://github.com/AndyMalgonne/dotfiles.git

private machine: 
curl https://mise.run | sh
mise use --global chezmoi@
chezmoi init --apply git@github.com:AndyMalgonne/dotfiles.git
