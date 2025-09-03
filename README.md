Used LPC2129 microcontroller for getting access to RFID module.
RFID module is connected to the lpc2129 microcontroller and used I2C protocol for communication between the rfid module and microtroller.
Linux tty used to communicate with the microcontroller to get the rfid module scanned data to the system.
When RFID card is placed near to thge module,it gets scanned and the 11 digit unique identification number tagged to the card is acquired by the system.
Now this number is scanned in the database we had created in our system.
if the number number is matched in the database then the attendence of the person who scanned the card will be marked present.
Along with the attendende in time and out also marked or noted.
