Deprecated. Check out [vimclip](https://github.com/hrantzsch/vimclip) instead.

# vim-anywhere

Edit text in Vim, Neovim, or Gvim and have it copied to the clipboard when the buffer is closed to be pasted into an application.

Files are temporarily saved in /tmp/vim-anywhere if you need to go back to them.

## Installation

### Manual

Requires xclip, which should be installed from your distro's package manager.

Then run the following:
```sh
curl -LO https://raw.githubusercontent.com/cjbassi/vim-anywhere/master/vim-anywhere
chmod +x vim-anywhere
```

Then copy vim-anywhere into your $PATH.

### Arch Linux

Install `vim-anywhere-git` from the AUR.

## Usage

Run the script and give `vim`, `nvim`, or `gvim` and your default terminal if you're using Vim or Neovim.

Example:
```sh
vim-anywhere nvim alacritty
```
or
```sh
vim-anywhere gvim
```

It's recommended to bind the command to a keybind for convenience.
