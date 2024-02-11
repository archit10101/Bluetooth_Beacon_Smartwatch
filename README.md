# Bluetooth Low Energy Distance Monitoring App

This Android application is designed to connect to multiple Bluetooth Low Energy (BLE) devices, facilitating distance monitoring between them. The main components of this application include:

## Beacon
The beacon utilized in this application is a XIAO ESP32C3 microcontroller. It establishes a Bluetooth connection with an Android smartwatch and broadcasts information about its position. Additionally, it utilizes the received signal strength indicator (RSSI) to determine the distance from the smartwatch.

## Microcontroller
This device acts as the receiver of the data transmitted by the smartwatch. When the smartwatch enters a certain range of distance from the beacon, it broadcasts a signal indicating that it is too close.

## Functionality
The primary function of this application is to determine the proximity between the XIAO ESP32C3 beacon and an Android smartwatch. It then relays this information to another microcontroller, allowing the user to utilize the data as per their requirements.

## Usage
To use this application, follow these steps:

1. Install the application on your Android device.
2. Ensure that your Android device supports Bluetooth Low Energy.
3. Power on the XIAO ESP32C3 beacon and the microcontroller.
4. Pair the Android device with the beacon.
5. Monitor the distance readings between the beacon and the smartwatch using the application.

## Note
This application serves as a demonstration of BLE distance monitoring and can be customized or integrated into larger projects as needed.

For more information, refer to the documentation or contact the repository owner.

**Disclaimer**: This application is provided as-is without any warranty. Use at your own risk.

---

Feel free to contribute or provide feedback by opening an issue or submitting a pull request!
