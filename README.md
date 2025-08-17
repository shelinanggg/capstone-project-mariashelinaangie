# My Daily Planner (Jupyter Notebook)

## Deskripsi
Project ini adalah aplikasi *Daily Planner* interaktif berbasis **Jupyter Notebook** menggunakan **ipywidgets**. Aplikasi ini memungkinkan pengguna untuk membuat, menandai selesai, dan menghapus tugas harian mereka dengan antarmuka yang **warna-warni, intuitif, dan mudah digunakan**. Setiap tugas juga dapat diatur tanggal, waktu, dan prioritasnya, sehingga membantu pengguna tetap terorganisir.

## Teknologi yang Digunakan
- Python 3.x
- Jupyter Notebook
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
1. **Clone atau unduh repository** ini.
2. Pastikan Python dan Jupyter Notebook sudah terinstall.
3. Install library yang dibutuhkan:
```bash
pip install git+https://github.com/ibm-granite-community/utils "langchain_community<0.3.0" replicate ipywidgets
```
4. Jalankan Jupyter Notebook:
```bash
jupyter notebook
```
5. Buka file PROJEK IBM.ipynb dan jalankan seluruh sel untuk melihat aplikasi planner interaktif.

## Dukungan AI
Project ini menggunakan IBM Granite AI untuk menghasilkan kode Python interaktif secara otomatis. AI membantu:
- Membuat template kode antarmuka interaktif
- Menyusun widget input dan tombol secara otomatis
- Mengoptimalkan tampilan daftar tugas
- Mengurangi waktu pengembangan dengan menghasilkan kode siap pakai untuk Jupyter Notebook
