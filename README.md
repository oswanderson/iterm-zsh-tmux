# Custom Terminal Settup

This is a guide to the setting of a custom terminal using iTerm, oh-my-zsh and tmux.

## iTerm

**iTerm** is an alternative to the default Mac (OS X) terminal interface. They both have the same goal, but different layout and colors scheme. If you do not use Mac, you don't need to install it.

In order to install iTerm, download it on the link https://www.iterm2.com/

## Oh-My-Zsh

**Oh-y-zsh** is tool to customize your terminal interface using different colors themes and caracteres.

Install oh-my-zsh using the tutorial on https://github.com/robbyrussell/oh-my-zsh

It's made using a `curl` or `wget` command. Super simple.

## PowerLevel9K

POWERLEVEL9K is a terminal theme. In order to install it for oh-my-zsh, run the command `git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k`

After install it, open the `.zshrc` file and alter the `ZSH_THEME` option to `ZSH_THEME="powerlevel9k/powerlevel9k"`.

## Powerline Fonts

Powerline is a package of fonts used by **POWERLEVEL9K** theme. Install the fonts using the tutorial on https://github.com/powerline/fonts

## Text Fonts

After all this proccess, on Mac OS, open iTerm (or you terminal) and alter you terminal fonts to `Meslo LG M DZ Regular for Powerline` and set the **Non-ASCII Font** to the same.

## Solarized Dark

**Solaraized Dark** is a color theme available for Mac OS. In order to use it, open iTerm preferences and, in **Profiles**, in **Color**, alter your Color Presets to **__Solarized Dark__**.

If you are using Linux, check the options for you terminal and choose one of your choice.

## Tmux

**tmux** is a terminal tool to manage sessions and screens using only your keyboard.

To install it, use the commands according to you OS.

Linux Mint or Ubuntu: `sudo apt-get update && sudo apt-get install tmux`

Mac (OS X): `brew install tmux`

Two good beginner guides for tmux:

https://hackernoon.com/a-gentle-introduction-to-tmux-8d784c404340

https://www.hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/
