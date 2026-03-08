# Fun on Bluepill
## Building
1. Dependencies
```
arm-none-eabi-gcc
arm-none-eabi-gdb
arm-none-eabi-newlib
stlink
```
2. Build & flash
```
make && sudo st-flash --reset write build/stm32disco.bin 0x08000000
```
