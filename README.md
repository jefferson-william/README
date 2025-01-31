# jeffersonwilliammachado

## Software

- [Google Chrome](https://www.google.com/chrome/)
- [Google Chrome Canary](https://www.google.com/chrome/canary/)
- [Visual Studio Code](https://code.visualstudio.com/docs/?dv=osx)
- [JetBrains Toolbox App](https://www.jetbrains.com/toolbox-app/download/download-thanks.html?platform=mac)
- [Docker](https://docs.docker.com/desktop/setup/install/mac-install/)

## terminal

- Brew
- Bun
- nvm
- Zsh
- Zap (zsh plugins manager)

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

curl -fsSL https://bun.sh/install | bash

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

zsh <(curl -s https://raw.githubusercontent.com/zap-zsh/zap/master/install.zsh) --branch release-v1

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.1/install.sh | bash

curl -sS https://starship.rs/install.sh | sh

code ~/.zshrc
```

```sh
# ~/.zshrc

# Created by Zap installer
[ -f "${XDG_DATA_HOME:-$HOME/.local/share}/zap/zap.zsh" ] && source "${XDG_DATA_HOME:-$HOME/.local/share}/zap/zap.zsh"

plug "zap-zsh/supercharge"
plug "zsh-users/zsh-autosuggestions"
plug "zsh-users/zsh-syntax-highlighting" "122dc46"
plug "zap-zsh/zap-prompt"
plug "esc/conda-zsh-completion"
plug "zap-zsh/nvm"

# Load and initialise completion system
autoload -Uz compinit
compinit
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"
```