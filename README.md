# Fastboot Marble

> Untuk melakukan Oprek pada POCO F5, ponsel harus dalam keadaan Unlock Bootloader.
  
---
  
## 1: Download & Pasang Recovery.

- **Download** `recovery.img` from: **[here](https://t.me/mengpoi/327)**
- **Download** `Platform Tools` from: **[here](https://dl.google.com/android/repository/platform-tools-latest-windows.zip?hl=id)**
> Extrak dan buka Folder `Platform Tools` , Extrak Dan pindahkan juga file `recovery.img` ke folder `Platform Tools`  .. buka CMD pada folder tersebut .. hubungkan PC Dan Ponsel yang berada dalam kondisi Fastboot .. lalu ketikan: 
```properties
fastboot devices
```
> ketik lagi
```properties
fastboot flash recovery_ab recovery.img
```
> Setelah selesai kamu bisa melakukan reboot ke `Recovery` dengan menekan tombol Power & Volume Atas , atau bisa juga dengan mengetikan ini pada CMD 
```properties
fastboot reboot recovery
```

---
