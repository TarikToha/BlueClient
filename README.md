# BLE Peripheral macOS App

## Project Summary

- A macOS app developed using Swift, Cocoa, and CoreBluetooth.
- Acts as a BLE Peripheral that advertises a custom service with two characteristics.
- rxCharacteristic (notify) is used to send data to the connected central device.
- txCharacteristic (writeWithoutResponse) is used to receive data from the central.
- Begins advertising when the user starts the process and the peripheral is ready.
- Stops advertising automatically once a central subscribes to the notify characteristic.
- Allows the user to send text input to the connected central.
- Logs Bluetooth status updates, subscription events, and message exchange in a debug area.
