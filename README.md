**This repo is supposed to used as config by NvChad users!**

- The main nvchad repo (NvChad/NvChad) is used as a plugin by this repo.
- So you just import its modules , like `require "nvchad.options" , require "nvchad.mappings"`
- So you can delete the .git from this repo ( when you clone it locally ) or fork it :)

# Install
## Windows (PowerShell)
```PowerShell
git clone https://github.com/ilyash0/nvim $ENV:USERPROFILE\AppData\Local\nvim
```
## Linux
```Bash
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim.appimage
chmod u+x nvim.appimage
mv nvim.appimage /usr/local/bin/nvim
git clone https://github.com/ilyash0/nvim ~/.config/nvim && nvim
```


# Credits

1) Lazyvim starter https://github.com/LazyVim/starter as nvchad's starter was inspired by Lazyvim's . It made a lot of things easier!

