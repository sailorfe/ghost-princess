# Ghost Princess

a pink-tinged dark terminal theme inspired by ghost princess perona and her beloved kumashi

<div align="center">

![ghost princess](assets/bash.png)
![thriller bark](assets/op-thriller-bark.png)

</div>

| name           | hex                                                                |
| -------------- | ------------------------------------------------------------------ |
| background     | ![#0e030b](https://placehold.co/15x15/0e030b/0e030b.png) `#fec8d5` |
| foreground     | ![#fec8d5](https://placehold.co/15x15/fec8d5/fec8d5.png) `#fec8d5` |
| black          | ![#1c0817](https://placehold.co/15x15/1c0817/1c0817.png) `#1c0817` |
| red            | ![#ed1d2f](https://placehold.co/15x15/ed1d2f/ed1d2f.png) `#ed1d2f` |
| green          | ![#d673d9](https://placehold.co/15x15/d673d9/d673d9.png) `#d673d9` |
| yellow         | ![#ff5c74](https://placehold.co/15x15/ff5c74/ff5c74.png) `#ff5c74` |
| blue           | ![#8896c8](https://placehold.co/15x15/8896c8/8896c8.png) `#8896c8` |
| magenta        | ![#ff72b3](https://placehold.co/15x15/ff72b3/ff72b3.png) `#ff72b3` |
| cyan           | ![#d5396a](https://placehold.co/15x15/d5396a/d5396a.png) `#d5396a` |
| white          | ![#ecc9ef](https://placehold.co/15x15/ecc9ef/ecc9ef.png) `#ecc9ef` |
| bright_black   | ![#2a0e25](https://placehold.co/15x15/2a0e25/2a0e25.png) `#2a0e25` |
| bright_red     | ![#ff4d4a](https://placehold.co/15x15/ff4d4a/ff4d4a.png) `#ff4d4a` |
| bright_green   | ![#f993fb](https://placehold.co/15x15/ff93fb/f993fb.png) `#f993fb` |
| bright_yellow  | ![#ff7f92](https://placehold.co/15x15/ff7f92/ff7f92.png) `#ff7f92` |
| bright_blue    | ![#a8b6ea](https://placehold.co/15x15/a8b6ea/a8b6ea.png) `#a8b6ea` |
| bright_magenta | ![#ff94d4](https://placehold.co/15x15/ff94d4/ff94d4.png) `#ff94d4` |
| bright_cyan    | ![#fa5d88](https://placehold.co/15x15/fa5d88/fa5d88.png) `#fa5d88` |
| bright_white   | ![#f9e3fb](https://placehold.co/15x15/f9e3fb/f9e3fb.png) `#f9e3fb` |
|                |                                                                    |


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
