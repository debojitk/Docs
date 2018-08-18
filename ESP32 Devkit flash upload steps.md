Button setting
--------------
#### EN:


    Reset button: pressing this button resets the system.
#### Boot:

    
    Download button: Holding down the Boot button and pressing the EN button initiates the firmware download mode. 
    Then user can download firmware through the serial port.


Hardware fix for automatic flash mode enter:
-------------------------------------------

Add a 2.2uf capacitor between EN and GND would fix the problem.

Ref=https://github.com/espressif/esptool/issues/136
