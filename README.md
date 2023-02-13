# My Dev Environment Files 🚀
**IMPORTANT:** These are primarily meant for inspiration. I wouldn't just blindly use them. Proceed at your own risk!

📹 Youtube Playlist With Detailed Walkthroughs on My Setup: [💻 My Dev Environment & Workflow](https://youtube.com/playlist?list=PLnu5gT9QrFg36OehOdECFvxFFeMHhb_07)

# Terminal Setup
✍🏼 Blog Post Step-by-Step Guide: [How To Setup Your Mac Terminal](https://josean.com/posts/terminal-setup)

📹 Youtube Guide: [How To Make Your Boring Mac Terminal So Much Better](https://www.youtube.com/watch?v=CF1tMjvHDRA&list=PLnu5gT9QrFg36OehOdECFvxFFeMHhb_07&index=2&t=479s)

### Relevant Files
- [.zshrc](.zshrc) - Zsh Shell Configuration
- [coolnight.itermcolors](coolnight.itermcolors) - iTerm2 Color Scheme

# Tmux Setup
✍🏼 Blog Post: [How To Use and Configure Tmux Alongside Neovim](https://josean.com/posts/tmux-setup)

📹 Youtube Guide: [How I Setup And Use Tmux Alongside Neovim for an Awesome Dev Workflow](https://youtu.be/U-omALWIBos)

### Relevant Files
- [.tmux.conf](.tmux.conf) - Tmux Configuration File

# Yabai Tiling Window Manager Setup
✍🏼 Blog Post: [How To Setup And Use The Yabai Tiling Window Manager On Mac](https://josean.com/posts/yabai-setup)

📹 Youtube Guide: [How To Setup And Use The Yabai Tiling Window Manager On Mac](https://youtu.be/k94qImbFKWE)

### Relevant Files
- [.config/yabai/yabairc](.config/yabai/yabairc)
- [.config/skhd/skhdrc](.config/skhd/skhdrc)

# Neovim Setup
💡 **Tip:** I highly recommend following along with me on youtube and use the repo as reference to set up the config. You'll understand everything a lot better and be able to change things and evolve the setup into your own!

*If you clone the repo into your machine and use the config by copying .config/nvim to your home folder, you'll have to restart neovim after the plugins install. After restart, if you are opening a lua file or another file I have language servers configured for, like html, css or javascript/typescript, you might also get an error saying that the server failed to start. This is because Mason hasn't installed it yet. Press enter to continue, Mason will automatically install it.*

📹 Youtube Step-by-Step Guide: [How I Setup Neovim On My Mac To Make It Amazing](https://youtu.be/vdn_pKJUda8)

### Relevant Files
- [.config/nvim](.config/nvim)

### Setup Requires
- True Color Terminal Like: [iTerm2](https://iterm2.com/)
- [Neovim](https://neovim.io/) (Version 0.8 or Later)
- [Nerd Font](https://www.nerdfonts.com/) - I use Meslo Nerd Font
- [Ripgrep](https://github.com/BurntSushi/ripgrep) - For Telescope Fuzzy Finder
- XCode Command Line Tools
- If working with typescript/javascript and the typescript language server like me. You might need to install node.

If you're on mac, like me, you can install iTerm2, Neovim, Ripgrep and Node with homebrew.
```bash
brew install --cask iterm2
```
```bash
brew install neovim
```
```bash
brew install ripgrep
```
```bash
brew install node
```

For XCode Command Line Tools do:
```bash
xcode-select --install
```

### Nvim-Treesitter Updates
When nvim-treesitter updates, there might be breaking changes to corresponding parsers being used. I made a change to make sure parsers are automatically updated whenever nvim-treesitter is installed/updated. The code is found in this file: [plugins-setup.lua](.config/nvim/lua/josean/plugins-setup.lua)

The updated code is this:
```lua
use({
    "nvim-treesitter/nvim-treesitter",
    run = function()
      local ts_update = require("nvim-treesitter.install").update({ with_sync = true })
      ts_update()
    end,
  })

```

## Plugins
#### Plugin Manager
- [wbthomason/packer](https://github.com/wbthomason/packer.nvim) - Popular plugin manager

#### Dependency For Other Plugins
- [nvim-lua/plenary](https://github.com/nvim-lua/plenary.nvim) - Useful lua functions other plugins use

#### Preferred Colorscheme
- [bluz71/vim-nightfly-guicolors](https://github.com/bluz71/vim-nightfly-guicolors)

#### Navigating Between Neovim Windows and Tmux
- [christoomey/vim-tmux-navigator](https://github.com/christoomey/vim-tmux-navigator)

#### Essentials
- [tpope/vim-surround](https://github.com/tpope/vim-surround) - manipulate surroundings with "ys", "ds", and "cs"
- [vim-scripts/ReplaceWithRegister](https://github.com/vim-scripts/ReplaceWithRegister) - replace things with register with "gr"
- [numToStr/Comment.nvim](https://github.com/numToStr/Comment.nvim) - toggle comments with "gc"

#### File Explorer
- [nvim-tree/nvim-tree.lua](https://github.com/nvim-tree/nvim-tree.lua)

#### VS Code Like Icons
- [kyazdani42/nvim-web-devicons](https://github.com/kyazdani42/nvim-web-devicons)

#### Status Line
- [nvim-lualine/lualine.nvim](https://github.com/nvim-lualine/lualine.nvim)

#### Fuzzy Finder
- [nvim-telescope/telescope-fzf-native.nvim](https://github.com/nvim-telescope/telescope-fzf-native.nvim) - Dependency for better performance
- [nvim-telescope/telescope.nvim](https://github.com/nvim-telescope/telescope.nvim) - Fuzzy Finder

#### Autocompletion
- [hrsh7th/nvim-cmp](https://github.com/hrsh7th/nvim-cmp) - Completion plugin
- [hrsh7th/cmp-buffer](https://github.com/hrsh7th/cmp-buffer) - Completion source for text in current buffer
- [hrsh7th/cmp-path](https://github.com/hrsh7th/cmp-path) - Completion source for file system paths

#### Snippets
- [L3MON4D3/LuaSnip](https://github.com/L3MON4D3/LuaSnip) - Snippet engine
- [rafamadriz/friendly-snippets](https://github.com/rafamadriz/friendly-snippets) - Useful snippets for different languages
- [saadparwaiz1/cmp_luasnip](https://github.com/saadparwaiz1/cmp_luasnip) - Completion source for snippet autocomplete

#### Managing & Installing Language Servers, Linters & Formatters
- [williamboman/mason.nvim](https://github.com/williamboman/mason.nvim)

#### LSP Configuration
- [williamboman/mason-lspconfig.nvim](https://github.com/williamboman/mason-lspconfig.nvim) - Bridges gap b/w mason & lspconfig
- [neovim/nvim-lspconfig](https://github.com/neovim/nvim-lspconfig) - Easy way to configure lsp servers
- [hrsh7th/cmp-nvim-lsp](https://github.com/hrsh7th/cmp-nvim-lsp) - Smart code autocompletion with lsp
- [glepnir/lspsaga.nvim](https://github.com/glepnir/lspsaga.nvim) - Enhanced uis for lsp
- [jose-elias-alvarez/typescript.nvim](https://github.com/jose-elias-alvarez/typescript.nvim) - Additional functionality for typescript server
- [onsails/lspkind.nvim](https://github.com/onsails/lspkind.nvim) - Vs Code Like Icons for autocompletion

#### Formatting & Linting
- [jose-elias-alvarez/null-ls.nvim](https://github.com/jose-elias-alvarez/null-ls.nvim) - Easy way to configure formatters & linters
- [jayp0521/mason-null-ls.nvim](https://github.com/jayp0521/mason-null-ls.nvim) - Bridges gap b/w mason & null-ls

#### Syntax Highlighting & Autoclosing Things
- [nvim-treesitter/nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter) - Treesitter configuration
- [windwp/nvim-autopairs](https://github.com/windwp/nvim-autopairs) - Autoclose brackets, parens, quotes, etc...
- [windwp/nvim-ts-autotag](https://github.com/windwp/nvim-ts-autotag) - Autoclose tags

#### Git
- [lewis6991/gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim) - Show line modifications on left hand side












