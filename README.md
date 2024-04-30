# Initial Device Setup (MacOS)

My setup preferences for development

## Development App
1. Homebrew https://brew.sh/
2. Oh My Zsh https://ohmyz.sh/
3. VM https://mac.getutm.app/
4. VSCode https://formulae.brew.sh/cask/visual-studio-code
5. Postman https://formulae.brew.sh/cask/postman
6. NetBird VPN https://docs.netbird.io/how-to/installation#mac-os

## General App
1. Rectangle https://formulae.brew.sh/cask/rectangle
2. Stats https://formulae.brew.sh/cask/stats
3. Pomodoro Timer https://formulae.brew.sh/cask/tomatobar
4. AltTab https://alt-tab-macos.netlify.app/
5. Telegram https://formulae.brew.sh/cask/telegram
6. Zoom https://formulae.brew.sh/cask/zoom
7. Spotify https://formulae.brew.sh/cask/spotify

### Oh My Zsh
1. Fonts https://github.com/tonsky/FiraCode
2. Powerlevel10k https://github.com/romkatv/powerlevel10k?tab=readme-ov-file#homebrew
3. Plugins
    - https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md
    - https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md
    - https://github.com/zsh-users/zsh-history-substring-search
    - https://github.com/junegunn/fzf?tab=readme-ov-file#using-homebrew

### Visual Studio Code
1. Fonts https://github.com/tonsky/FiraCode/wiki/VS-Code-Instructions
2. Import settings.json from GitHub

## Dev Environment

### Snippet
- Various git shortcut
    ```
    alias gs='git status'
    alias ga='git add'
    alias gpl='git pull origin "$(git rev-parse --abbrev-ref HEAD)"'
    alias gps='git pull origin "$(git rev-parse --abbrev-ref HEAD)"'
    ```


### SSH
https://docs.gitlab.com/ee/user/ssh.html

### Node/JS/TS
NVM https://github.com/nvm-sh/nvm?tab=readme-ov-file#installing-and-updating

### Rust
RSVM https://github.com/sdepold/rsvm?tab=readme-ov-file#rsvm

### Go
GVM https://github.com/moovweb/gvm?tab=readme-ov-file#installing (notes: [1](https://github.com/moovweb/gvm?tab=readme-ov-file#to-install-go-120) [2](https://github.com/moovweb/gvm/issues/385#issuecomment-1030190550))
