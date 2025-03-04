# Microtouch - AVR development board with 2.8" TFT Touch Screen

<a href="http://www.adafruit.com/products/330"><img src="assets/board.jpg?raw=true" width="500px"></a>

[We've not made the Microtouch for many years - check out the PyPortal for a similar device that also includes WiFi and a Cortex M4 processor!](https://www.adafruit.com/product/4116)

Sure, the latest "iTouchy" gadgets are pretty cool. But who wants a locked down device? __Why not build your own touch-screen device__, with your own apps, all on open source hardware and using open source tools? OK, it can't play MP3s, but it does have a 320x240 TFT color display with resistive touch screen, an Atmega32u4 8-bit microcontroller, lithium polymer battery charger, backlight control, micro-SD slot, and a triple-axis accelerometer. Yeah, this is the next big thing and for those of us who like to DIY, you can do a lot of cool stuff with this dev board.

This product is just the Microtouch dev board (preloaded with some demo Apps), and does not include a lithium polymer battery or a microSD card. You will need a lipoly battery with 2-pin JST connector for best performance. It can run straight from USB but due to the charger design, the backlight will be dimmed so it will not appear as bright as with a battery installed. [We strongly suggest our medium lipoly](https://www.adafruit.com/product/258) but you can substitute another 3.7V cell. [A microSD](https://www.adafruit.com/product/102) card will be handy if you want to display images, slideshows or animations.

[On board you will find a whole bunch of goodies:](http://www.ladyada.net/products/microtouch/index.html#hardware_design)

- Atmega32u4 - 32KB of flash, 2.5K of RAM [with usb bootloader](http://www.ladyada.net/products/microtouch/index.html#bootloader)
- 2.8" 320x240 16-bit color, TFT display with resistive touch screen
- Lithium polymer battery charging via USB
- 3-axis accelerometer, MMA7544 +-2g to +-8g resolution
- Micro SD card slot
- Battery monitoring, backlight control and on/off switch

Of course, we wouldn't just leave you with a schematic or datasheet and say 'good luck'! The designer of the Microtouch (known to us by the code name "Rossum" ) has written a full hardware core operating system and multiple demo apps such as...

- [Image viewer](http://www.ladyada.net/products/microtouch/index.html#image_viewer_built-in) built into the hardware core, you can plug in a microSD card with images, slide shows or animations that show up as 'mini Apps'
- [Calibrate](http://www.ladyada.net/products/microtouch/index.html#calibrate_app) Touch-screen
- [Doomed](http://www.ladyada.net/products/microtouch/index.html#doomed) a 3D rendering maze
- [Accelerate](http://www.ladyada.net/products/microtouch/index.html#accelerate_app) keep the ball in the center of the screen by tilting
- [Paint](http://www.ladyada.net/products/microtouch/index.html#paint_app) fingerpainting but without the cleanup
- [Flip](http://www.ladyada.net/products/microtouch/index.html#flip_app) a Reversi game
- [Mines](http://www.ladyada.net/products/microtouch/index.html#mines_app) like Minesweeper but without the hassle of installing Windows
- [3D Icosohedron](http://www.ladyada.net/products/microtouch/index.html#icosohedron_app) controllable by tilting the board
- [Pacman](http://www.ladyada.net/products/microtouch/index.html#pacman_app) a sprite animation demo
- [Lattice](http://www.ladyada.net/products/microtouch/index.html#lattice_app) 3D lattice demo

The Microtouch is powerful and fun but is not meant for microcontroller beginners! If you're just starting out, we suggest checking out the Arduino to get your feet wet. Once you feel comfy with programming C and programming microcontrollers directly, come back and pick up one of these.

The project is a collaboration between Rossum & Ladyada! [For detailed documentation and files, please visit the product page](http://www.ladyada.net/products/microtouch/index.html)
