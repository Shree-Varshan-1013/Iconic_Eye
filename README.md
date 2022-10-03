# Iconic_Eye
# Its like a third eye that captures photo when motion is detected.
the photos are send to user's telegram account. The major components are ESP32CAM, FTDI USB, PIR SENSOR.
The ESP32-CAM provides an inexpensive way to build more advanced home automation projects that feature video, taking photos, and face recognition and the FTDI USB Serial Port driver is the software that helps your operating system to communicate with USB Serial Port devices and finally the Passive infrared (PIR) sensors use a pair of pyroelectric sensors to detect heat energy in the surrounding environment. 
These two sensors sit beside each other, and when the signal differential between the two sensors changes.

We can use ESP32CAM in both online and offline cases . let's talk about offline case it doesn't need WIFI for communication and it manually stores the picture in the MicroSD card and later when u want to see the pictures you simply remove the MicroSD card from ESP32CAM and read it by using card reader but it needs a constant 5V External power supply. 

Next online case it requires WIFI connection to send and receive messages here we don't need MicroSD card and for long meter connections we use IPEX connector.
