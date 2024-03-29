# macos_init
Details what and how to install on the MacOs

## OhMyZsh
https://ohmyz.sh/#install
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### OhMyZsh Plugins
```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
git clone https://github.com/MichaelAquilina/zsh-you-should-use.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/you-should-use
git clone https://github.com/olivierverdier/zsh-git-prompt.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-git-prompt
git clone https://github.com/agpenton/1password-zsh-plugin.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/1password-zsh-plugin
git clone https://github.com/ascii-soup/zsh-url-highlighter.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-url-highlighter
git clone https://github.com/AndrewHaluza/zsh-update-plugin.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/update-plugin
```

#### zsh-autosuggestions
https://github.com/zsh-users/zsh-autosuggestions 
```
brew install zsh-autosuggestions
```

#### zsh-syntax-highlighting
https://github.com/zsh-users/zsh-syntax-highlighting
```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

#### zsh-git-prompt
https://github.com/olivierverdier/zsh-git-prompt
```
brew install zsh-git-prompt
```

#### zsh-you-should-use
https://github.com/MichaelAquilina/zsh-you-should-use
```
brew install zsh-you-should-use
```

### OhMyZsh Themes
- https://github.com/Powerlevel9k/powerlevel9k
- https://github.com/zthxxx/jovial
- https://github.com/halfo/lambda-mod-zsh-theme
- https://github.com/gantoreno/saturn-prompt
  ```
  curl -fsSL https://raw.githubusercontent.com/gantoreno/saturn-prompt/master/scripts/install.sh | zsh
  ```
- https://github.com/MrYazdan/zsh-linear-theme
  ```
  curl -o ~/.oh-my-zsh/themes/linear.zsh-theme https://raw.githubusercontent.com/MrYazdan/zsh-linear-theme/main/linear.zsh-theme
  ```
- https://github.com/Saleh7/igeek-zsh-theme
  ```
  curl -o ~/.oh-my-zsh/themes/igeek.zsh-theme https://raw.githubusercontent.com/Saleh7/igeek-zsh-theme/master/igeek.zsh-theme
  ```

## Good to have Apps
- pls - https://dhruvkb.github.io/pls
- Clockify - https://clockify.me/ - https://clockify.me/downloads/ClockifyDesktop.zip
- TickTick - https://ticktick.com/about/download - https://ticktick.com/static/getApp/download?type=mac
- itsycal - https://www.mowglii.com/itsycal/
- 1Password - https://1password.com/downloads/mac/
- Brave Browser - https://brave.com/download/
- Visual Studio Code - https://code.visualstudio.com/download
- gr - http://mixu.net/gr/ - https://github.com/mixu/gr
  ```
  gr @work bash -c  "git checkout master ; git checkout main"
  ```
  
- trailer - https://ptsochantaris.github.io/trailer/
- DBeaver - https://dbeaver.io/download/
- Rectangle - https://github.com/rxhanson/Rectangle
- Guidde - https://www.guidde.com
- Yippy - https://yippy.mattdavo.com/

## Good to Know
### DevOps
- https://github.com/coroot/coroot

## Maven
- https://blog.frankel.ch/faster-maven-builds/1/
