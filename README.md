# SecurityCam
ESP32 security cam Arduino

This is an old project I wrote a few years ago that I wanted to repurpose as an IoT project.
It involves configuring an ESP32 wi-fi as a sensing sensor to send the image that is captured into a telegram chatbot.

I created this script so that whoever takes this code only has to change the SSID of his wi-fi network, the password, the TokenBot and the ChatID. 

My ESP32 has a modular camera that I specially inserted to be able to do this experiment. I have another script where you can also turn on the flash during photo capture but you don't always get a sharp photo so I preferred to remove this feature.
