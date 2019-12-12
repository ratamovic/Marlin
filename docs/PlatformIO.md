# PlatformIO

## Initialize project

### Anet A8
`platformio init -b sanguino_atmega1284p`

## Clean project

`platformio run -e sanguino_atmega1284p -t clean`

## Build project

`platformio run -e sanguino_atmega1284p`

## Upload project

`platformio run -e sanguino_atmega1284p -t upload --upload-port /dev/ttyUSB0`

