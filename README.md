# SSD1306-OLED-display-driver-for-BeagleBone
This is a SSD1306 OLED Display Library fully compatible with the BeagleBone.

The Library has 3 components:
1. I2C component for enabling communication between the BeagleBone and display.
2. Control component for sending I2C commands to configure and control the display.
3. Graphics component for drawing geometrical figures, bitmaps, texts, characters, emoticons and numbers.

Written by: Vinay Divakar

Website: www.deeplyembedded.org

Blog Post: https://deeplyembedded.org/ssd1306-oled-driver-beaglebone/

Youtube: https://youtu.be/sDKf6zW6Pyg

MIT license, check LICENSE file for more information

Hardware connections are as shown below:

Beagle + SSD1306  
P9_19  - I2C2_SCL
P9_20  - I2C2_SDA
----------------
P9_02  - GND
P9_03  - DC_3.3V

This Library is written in C. To use it, just include the I2C and SSD1306 Libraries in your project.
