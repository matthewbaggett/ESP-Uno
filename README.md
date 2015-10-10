# ESPUno - A dirty ESP8266 Arduino Uno clone

Using an ESP8266 should be fun! These processors are cheap enough to be disposable, lets make that easier to achieve as a hobbist.

Features: 

+ 80/160Mhz ESP8266
+ 5 working ADC pins (A0 is the 0-1 volt ESP8266 ADC, A1-A5 are provided by an i2c ADC controller (ADS1015) 
+ Pin 13 LED still present, tied to SCLK/GPIO6
+ LiPo cell support on-board! MCP73831 Charger circuit, TSP61200 Boost converter (shamelessly stolen from a [Sparkfun reference design](https://www.sparkfun.com/products/11231)) 
+ 3.3V regulator ([AMS1117](http://www.aliexpress.com/premium/ams1117.html?ltype=wholesale&SearchText=ams1117&d=y&origin=y&initiative_id=SB_20151010010621&isViewCP=y&catId=0))
+ All the associated recommended pullups as per the [Arduino ESP8266 project](https://github.com/esp8266/Arduino) ([Schematic](https://github.com/esp8266/Arduino/blob/esp8266/docs/ESP_improved_stability.png)
+ Built-in USB programmer ([FTDI FT232R](http://www.aliexpress.com/premium/FT232R.html?spm=2114.01020208.0.312.zEmQlv&site=glo&g=y&SortType=price_asc&SearchText=FT232R&isUnitPrice=y&initiative_id=SB_20151010010739&shipCountry=uk&needQuery=n)) similar to how the Arduinos have.
+ Mini-USB port. They're easier to get hold of, for me, and the full-size USB connector tends to short out cheaply made boards that ride up on top of the Arduino. Also should help reduce the deck height of the board.

![alt text](https://raw.githubusercontent.com/matthewbaggett/ESP-Uno/master/espuno.brd.png)
![alt text](https://raw.githubusercontent.com/matthewbaggett/ESP-Uno/master/espuno.sch.png)

# Licence

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

May be re-licenced on request.
