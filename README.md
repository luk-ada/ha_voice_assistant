# Asystant głosowy na bazie Voice Assistant PE

# 1. Hardware
- ESP32 S3 16MB -> https://pl.aliexpress.com/item/1005005051294262.html
- 2x Max98357 -> https://pl.aliexpress.com/item/1005007008134910.html
- INMP441 -> https://pl.aliexpress.com/item/1005007096781008.html
- LED Ring 12 LEDs -> https://pl.aliexpress.com/item/1005007095317230.html
- Głośnik 10W 4ohm dla wysokich tonów -> https://pl.aliexpress.com/item/1005007917972560.html
- Głośnik 10W 4ohm dla niskich tonów -> https://pl.aliexpress.com/item/1005006867491648.html
- Gniazdo zasilania USV-C -> https://pl.aliexpress.com/item/1005007469691687.html

# 2. Połącznie
![Diagram bez tytułu drawio](https://github.com/user-attachments/assets/f2bd5215-939a-458b-85e2-fd8fd9ef8820)

# 3. Obudowa
Pliki .stl dostępny w repozytorium. Osobiście drukowałem z funkcją FuzzySkin, aby nie było widać warstw

# 4. Software
Kod ESPHome jest zbudowany na bazie Voice Assistant PE. Wszystkie parametey są na górze - pinout oraz staticIp (preferuję ustawianie statycznych adresów urządzeń)

# 5. Ustawienie w Home Assistant
<img width="618" alt="image" src="https://github.com/user-attachments/assets/da9301a7-b4f6-4a19-901c-776bcd00e4a8" />

# 6. Efekt i podsumowanie
Aktualna wersja działa bardzo dobrze nawet z 10 metrów. Zakłucenia takie jak włączony TV nie przeszkadza, ale jeśli z TV lecą dialogi to urządzenie dłużej nasłuchuje (finalnie dobrze reaguje na nasz tekst, a nie dialogi z TV)
![IMG_9459](https://github.com/user-attachments/assets/95178788-29d4-473c-92dd-2e7483edc058)

![IMG_9460](https://github.com/user-attachments/assets/0c09ec26-d581-492c-8a72-d44eafb48b19)

![IMG_9462](https://github.com/user-attachments/assets/22aa4b56-518c-49d8-9433-fe9b649370be)

![IMG_9463](https://github.com/user-attachments/assets/6f9fe57a-90d1-4e92-8b4f-064b80ec22da)

![IMG_9464](https://github.com/user-attachments/assets/ac6c1fdf-078f-45b4-bea9-d3d83eec440f)


