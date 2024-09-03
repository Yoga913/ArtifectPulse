# ArtifactPulse

ArtifactPulse adalah alat canggih berbasis PowerShell yang dirancang untuk mempercepat proses triase dan memfasilitasi pengumpulan bukti penting dari artefak forensik dan data volatil sementara dalam ekosistem Windows. Alat ini bertujuan untuk memberikan dukungan yang sangat diperlukan dalam mengidentifikasi potensi pelanggaran keamanan dengan menyederhanakan pengumpulan dan analisis data penting.

## Threat Hunting - Incident Response - PowerShell Hunting-Blu - DEFENSE BY OFFENSE BLUE TEAM

## Fitur Utama

- **Pengumpulan dan Analisis Artefak**: Mengumpulkan data penting dari berbagai sumber untuk membantu dalam proses penyelidikan forensik.
- **Pemetaan Data yang Terstruktur**: Mengatur data ke dalam berkas teks yang dinyatakan dengan nomenklatur nama host sistem, mendukung transisi mulus ke tahap penyelidikan berikutnya.
- **Queri Beragam**: Menyediakan berbagai kueri untuk mengumpulkan informasi penting dari sistem.

## Queri Konten

ArtifactPulse mendukung berbagai kueri untuk mengumpulkan informasi dari sistem, termasuk:

- **Informasi Umum**
- **Informasi Akun dan Grup**
- **Jaringan**
- **Informasi Proses**
- **Build OS dan Hotfix**
- **Ketahanan**
- **Informasi Perangkat Keras**
- **Informasi Enkripsi**
- **Informasi Firewall**
- **Layanan**
- **Riwayat**
- **Queri SMB**
- **Queri Remoting**
- **Analisis Registri**
- **Queri Log**
- **Instalasi Perangkat Lunak**
- **Aktivitas Pengguna**

## Queri Lanjutan

- **Informasi File Prefetch**
- **Daftar DLL**
- **Filter dan Konsumen WMI**
- **Pipa Bernama**

## Penggunaan

1. **Jalankan Skrip**: Untuk menggunakan ArtifactPulse, jalankan skrip dari konsol PowerShell dengan hak istimewa administratif. Hasil akan disimpan dalam bentuk file teks di direktori kerja.

   ```powershell
   PS > ./artifactpulse.ps1
   ```

2. **Penggunaan Lanjutan**: Untuk menjalankan skrip dengan opsi tambahan, gunakan parameter `-a`:

   ```powershell
   PS > ./artifactpulse.ps1 -a
   ```

## Dukungan

Jika Anda mengalami masalah atau memerlukan bantuan, jangan ragu untuk menghubungi tim pengembangan atau memeriksa dokumentasi tambahan yang tersedia di repositori proyek.
