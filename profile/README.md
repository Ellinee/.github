# Eline

Eline menghubungkan keluarga dan caregiver dengan Eline Vest serta Eline Radar untuk pemantauan perangkat dan notifikasi keselamatan di rumah.

## Repositories

| Repository | Stack | Fungsi |
| --- | --- | --- |
| [Eline-Mobile](https://github.com/Ellinee/Eline-Mobile) | Expo, React Native, TypeScript | Aplikasi rumah, perangkat, akun, dan notifikasi |
| [Eline-Backend](https://github.com/Ellinee/Eline-Backend) | Express, Prisma, PostgreSQL | API, autentikasi, event perangkat, dan push notification |
| [Eline-Webiste](https://github.com/Ellinee/Eline-Webiste) | Next.js, React, TypeScript | Website produk, informasi privasi, dan unduhan aplikasi |
| [Eline-mmWave-IoT](https://github.com/Ellinee/Eline-mmWave-IoT) | ESP32, Arduino, LD2450 | Prototype firmware Eline Radar |

## Sistem

Arsitektur yang dituju menghubungkan aplikasi dan perangkat melalui backend, dengan PostgreSQL untuk data utama dan Firebase Cloud Messaging untuk notifikasi.

Redis, Kafka, Prometheus, Grafana, dan bucket privat baru diprovisikan di Railway; belum terintegrasi dengan aplikasi. Integrasi firmware, pairing perangkat, dan validasi deteksi jatuh radar masih dalam pengembangan.

## Pengembangan

Petunjuk menjalankan aplikasi, konfigurasi environment, dan pemeriksaan tersedia di README masing-masing repository. Jangan menyimpan credential, token, atau kunci perangkat di source control.
