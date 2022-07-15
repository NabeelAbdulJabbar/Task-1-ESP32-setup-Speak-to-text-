# Task-1-ESP32-setup-Speak-to-text-
How to setup ESP32 and a website that transfers speech to text.

Task 1 : https://eatable-soap.surge.sh/

Task 2 : To install the ESP32 board in your Arduino IDE, follow these next instructions:

first step 1. In your Arduino IDE, go to File> Preferences

2. Enter the following into the “Additional Board Manager URLs” field: https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json     Then, click the “OK” button

3.Open the Boards Manager. Go to Tools > Board > Boards Manager

4.Search for ESP32 and press install button for the “ESP32 by Espressif Systems“

5.That’s it. It should be installed after a few seconds.

After that you need to test the Installation to check the Installation you need to follow those steps 

1.Select your Board in Tools > Board menu (in my case it’s the DOIT ESP32 DEVKIT V1)

2.Select the Port (if you don’t see the COM Port in your Arduino IDE, you need to install the CP210x USB to UART Bridge VCP Drivers):

3.Open the following example under File > Examples > WiFi (ESP32) > WiFiScan

4.A new sketch opens in your Arduino IDE:

5.Press the Upload button in the Arduino IDE. Wait a few seconds while the code compiles and uploads to your board.

6. If everything went as expected, you should see a “Done uploading.” message

7.Open the Arduino IDE Serial Monitor at a baud rate of 115200:

8. Press the ESP32 on-board Enable button and you should see the networks available near your ESP32:





