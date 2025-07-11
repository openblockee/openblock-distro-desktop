# Change Log

## 2.6.3-1.3

- **Fix bug**

    1. Fixed the compile error of esp32 due to the change of pwm and servo functions after updating arduino core.
    2. Fixed serious errors in esp32s3 control board. Adjusted the pin list and function blocks.
    3. Fixed the possible conflict between ESP32x board servo and PWM function.
    4. Change the default pin of esp32 block to io4.

## 2.6.1-1.2

- **New feature**

    1. Use 7z format to publish the installation package for macos in github release.
    2. No longer publish on Google Drive.

- **Fix bug**

    1. Unsupported realtime mode extensions showing up in upload mode extensions selection menu.

## 2.6.0-1.1

- **New feature**

    1. Use a separate configuration file to avoid conflicts with Arduino IDE.
    2. In pure scratch programming state without selecting a device, the signal strength icon is not displayed in the stage bar.
    3. Supports using environment variables to specify the path of external resources.
    4. Added new built-in boards: UNOR4, ESP32S3, PRI PICO W, PRI PICO 2, PRI PICO 2 W.
    5. Allow users in China to choose whether to skip the main program update check.

- **Fix bug**

    1. Unable to properly load project files containing devices.
    2. Unable to double-click to open project files containing the device.
    3. In realtime mode, when no device is connected, after running the program to assign the device block to the custom variable, the saved project will be corrupted and cannot be opened.
    4. Unsupported script action blocks are not hidden in upload mode.
    5. An error occurs when opening a project that does not contain hardware and was saved with a version of the software prior to V2.5.0.
    6. The software cannot get the focus normally after switching windows in Windows system.
    7. Software update function error.
    8. The block pasting function is not available.
    9. Some window images were lost and could not be displayed.
    10. The resources library file cannot be found.

## 2.5.1-1.0

- **New feature**

    1. Complete the merging work with the community version content, add multi-framework programming and external resource hot loading functions.
