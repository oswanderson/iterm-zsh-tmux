# Custom Terminal Setup

This is a guide to the setting of a custom terminal using iTerm, oh-my-zsh and tmux.

## iTerm2

**iTerm2** is an alternative to the default Mac (OS X) terminal interface. They both have the same goal, but different layout and colors scheme. If you do not use Mac, you don't need to install it.

In order to install iTerm, download it on the link https://www.iterm2.com/

## Oh-My-Zsh

**Oh-y-zsh** is a tool to manage your ZSH (a more robust version of sh) configuration.

Install oh-my-zsh using the tutorial on https://github.com/robbyrussell/oh-my-zsh

It can be done by using a `curl` or `wget` command. Super simple.

## PowerLevel10K

POWERLEVEL10K is a tool to customize your terminal interface using different colors themes, icons and characteres. In order to install it for oh-my-zsh, use the tutorial described on https://github.com/romkatv/powerlevel10k. Also pretty simple.

After install it, open the `.zshrc` file and alter the `ZSH_THEME` option to `ZSH_THEME="powerlevel10k/powerlevel10k"`.

## Wizard

Run the command `source $HOME/.zshrc` and a PowerLevel10K wizard will show in order to configure your terminal according to your preferences. Follow the instructions.

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
