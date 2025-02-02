



# BCD-S3-DevKitC-1

ESP32-S3-WROOM-1-N16R8 Development Board

## Description

An ESP32-S3 development board based on Espressif's ESP32-S3-DevKitC-1.

![Board Description](/BCD-S3-DevKitC-1-N16R8V.images/BCD-S3-DevKitC-1-N16R8V_Description.png)

|Key Component         |Description                                                                         |
|----------------------|------------------------------------------------------------------------------------|
|ESP32-S3-WROOM-1-N16R8|ESP32-S3R8 with 3.3V, 8 MB Octal PSRAM die inside, 16 MB Quad SPI flash, PCB antenna.[^1]|
|3V3 LDO               |Power regulator that converts a 5 V supply into a 3.3 V output.|
|Boot Button           |Holding down Boot and then pressing Reset initiates Firmware Download mode for downloading firmware through the serial port.|
|Reset Button          |Press this button to restart the system.|
|RGB48 Config          |Configuration options for the RGB Led / GPIO 48.|
|USB-to-Uart Port      |A Micro-USB port used for power supply to the board, for flashing applications to the chip, as well as for communication with the chip via the on-board USB-to-UART bridge.|
|USB Port              |ESP32-S3 full-speed USB OTG interface, compliant with the USB 1.1 specification. The interface is used for power supply to the board, for flashing applications to the chip, for communication with the chip using USB 1.1 protocols, as well as for JTAG debugging.|
|UART Led              |Indicate if the USB-to-UART port is connected.|
|USB Led               |Indicate if the USB port is connected.|
|3V3 Power On          |Indicate if the 3V3 bus is powered.|
|TX Led                |Indicate if the serial bus is transmitting.|
|RX Led                |Indicate if the serial bus is receiving.|
|RGB Led               |Addressable RGB LED, driven by GPIO48.|

[^1]: GPIO35, GPIO36 and GPIO37 are used for the internal communication between ESP32-S3 and SPI flash/PSRAM memory, thus not available for external use.|

## Pinout

![Board Pinout](/BCD-S3-DevKitC-1-N16R8V.images/BCD-S3-DevKitC-1-N16R8V_Pinout.png)

## Bulding / Ordering PCB

The board layout and bill of material has been optimised for JLCPCB's capabilities and inventories to minimise cost. The footprint for the ESP32-S3 module has been optimised for hand-soldering since this part alone greatly increase the price of the assembly.

## Version History

* 1.0(2025-01-05)
    * Initial Release

## License

This project is licensed under the [BSD 3-Clause License](LICENSE).
