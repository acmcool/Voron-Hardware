# V0 Display #
![V-Naught_Display](Images/Overview.png)

Reminder, this board is a **BETA** and may have some changes to it.

[Interactive bom](http://htmlpreview.github.io/?https://github.com/VoronDesign/Voron-Hardware/blob/master/V0_Display/KiCad/V0_Display-ibom.html)
## The board has: ##
 - STM32F042F6P6 MCU with internal oscillator
 - SWD header for easy debugging
 - I2C Screen connections for  1.3" display with jumpers on back for slecting which pins (1 or 2) are power and ground
 - 4 way button pad OR EN11-style click encoder support
 - Reset/kill button
 - 3 GPIO pin header
 - 1 on-board Neopixel with data line broken out for expansion
 - Dual USB port (Vertical or Horizontal)


## In addition to the PCB, you will need: ##
 - Encoder [Amazon](https://www.amazon.com/DIYhz-Rotary-Encoder-Digital-Potentiometer/dp/B07D3D64X7)/[DigiKey](https://www.digikey.com/product-detail/en/tt-electronics-bi/EN11-HSB1AF15/987-1186-ND/2408764) or [6mm Tactile buttons](https://www.amazon.com/BOJACK-Pushbutton-Switches-Momentary-Assortment/dp/B07ZBHXBZ4)
 - An OLED display [1.3"](https://www.amazon.com/HiLetgo-Serial-SSH1106-Display-Arduino/dp/B01MRR4LVE/)
 - Micro USB port (Horizontal [Molex 105017-0001](https://www.digikey.com/product-detail/en/molex/1050170001/WM1399CT-ND/2350885) or equivalent [Amazon](https://www.amazon.com/gp/product/B01IQ8VN94)) *or* (Vertical [Molex 105017-0001](https://www.digikey.com/product-detail/en/molex/1051330001/WM9734CT-ND/4037910))

### Optionally you can get: ###
- [Neopixels](https://www.digikey.com/products/en?mpart=1655&v=1528) or look on ebay for bare 5050 Neopixels
