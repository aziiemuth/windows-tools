# 🛠️ Windows Tools

<div align="center">

![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-2.0-blue?style=for-the-badge)

**Kumpulan tools Windows all-in-one untuk aktivasi, optimasi, dan perbaikan sistem.**

[Fitur](#-fitur) • [Instalasi](#-instalasi) • [Penggunaan](#-penggunaan) • [Daftar Menu](#-daftar-menu)

</div>

---

## ✨ Fitur

- 🔑 **Aktivasi Windows & Office** - Aktivasi digital untuk Windows dan Microsoft Office
- 🌐 **Reset Jaringan** - Perbaiki masalah koneksi internet
- 🧹 **Cleaning** - Bersihkan file sampah dan cache
- 🔧 **Perbaiki Registry** - Scan dan perbaiki registry Windows
- 💾 **Perbaiki Bad Sector** - Scan dan perbaiki bad sector pada hardisk
- 🔒 **BitLocker Management** - Nonaktifkan partisi yang dikunci BitLocker
- 🎵 **Aktivasi Spotify** - Install Spicetify untuk Spotify premium features
- ⚡ **Dan banyak lagi!**

---

## 📥 Instalasi

### Metode 1: One-Line Command (Recommended)

Buka **PowerShell** dan jalankan command berikut:

```powershell
iwr https://raw.githubusercontent.com/aziiemuth/windows-tools/main/windows.cmd -OutFile $env:TEMP\windows.cmd; cmd /c $env:TEMP\windows.cmd
```

### Metode 2: Download Manual

1. Download file `windows.cmd` dari [Releases](https://github.com/aziiemuth/windows-tools/releases) atau klik [disini](https://raw.githubusercontent.com/aziiemuth/windows-tools/main/windows.cmd)
2. Klik kanan pada file → **Run as Administrator** (jika diperlukan)

---

## 🚀 Penggunaan

1. Jalankan script menggunakan salah satu metode instalasi di atas
2. Pilih menu dengan memasukkan angka (0-20)
3. Ikuti instruksi yang muncul di layar
4. Script akan meminta hak Administrator **hanya saat diperlukan**

> **💡 Tips:** Script akan otomatis meminta hak Administrator untuk menu yang memerlukannya. Anda tidak perlu menjalankan sebagai Administrator dari awal.

---

## 📋 Daftar Menu

| No  | Menu                        | Deskripsi                               | Admin |
| --- | --------------------------- | --------------------------------------- | :---: |
| 1   | Cek Status Aktivasi Windows | Melihat status aktivasi Windows         |  ✅   |
| 2   | Aktivasi Windows Digital    | Aktivasi Windows (dalam pengembangan)   |  ✅   |
| 3   | Cek Status Aktivasi Office  | Melihat status aktivasi Office          |  ✅   |
| 4   | Aktivasi Office Digital     | Aktivasi Office (dalam pengembangan)    |  ✅   |
| 5   | Reset Jaringan              | Reset semua konfigurasi jaringan        |  ✅   |
| 6   | Jeda Windows Update         | Jeda Windows Update hingga 2099         |  ✅   |
| 7   | Cleaning                    | Bersihkan file temporary dan cache      |  ✅   |
| 8   | Perbaiki Registry           | Scan dan perbaiki registry              |  ✅   |
| 9   | Download WinRAR             | Download dan install WinRAR             |  ✅   |
| 10  | Flush DNS                   | Bersihkan cache DNS                     |  ✅   |
| 11  | Perbaiki Bad Sector         | Scan dan perbaiki bad sector            |  ✅   |
| 12  | Nonaktifkan BitLocker       | Nonaktifkan semua partisi BitLocker     |  ✅   |
| 13  | Disable Driver Signature    | Nonaktifkan verifikasi driver signature |  ✅   |
| 14  | Masuk ke BIOS               | Restart dan masuk ke BIOS/UEFI          |  ✅   |
| 15  | Ekstrak Product Key         | Ekstrak product key Windows/Office      |  ✅   |
| 16  | Aktivasi Online V1          | Aktivasi Windows/Office via KMS         |  ✅   |
| 17  | Windows Utility             | Buka Windows Utility (ChrisTitus)       |  ✅   |
| 18  | Aktivasi Online V2          | Aktivasi Windows/Office (MAS)           |  ✅   |
| 19  | Ekstrak Serial Number       | Ekstrak SN dan model PC                 |  ✅   |
| 20  | Aktivasi Spotify            | Install Spicetify untuk Spotify         |  ❌   |
| 0   | Keluar                      | Keluar dari script                      |  ❌   |

---

## 🖥️ Kompatibilitas

| OS          |     Status     |
| ----------- | :------------: |
| Windows 10  |  ✅ Supported  |
| Windows 11  |  ✅ Supported  |
| Windows 7/8 | ⚠️ Tidak Diuji |

---

## ⚠️ Disclaimer

> **Penggunaan script ini sepenuhnya menjadi tanggung jawab pengguna.**
>
> Script ini disediakan "sebagaimana adanya" tanpa jaminan apapun. Penulis tidak bertanggung jawab atas kerusakan yang mungkin terjadi akibat penggunaan script ini.
>
> Beberapa fitur aktivasi mungkin melanggar ketentuan layanan Microsoft. Gunakan dengan bijak.

---

## 🤝 Kontribusi

Kontribusi selalu diterima! Silakan buat **Pull Request** atau **Issue** jika menemukan bug atau ingin menambahkan fitur baru.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<div align="center">

**Created with ❤️ by [@Athiief](https://github.com/aziiemuth)**

</div>
