# PIO STM32L4 Arduino Core Example

## Description

Example project for using the PIO integrated STM32L4 core (originally
https://github.com/GrumpyOldPizza/arduino-STM32L4/). 

For configuratation refer to https://github.com/maxgerhardt/arduino-STM32L4

## Configuration of example

Select correct environment for your board in the `default_envs` of the `platformio.ini`, otherwise it will build
for all boards.

## Uploading

The default upload method is `stlink`. It can be changed to DFU via the commented-out `upload_protocol = dfu`
setting. DFU is untested since I don't have any actual board, but it seems to do the right invocation for
`dfu-util`.  
