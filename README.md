# fzf-lsp.nvim

# Installation

Install using [vim-plug](https://github.com/junegunn/vim-plug).
Put this in your `init.vim`.

```vim
Plug 'Fanto94/fzf-lsp.nvim'
```

**Note:** You need to have `fzf` installed in addition to use this plugin.
See <https://github.com/junegunn/fzf/blob/master/README-VIM.md#installation>.

## Features

This is an extension for fzf that give you the ability to search for symbols
using the neovim builtin lsp.

# Commands and settings

If you have [fzf.vim](https://github.com/junegunn/fzf.vim) installed,
this plugin will respect your `g:fzf_command_prefix` setting.

- Call `:LSPDefinitions` to show the definition for the symbols under the cursor
- Call `:LSPReferences` to show the references for the symbol under the cursor
- Call `:LSPDocumentSym` to show all the symbols in the current buffer
- Call `:LSPWorkspace` to show all the symbols in the workspace
