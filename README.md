<div align="center">

# ghost princess

a pink-tinged dark theme inspired by ghost princess perona of thriller bark

![ghost princess](assets/bash.png)
![thriller bark](assets/op-thriller-bark.png)

</div>

## Palette

| name       | ansi                                                                | bright                                                                   |
| ---------- | ------------------------------------------------------------------ | ------------------------------------------------------------------ |
| background | ![#0e030b](https://placehold.co/15x15/0e030b/0e030b.png) `#0e030b` |                                                                    |
| foreground | ![#fec8d5](https://placehold.co/15x15/fec8d5/fec8d5.png) `#fec8d5` |                                                                    |
| black      | ![#160813](https://placehold.co/15x15/160813/160813.png) `#160813` | ![#271823](https://placehold.co/15x15/271823/271823.png) `#271823` |
| red        | ![#ed1d2f](https://placehold.co/15x15/ed1d2f/ed1d2f.png) `#ed1d2f` | ![#ff4d4a](https://placehold.co/15x15/ff4d4a/ff4d4a.png) `#ff4d4a` |
| green      | ![#d673d9](https://placehold.co/15x15/d673d9/d673d9.png) `#d673d9` | ![#f993fb](https://placehold.co/15x15/ff93fb/f993fb.png) `#f993fb` |
| yellow     | ![#ff5c74](https://placehold.co/15x15/ff5c74/ff5c74.png) `#ff5c74` | ![#ff7f92](https://placehold.co/15x15/ff7f92/ff7f92.png) `#ff7f92` |
| blue       | ![#8896c8](https://placehold.co/15x15/8896c8/8896c8.png) `#8896c8` | ![#a8b6ea](https://placehold.co/15x15/a8b6ea/a8b6ea.png) `#a8b6ea` |
| magenta    | ![#ff72b3](https://placehold.co/15x15/ff72b3/ff72b3.png) `#ff72b3` | ![#ff94d4](https://placehold.co/15x15/ff94d4/ff94d4.png) `#ff94d4` |
| cyan       | ![#d5396a](https://placehold.co/15x15/d5396a/d5396a.png) `#d5396a` | ![#fa5d88](https://placehold.co/15x15/fa5d88/fa5d88.png) `#fa5d88` |
| white      | ![#ecc9ef](https://placehold.co/15x15/ecc9ef/ecc9ef.png) `#ecc9ef` | ![#f9e3fb](https://placehold.co/15x15/f9e3fb/f9e3fb.png) `#f9e3fb` |

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

## Screenshots

<div align="center">
    
![lua in vim](assets/vim.png)

![spotify_player](assets/sp.png)

</div>
