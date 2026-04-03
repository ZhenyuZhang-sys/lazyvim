# 💤 LazyVim by zhenyu

## Install Lazy: 
git clone https://github.com/ZhenyuZhang-sys/lazyvim.git ~/.config/nvim

## Install neovim
Pre-built archives

The Releases page provides pre-built binaries for Linux systems.

```bashrc
```
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim-linux-x86_64.tar.gz
sudo rm -rf /opt/nvim-linux-x86_64
sudo tar -C /opt -xzf nvim-linux-x86_64.tar.gz
```
```

Then add this to your shell config (~/.bashrc, ~/.zshrc, …):
```bashrc
export PATH="$PATH:/opt/nvim-linux-x86_64/bin"
```

## Install dependencies
```bashrc
sudo apt install unzip
```
