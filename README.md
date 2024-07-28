### My custom neovim configuration
##### Prerequisites:
- NeoVim
- git
- cmake
- NodeJS
##### Get nerd fonts for amazing dev-icons
```
mkdir -p ~/.local/share/fonts
cd ~/.local/share/fonts && curl -fLO https://github.com/ryanoasis/nerd-fonts/raw/HEAD/patched-fonts/Hack/Regular/HackNerdFontMono-Regular.ttf
```
*The path is for Linux. In other OS it could be different.*
*This font is my preferred font if you like something else than change it to your preference. Go to the **ryanoasis/nerd-fonts** repo and check the available fonts.*
##### Clone this repo to your local machine...
```git
git clone https://github.com/ridwanalmahmud/init.lua.git ~/.config/nvim
```
*Do not change the path(~/.config/nvim)*.       

At first you may have some errors so...
- Go through each file and source it
- If the error is with LSP than ignore it for the moment | (tsserver, rust_analyzer, gopls).
*Lastly, go through the remaps and options and change it according to what you prefer. Use the LSP that you need.*

*Have a good day*
