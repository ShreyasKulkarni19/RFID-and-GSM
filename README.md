# RFID-and-GSM
This project uses a servo motor to simulate a door locking system. It also has a password protection for double authentication. The numeric keypad is placed. After three wrong entries, the owner gets an alert message to his/her mobile telling that someone is trying to access the security system.

1. RFID card must be placed on the scanner.
2. IF the card is a match, the person is asked to enter a 4 digit password. A seperate keypad is used for this passwrod entry.
3. Once the password is correct, the servo motor emulating the doorlock, moves 90 degrees indicating that the door is open now.
4. If the password is wrong, then the person has 2 more tries untill a message is sent to the owner's mobile telling that there is somebody accessing your security.
5. If the RFID is wrong, then a text appears on the LCD screen that says that the RFID card is a mismatch, door cannot be opened.
6. For commmunication between between the system and a mobile phone, GSM module is used. 
