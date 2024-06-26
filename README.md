<picture align="center">
  <img alt="TOTEM logo" src="/docs/images/fabiTEM-logo.svg">
</picture>

fabiTEM is a 38 key, column-staggered, ortho-ergo, choc split keyboard forked from the [TOTEM](https://github.com/GEIGEIGEIST/TOTEM/tree/main). It is powered by:

 - an [RP2040](https://www.raspberrypi.com/documentation/microcontrollers/rp2040.html) (left side), and
 - an [MCP23017](https://www.microchip.com/en-us/product/mcp23017) IO expander (right side).

The core design concept is that everything was designed at the desk - zero hardware tinkering. Factory prints PCB and case, assembles the components, and all left for the user to do is put a few screws in. The jury is out as of whether that's gonna work in practice :-)

***

## LAYOUT

![fabiTEM layout](/case/inkscape/fabiTEM-brd.png)

***

## PCB

[Here](/PCB/) you can find the KiCad files for the fabiTEM.

***

## CASE

Being designed.

## CREDITS

### INSPIRATION

The original design with diodes on the front and two controllers is from [TOTEM](https://github.com/GEIGEIGEIST/TOTEM/tree/main). I've modified it quite a bit to add more angle on the thumb keys, simplify factory assembly (everything is on the back), forgo breakout boards for an actual RP2040, use a single MCU to simplify flashing, etc.
