# Neovim Keymaps

Here's a list of the keymaps you can use with the Neovim config. It does not include standard Vim keymaps.

In this config `<leader>` = `<space>`

## Insert Mode Keymaps

| Keymap | Action           |
| ------ | ---------------- |
| `jk`   | Exit Insert Mode |

## Normal Mode Keymaps

### Search Related Keymaps

| Keymap       | Action                  |
| ------------ | ----------------------- |
| `<leader>nh` | Clear Search Highlights |

### Increment/Decrement Numbers

| Keymap      | Action           |
| ----------- | ---------------- |
| `<leader>+` | Increment number |
| `<leader>-` | Decrement number |

### Split Window Management

| Keymap       | Action                                  |
| ------------ | --------------------------------------- |
| `<leader>sv` | Split Window Vertically                 |
| `<leader>sh` | Split Window Horizontally               |
| `<leader>se` | Make Split Windows Equal Width & Height |
| `<leader>sx` | Close Current Split Window              |
| `<leader>sm` | Toggle Split Window Maximization        |

### Tab Management

| Keymap       | Action             |
| ------------ | ------------------ |
| `<leader>to` | Open New Tab       |
| `<leader>tx` | Close Current Tab  |
| `<leader>tn` | Go To Next Tab     |
| `<leader>tp` | Go To Previous tab |

### Nvim-Tree File Explorer

| Keymap      | Action               |
| ----------- | -------------------- |
| `<leader>e` | Toggle File Explorer |

### Telescope Fuzzy Finder

| Keymap       | Action                                  |
| ------------ | --------------------------------------- |
| `<leader>ff` | Find files within project               |
| `<leader>fs` | Find string within project              |
| `<leader>fc` | Find string under cursor within project |
| `<leader>fb` | Show open buffers                       |
| `<leader>fh` | Show help tags                          |

The following git related keymaps for telescope are not in the youtube video. They must must be present in [keymaps.lua](.config/nvim/lua/josean/core/keymaps.lua) as they are in this repository.
| Keymap | Action |
| ------ | ------ |
| `<leader>gc` | List git commits for repository |
| `<leader>gfc` | List git commits for current file/buffer |
| `<leader>gb` | List git branches for repository |
| `<leader>gs` | List current changes per file with diff preview |

### LSP

| Keymap       | Action      |
| ------------ | ----------- |
| `<leader>rs` | Restart lsp |
