# The Archrice (Adam Colaianni <https://adamcolaianni.us>'s dotfiles)

These are the dotfiles deployed by [ANUS](https://github.com/AdamColaianni/AdamsNewUserSystem) as is
configured on my personal setup.

- Very useful scripts are in `~/.local/bin/`
- Settings for:
	- nvim (text editor)
	- zsh (shell)
	- lf (file manager)
	- mpd/ncmpcpp (music)
	- sxiv (image/gif viewer)
	- mpv (video player)
	- other stuff like xdg default programs, inputrc and more, etc.
- I try to minimize what's directly in `~` so:
	- All configs that can be in `~/.config/` are.
	- Some environmental variables have been set in `~/.zprofile` to move configs into `~/.config/`
- Bookmarks in text files used by various scripts (like `~/.local/bin/shortcuts`)
	- File bookmarks in `~/.config/shell/bm-files`
	- Directory bookmarks in `~/.config/shell/bm-dirs`

## Usage

These dotfiles are intended to go with numerous suckless programs I use:

- [dwm](https://github.com/AdamColaianni/dwm) (window manager)
- [dwmblocks](https://github.com/AdamColaianni/dwmblocks) (statusbar)
- [st](https://github.com/AdamColaianni/st) (terminal emulator)

I also recommend trying out
[mutt-wizard](https://github.com/lukesmithxyz/mutt-wizard), which additionally
works with this setup. It gives you an easy-to-install terminal-based email
client regardless of your email provider. It is integrated into these dotfiles
as well.

## Install these dotfiles and all dependencies

Use [ANUS](https://github.com/AdamColaianni/AdamsNewUserSystem) to autoinstall everything:

```
curl -LO https://adamcolaianni.us/anus.sh
```

or clone the repo files directly to your home directory and install the
[dependencies](https://github.com/AdamColaianni/AdamsNewUserSystem/blob/master/progs.csv).
