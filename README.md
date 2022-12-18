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
3. Cari DHT sensor library by Adafruit, kemudian instal. Atau dapat melalui link DHT Library dan upload pada libraries di direktori projek. Rename direktori menjadi DHT_sensor_library.
4. Instal juga library Adafruit unified sensor by Adafruit. Atau dapat melalui link Adafruit Sensor dan upload pada libraries di direktori projek. Rename direktori menjadi Adafruit_Unified_Sensor.

## Percobaan MAC Address
### Rangkaian & Instalasi
1. Siapkan ESP32 dan hubungkan ke Arduino IDE
2. Download dan jalankan kode dari source code sesuai project.

### Keluaran
![](https://camo.githubusercontent.com/5729ffe8a869f3f29c3c38cd30e6a19b44007cb4f6d9c71fb1f66b45871f7f04/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f313034333436323531393333363939363839342f313034383935303636383835353039313330312f412e5f4d61632e706e67)

## Percobaan One-Way Point-to-Point Communication
### Rangkaian & Instalasi
1. Siapkan 2 ESP32 yang sudah diketahui Mac Address wifinya.
2. Download dan jalankan kode dari source code sesuai project.
![]
(https://camo.githubusercontent.com/3087a187ce5a594d4db6b35212c404f04ef685db9550509a9a7c6e0d99f32ee5/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f313034333436323531393333363939363839342f313034383935313930323039373932303039302f422e5f53696d706c65785f5054502e77656270)


