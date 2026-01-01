# NvChad Configuration

![Neovim](https://img.shields.io/badge/Neovim-v0.9+-57A143?style=for-the-badge&logo=neovim)
![NvChad](https://img.shields.io/badge/Base-NvChad-4682B4?style=for-the-badge&logo=lua)

This is my personal **Neovim** configuration built on top of [NvChad](https://nvchad.com/). This setup is optimized for **DevOps workflows, Shell Scripting, and System Administration**, focusing on code visibility and structure.

## 🚀 Key Features

- **Enhanced Code Visibility**: Integrated `shellRaining/hlchunk.nvim` to visualize indentation scopes, making it easier to track nested loops and conditions in Shell scripts.
- **LSP Configuration**: Fully configured **Bash Language Server** via Mason for robust shell scripting support (autocompletion, diagnostics).
- **Custom UI**: Personalized `chadrc` settings, including custom tabline configuration and `base46` theme adjustments.
- **Git Integration**: Optimized workflow for tracking changes effectively using Conventional Commits.

## 🛠️ Installation

To use this configuration, ensure you have Neovim installed (v0.9+), then follow these steps:

```bash
# 1. Backup your current nvim config (if any)
mv ~/.config/nvim ~/.config/nvim.bak

# 2. Clone this repository
git clone [https://github.com/RifkiAndriyanPratama/nvim-nvchad](https://github.com/RifkiAndriyanPratama/nvim-nvchad) ~/.config/nvim

# 3. Start Neovim
nvim
