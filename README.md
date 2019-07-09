# ESPEggBot

### Project features
Child friendly, WiFi based EggBot with Web Interface. Just upload *.svg file and click button to start drawing.

[![Demo video](https://user-images.githubusercontent.com/19974755/60900190-cbf24a80-a239-11e9-9bfd-a68f9473a3cb.png)](https://youtu.be/IVm5nGUV1zs "Demo video")

### Hardware
1. NodeMCU board X 1 <br>
2. I2C 128x64 OLED Display X 1 <br>
3. DRV8825 Stepper Motor Driver X 2 <br>
4. L7805 5v Positive Voltage Regulator X 1 <br>
5. Hinge Lever Type Miniature Micro Switch X 2 <br>
6. 12V 3A Wall-Mount AC/DC Power Adapter X 1 <br>
7. Nema 17 Stepper motor X 2
8. SG90 Micro Servo Motor X 1
9. 3D printed EggBot parts, nuts and bolts

### Project goals 
- [x] No external software needed (assuming you already have .svg files). Open web browser, select .svg file, Click Start button.
- [x] Render WiFi QR Code on OLED screen to configure WiFi router's SSID and password.
- [x] Render EggBot IP Address QR Code on OLED screen to connect to EggBot UI from mobile device.
- [x] Friendly Web UI. (computer and mobile device)
- [x] Monitor progress from Web UI. (computer and mobile device)
- [x] Automatically split multi-colored .svg files into layers.
- [x] Auto Homing cycle (no need to remember to move arm) 
- [ ] Automatically stop and prompt to change the color pen when drawing with multiple colors.
- [ ] Automatically home cycle when start drawing and after changing color pen.

### Credits
 [EggBot](https://egg-bot.com/) <br>
 [Arduino](https://www.arduino.cc/en/main/software/)<br>
 [AccelStepper](https://www.airspayce.com/mikem/arduino/AccelStepper/) <br>
 [ESP8266 QRcode](https://github.com/anunpanya/ESP8266_QRcode) <br>
 [nanosvgjs](https://github.com/deanm/nanosvgjs) <br>
