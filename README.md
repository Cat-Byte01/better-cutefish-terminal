# Better cutefish terminal
 **A better maintained cutefish terminal with missing features.**
So the default cutefish terminal looks good,and is functional, but there are some features missing, and some that I personally didn't like( for example the green text when using dark mode), so i created this repository in that purpose.

This is a fork of **https://github.com/cutefishos/Terminal**

## Features included right now:
- When using dark mode the text color is white
## To-Do:
- [X] ~~Change the text color when using dark mode to white~~
- [ ] Add a option in the settings to change text color  ( in dark and in light mode seperatly )
- [ ] Change the settings menu  to be similar to the settings app in cutefishos

If you want something else to be added, make a issue about it and i will add it to my To-Do.

## Build instructions:

### Third Party Code:

[qmltermwidget](https://github.com/Swordfish90/qmltermwidget).

### Dependencies:

```sh
sudo apt install extra-cmake-modules qtbase5-dev qtdeclarative5-dev qtquickcontrols2-5-dev qttools5-dev
```
### Commands to build this:
```shell
git clone https://github.com/cat-byte01/better-cutefish-terminal
cd better-cutefish-terminal
cd Terminal
mkdir build
cd build
cmake ..
make
sudo make install
```
