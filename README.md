# moderno-zsh
A modern ZSH theme inspired by the robbyrussell's Oh-my-zsh theme

## Installation  
### For [antigen](https://github.com/zsh-users/antigen) users
1. Add `antigen bundle tylerreckart/hyperzsh` to your `.zshrc`. Antigen will clone and load the hyperzsh repository automaticall the next time you start a zsh session.  

### For [oh-my-zsh](http://ohmyz.sh) users  
If you're using oh-my-zsh, follow these steps to install hyperzsh:  
1. `mkdir $ZSH_CUSTOM/themes` _You can skip this command if the directory exists already_
2. `wget -O $ZSH_CUSTOM/themes/hyperzsh.zsh-theme https://raw.githubusercontent.com/obrassard/moderno-zsh/master/moderno.zsh-theme`  
3. `vim ~/.zshrc`  
4. Set `ZSH_THEME="current_theme"` to `ZSH_THEME="moderno"`  

### For [Zgen](https://github.com/tarjoilija/zgen) users
1. Add `zgen load tylerreckart/hyperzsh` to your `.zshrc` with your other `zgen load` statements.  
`zgen save` and zgen will automaticall handle cloning the repository for you.  
