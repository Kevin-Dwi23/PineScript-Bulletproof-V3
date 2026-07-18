# PineScript-Bulletproof-V3
Algoritma trading otomatis dengan fitur Dynamic Risk Management (ATR), Trailing Stop, dan perlindungan modal (Circuit Breaker) berbasis Pine Script v6.
## ⚙️ Fitur Utama Logika (Features)

* **Dynamic Risk Management:** Sistem *Take Profit* (TP) dan *Stop Loss* (SL) tidak hanya menggunakan persentase tetap (Fixed %), tetapi beradaptasi secara dinamis mengikuti volatilitas pasar melalui indikator *Average True Range* (ATR).
* **Proteksi Laba (Trailing Stop):** Algoritma dilengkapi dengan fitur pengunci keuntungan otomatis yang aktif melindungi laba berdasarkan jarak persentase (*Trailing Distance*) yang telah dikonfigurasi.
* **Circuit Breaker (Auto-Sleep):** Terdapat mesin pencegah eror yang akan menonaktifkan eksekusi (*cooldown*) secara otomatis jika sistem mendeteksi *loss* beruntun melebihi batas maksimal guna mencegah penarikan dana (*drawdown*) berlebih.

## 🚀 Cara Penggunaan
Skrip ini dapat disalin dan ditempelkan langsung ke dalam editor Pine Script untuk diuji coba (*Backtest*) guna mengukur profitabilitas strategi pada berbagai kondisi pasar.
