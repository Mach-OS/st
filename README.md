![st](st.png)

st is a simple terminal emulator for X which sucks less.

## Install

```
git clone https://github.com/ChristianChiarulli/st.git
cd st
sudo make clean install
```

## Xresources

This terminal uses `~/.Xresources` for colors and other variables.

There is an example included with this repo:

**Note** this will overwrite your current Xresources if present.

```
mv Xresources ~/.Xresources
```

## Patches in order

- xresources
- alpha
- anysize
- desktopentry
- add boxdraw and ligatures together
- appsync
- font2 (doesn't work perfect, trying to find fonts that work with braille and emoji)
- clipboard
- scrollback
- bold is not bright
- external pipe (url opening using [this](https://github.com/LukeSmithxyz/st/blob/master/st-urlhandler) script)

## TODO

- more keybindings

