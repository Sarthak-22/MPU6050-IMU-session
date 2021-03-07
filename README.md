# MPU6050 (IMU) session
## Electronics Club

### **Note**: 
The below procedure is meant for you to try out before the session and ensure everything is installed properly. However, **please note that** these instructions would not be repeated in the session from scratch and would be skipped. It would hardly take 15-20 mins to execute the below instructions, hence please try it out.

### Pre-session Instructions
* Download this Github repo as a zip folder (At the top right, click on the tab which says `Code`. Click on `Download ZIP`).
* The zip file should now be visibe in your system file storage. Extract all the files from that zip file, **except for `README.md`**, and store the remaining 3 files (index.html, style.css, script.js) inside a new folder named `data`.
* Store the folder `data` in a suitable location in your system storage which can be retrieved later.

### IMU webserver Pre-session instructions
* Search and install `Adafruit_MPU6050` library from `Sketch->Include Library->Manage Libraries` section in Arduino IDE. Install all the dependent libraries if there is any prompt for the same.
* Follow exactly the same procedure as above and install `Arduino_JSON` library in Arduino IDE.
* Download the zip file for the external libraries(not in-built in Arduino IDE) [ESPAsyncWebServer](https://github.com/me-no-dev/ESPAsyncWebServer/archive/master.zip) and [AsyncTCP](https://github.com/me-no-dev/AsyncTCP/archive/master.zip). Inorder to install these libraries in Arduino IDE, go to `Sketch->Include Library->Add .zip Library` and select the two libraries you just downloaded.
* Follow this [tutorial](https://randomnerdtutorials.com/install-esp32-filesystem-uploader-arduino-ide/) to understand and install **SPIFFS Plugin** in Arduino IDE for ESP32. **Follow the tutorial only until first 4 points for installing SPIFFS plugin. Do not execute anything else beyond that**. However, you can give it a read for your understanding.

### Basic Connection instructions
* In the custom board, you should see pin `SDA` and pin `21` adjacent to each other and pin `SCL` and pin `22` adjacent to each other.
* Connect these two pair of pins i.e `SDA with 21` and `SCL with 22` in your custom board using **Jumper caps** or **Jumper Wires**, whichever is available.
