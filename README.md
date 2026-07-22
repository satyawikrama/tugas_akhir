# Dataset dan Source Code Penelitian

Repositori/folder ini berisi **dataset** dan **source code** yang digunakan dalam penelitian mengenai ekstraksi tokoh, pengelompokan alias, klasifikasi tipe tokoh, serta klasifikasi nilai moral pada cerita rakyat.

Sebagian kode disimpan dalam format **Jupyter Notebook (`.ipynb`)**, sedangkan model dan berkas pendukung lainnya dapat diakses melalui Google Drive yang tercantum pada bagian berikut.

## Google Drive

Model dan berkas pendukung penelitian dapat diakses melalui tautan berikut:

[Google Drive Model dan Berkas Pendukung](https://drive.google.com/drive/folders/1uVjA_Ogtx-DGx-zwvcQrumBcJ0X_GTA5?usp=drive_link)

Pastikan akun yang digunakan telah memperoleh izin akses apabila folder tidak dapat dibuka.

## Dataset

Dataset yang digunakan dalam penelitian dapat mencakup:

- teks cerita rakyat dalam bahasa Bali, Indonesia, dan Inggris;
- anotasi entitas tokoh menggunakan format BIO;
- daftar nama dan alias tokoh;
- hasil pengelompokan alias tokoh;
- label tipe tokoh;
- anotasi nilai moral berdasarkan Moral Foundations Theory;
- pembagian data latih, validasi, dan data uji;
- hasil prediksi serta evaluasi model.

## Cara Menjalankan Notebook

1. Unduh dataset dan berkas pendukung dari Google Drive.
2. Buka notebook menggunakan Jupyter Notebook, JupyterLab, Visual Studio Code, atau Google Colab.
3. Sesuaikan lokasi file pada variabel path di dalam notebook.
4. Instal pustaka yang dibutuhkan.
5. Jalankan setiap cell secara berurutan dari awal sampai akhir.

Contoh instalasi pustaka utama:

```bash
pip install pandas numpy scikit-learn matplotlib transformers datasets torch openpyxl
```

Kebutuhan pustaka dapat berbeda pada setiap notebook. Periksa bagian import pada masing-masing file sebelum menjalankan kode.

## Catatan Penggunaan

- Sesuaikan path dataset sebelum menjalankan notebook.
- Gunakan versi pustaka yang kompatibel dengan model Transformer yang digunakan.
- Proses pelatihan model disarankan menggunakan GPU.
- Hasil eksperimen dapat berbeda karena perbedaan random seed, versi pustaka, perangkat keras, dan pembagian dataset.
- Pastikan file model, tokenizer, label, dan dataset tersedia sebelum melakukan prediksi.

## Tujuan Repositori

Folder ini disediakan sebagai dokumentasi dataset dan implementasi kode penelitian. Seluruh file digunakan untuk mendukung proses:

1. ekstraksi entitas tokoh;
2. normalisasi dan pengelompokan alias;
3. klasifikasi tipe tokoh;
4. klasifikasi nilai moral;

## Lisensi dan Sitasi

Dataset dan source code digunakan untuk kepentingan penelitian dan akademik. Apabila materi ini digunakan kembali, cantumkan sumber penelitian, penulis, institusi, dan referensi terkait sesuai ketentuan yang berlaku.
