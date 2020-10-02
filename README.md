This is the Python Source Code for Wireless Video Streaming using Raspberry Pi. This code runs on the RaspberryPi which acts as the server and renders real time video captured from the PiCamera. On the client side, we can use our browser to view the live stream.

Required Python Modules
1) io
2) picamera
3) logging 
4) socketserver 

Steps to Connect 
1) Go to the terminal of Raspberry Pi device. 
2) cd directory 
3) python PiVideoStreaming.py 
4) On the Client Side, to view the stream, visit http://<IP_Address_of_Pi>:8000 [as PORT = 8000] on your browser    
