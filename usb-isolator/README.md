USB Isolator PCB
================


Notes
-----

This is a very simple PCB so little documentation is needed.  Information
about the isolation can be found in the ADUM3160 [data sheet](http://www.analog.com/en/interface-isolation/digital-isolators/adum3160/products/product.html).

It is VERY important to realise that the power needs to come from a plug
pack and not the computer.  Supplying power to the power input from the
computer removes most of the isolation (data is still isolated).

Note that pin one is not marked on early versions of the PCB. Please refer
to the photo in this repository.

Parts
-----

PCBs are for sale on [Tindie](https://www.tindie.com/products/TomKeddie/usb-isolator-pcb-only/)

All the USB connectors were originally purchased on ebay.

You may be able to get a sample of the ADUM3160BRWZ from Analog Devices.

The parts list is below, thanks to Mike for supplying the connector part numbers, the rest should be fairly easy to determine.


| Qty | Value | Device | Parts | Description | Digikey | 
| --- | ----- | ------ | ----- | ----------- | ------- |
| 2 | 10uF | C-EUC0805K | C1, C6 | 10uF 0805 Ceramic Capacitor | |
| 4 | 0.1uF | C-EUC0805K | C2, C3, C4, C5 | 0.1uF 0805 Ceramic Capacitor | |
| 1 | 47uF | CPOL-EUD/7343-31W | C7 | 47uF 2917 Size "D" Tantalum Capacitor | |
| 4 | 24R | R-EU_M0805 | R1, R2, R3, R4 | 24R 0805 5% resistor | |
| 1 | 10K | R-EU_M0805 | R5 | 10k 0805 5% resistor | |
| 2 | 1K | R-EU_M0805 | R6, R7 | 1k 0805 5% resistor (rev 1.2 and later) | |
| 2 | GREEN | LED-0805 | LED1, LED2 | Green 0805 LED (rev 1.2 and later) | |
| 1 | ADUM3160BRWZ | SO16W | IC1 | Analog Devices ADUM3160BRWZ | |
| 1 | CON-USB-F-2PB | CON-USB-F-2PB | USBOUT | USB SMD Female connector with 2 body pins | 1175-1016-ND |
| 2 | CON-USB-F-MINI-B | CONN_USB_MINI-B | POWER, USBIN | USB Mini Female connector | 609-4700-1-ND |
| 1 | PCB_DP_SQUARE-5X5 | DP5050_V1 | USB-ISOLATOR | USB Isolator PCB | NA |
