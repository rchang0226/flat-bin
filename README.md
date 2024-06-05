# flat-bin
Script that generates launchers for flatpaks in a bin folder, so they can be used with dmenu.

## Installation

```
git clone https://github.com/rchang0226/flat-bin.git
cd flat-bin
./flat-bin
```

For ease of use, you can add a symbolic link. Do ```ln -s ~/<PATH-TO-FILE> ~/.local/bin/flat-bin```.
Then you can just type ```flat-bin``` in the terminal anytime you want to run the script. 

## Usage
By default the script generates the launchers in $HOME/.local/bin/ so that folder should be part of your PATH.

Create the folder if you don't have it already. To add to PATH, do ```echo 'export PATH="$PATH:$HOME/.local/bin"' >> ~/.bashrc```. 

You should run this script every time that you install a flatpak app. If you uninstall a flatpak application, you need to manually delete the sh script from ~/.local/bin.
