
# M2_biometric 
### Fingerprint attendance systems are already readily available directly from the market, but what is more fun than building one?
We have also built a wide variety of Attendance Systems  earlier from a simple RFID based Attendance system to an IoT based biometric Attendance system  using Arduino and Raspberry Pi. 
In this project, we have used fingerprint Module and AVR(atmega32) to register attendance. By using fingerprint sensor, the system will become more secure for the users. Following sections explains technical details of making a fingerprint-based Biometric Attendance System using AVR.

![block diagram](https://user-images.githubusercontent.com/91199828/164916294-a0f5012d-2a3b-495d-a965-3f6bfd352c70.png)


In this fingerprint attendance system circuit, we have used the Fingerprint Sensor module to authenticate a person or employee’s identity by taking their finger-print input in the system. Here we are using 4 push buttons to enroll, Delete, Increment and Decrement finger-print data. Key 1 is used for enrollment of a new person into the system. So when the user wants to enroll a new finger, then he/she need to press key 1 then LCD asks him/her to place a finger on fingerprint sensor two times then it asks for an employee ID. Similarly, key 2 has double function, like when user enrolls new finger, then he/she need to select finger-print ID by using another two keys namely 3 and 4. Now user need to press key 1 (this time this key behave like OK) to proceed with selected ID. And key 2 is also used for reset or delete data from EEPROM of microcontroller.


![download](https://user-images.githubusercontent.com/91199828/164981990-a4598cef-6e7a-475a-8afc-e6d030e819d2.jpg)









Fingerprint sensor module captures finger’s print image and then converts it into the equivalent template and saves them into its memory as per selected ID by microcontroller. All the process is commanded by the microcontroller, like taking an image of finger’s print; convert it into templates and storing as ID etc. You can also check out these other finger print sensor projects, where we have built finger print sensor security system and fingerprint sensor voting machine.   

![Components-Required-for-Fingerprint-Based-Biometric-Attendance-System](https://user-images.githubusercontent.com/91199828/164912766-293a9ca9-abbe-47fd-bab4-e7f8cc95d800.jpg)
