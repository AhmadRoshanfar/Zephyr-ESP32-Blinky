## Blinky

### Setup Environmet Variables
```shell
 $ vim ~/.zshrc 
 alias zephyr_esp32='export ZEPHYR_TOOLCHAIN_VARIANT="espressif"; export ESPRESSIF_TOOLCHAIN_PATH="${HOME}/.espressif/tools/xtensa-esp32-elf/esp-2020r3-8.4.0/xtensa-esp32-elf"'
 alias zephyr='source ~/zephyrproject/zephyr/zephyr-env.sh'
```
### Project Setup
```shell
$ git clone https://github.com/AhmadRoshanfar/Zephyr-ESP32-Blinky.git
$ cd Zephyr-ESP32-Blinky
$ zephyr
$ zephyr_esp32
```
### Build and flash
```shell
$ west build -b esp32
$ west flash
```
