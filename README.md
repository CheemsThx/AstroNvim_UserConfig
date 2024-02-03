# AstroNvim User Configuration Example

A user configuration template for [AstroNvim](https://github.com/AstroNvim/AstroNvim)

## 🛠️ Installation

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
```

#### Clone AstroNvim

```shell
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
```

#### Create a new user repository from this template

Press the "Use this template" button above to create a new repository to store your user configuration.

You can also just clone this repository directly if you do not want to track your user configuration in GitHub.

#### Clone the repository

```shell
git clone https://github.com/CheemsThx/AstroNvim_UserConfig ~/.config/nvim/lua/user
```

#### Start Neovim

```shell
nvim
```

#### Copilot 如何使用

使用配置在`user.lua`,可以配置在哪些文件自动启用,键位配置

<M-l>中的M是Alt键，在MacOs中是Option，在MacOs中有一个比较坑的点，Option按键组合其他按键，大部分会输出奇怪的字符，导致组合键不生效

解决方法是通过配置终端Profiles中Keys页面，将Option key配置为`+Esc`
