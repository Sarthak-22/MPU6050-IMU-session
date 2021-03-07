# MPU6050 (IMU) session
## Electronics Club

### Pre-session Instructions
* Download this Github repo as a zip folder (At the top left, click on the tab which says `Code`. Click on `Download ZIP`).
* The zip file should now be visibe in your system file storage. Extract all the files from that zip file, **except for `README.md`**, and store the remaining 3 files (index.html, style.css, script.js) inside a new folder named `data`.
* Store the folder `data` in a suitable location in your system storage which can be retrieved later.

### IMU webserver Pre-session instructions
* Search and install `Adafruit_MPU6050` library from `Sketch->Include Library->Manage Libraries` section in Arduino IDE. Install all the dependent libraries if there is any prompt for the same.
* Follow exactly the same procedure as above and install `Arduino_JSON` library in Arduino IDE.
* Download the zip file for the external libraries(not in-built in Arduino IDE) [ESPAsyncWebServer](https://github.com/me-no-dev/ESPAsyncWebServer/archive/master.zip) and [AsyncTCP](https://github.com/me-no-dev/AsyncTCP/archive/master.zip). Inorder to install these libraries in Arduino IDE, go to `Sketch->Include Library->Add .zip Library` and select the tw libraries you have just downloaded.
* Follow this [tutorial](https://randomnerdtutorials.com/install-esp32-filesystem-uploader-arduino-ide/) to understand and install **SPIFFS Plugin** in Arduino IDE for ESP32.
