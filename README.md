# CentenV's `zsh` Config


## Installation

Clone this into a discrete directory and create a hardlink to it via the `ln` command.

```shell
git clone git@github.com:centenv-config/zshrcenten.git
ln <path-to-dir>/.zshrc ~/.zshrc
```

## Setup + Dependencies
This *zsh* setup is dependent on *oh-my-zsh* which can be installed with:

```shell
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

The `fastfetch` command is used to display the system information at the start of every zsh session.

See `fastfetch` [Installation Instructions](https://github.com/fastfetch-cli/fastfetch?tab=readme-ov-file#installation)


## Plugins
zsh-autosuggestions: Used for inline command suggestions based on command history
```shell
git clone https://github.com/zsh-users/zsh-autosuggestions $HOME/.zsh/zsh-autosuggestions
```
zsh-autocompletion: Fish-like autocomplete menu (currently disabled since it can be annoying)
```shell
git clone --depth 1 https://github.com/marlonrichert/zsh-autocomplete.git $HOME/.zsh/zsh-autocompletion
```
