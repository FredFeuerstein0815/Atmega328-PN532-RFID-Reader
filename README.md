# Atmega328-PN532-RFID-Reader
Use a Arduino Nano with Software Serial to read RFID-Tags with a PN532-RFID-Reader to switch the GPIOs LOW/HIGH.
Mismatch IDs will block the device for 30 seconds.(you can change it in the code)

Mit diesem Code lassen sich RFID-Chips mit einem PN532 lesen, um per Software-Serial die GPIOs eines Atmega328 zu schalten.
Beim Versuch mit einer falschen ID, wird das Gerät für 30 Sekunden gesperrt.(Lässt sich im Code einstellen)
