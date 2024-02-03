# VIK Bare Display adapter

Small adapter for bare LCD displays to [VIK](https://github.com/sadekbaroudi/vik) connector.

## Supported displays

Theoretically any display with 12pin 0.7mm spacing welding type FPC with this pin out:

```
- GND
- LEDK
- LEDA
- VDD
- GND
- GND
- DC
- CS
- SCL
- SDA
- RESET
- GND
```

Bare displays can be used with any PCB size, but they are pretty fragile without any support, so be careful.

Existing PCBs for specific sizes:

- 1.47" rectangular display

## Used projects and resources

- https://www.waveshare.net/w/upload/f/f5/1.47inch_LCD_Module_SchDoc.pdf
- https://hackaday.io/project/168130-universal-ips-display-breakout-board
- 1.47" LCD model https://grabcad.com/library/1-47-rgb-tft-lcd-screen-display-module-172-320-ips-screen-st7789-driver-8pin-1
- 1.28" round LCD model https://grabcad.com/library/1-28-lcd-ga9a01-1
