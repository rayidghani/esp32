# ESPresso32

## Getting started
1. connect ESP32 to your computer and find the port it is on:

 `ls /dev/cu.*`
 
2. flash it with a micropython firmware using esptool.py

 `pip install esptool`
 
 `esptool.py --chip esp32 --port /dev/cu.usbserial-0001 write_flash -z 0x1000 esp32-idf3-20210202-v1.14.bin`
 
3. Ready to go
    - copy boot.py and main.py to the board
    - install any micropython modules with upip

## Parts
- [Board](https://www.amazon.com/gp/product/B08D5ZD528/ref=ppx_yo_dt_b_asin_title_o08_s00?ie=UTF8&psc=1)
- [OLED](https://www.amazon.com/gp/product/B08KPQT75M/ref=ppx_yo_dt_b_asin_image_o06_s00?ie=UTF8&psc=1)
- [Load cell and ADC Amp](https://www.amazon.com/gp/product/B08KRV8VYP/ref=ppx_yo_dt_b_asin_title_o04_s00?ie=UTF8&psc=1)
- [Water Level Sensor](https://www.amazon.com/gp/product/B07THDH7Y4/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8&psc=1)
- [External Hall Sensor](https://www.mouser.com/datasheet/2/187/honeywell-sensing-omnipolar-digital-hall-effect-se-1846243.pdf)

## Utilities
- [convert fonts to micropython](https://github.com/peterhinch/micropython-font-to-py)
- [Ampy: to copy files over to esp32](https://github.com/scientifichackers/ampy)
- [HX711 code](https://github.com/robert-hh/hx711)

## Notes and Helpful Links
- [micropython](http://docs.micropython.org/en/v1.10/esp32/quickref.html)
