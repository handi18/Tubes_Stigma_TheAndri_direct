  Algoritma ini adalah greedy dengan beberapa logika tambahan untuk menghindari rintangan dan memprioritaskan pulang ke base jika kondisi tertentu terpenuhi. 
Bot selalu memilih langkah yang secara lokal paling menguntungkan, dengan sedikit perhitungan untuk menghindari bahaya di jalur.


**Tujuan Algoritma**


1. Bot bergerak secara greedy untuk mengambil diamond terdekat, menghindari rintangan (teleporter, red diamond), dan kembali ke base jika sudah cukup diamond atau waktu hampir habis.
2. Jika diamond penuh (5) atau waktu hampir habis, bot langsung pulang ke base. Jika tidak, bot mencari diamond terdekat, atau red button jika lebih dekat.


**File utama direct.py dan direct_attack.py**
