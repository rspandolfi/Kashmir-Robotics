How to Flash Pixracer firmware to ESP-01 (ESP8266) WiFi module

1.  Remove ESP826 Programming Assembly from Shoebox over Ron’s Table

2.  Plug WSP-01 into 8-pin socket

3.  Plug USB cable into Laptop

4.  Open ESP Flash Utility V3.4.8 (download first if not on Laptop)

5.  Select ESP8266 Download Tool

6.  Read ESP-01

    1.  Press and hold Reset button (SW1) for 5 seconds (do not release yet)

    2.  Press and hold Flash button (SW2) for 5 seconds

    3.  Release Reset button

    4.  Release Flash button

    5.  Press Start button at the lower left of the tool window

7.  Write Firmware

    1.  Select Pixracer Firmware-1.1.1.bin\@0x0000(download first if not on your
        Laptop

    2.  Observe firmware and location are “green”

    3.  Press and hold Reset button (SW1) for 5 seconds (do not release yet)

    4.  Press and hold Flash button (SW2) for 5 seconds

    5.  Release Reset button

    6.  Release Flash button

    7.  After Flash is completed, press Reset button and remove USB cable from
        Laptop

For more information, refer
to: <https://www.allaboutcircuits.com/projects/flashing-the-ESP-01-firmware-to-SDK-v2.0.0-is-easier-now/>
