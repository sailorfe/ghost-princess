# Ghost Princess

a pink-tinged dark terminal theme inspired by ghost princess perona and her beloved kumashi

<div align="center">

![ghost princess](assets/bash.png)
![thriller bark](assets/op-thriller-bark.png)

</div>

| name           | hex     |
| -------------- | ------- |
| background     | #0e030b |
| foreground     | #fec8d5 |
| black          | #1c0817 |
| red            | #ed1d2f |
| green          | #d673d9 |
| yellow         | #ff5c74 |
| blue           | #8896c8 |
| magenta        | #ff72b3 |
| cyan           | #d5396a |
| white          | #ecc9ef |
| bright_black   | #2a0e25 |
| bright_red     | #ff4d4a |
| bright_green   | #f993fb |
| bright_yellow  | #ff7f92 |
| bright_blue    | #a8b6ea |
| bright_magenta | #ff94d4 |
| bright_cyan    | #fa5d88 |
| bright_white   | #f9e3fb |

## Installation

### WezTerm

```sh
git clone https://github.com/sailorfe/ghost-princess.git
cp ghost-princess/colors/ghost-princess.toml ~/.config/wezterm/themes
```

Then edit `wezterm.lua`:

```lua
config.local {
    color_scheme = "Ghost Princess"
}
```

### vim

```sh
git clone https://github.com/sailorfe/ghost-princess.git
cp ghost-princess/colors/ghost-princess.vim ~/.vim/colors
```
Open `.vim/colors/ghost-princess.vim` and `:source` it. Then in `.vim/vimrc`:

```vim
set background=dark
colorscheme ghost-princess
syntax on
```
