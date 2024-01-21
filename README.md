# Yet another nixie display RTC project.

### Overview
Wanted to desing esp32 powered control board usable for multiple different 8 tubes clock.
Want to make 3 iterations of clocks.

Will try to code in platformio.

Case: glass lid, 3d print support, metal exterior.
Single Type-C connector.

Based on Tom Titor design.

### Target for v1
PCB design in EAGLE. Fusion for case.
All caps MLCC.

1. Display board 
    * 2 layers
    * Minimal footprint
    * SMD only
    * Circuitry on one side (tubes on opposite)
    * HV path minimized
    * 8 tubes IN12
    * [HV552](https://ww1.microchip.com/downloads/en/DeviceDoc/HV5523-32-Channel-Serial-to-Parallel-Converter-with-Open-Drain-Outputs-Data-Sheet-20005700A.pdf)
    
    * optional: custom HV supply onboard
    
2. Control board (beta)
    * 2 layers
    * Modules usage
    * Same footprint as display
    * Circuitry on one side
    * ESP32
    * [DS3232](https://www.analog.com/media/en/technical-documentation/data-sheets/ds3232.pdf)
    * [Taylor Electronics HVPS 1364](https://www.shop-tes.com/content/Datasheets/8002K.pdf)
    * [Potentiometer](https://www.mouser.jp/datasheet/2/609/MAX5460_MAX5468-3129691.pdf)
    * Type C
    * Full control on HV 

    * optional: battery support

### Target for v2

2. Control board
    * 2 layers
    * Minimal footprint
    * SMD only except USB-c
    * No modules
    * Battery support


