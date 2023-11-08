# list-images

a simple darktable Lua add-on to export a list of images in the current collection as text file

## AUTHOR

สาริศ ธนาโสภณ (t.saris@live.com)

## INSTALLATION

* copy this file in $CONFIGDIR/lua/ where CONFIGDIR is your darktable configuration directory
* add the following line in the file $CONFIGDIR/luarc
  require "list_images"

## USAGE

* select the output string format
* select the seperator between each image's entry in the output text file
* set the target directory and output text file name
* click 'export'

## LICENSE

GPLv2
