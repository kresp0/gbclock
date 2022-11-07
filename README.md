# gbclock
The first proper clock for the Game Boy

* Accurate time **from the RTC**
* Big numbers
* Vertical orientation
* Moving dot
* Hourly chimes
* It keeps the time even when powered off

Other homebrew clocks use CPU cycles to keep track of the time, and that makes those clocks drift more than one minute per hour.

gbclock requires a cartridge with **MBC3 support and RTC**. I'm loading it from an [Everdrive x7](https://krikzz.com/our-products/cartridges/edgbx7.html), but it should also work on the [BennVenn's MBC3000 MBC3 cart](https://bennvenn.myshopify.com/products/mbc3000-rtc-gbc-cart?variant=39901988454503), [insideGadget's MBC3 RTC LinkNLoad USB Flash Cart](https://shop.insidegadgets.com/product/gameboy-mbc3-rtc-linknload-usb-flash-cart-works-with-pokemon-games-hacks-like-cc/) and other flashcarts with MBC3+RTC support.

I'm powering it with a USB to 3.5mm barrel jack cable **with the polarity reversed**, connected to an old phone charger.

Instructions
It will automatically show the clock at boot.

Press Select to set up the time.

Source code and assets
The source code and all assets used in the clock are available on github and published under the CC0. Feel free to customize and do whatever you want!

https://github.com/kresp0/gbclock/​

