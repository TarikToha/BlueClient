# BLE Peripheral macOS App

## Project Summary

- A macOS app built with Swift, Cocoa (AppKit), and CoreBluetooth.
- Acts as a BLE Peripheral that advertises a custom GATT service.
- Defines two characteristics:
  - rxCharacteristic (notify) to send data to a connected central.
  - txCharacteristic (writeWithoutResponse) to receive data from a central.
- Advertising is manually triggered via a user interface button.
- Stops advertising once a central subscribes to the notify characteristic.
- Allows users to input and send messages through the GUI.
- Displays a real-time debug log in the interface using NSTextField.
- Handles Bluetooth state updates, subscriptions, and data exchange.
