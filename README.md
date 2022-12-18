# Job 1.1 ESP NOW

## Alat dan Bahan
1. ESP32 >4
2. Arduino IDE (Terinstal ESP32)
3. Library DHT dan Adafruit unified sensor
4. Breadboard
5. Kabel Jumper
6. Resistor < 220Ω
7. Sensor DHT

## Instalasi ESP32
1. Buka Arduino IDE
   - Masuk ke Preferences
   - Isikan board url dengan link : https://dl.espressif.com/dl/package_esp32_index.json dan simpan
   - Buka Tools > Board > Boards Manager
   - Cari ESP32, by Espressif. Kemudian instal
   - Pilih flash mode DIO/QIU menyesuaikan
2. Jalankan program .ino
3. Jika terdapat error saat uploading, tekan dan tahan tombol Boot pada ESP32 saat upload, hingga Connecting selesai

## Instalasi DHT & Adafruit Libraries
1. Buka Arduino IDE
2. Buka Sketch > Include Library > Library Manager
3. Cari DHT sensor library by Adafruit. Kemudian instal. Atau dapat melalui link DHT Library dan upload pada libraries di direktori projek. Rename direktori menjadi DHT_sensor_library.
4. Instal juga library Adafruit unified sensor by Adafruit. Atau dapat melalui link Adafruit Sensor dan upload pada libraries di direktori projek. Rename direktori menjadi Adafruit_Unified_Sensor.
