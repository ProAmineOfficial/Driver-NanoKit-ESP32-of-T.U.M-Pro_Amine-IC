# NanoKit Integrated ESP32 of UMT (Pro_Amine IC) Windows Driver

This repository contains the Windows driver for **NanoKit Integrated ESP32 board** developed by **Pro_Amine Inc.**. This driver is customized from the Silicon Labs CP210x USB to UART Bridge driver to properly recognize and interface with NanoKit Integrated ESP32 board.

## How to Install the Driver

### 1. Download the Driver

- You can download the latest version of the driver from the [Releases](https://github.com/ProAmineOfficial/Driver-NanoKit-ESP32-of-T.U.M-Pro_Amine-IC/releases) section.

### 2. Temporarily Disable Driver Signature Enforcement and Install the Unsigned Driver
If you encounter an issue related to driver signature during installation, follow these steps to temporarily disable driver signature enforcement:

1. **Press and hold the Shift key** while clicking **Restart** from the Start menu.
2. **The system will restart and open the Advanced Startup menu**.
3. **Select** `Troubleshoot > Advanced Options > Startup Settings`.
4. **Click** `Restart`.
5. **Upon restarting, select the option** `Disable driver signature enforcement` **by pressing the appropriate key (usually F7)**.
6. **After disabling driver signature enforcement, proceed to install the unsigned driver** as described in the previous steps.

 
### 3. Install the Driver
- After downloading, extract the contents of the ZIP file.
- Open **Device Manager** on your Windows PC.
- Locate the **NanoKit Integrated ESP32** device under "Other devices".
- Right-click the device and choose **Update driver**.
- Select **Browse my computer for driver software**.
- Navigate to the folder where you extracted the driver files.
- Click **Next** to install the driver.



### 4. Verify Installation
- Once the installation is complete, the device should appear under **Ports (COM & LPT)** in **Device Manager** as `NanoKit Integrated ESP32 of UMT (Pro_Amine IC)`.

## Features
- **Automatic Recognition**: Automatically recognizes NanoKit Integrated ESP32 boards.
- **Compatibility**: Fully compatible with all standard USB to UART operations.
- **Open Source**: Licensed under the MIT License.

## License
This project is open-source and licensed under the MIT License. See the `LICENSE` file for more details.

## Support
For any issues, suggestions, or contributions, please contact **Pro_Amine Inc.** at https://proamine.tech/.
