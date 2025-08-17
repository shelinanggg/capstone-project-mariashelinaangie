# My Daily Planner (Jupyter Notebook)

## Deskripsi
Project ini adalah website *Daily Planner* interaktif berbasis **Jupyter Notebook** menggunakan **ipywidgets**. Website ini memungkinkan pengguna untuk membuat, menandai selesai, dan menghapus tugas harian mereka dengan antarmuka yang **warna-warni, intuitif, dan mudah digunakan**. Setiap tugas juga dapat diatur tanggal, waktu, dan prioritasnya, sehingga membantu pengguna tetap terorganisir.

## Teknologi yang Digunakan
- Python
- Jupyter Notebook / Google Colab
- [ipywidgets](https://ipywidgets.readthedocs.io/) untuk antarmuka interaktif
- Modul `datetime` untuk manajemen tanggal dan waktu
- [IBM Granite AI](https://github.com/ibm-granite-community) untuk dukungan pembuatan kode otomatis

## Fitur
- **Tambah Tugas Baru** dengan input teks, tanggal, waktu, dan prioritas
- **Daftar Tugas Interaktif** dengan tampilan dinamis
- **Prioritas Tugas**: Tinggi 🔥, Sedang ⚡, Rendah 🌟 dengan warna berbeda
- **Tandai Tugas Selesai** dengan tombol ✅
- **Hapus Tugas** dengan tombol 🗑️
- **Sortir Otomatis** berdasarkan status selesai, tanggal, dan waktu
- **Header & Tampilan Warna-warni** yang menarik dan mudah dibaca

## Cara Menjalankan
### 1. Simpan API Token Replicate
1. Buka Google Colab.  
2. Pilih ikon **Key** pada menu sidebar di halaman “Welcome to Colab”.  
3. Pilih **Add new secret**.  
4. Ketik `REPLICATE_API_TOKEN` pada kolom **Name**.  
5. Paste API token Replicate Anda pada kolom **Value**.  
6. Aktifkan toggle **Notebook access** dan pilih **Close**.  

### 2. Load Notebook dari GitHub
1. Di workspace Colab, klik **File → Open notebook**.  
2. Pilih tab **GitHub**.  
3. Masukkan URL repo:  
   [https://github.com/shelinanggg/capstone-project-mariashelinaangie](https://github.com/shelinanggg/capstone-project-mariashelinaangie)  
4. Klik ikon kaca pembesar untuk mencari.  
5. Pilih **main** di bagian **Branch**.  
6. Pilih notebook `capstone_project_dailyplanner.ipynb` untuk membukanya di Colab.  

### 3. Hubungkan Runtime
1. Pilih **Connect** pada navigasi Colab.  
2. Pilih **Connect to a hosted runtime**.  
3. Tanda centang hijau menunjukkan runtime berhasil terhubung.

### 4. Install library yang dibutuhkan:
```bash
pip install git+https://github.com/ibm-granite-community/utils "langchain_community<0.3.0" replicate ipywidgets
```

### 5. Jalankan seluruh sel untuk melihat website planner interaktif.

## Dukungan AI
Project ini menggunakan IBM Granite AI untuk menghasilkan kode Python interaktif secara otomatis. AI membantu:
- Membuat template kode antarmuka interaktif
- Menyusun widget input dan tombol secara otomatis
- Mengoptimalkan tampilan daftar tugas
- Mengurangi waktu pengembangan dengan menghasilkan kode siap pakai untuk Jupyter Notebook
