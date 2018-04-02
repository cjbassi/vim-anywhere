# vim-anywhere

Edit text for any application in Vim, Neovim, or Gvim and have it pasted into the application when you close the buffer.

## Installation

### Manual

Requires xclip and xdotool. You should install these from your distro's package manager.

Then run the following:
```
curl -LO https://raw.githubusercontent.com/cjbassi/vim-anywhere/master/vim-anywhere
chmod +x vim-anywhere
```

Then copy vim-anywhere into your $PATH.

### Arch

Install vim-anywhere-git from the AUR.

## Usage

Run the script and give your default terminal name along with 'vim', 'nvim', or 'gvim'.

Example:
```
vim-anywhere alacritty nvim
```

It's recommended that you bind the above command to a keybind for convenience.
