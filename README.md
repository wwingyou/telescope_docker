# Telescope Docker

A neovim docker plugin powered by **Telescope**

## Usage

```lua
local docker = require'telescope-docker'

vim.keymap.set('n', '<leader>oi', docker.view_docker_images, {})
vim.keymap.set('n', '<leader>oc', docker.view_docker_containers, {})
```
