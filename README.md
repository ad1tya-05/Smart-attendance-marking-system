# Smart-home-automation-system

Working of our project -
-> After the code is executed in the terminal, there is a scan RFid message 
-> After we scan the rfid at the reader, if the rfid is registered in the database/if it is genuine, it shows an authorized rfid msg in the terminal. If not, it shows unauthorized rfid
-> If the RFid is genuine, the camera opens and takes the picture of the person in front of it 
-> If the photo taken matches the one in our database and is matching with corresponding RfId, it shows detected and recognized, and the door opens and closes after 5 seconds 
-> Then the attendance is marked in thingspeak and a mail is sent to the student regarding the same 
-> If the face is not detected or does not match the terminal shows, the message of the same .
Refer to the videos for better understanding

Componenet used 
- SMTP
- Thingspeak
- Pi Camera
- servo motor
- RFID(MFRC522)
- Raspberry Pi 4B

  
