# nvm.nvim

A Node Version Manager integration for Neovim

This plugin will make the expected Node.js available in Neovim.

It will add nvm installation dir to the PATH.

Because of the way nvm works, this plugin **wil not be able** to install node.js versions that are not available.

## Installation

Using [lazy.nvim](https://github.com/folke/lazy.nvim):

```lua
return {
  "pipoprods/nvm.nvim",
  config = true,
}
```
