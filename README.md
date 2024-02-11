# list-images

![image](https://github.com/saris-a37/list-images/assets/62101258/99bda10b-9c3e-4a4c-ae0a-f3c4a8d45ebb)

a simple darktable Lua add-on to export a list of images in the current collection as text file

## AUTHOR

สาริศ ธนาโสภณ (t.saris@live.com)

## INSTALLATION

* copy this file in $CONFIGDIR/lua/ where CONFIGDIR is your darktable configuration directory
* add the following line in the file $CONFIGDIR/luarc

``` require "list_images" ```

## USAGE

* select the output string format
* select the seperator between each image's entry in the output text file
* set the target directory and output text file name
* click 'export'

## TO-DOs

- [x] selected image(s) only check-button
- [x] use common parent directory as destination check-button (with function to find path)
- [x] auto-apply default settings

## LICENSE

GPLv2
