# gbclock
The first proper clock for the Game Boy.

## Features
* Accurate time **from the RTC**
* Day of the week
* Big numbers
* Vertical orientation
* Moving dot
* Hourly chimes
* It keeps the time even when powered off
* [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/)

Other homebrew clocks use CPU cycles to keep track of the time, and that makes those clocks drift more than one minute per hour.

## Requirements

gbclock requires a cartridge with **MBC3 support and RTC**.

Tested with:
* [Everdrive x7](https://krikzz.com/our-products/cartridges/edgbx7.html)
* [BennVenn's MBC3000 MBC3 cart](https://bennvenn.myshopify.com/products/mbc3000-rtc-gbc-cart?variant=39901988454503)
* [HDR's MBC3 Flashcart](https://github.com/HDR/MBC3-Flashcart)
* [HDR's MBC30 Flashcart](https://github.com/HDR/MBC30-Flashcart) One user had 2 kernel panics using the MBC30 with the Analoge Pocket. Not sure what the problem was.
* [insideGadget's MBC3](https://shop.insidegadgets.com/product/gameboy-2mb-32kb-fram-mbc3-with-rtc-flash-cart/) 
* insideGadget's MBC3 4MB variant
* flash converted MBC3 cartridge (DMG-KFDN-10 with [J.Rodrigo's adapter](https://www.jrodrigo.net/project/flash-memory-adapter-for-some-game-boy-cartridges/))

Not tested (yet) but it should work:
* [EZ flash junior](https://www.ezflash.cn/product/ezflash-junior/)
* [insideGadget's MBC3 RTC LinkNLoad USB Flash Cart](https://shop.insidegadgets.com/product/gameboy-mbc3-rtc-linknload-usb-flash-cart-works-with-pokemon-games-hacks-like-cc/) 
* other flashcarts with MBC3 support **and RTC**.

I'm powering it with a USB to 3.5mm barrel jack cable **with the polarity reversed** (center negative), connected to an old phone charger.

## Instructions

It will automatically show the clock at boot.

Press Select to set up the time.

## License
The source code and assets used in the clock are available under the [CC0](https://creativecommons.org/share-your-work/public-domain/cc0/). Feel free to customize and do whatever you want with it!

## Other clocks for the Game Boy
* pixjuan's [clockboy](https://github.com/pixjuan/clockboy), made for GB Compo 21​​
* [GBClock](http://www.devrs.com/gb/files/software.html), Jeff Frohwein's **talking clock** from 1997​


