# Tibber_Price_Monitor

Small project to show dynamic hourly energy prices from Tibber on a simple LED matrix.
First column is the current hour, the other colums show the next 7 hours.
High/low are the max/min price for the next 24 hours.
Colours are the price levels estimated by the Tibber API.

##Installation instructions:
- Connect the LED matrix to the board (power, ground, data to PIN D3)
- Modify your Tibber API key, WiFi settings in the settings.h file
- And compile/upload the project with the Arduino IDE

##Hardware used:

AZDelivery 8x8 LED Matrix
https://www.amazon.nl/dp/B078HYP681?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1

AZDelivery D1-Mini
https://www.amazon.nl/-/en/dp/B01N9RXGHY/ref=twister_B07Z95B4BJ?_encoding=UTF8&th=1

Hardware cost: Electronics around 10 Euro

##There is also a 3D-printable case created by Hatrick3D that can be used: 
[https://www.printables.com/de/model/908102-8x8-led-matrix-display-as-energy-price-indicator-f](https://www.printables.com/de/model/908102-8x8-led-matrix-display-as-energy-price-indicator-f)

##Final result:
![A LED display with 8 columns](https://github.com/Till-83/Tibber_Price_Monitor/blob/main/images/picture.jpeg)
