<h1 align="center">
citruszest.nvim

<a href="https://www.gnu.org/licenses/gpl-3.0.en.html" rel="nofollow"><img alt="MIT" src="https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge" style="max-width: 100%;"></a>
<a href="https://www.lua.org/"><img alt="Lua" src="https://img.shields.io/badge/Lua-blue.svg?style=for-the-badge&logo=lua" style="max-width:100%"></a>

</h1>

<p align="center">
<b>citruszest.nvim</b> features a combination of bright and juicy colors reminiscent of various citrus fruits. The primary colors include vibrant oranges, zesty yellows, and refreshing greens. These colors are carefully selected to provide a visually stimulating and attention-grabbing experience while coding.
</p>

## :fire: Showcase

![Screenshot_2023-07-02-03-23-01_1920x1080](https://github.com/zootedb0t/citruszest.nvim/assets/62596687/ad44cfa5-a49c-4ff0-9d0f-e1c5bd236ee5)

![Screenshot_2023-07-02-03-21-52_1920x1080](https://github.com/zootedb0t/citruszest.nvim/assets/62596687/062f285e-1034-4ddb-87d7-7e91b1c58eaf)

## :wrench: Installation

[lazy.nvim](https://github.com/folke/lazy.nvim)

```lua
{
  "zootedb0t/citruszest.nvim",
  lazy = false,
  priority = 1000,
},
```

[packer.nvim](https://github.com/wbthomason/packer.nvim)

```lua
use { "zootedb0t/citruszest.nvim" }
```

[vim-plug](https://github.com/junegunn/vim-plug)

```viml
Plug 'zootedb0t/citruszest.nvim'
```

## :question: Usage

Enable `colorscheme` after installation.

In `init.lua`

```lua
vim.cmd("colorscheme citruszest")
```

In `init.vim`

```viml
colorscheme citruszest
```

## Configration

To know `highlight` group of word under cursor. Use `Inspect` command.

```lua
    -- For using default config leave this empty.
    require("citruszest").setup({
        transparent = true, -- Enable/Disable transparency
        -- Override default style in this table
        -- E.g If you want to override `Constant` highlight style
        style = {
        -- This will change Constant foreground color and make it bold.
        Constant = { fg = "#FFFFFF", bold = true}
        },
    })
```

## :pushpin: Supported Plugins

- [nvim-cmp](https://github.com/hrsh7th/nvim-cmp)
- [Telescope](https://github.com/nvim-telescope/telescope.nvim)
- [Nvimtree](https://github.com/nvim-tree/nvim-tree.lua)
- [nvim-ts-rainbow2](https://gitlab.com/HiPhish/nvim-ts-rainbow2)
- [fidget.nvim](https://github.com/j-hui/fidget.nvim)
- [gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim)
- [alpha.nvim](https://github.com/goolord/alpha-nvim)
- [whichkey.nvim](https://github.com/folke/which-key.nvim)

## :pray: Acknowledgments

- [SpaceCamp](https://github.com/jaredgorski/SpaceCamp) - For inspiring me write my own colorscheme.
- [FluoroMachine.nvim](https://github.com/maxmx03/FluoroMachine.nvim) - For the beautiful colorscheme.

<div align="center">
    <h4>
    Made in Neovim with 💕 For Neovim
    </h4>
</div>
