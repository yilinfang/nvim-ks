# nvim-ks

Personal [Neovim](https://neovim.io) configuration based on the [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim).

For the plugins I use, check the [`lazy-lock.json`](lazy-lock.json).

For the other tools used in my PDE([Personal Development Environment](https://youtu.be/QMVIJhC9Veg?si=VgJQLBVTIYmNjVSDs)), check my [PDE bootstrap scripts](https://github.com/yilinfang/pde-starter).

## Extra requirements

- [fd](https://github.com/sharkdp/fd) (for file searching)

## Key changes

- Replace `telescope` with `snacks.picker`
- Replace `tokyonight` with `solarized-osaka`

## Language support

- Json
- Lua
- Markdown
- Python
- Shell
- Toml
- Yaml

## Usage

### Option 1: Clone the repository

```bash
git clone https://github.com/yilinfang/nvim-ks.git ~/.config/nvim
```

### Option 2: Copy the `_init.lua` file to `~/.config/nvim/init.lua`

```bash
mkdir -p ~/.config/nvim
curl -o ~/.config/nvim/init.lua https://raw.githubusercontent.com/yilinfang/nvim-ks/main/_init.lua
```
