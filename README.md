# CAN-Examples
Przykład użycia SocketCAN w URVEBoardzie A18 PRO (Linux/Rockchip 3288)

* Port can0 jest ustawiony w kodzie na stałe, możesz to łatwo zmienić

 Aby skompilować przykład użyj /opt/gcc/bin/arm-linux-gnueabihf-cpp:
```
$ /opt/gcc/bin/arm-linux-gnueabihf-cpp cantransmit.c -o cantransmit

$ /opt/gcc/bin/arm-linux-gnueabihf-cpp canreceive.c -o canreceive

$ /opt/gcc/bin/arm-linux-gnueabihf-cpp canfilter.c -o canfilter
```
