# MPU6050

This is the zephyr/samples/mpu6050 sample, which was originally written for the nRF52832, ported to the nRF9161DK.

## Steps to run

Use the nRF Connect for Desktop application to configure VDD on the nRF9161DK to be 3.3V. Then connect the VCC pin of the MPU6050 to the kit's VDD pin, the ground pins of the sensor to the board, and the SDA and SCL pins to P0.30 and P0.31 respectively. Build the project and flash it to the board.