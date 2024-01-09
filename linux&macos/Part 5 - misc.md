# Misc

Here are some plugin to make your terminal more beautiful or efficient.

## Preference

Here I only include settings for `iTerm2`. You can use `cmd+,` to open your preference setting. Click profile and change the background and opacity here.

## Ranger

See [official repo](https://github.com/ranger/ranger)

## lsd

`ls` command with logo.

See [official repo](https://github.com/lsd-rs/lsd)

Add following command to your `.zshrc` to replace `ls` and `tree` command.

```bash
alias ls='lsd --group-dirs first'
alias tree='lsd --tree'
```

See outcome by typing `ls`.

![demo_lsd](../pic/lsd.png)

## bat

See [official repo](https://github.com/sharkdp/bat)

Add following command to your `.zshrc` to replace `cat` and `less` command.

```bash
alias bat='bat --theme=ansi'
alias cat='bat --pager=never'
alias less='bat'
```

See outcome by typing `bat`.

![demo_bat](../pic/bat.png)

## neofetch

As a convention, after you beautified your terminal, you should post a picture of `neofetch`. You can use your package manager to install it.

![demo_neofetch](../pic/demo.png)
