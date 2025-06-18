## Installation

### On Mac/Linux:

Delete or backup old nvim folder just in case. Below commands shows how to delete old configuration

```
rm -rf ~/.config/nvim

rm -rf ~/.local/share/nvim
```

Then, clone this repo

```
git clone https://github.com/jereok91/gNvimConfig.git ~/.config/nvim && nvim
```

### On Windows:

```
rm -Force ~\AppData\Local\nvim
rm -Force ~\AppData\Local\nvim-data
```

```
git clone https://github.com/FStanDev/nvichad-jp-custom.git $ENV:USERPROFILE\AppData\Local\nvim && nvim
```

Then, after all plugins installs, execute `:MasonInstallAll` and is done 😀
