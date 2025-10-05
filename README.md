|Shutout to my friend Guts |                     


```markdown
# 💤 BobOfTheHawk’s Vim Configuration

A clean, modular, and modern Vim setup designed for productivity, readability, and speed.  
This repository contains all configuration files for Vim, split by purpose for easy maintenance.

---

## 📁 Folder Structure

```

---

.vim/
├── colors.vim       # Theme and color scheme settings
├── fzf.vim          # FZF integration and UI tweaks
├── keybinds.vim     # Custom key mappings
├── lightline.vim    # Statusline configuration
├── lsp.vim          # LSP setup for intelligent code features
├── options.vim      # General Vim settings
├── plugins.vim      # Plugin management and configuration
└── vimrc            # Main entry point (sources all above)

````

---

## ⚙️ Features

- 🧩 **Modular design** – Each component of your setup is isolated and maintainable  
- 🚀 **Fast startup** – Minimal overhead with on-demand plugin loading  
- 🔍 **FZF integration** – Fuzzy file search and command palette  
- 💡 **LSP support** – Language-aware completion, linting, and diagnostics  
- 🎨 **Custom colors** – Easy-to-tweak themes and lightline styles  
- ⌨️ **Productive keybinds** – Logical shortcuts for faster editing  

---

## 🛠️ Installation

### 1. Clone the repo
```bash
git clone https://github.com/BobOfTheHawk/.vim ~/.vim
````

### 2. Symlink your vimrc

```bash
ln -s ~/.vim/vimrc ~/.vimrc
```

### 3. Install plugins

If you’re using **vim-plug** (recommended), open Vim and run:

```vim
:PlugInstall
```

---

## 🧱 Dependencies

Some modules depend on external tools. Make sure you have:

| Tool                    | Description                            | Install command (Ubuntu / Arch)               |
| ----------------------- | -------------------------------------- | --------------------------------------------- |
| `fzf`                   | Fuzzy finder                           | `sudo apt install fzf` / `sudo pacman -S fzf` |
| `bat`                   | Syntax-highlighted previews (optional) | `sudo apt install bat` / `sudo pacman -S bat` |
| `lightline.vim`         | Statusline plugin                      | Installed via plugin manager                  |
| `vim-lsp` or `coc.nvim` | Language server client                 | Installed via plugin manager                  |

---

## 🧠 Usage Tips

* Press `<leader>f` (or your configured key) to trigger FZF search
* Statusline colors can be adjusted in `lightline.vim`
* Modify or extend `plugins.vim` to include more Vim/Neovim plugins
* Add new settings safely in their own `*.vim` files

---

## 🧩 Customization

You can easily add your own configurations:

```bash
cd ~/.vim
touch myconfig.vim
```

Then source it in your `vimrc`:

```vim
source ~/.vim/myconfig.vim
```

---

## 🧰 Troubleshooting

* If FZF or LSP doesn’t work, ensure the external executables are installed
* Run `:checkhealth` (in Neovim) or `:messages` (in Vim) for diagnostics
* Use `:scriptnames` to verify all files are sourced correctly

---

## 📜 License

This configuration is open source under the **MIT License**.
Feel free to fork, modify, and share improvements!

---

**Author:** [BobOfTheHawk](https://github.com/BobOfTheHawk)
**Version:** 1.0
**Last updated:** October 2025

```

---

“Made with Bob in Vim” or “Powered by fzf”
```
