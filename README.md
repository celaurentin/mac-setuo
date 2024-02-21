# MAC SETUP
## a list of tools / references

* Homebrew
    * /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
* brew install --cask iterm2
* brew install git
* brew install git-flow
* brew install zsh
  * sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
  * nano ~/.zshrc
  * source ~/.zshrc
* zsh autosuggestions
  * git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
  * https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh
* zsh highlighting
  * https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md
* brew install ammonite-repl
* brew install nvm
* brew install pre-commit
* brew install --cask openlens
* sdkman
  * curl -s "https://get.sdkman.io" | bash
  * source "$HOME/.sdkman/bin/sdkman-init.sh"
  * sdk version
  * sdk current
  * sdk list java
  * sdk install 8.322.06.1-amzn
  * sdk install sbt
* xcode-select --install
* brew install tree
* brew install --cask sublime-text
* brew install --cask visual-studio-code
  * https://code.visualstudio.com/docs/setup/mac#_launching-from-the-command-line
