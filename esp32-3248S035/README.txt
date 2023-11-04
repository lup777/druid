Commands:

## apply board configuration:
#
make distclean
./tools/configure.sh -l ../esp32-3248S035/configs/nsh

## flash ESP32 board:
#
make flash ESPTOOL_PORT=/dev/ttyUSB0

## run minicom
#
minicom -D /dev/ttyUSB0

## save config
make savedefconfig