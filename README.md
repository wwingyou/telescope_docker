# Telescope Docker

A neovim docker plugin powered by **Telescope**

## Dependencies

- [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim)

## Setup

### Lazy.nvim
```lua
return {
  'wwingyou/telescope_docker',
  dependencies = {
    'nvim-telescope/telescope.nvim',
  },
  config = function ()
    -- Your configuration goes here...
  end
}
```

## Usage

```lua
local docker = require'telescope-docker'

vim.keymap.set('n', '<leader>oi', docker.view_docker_images, {})
vim.keymap.set('n', '<leader>oc', docker.view_docker_containers, {})
```
