# LiveStreamRaspberryPi
This is the Python Source Code for Wireless Video Streaming using Raspberry Pi. This code runs on the RaspberryPi which acts as the server and renders real time video captured from the PiCamera. On the client side, we can use our browser to view the live stream.

## PIP Modules
- io
- picamera
- logging
- socketserver 

## Steps to Connect 
- Go to the terminal of Raspberry Pi device.
- cd directory
- python PiVideoStreaming.py
- On the Client Side, to view the stream, visit http://<IP_Address_of_Pi>:8000 [as PORT = 8000] on your browser    
