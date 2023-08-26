# RoBat
Design and Robotics course AY 21/22
5 Team Members (three computer science engineers and two designers) project

Demo video here -> https://www.instagram.com/reel/CfEaHMZKv9c/
 
### Platform
- Raspberry Pi 3B
- 2x ST7735 displays
- Passive buzzer
- Fish eye camera module
- 2x HC-SR04 sensors

### Dependencies
- cv2
- PIL
- adafruit_rgb_display

### Run
To run the code just launch `rpi/main.py`, or set `crontab` to execute it during startup.

### Debug
To see the results of the camera while it's processing images, you should:
1. Connect a client and the board to the same network
2. In `rpi/constants.py` set `ARGS["debug"]` to `True`
3. Run `client/videorx.py` and `rpi/main.py` together
> **_Note_**: the client machine must also have cv2 installed
