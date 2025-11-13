🧩 Trouble External Disk
🔧 1. Mengembalikan File yang Hilang Menggunakan Command Prompt
Langkah-langkah:

Catat huruf drive flashdisk kamu (misalnya E:).

Buka Command Prompt (CMD) sebagai Administrator.

Ketik perintah berikut (ganti E: dengan huruf drive flashdiskmu):

attrib -h -r -s /s /d E:\*.*

Penjelasan perintah:

-h → Menghapus atribut hidden (tersembunyi)

-r → Menghapus atribut read-only (hanya baca)

-s → Menghapus atribut system (file sistem)

/s dan /d → Berlaku untuk semua file dan folder di dalamnya
