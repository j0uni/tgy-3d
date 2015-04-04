This is a fork of the SimonK ESC firmware.

All hex files are in 3D mode allowing both normal and reverse rotation of the motor.

I used following command on OS X to flash the FW:

/Applications/Arduino.app/Contents/Resources/Java/hardware/tools/avr/bin/avrdude -e -c usbasp -pm8 -U flash:w:afro_nfet.hex

