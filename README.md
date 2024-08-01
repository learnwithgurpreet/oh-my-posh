# Oh my posh

## Install

```
brew install oh-my-posh
```

## Call oh-my-posh in zsh

```
# ~./zshrc

eval "$(oh-my-posh init zsh)"
```

## Make a copy of existing configuration

```
oh-my-posh config export --format toml --output ~/.config/ohmyposh/zen.toml
```

It will create a copy of existing configuration file, now we need to make changes and point the file to oh-my-posh configuration

```
# ~./zshrc

eval "$(oh-my-posh init zsh --config $HOME/.config/ohmyposh/zen.toml)"
```

## Auto Suggestions

```
$ brew install zsh-autosuggestions

# Add following to ~./zshrc

source $(brew --prefix)/share/zsh-autosuggestions/zsh-autosuggestions.zsh
```
