# DHT22

This is the zephyr/samples/dht sample, which was originally written for the nRF52832, ported to the nRF9161DK.

## Steps to run

Connect the VCC and GND pins of the DHT22 sensor to the 5V pin and GND pin respectively of the nRF9161DK. In this sample, P0.05 was used, so the data pin of the DHT22 should connect to P0.05 on the board. Then the sample would output the temperature and humidity on the console. However, you can use any pin you wish by modifying the devicetree overlay.