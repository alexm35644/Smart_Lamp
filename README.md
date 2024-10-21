# Smart_Lamp

### USB Power mode

Wireless charger → battery IC → Battery || LED || MCU

### Battery Power Mode

Battery → battery IC → LED || MCU

### Battery Dead

Battery → RTC 

- I can use the battery management IC to monitor the battery voltage through I2C
- I can use the MCU to cut off the power using a MOSFET that is powering the LED
