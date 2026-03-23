Introduction
An Automatic Toll Collection System (ATCS) eliminates manual toll booths by using RFID technology. Vehicles are equipped with RFID tags, and toll is deducted automatically when they pass through the toll gate.
This project uses:
•	ESP32 for processing & WiFi communication
•	RFID module (MFRC522) for vehicle identification
•	Firebase for real-time database & cloud storage

 Objective
•	Automate toll collection
•	Reduce traffic congestion
•	Maintain real-time vehicle records
•	Enable cashless transactions

  Working Principle
1.	Vehicle approaches toll gate
2.	RFID tag is scanned using MFRC522
3.	ESP32 reads UID of the tag
4.	UID is sent to Firebase
5.	Firebase checks balance
6.	If balance sufficient:
o	Deduct toll amount
o	Gate opens
7.	If insufficient:
o	Gate remains closed
o	Alert generated
