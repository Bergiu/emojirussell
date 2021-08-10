# Emojirussell
Emojirussell is a fork of the [robbyrussell oh-my-zsh theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme), with more emojis.

Replaced arrow of exit status of the last executed command with emojis.

Features:
- Display last return code as emoji (0=😀; not 0=😡)
- Show current working directory name
- Show git branch
- Show if git status contains changes with an ✗

How to install

- Download the theme into oh-my-zsh's custom themes directory: `$ mkdir -p $ZSH_CUSTOM/themes && curl https://raw.github.com/Bergiu/emojirussell/master/emojirussell.zsh-theme -o $ZSH_CUSTOM/themes/gitsome.zsh-theme`
- Set the theme in your `.zshrc` file: `ZSH_THEME="emojirussell"`
