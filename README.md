# ANTICIT UANG BY AIURA NOT FARUQ!

Anticit uang buatan sendiri dengan bantuan YSI-Includes.
Download YSI 5 untuk menggunakan include dari ANTICIT UANG!!!!

edit server.cfg lalu tambahkan
```
filterscripts anticit-uang
```

Jika kamu menggunakan config.json, tambahkan
```json
"pawn": {
    "side_scripts": ["anticit-uang"]
}
```

Taruh anticit-uang.amx kedalam folder filterscript

Jika ingin anticit aktif, ada dua cara:

1. Menggunakan fungsi `GetMoney` dan `GiveMoney` kedalam skrip kalian dengan `#include <anticit-uang>`
2. Menggunakan `#define ANTICHEAT_HOOK_MONEY` sebelum `#include <anticit-uang>`, tidak perlu menggunakan fungsi karena skrip akan otomatis menggunakan fungsi tsb.

skrip tidak dapat berjalan secara otomatis tanpa menggunakan API!

## Credits:
* Gotoh Aiura
* Y-Less
