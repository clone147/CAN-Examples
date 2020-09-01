# CAN-Examples
Przykład użycia SocketCAN w URVEBoardzie A18 PRO (Linux/Rockchip 3288)
 

* Based on documentation at: https://www.kernel.org/doc/Documentation/networking/can.txt
* A simplified tutorial can be found at: https://www.beyondlogic.org/example-c-socketcan-code/
* Hardcoded to use the vcan0 virtual CAN device.

 Aby skompilować przykład użyj /opt/gcc/bin/arm-linux-gnueabihf-cpp:
```
$ /opt/gcc/bin/arm-linux-gnueabihf-cpp cantransmit.c -o cantransmit

$ /opt/gcc/bin/arm-linux-gnueabihf-cpp canreceive.c -o canreceive

$ /opt/gcc/bin/arm-linux-gnueabihf-cpp canfilter.c -o canfilter
```
