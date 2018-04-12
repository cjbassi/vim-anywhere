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

### Arch Linux

Install `vim-anywhere-git` from the AUR.

## Usage

Run the script and give 'vim', 'nvim', or 'gvim' and your default terminal if you are using vim or nvim.

Example:
```
vim-anywhere nvim alacritty
```

It's recommended that you bind the above command to a keybind for convenience.
