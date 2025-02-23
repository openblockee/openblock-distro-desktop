# Change Log

## 2.5.4

- **Fix bug**

    1. Unable to properly load project files containing devices.
    2. Unable to double-click to open project files containing the device.

## 2.5.3

- **New feature**

    1. Use a separate configuration file to avoid conflicts with Arduino IDE.
    2. In pure scratch programming state without selecting a device, the signal strength icon is not displayed in the stage bar.

- **Fix bug**

    1. In realtime mode, when no device is connected, after running the program to assign the device block to the custom variable, the saved project will be corrupted and cannot be opened.
    2. Unsupported script action blocks are not hidden in upload mode.
    3. An error occurs when opening a project that does not contain hardware and was saved with a version of the software prior to V2.5.0.
    4. The software cannot get the focus normally after switching windows in Windows system.
    5. Software update function error.
    6. The block pasting function is not available.

## 2.5.2

- **New feature**

    1. Supports using environment variables to specify the path of external resources.

- **Fix bug**

    1. Some window images were lost and could not be displayed.
    2. The resources library file cannot be found.

## 2.5.1-1.0

- **New feature**

    1. Complete the merging work with the community version content, add multi-framework programming and external resource hot loading functions.
