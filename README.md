# tada68
Keyboard layout generated from [qmk-fm](https://config.qmk.fm/#/tada68/LAYOUT_ansi)

## Setup

1. Connect keyboard and push the reset button on the bottom
2. Navigate to the mounted keyboard and flash it

```shell
# Navigate to the keyboard
$ cd /Volumes/TADA68

# Delete the existing flash file
$ rm FLASH.BIN

# Copy the new flash file
$ cp ~/location/of/FLASH.BIN ./

# Delete junk files
$ rm -rf .Trashes/ .fseventsd/ ._.Trashes ._FLASH.bin
```

3. Eject the keyboard

## Troubleshooting
On osx, make sure to delete all the files in the `/VOLUMES/TADA68` directory except for `FLASH.BIN`. Best to do this on the command line and double check with `ls -la`

## Links
* [QMK configurator](https://config.qmk.fm/#/tada68/LAYOUT_ansi)
* [mac remapping](https://gist.github.com/egstad/03dc892076c5f97e0c1e371013f952d7)
