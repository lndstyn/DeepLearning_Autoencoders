
# 🧠 Autoencoder untuk Penghapusan Noise pada Fashion MNIST

Repositori ini berisi implementasi Autoencoder menggunakan TensorFlow dan Keras untuk menghilangkan noise pada dataset Fashion MNIST. Proyek ini merupakan adaptasi dari [Image-Denoising-Using-Autoencoder](https://github.com/13muskanp/Image-Denoising-Using-Autoencoder) dengan penyesuaian pada dataset dan visualisasi.

## 📁 Struktur Proyek

* `AutoEncoders_for_Fashion_Class_Noise_Removal.ipynb`: Notebook utama yang mencakup seluruh proses dari pemuatan data hingga evaluasi model.
* `img/`: Folder yang berisi visualisasi hasil denoising, termasuk perbandingan antara gambar asli, gambar dengan noise, dan hasil rekonstruksi.

## 🧩 Deskripsi Proyek

Autoencoder adalah jenis jaringan neural yang digunakan untuk belajar representasi efisien dari data tanpa label (unsupervised learning). Dalam proyek ini, Autoencoder dilatih untuk menghapus noise dari gambar Fashion MNIST, memungkinkan model untuk merekonstruksi gambar asli dari versi yang telah terkontaminasi noise.

## 🛠️ Langkah-langkah Implementasi

1. **Pemuatan dan Visualisasi Data**:

   * Mengimpor dataset Fashion MNIST.
   * Menampilkan sampel gambar untuk pemahaman awal.

2. **Penambahan Noise**:

   * Menambahkan noise Gaussian pada gambar untuk mensimulasikan data yang terkontaminasi.

3. **Pembangunan Model Autoencoder**:

   * Membangun arsitektur encoder dan decoder menggunakan Keras.
   * Menggunakan fungsi aktivasi ReLU dan sigmoid untuk menangani non-linearitas.

4. **Pelatihan Model**:

   * Melatih model dengan data yang telah ditambahkan noise.
   * Menggunakan fungsi loss Mean Squared Error (MSE) dan optimizer Adam.

5. **Evaluasi dan Visualisasi**:

   * Mengevaluasi kinerja model pada data uji.
   * Menampilkan perbandingan antara gambar asli, gambar dengan noise, dan hasil rekonstruksi.

## 📊 Hasil Visualisasi

Visualisasi hasil denoising dapat ditemukan di folder `img/`. Berikut adalah contoh perbandingan:

* **Gambar Asli**: Gambar Fashion MNIST tanpa noise.
* **Gambar dengan Noise**: Gambar yang telah ditambahkan noise Gaussian.
* **Hasil Rekonstruksi**: Gambar hasil rekonstruksi oleh Autoencoder.

## 📚 Referensi

* [Autoencoder - Wikipedia](https://en.wikipedia.org/wiki/Autoencoder)
* [Autoencoders in Deep Learning: Implementation, Uses & Applications](https://intellipaat.com/blog/autoencoders-in-deep-learning/)
* [Image Denoising using AutoEncoders - A Beginner's Guide](https://www.analyticsvidhya.com/blog/2021/07/image-denoising-using-autoencoders-a-beginners-guide-to-deep-learning-project/)

## 🧑‍💻 Kontributor

* [lndstyn](https://github.com/lndstyn)
* Berdasarkan kode oleh: 13muskanp


