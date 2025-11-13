# Trouble_external_Disk

1. Gunakan Command Prompt untuk Mengembalikan File
a. Catat huruf drive flashdisk (misal E:).
b. Buka Command Prompt (CMD) sebagai Administrator.
Ketik perintah ini (ganti E: dengan huruf flashdiskmu):
attrib -h -r -s /s /d E:\*.*

Artinya:
-h → hapus atribut “hidden”
-r → hapus atribut “read-only”
-s → hapus atribut “system”
/s dan /d → berlaku untuk semua file & folder di dalamnya
Setelah ini, cek lagi isi flashdisk. Biasanya file yang “hilang” akan muncul kembali.
