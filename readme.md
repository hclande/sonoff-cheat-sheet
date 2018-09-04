# sonoff cheatsheet

# flash prosedyre

https://www.youtube.com/watch?v=UDnNI5wkNNY


 1. last ned ESPEASY : https://github.com/letscontrolit/ESPE...
 2. kopier esptool.exe og FlashESP8266.exe til en egnet mappe
 3. last ned tasmota bin fil: https://github.com/arendst/Sonoff-Tasmota/releases
    eks sonoff.bin
 4. last ned termite : https://www.compuphase.com/software_termite.htm
 5. kopier bin fil til mappen med esptool filene
 6. koble sonoff og plugg i usb mens knappen på sonoff holdes inne :
    ![pinout](https://github.com/hclande/sonoff-cheat-sheet/blob/master/pinout.jpg)

 7. åpne flashESP8266.exe, velg com port, bin og trykk flash

 8. restart sonoff. plugg inn på ny uten å holde inne knappen 
 
 
# sette opp wifi
 
 
 1. restart sonoff. plugg inn på ny uten å holde inne knappen
 2. start termite, velg com port og baudrate 115200 
 3. kommando: ssid1 "skriv inn ssid her"
 4. kommando: password1 "skriv inn passord her"
 
# sett opp statisk ip


  les ip adressen i kommando vindu etter du har satt opp ip


1. skriv kommando:
    ipaddress1 "ip adressen" 
2. skriv kommando : ipaddress2 "gateway"
3. skriv kommando : ipaddress3 "subnetmask"


# restart 
 skriv inn kommando for restart: restart 1