# Dicoding ML 
# Rock-Paper-Scissors Image Classification

Proyek ini bertujuan untuk membuat model *machine learning* yang dapat mengklasifikasikan gambar batu, kertas, dan gunting. Model ini dibangun menggunakan *Convolutional Neural Network* (CNN) dan dilatih menggunakan dataset gambar *rock-paper-scissors* dari Dicoding Academy.

## Dataset

Dataset yang digunakan adalah dataset gambar *rock-paper-scissors* dari Dicoding Academy. Dataset ini berisi gambar batu, kertas, dan gunting dengan total 2188 gambar. Dataset ini dibagi menjadi dua bagian, yaitu data latih (1314 gambar) dan data validasi (874 gambar).

## Model

Model yang digunakan adalah CNN dengan arsitektur sebagai berikut:

* Input layer: gambar dengan ukuran 100x150 piksel
* Convolutional layer 1: 32 filter, kernel size 3x3, activation function ReLU
* Max pooling layer 1: pool size 2x2
* Convolutional layer 2: 64 filter, kernel size 3x3, activation function ReLU
* Max pooling layer 2: pool size 2x2
* Convolutional layer 3: 128 filter, kernel size 3x3, activation function ReLU
* Max pooling layer 3: pool size 2x2
* Convolutional layer 4: 128 filter, kernel size 3x3, activation function ReLU
* Max pooling layer 4: pool size 2x2
* Flatten layer
* Dense layer 1: 512 neuron, activation function ReLU
* Dropout layer: dropout rate 0.5
* Dense layer 2: 3 neuron, activation function Softmax

## Cara Penggunaan

1. Download dataset gambar *rock-paper-scissors* dari Dicoding Academy.
2. Ekstrak file zip dataset ke dalam folder `rockpaperscissors`.
3. Jalankan kode Python yang ada di file `RockPaperScissors_ImageClassification.ipynb`.
4. Upload gambar batu, kertas, atau gunting yang ingin diklasifikasikan.
5. Model akan memprediksi kelas dari gambar yang diupload.

## Hasil

Model yang dibuat memiliki akurasi sekitar 98% pada data validasi.

## Kontributor

* Chanan Artama (chanan.artama@gmail.com)

## Lisensi

Proyek ini dilisensikan di bawah lisensi MIT.
