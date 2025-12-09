# Form-Kubus
# Aplikasi Kubus Sederhana

Aplikasi *desktop* ini berfungsi sebagai kalkulator sederhana untuk menghitung volume dan total panjang rusuk sebuah kubus berdasarkan panjang sisinya. Aplikasi ini menerapkan validasi ketat untuk memastikan data input akurat.

## Fitur Utama

* **Perhitungan Geometri:** Menghitung dua parameter kunci kubus:
    * **Volume Kubus** (SV = s*s*s)
    * **Total Panjang Rusuk** (SL = 12 * s)
* **Validasi Input Ketat:** Input Panjang Sisi dibatasi secara eksplisit untuk menjamin integritas data:
    * **Hanya Angka:** Menerima input karakter numerik saja.
    * **Batasan Rentang:** Hanya menerima angka dalam rentang **1 hingga 20**. Input di luar rentang ini akan ditolak dengan pesan peringatan yang jelas.
* **Antarmuka Pengguna (GUI):** Dibangun menggunakan **Java Swing** dengan tampilan yang mudah digunakan.

## Detail Teknis

* **Bahasa:** Java
* **Platform:** Aplikasi Desktop (GUI)
* **Kompiler/IDE:** Apache NetBeans (disarankan)