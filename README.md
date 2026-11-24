# 🌿 IoT Dashboard – Monitoring Suhu dan Kelembaban

## Identitas Pengembang
- **Nama:** Miski Asifa
- **NPM:** 2410020049

## 1. Deskripsi Project
IoT Dashboard merupakan sistem monitoring berbasis Internet of Things (IoT) yang digunakan untuk memantau suhu dan kelembaban secara real-time. Sistem ini mengintegrasikan simulasi ESP32, MQTT, Node-RED, REST API, WebSocket, dan SQLite untuk mengolah serta menampilkan data sensor melalui dashboard berbasis web.

Dashboard menggunakan kombinasi warna hijau matcha dan putih dengan tampilan sederhana, modern, dan responsif.

## 2. Fitur Utama
- Monitoring suhu dan kelembaban secara real-time.
- Grafik perubahan data sensor.
- Informasi status koneksi sensor.
- Kontrol perangkat lampu.
- Riwayat data pengukuran sensor.
- REST API untuk pertukaran data.
- WebSocket untuk pembaruan data secara langsung.
- Penyimpanan data menggunakan SQLite.

## 3. Teknologi yang Digunakan

| Teknologi | Fungsi |
|---|---|
| Python | Simulasi ESP32 |
| MQTT Mosquitto | Komunikasi data sensor |
| Node-RED | Pengolahan alur sistem |
| REST API | Pertukaran data |
| WebSocket | Komunikasi real-time |
| SQLite | Penyimpanan data |
| HTML, CSS, JavaScript | Pengembangan dashboard |

## 4. Alur Kerja Sistem
1. Simulasi ESP32 menghasilkan data suhu dan kelembaban.
2. Data dikirim melalui MQTT.
3. Node-RED menerima dan mengolah data.
4. Data disimpan ke database SQLite.
5. WebSocket meneruskan data ke dashboard.
6. Dashboard menampilkan informasi sensor secara real-time.

## 5. Cara Menjalankan Project

**Menjalankan simulasi ESP32:**
```cmd
cd /d "C:\rest api"
py simulasi_esp32.py
```

**Menjalankan Node-RED:**
```cmd
node-red
```

Buka Node-RED melalui browser:

```text
http://localhost:1880
```

Kemudian buka dashboard:

```text
http://localhost:1880/dashboard.html
```

Pastikan Mosquitto, Node-RED, dan konfigurasi dashboard sudah berjalan dengan benar.

## 6. Kesimpulan
Project ini merupakan penerapan teknologi Internet of Things untuk monitoring suhu dan kelembaban dengan memanfaatkan MQTT, REST API, WebSocket, dan database SQLite. Sistem dirancang untuk mempermudah pemantauan data sensor melalui dashboard secara real-time.
