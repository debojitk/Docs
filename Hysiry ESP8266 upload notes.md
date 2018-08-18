Hysiry Devices
--------------
For all Hysiry devices flash mode settings are:

Upload mode-DIO. In Arduino IDE always select Node MCU 1.0 (and not 0.9). It uses DIO mode by default.
Speed-40M
Upload speed-115200, VVI-with pl2303 upload speed should be 115200 during upload. It does not support higher values.
Max serial baud rate - 921600, 1000000 did not work on these devices

