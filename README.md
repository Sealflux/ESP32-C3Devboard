# ESP32-C3Devboard
## Description
Custom ESP32-C3 Devboard with bulit in charging, wifi and antenna.
## Features
- ESP32-C3 which has wifi capabilities along with bulit in charging for lipo battery.
- 16 MB of onboard flash storage
- Charges through USB-C
- Tactile button to reset.
## Hardware
- ESP32-C3
- BLE Wifi
- Battery Charging
- Lots and lots of capacitors and resistors


# Bill Of Materials (BOM)
| Designator | Part | Qty | Cost (each) | Total | Link | LCSC # |
|------------|------|:---:|------------|-------|------|--------|
| BT1 | Battery Cell | 1 | Depends on battery | Depends on battery | Depends on battery | N/A |
| C1, C5, C6, C7 | 100nF Capacitor (0402) | 4 |$0.0073|$0.73| [LCSC](https://lcsc.com/product-detail/C60474.html) | C60474 |
| C2, C3, C4, C9 | 10µF Capacitor (0603) | 4 |$0.0411|$0.82| [LCSC](https://lcsc.com/product-detail/C85713.html) | C85713 |
| C8 | 1µF Capacitor (0603) | 1 |$0.0225|$1.13| [LCSC](https://lcsc.com/product-detail/C29936.html) | C29936 |
| J1 | USB-C Receptacle USB2.0 14P | 1 |$0.1709|$0.1709| [LCSC](https://www.lcsc.com/product-detail/C165948.html) | C165948 |
| J2, J3 | 1x12 Pin Header (2.54mm) | 2 |N/A|Generic, use whatever you want.| N/A | N/A |
| R1, R11 | 1kΩ Resistor (0603) | 2 |$0.0045|0.45 | [LCSC](https://lcsc.com/product-detail/C2907002.html) | C2907002 |
| R2, R8, R9, R10 | 10kΩ Resistor (0402) | 4 |$0.0038|0.38| [LCSC](https://lcsc.com/product-detail/C60490.html) | C60490 |
| R3, R4 | 5.1kΩ Resistor (0603) | 2 |$0.0027|0.27| [LCSC](https://lcsc.com/product-detail/C2907044.html) | C2907044 |
| R6 | 2.2kΩ Resistor (0402) | 1 |$0.0024|$0.24| [LCSC](https://lcsc.com/product-detail/C2906865.html) | C2906865 |
| SW1, SW2 | Push Button Switch (B3U-1000PM) | 2 |$0.1869|$0.93|[LCSC](https://www.lcsc.com/product-detail/C231329.html)| C231329 |
| U1 | ESP32-C3 (QFN-32) | 1 |N/A|Depends on where you buy from|[Datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-c3_datasheet_en.pdf) | N/A |
| U2 | W25Q16JVUXIQ (USON-8) | 1 |$1.6193|$1.6193| [LCSC](https://lcsc.com/product-detail/C2843335.html) | C2843335 |
| U3 | H7233-1 LDO (SOT-23-3) | 1 |$0.1102|$0.55| [LCSC](https://lcsc.com/product-detail/C277859.html) | C277859 |
| U4 | TP4056 Battery Charger (ESOP-8) | 1 |$0.1864|$0.93 | [LCSC](https://lcsc.com/product-detail/C16581.html) | C16581 |
| | **Shipping** | | | Depends on your address | | |
| | **Total Costs** | | | Without shipping | | |


## Steps To Reproduce
1. Download the gerbers.zip from production folder
2. Manufacture the PCBs from whatever manufacturer you want using the gerbers.zip
3. Order the components from BOM
4. Solder the components onto the PCBs
5. Enjoy your dev board!
## Schematic
![image](https://cdn.hackclub.com/019fdd21-2753-7a5b-98aa-21d6a796d512/paste-1786121362317.png)
## PCB
![image](https://cdn.hackclub.com/019fdd21-852c-774c-b6b6-3f0114b938ce/paste-1786121388260.png)
## PCBA
![image](https://cdn.hackclub.com/019fdd22-1bd0-78ee-bd46-58197b9e40fe/paste-1786121425258.png)