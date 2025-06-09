# micro-ROS
- [Adafruit ESP32-S3 Feather with 4MB Flash 2MB PSRAM](https://www.adafruit.com/product/5477)

<!-- ## Setup ESP32
- [Arduino IDE Download](https://www.arduino.cc/en/software/)
- plug in board and boot reset
- select com5 as source (should install esp32 library)
- go to Tools > Board> Adafruit Feather ESP32-S3 2MB PSRAM
- try uploading this sample blink code
    ```cpp
    void setup() {
    pinMode(LED_BUILTIN, OUTPUT);
    Serial.begin();
    }

    void loop() {
    digitalWrite(LED_BUILTIN, HIGH);
    delay(1000);
    digitalWrite(LED_BUILTIN, LOW);
    delay(1000);
    }
    ``` -->
## Installing ROS
- [ESP-IDF VS Code Extension Setup](https://github.com/espressif/vscode-esp-idf-extension/blob/master/README.md)
- [micro-ROS/micro_ros_espidf_component](https://github.com/micro-ROS/micro_ros_espidf_component/tree/humble)
- [cmake](https://cmake.org/download/)
-[Visual Studio 2022](https://visualstudio.microsoft.com/downloads/)
-[eProsima/Micro-XRCE-DDS-Client](https://github.com/eProsima/Micro-XRCE-DDS-Client)
<!-- - [ESP-IDF Getting Started](https://idf.espressif.com/) -->

In the Visual Studio Installer, confirm that Desktop development with C++ is selected and installed. Instead of a normal PowerShell prompt, open the x64 Native Tools Command Prompt for VS 2022 (search in Start Menu) and try the cmake command there:
```powershell
cmake -G "Visual Studio 17 2022" -A x64 ..
```

## Youtube
- [Youtube Tutorial 1](https://www.youtube.com/watch?v=XDDcS7HQNlI)
- [Youtube Tutorial 2](https://www.youtube.com/watch?v=EBXK3Mr6y7I)
- [Youtube Tutorial 3](https://youtube.com/playlist?list=PL1YH3iMfizDJge1nDCuEMvCvhBkKinIJ-&si=OmQa3Vp86LegoRsm)