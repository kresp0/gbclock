# gbclock
The first proper clock for the Game Boy.

## Features
* Accurate time **from the RTC**
* Big numbers
* Vertical orientation
* Moving dot
* Hourly chimes
* It keeps the time even when powered off

Other homebrew clocks use CPU cycles to keep track of the time, and that makes those clocks drift more than one minute per hour.

## Requirements

gbclock requires a cartridge with **MBC3 support and RTC**.

Tested with:
* [Everdrive x7](https://krikzz.com/our-products/cartridges/edgbx7.html)
* [HDR's MBC3 Flashcart](https://github.com/HDR/MBC3-Flashcart)
* [insideGadget's MBC3](https://shop.insidegadgets.com/product/gameboy-2mb-32kb-fram-mbc3-with-rtc-flash-cart/) 

Not tested (yet) but it should work:
* [BennVenn's MBC3000 MBC3 cart](https://bennvenn.myshopify.com/products/mbc3000-rtc-gbc-cart?variant=39901988454503)
* [HDR's MBC30 Flashcart](https://github.com/HDR/MBC30-Flashcart)
* flash converted MBC3
* [insideGadget's MBC3 RTC LinkNLoad USB Flash Cart](https://shop.insidegadgets.com/product/gameboy-mbc3-rtc-linknload-usb-flash-cart-works-with-pokemon-games-hacks-like-cc/) 
* other flashcarts with MBC3 support **and RTC**.

I'm powering it with a USB to 3.5mm barrel jack cable **with the polarity reversed**, connected to an old phone charger.

## Instructions

It will automatically show the clock at boot.

Press Select to set up the time.

## License
The source code and assets used in the clock are available under the [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/). Feel free to customize and do whatever you want with it!

