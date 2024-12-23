# Zsh
- Install `zsh` and `zsh-autosuggestions` via apt
- Then install ohmyzsh (look on official website):
> `sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
- Git plugin should already be installed
- Get the zsh-autosuggestions plugin (clone as it is a custom plugin):
> `git clone git@github.com:zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh_autosuggestions`
- Fix the way directories are displayed in terminal like so ... https://stackoverflow.com/questions/27885057/zsh-theme-for-full-path-display-git-changes#:~:text=To%20get%20the%20full%20path,with%20%25d%20in%20the%20PROMPT%20:
> `echo $ZSH_THEME`\
> `cp $ZSH/themes/robbyrussell.zsh-theme $ZSH_CUSTOM/themes/`\
> `vim $ZSH_CUSTOM/themes/robbyrussell.zsh-theme`\
> Modify PROMPT key, replace `%c%` with `%~%`.\
- Restart for default terminal to change

