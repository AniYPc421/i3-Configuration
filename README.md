# i3-Configuration

You can decorate your i3 with the files in this repository.

### Preview
![Image text](https://github.com/AniYPc421/i3-Configuration/blob/master/readme_sources/preview.png)

## Preparation
install i3 metapackage, imagemagick and scrot
``` shell
$ sudo apt install i3 imagemagick scrot
```
install firefox and pulseaudio if you want to make it work without modification
``` shell
# alternatives are alsa and chromium, or something you prefer
$ sudo apt install firefox pulseaudio
```

### Usage
clone this repository
``` shell
$ git clone https://github.com/AniYPc421/i3-Configuration.git
$ cd i3-Configuration/
```
move .Xresources if you want to adopt my color scheme
```shell
$ mv config/Xresources ~/.Xresources
```
move files from config/ to $HOME/.config
``` shell
$ mv config/* ~/.config/
```
move i3exit to /usr/local/bin or somewhere else which has been set to PATH
``` shell
$ sudo mv bin/i3exit /usr/local/bin/
```
