# Voice assistant based on Voice Assistant PE

# 1. Hardware
- ESP32 S3 16MB -> https://aliexpress.com/item/1005005051294262.html
- 2x Max98357 -> https://aliexpress.com/item/1005007008134910.html
- INMP441 -> https://aliexpress.com/item/1005007096781008.html
- LED Ring 12 LEDs -> https://aliexpress.com/item/1005007095317230.html
- Speaker 10W 4ohm for high tones -> https://aliexpress.com/item/1005007917972560.html
- Speaker 3W 4ohm for low tones -> https://aliexpress.com/item/32593991938.html
- Power socket USB-C -> https://aliexpress.com/item/1005007469691687.html
- Fabric for front cover np. -> https://allegro.pl/oferta/11641954458

# 2. Schema
It will be most convenient to follow what is in the ESPHome code (one of the first lines of code and comments), but if someone prefers, the diagram is shown below

WE CAN CONNECT ADDITIONALLY 'GAIN' TO 'GND' TO GET MORE SOUND AMPLIFICATION

![output-onlinepngtools](https://github.com/user-attachments/assets/ad5f3680-0635-48ea-a07e-813f39d14be7)

# 3. Speaker housing
.stl files available in the repository. I personally printed with FuzzySkin so that the layers were not visible

# 4. Software
The ESPHome code is built on the Voice Assistant PE. All parameters are at the top - pinout and staticIp (I prefer setting static device addresses)

# 5. My settings in Home Assistant
<img width="618" alt="image" src="https://github.com/user-attachments/assets/da9301a7-b4f6-4a19-901c-776bcd00e4a8" />

# 6. Effect and summary
The current version works very well even from 10 meters. Interference such as a TV being on does not bother, but if there are dialogues coming from the TV, the device listens longer (ultimately it responds well to our text, not dialogues from the TV)

![IMG_9459](https://github.com/user-attachments/assets/95178788-29d4-473c-92dd-2e7483edc058)

![IMG_9460](https://github.com/user-attachments/assets/0c09ec26-d581-492c-8a72-d44eafb48b19)

![IMG_9462](https://github.com/user-attachments/assets/22aa4b56-518c-49d8-9433-fe9b649370be)

![IMG_9463](https://github.com/user-attachments/assets/6f9fe57a-90d1-4e92-8b4f-064b80ec22da)

![IMG_9464](https://github.com/user-attachments/assets/ac6c1fdf-078f-45b4-bea9-d3d83eec440f)

![84A6D293-C8E8-4F24-B70F-969A713F1935_1_105_c](https://github.com/user-attachments/assets/4a830cac-edf9-4ba4-bfde-567adc4419e5)


# 7. Video of the 1-10 meter operation and a second video with interference in the form of the TV being turned on

[![Watch the video](https://img.youtube.com/vi/tZ6E8j-09wc/maxresdefault.jpg)](https://youtu.be/tZ6E8j-09wc)

[![Watch the video](https://img.youtube.com/vi/Pw-N4Iyd6_c/maxresdefault.jpg)](https://youtu.be/Pw-N4Iyd6_c)

