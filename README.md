# It's a home automation system where:

 - The door will open if anyone comes near at the door within 40cm and door will be open for 2 seconds. Then it will check again if anyone is still within 40cm, if yes, then the door will still open for 2 more seconds and if no, then the door will automatically be closed. ( I used here Ultrasonic Sensor for measuring distance and Servo motor for opening the door
 
 - If the room detects any movement, the light (LED) will automatically be lighting. If there is no movement in the room, then the light will remain off. ( I used here PIR for detecting movement and LED for Light )
 
 - It will detect room temperature and if that is greater than 20 (degree Celsius) then a fan will be running, otherwise, the fan will remain stopped. (I used here temperature sensor LM35 for detecting temperature and a motor for running a fan)
