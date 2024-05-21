
# My AstroNvim Conf

## 🛠️ Installation

1. Install a JetBrainsMono nerd font

```bash
wget "https://github.com/ryanoasis/nerd-fonts/releases/download/v3.1.1/JetBrainsMono.zip"
unzip JetBrainsMono.zip
rm JetBrainsMono.zip
sudo mv JetBrains*.ttf /usr/share/fonts/
fc-cache -f -v
```

verify font installation 
```bash
fc-list
```

2. Install nodejs
```bash
sudo dnf install nodejs
```

3. install neovim
```bash
sudo install neovim
```

4. follow the below steps:

#### Make a backup of your current nvim and shared folder

```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
```

#### Clone AstroNvim

```shell
git clone --depth 1 https://github.com/AstroNvim/template ~/.config/nvim
rm -rf ~/.config/nvim/.git
```

#### Create a new user repository from this template

Press the "Use this template" button above to create a new repository to store your user configuration.

You can also just clone this repository directly if you do not want to track your user configuration in GitHub.

#### Clone the repository

```shell
git clone https://github.com/itsmmdoha/astronvim_config ~/.config/nvim/lua/user
```

#### Start Neovim

```shell
nvim
```
