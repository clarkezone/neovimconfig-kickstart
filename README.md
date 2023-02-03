# neovimconfig-kickstart
My neovim config layered on kickstart

```bash
rm -rf ~/.config/nvim && rm -rf ~/.local/share/nvim
mkdir ~/.config/nvim
git clone --depth 1 https://github.com/clarkezone/neovimconfig-kickstart.git ~/.config/nvim
curl -Lo ~/.config/nvim/init.lua https://raw.githubusercontent.com/nvim-lua/kickstart.nvim/master/init.lua
```
