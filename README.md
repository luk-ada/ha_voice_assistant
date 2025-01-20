# Asystent głosowy na bazie Voice Assistant PE

# 1. Hardware
- ESP32 S3 16MB -> https://aliexpress.com/item/1005005051294262.html
- 2x Max98357 -> https://aliexpress.com/item/1005007008134910.html
- INMP441 -> https://aliexpress.com/item/1005007096781008.html
- LED Ring 12 LEDs -> https://aliexpress.com/item/1005007095317230.html
- Głośnik 10W 4ohm dla wysokich tonów -> https://aliexpress.com/item/1005007917972560.html
- Głośnik 10W 4ohm dla niskich tonów -> https://aliexpress.com/item/1005006867491648.html
- Gniazdo zasilania USB-C -> https://aliexpress.com/item/1005007469691687.html

# 2. Połącznie
Najwygodniej będzie sugerować się tym co jest w kodzie ESPHome (jedne z pierwszych linii kodu i komentarzami), ale jak ktoś woli to poniżej schemat rysunkowy
![output-onlinepngtools](https://github.com/user-attachments/assets/ad5f3680-0635-48ea-a07e-813f39d14be7)

# 3. Obudowa
Pliki .stl dostępny w repozytorium. Osobiście drukowałem z funkcją FuzzySkin, aby nie było widać warstw

# 4. Software
Kod ESPHome jest zbudowany na bazie Voice Assistant PE. Wszystkie parametey są na górze - pinout oraz staticIp (preferuję ustawianie statycznych adresów urządzeń)

# 5. Ustawienie w Home Assistant
<img width="618" alt="image" src="https://github.com/user-attachments/assets/da9301a7-b4f6-4a19-901c-776bcd00e4a8" />

# 6. Efekt i podsumowanie
Aktualna wersja działa bardzo dobrze nawet z 10 metrów. Zakłócenia takie jak włączony TV nie przeszkadza, ale jeśli z TV lecą dialogi to urządzenie dłużej nasłuchuje (finalnie dobrze reaguje na nasz tekst, a nie dialogi z TV)
![IMG_9459](https://github.com/user-attachments/assets/95178788-29d4-473c-92dd-2e7483edc058)

![IMG_9460](https://github.com/user-attachments/assets/0c09ec26-d581-492c-8a72-d44eafb48b19)

![IMG_9462](https://github.com/user-attachments/assets/22aa4b56-518c-49d8-9433-fe9b649370be)

![IMG_9463](https://github.com/user-attachments/assets/6f9fe57a-90d1-4e92-8b4f-064b80ec22da)

![IMG_9464](https://github.com/user-attachments/assets/ac6c1fdf-078f-45b4-bea9-d3d83eec440f)

# 7. Wideo działania 1-10 metrów oraz drugie wideo z zakłóceniami w postaci włączonego TV

[![Watch the video](https://img.youtube.com/vi/tZ6E8j-09wc/maxresdefault.jpg)](https://youtu.be/tZ6E8j-09wc)

[![Watch the video](https://img.youtube.com/vi/Pw-N4Iyd6_c/maxresdefault.jpg)](https://youtu.be/Pw-N4Iyd6_c)

