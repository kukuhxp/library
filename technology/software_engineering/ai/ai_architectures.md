# AI ARCHITECTURE

## Artificial Neural Network (Ann)

Artificial Neural Network) atau Jaringan Saraf Tiruan atau Neural Network (NN) atau Jaringan Saraf adalah model komputasi yang meniru cara kerja otak manusia untuk memproses informasi, mengenali pola, dan membuat keputusan.

ANN merupakan fondasi utama dari Deep Learning dan salah satu teknik paling penting dalam Machine Learning.

ANN terinspirasi dari neuron biologis di otak manusia. Setiap neuron buatan menerima input, memprosesnya, lalu mengirimkan output ke neuron lain.

Lapisan:

1. Input layer sebagai tempat data mentah masuk.
2. Hidden layer(s) sebagai tempat perhitungan dilakukan.
3. Output layer untuk menghasilkan hasil akhir.

Latihan:

1. Feedforward, proses data mengalir dari input ke output untuk menghasilkan prediksi.
2. Loss, proses membandingkan hasil dengan label sebenarnya.
3. Backpropagation, proses ANN memperbarui bobot untuk mengurangi error.
4. Repeat sampai error sekecil mungkin.

## Deep Neural Network (DNN)

Deep Neural Network (DNN) merupakan perkembangan dari Artificial Neural Network (ANN), namun dengan lebih banyak lapisan di dalamnya, itulah sebabnya disebut deep.

## Feedforward Neural Network (FNN)

Feedforward Neural Network (FNN) adalah jenis jaringan saraf paling dasar, di mana aliran data hanya bergerak satu arah dari input ke output, tanpa ada umpan balik.

Lapisan:

1. Input layer untuk menerima data masukan.
2. Hidden layer(s) untuk memproses data melalui bobot dan fungsi aktivasi.
3. Output layer untuk menghasilkan prediksi atau hasil akhir.

Latihan:

1. Input data dimasukkan ke dalam neuron pada lapisan input.
2. Setiap neuron mengalikan input dengan bobot dan menambahkan bias.
3. Hasilnya dilewatkan ke fungsi aktivasi seperti ReLU, Sigmoid, atau Tanh.
4. Output dari neuron di satu lapisan menjadi input bagi lapisan berikutnya.
5. Pada lapisan terakhir, jaringan menghasilkan output akhir.
6. Selama training, FNN menggunakan backpropagation untuk memperbarui bobot berdasarkan kesalahan.

Contoh:

1. Pengenalan gambar sederhana.
2. Klasifikasi data numerik.
3. Prediksi harga.
4. Deteksi pola data non-sekuensial

## Convolutional Neural Network (CNN)

Convolutional Neural Network (CNN) adalah jenis jaringan saraf yang dirancang khusus untuk memproses data berbentuk grid seperti gambar 2D atau video 3D.

CNN sangat populer di bidang Computer Vision, seperti pengenalan wajah, deteksi objek, dan klasifikasi gambar.

Lapisan:

1. Input layer untuk memasukkan data gambar masuk.
2. Convolutional layer untuk menerapkan filter kecil yang bergerak di seluruh gambar. Setiap filter belajar mendeteksi fitur tertentu, seperti tepi horizontal atau warna tertentu.
3. Activation layer untuk mengubah nilai negatif jadi 0 untuk menambah non-linearitas:
4. Pooling layer untuk engurangi ukuran data (downsampling) agar komputasi lebih efisien.
5. Fully connected layer untuk klasifikasi akhir.
6. Output layer untuk menghasilkan hasil akhir, misalnya kategori gambar.

Contoh:

Model sedang mengenali gambar kucing, maka prosesnya:

1. Layer awal (Conv1) belajar mengenali tepi dan garis.
2. Layer tengah (Conv2) mengenali bentuk telinga, mata, bulu.
3. Layer akhir (FC) mengenali bahwa kombinasi fitur itu adalah kucing.

## Recurrent Neural Network (RNN)

## Long Short-term Memory (LSTM)

## Transformer

Transformer adalah arsitektur model neural network yang diperkenalkan oleh Google pada tahun 2017 dalam paper terkenal yaitu Attention Is All You Need”.

Tujuannya adalah membuat mesin yang memahami urutan kata tanpa harus membaca dari awal ke akhir seperti RNN atau LSTM. Sebelum ada Transformer, model bahasa menggunakan RNN dan LSTM.

Masalahnya adalah proses berurutan atau tidak bisa paralel, kehilangan konteks ketika teks panjang, sulit dilatih, dan lambat.

Transformer memperkenalkan konsep utama, yaitu Self-attention. Di mana model memperhatikan setiap kata dalam konteks semua kata lain di kalimat.

Contoh:

“Kucing itu duduk di atas tikar.”. Ketika model membaca kata “itu”, ia akan memberi perhatian pada “Kucing” untuk memahami apa yang dimaksud “itu”.

Jenis:

1. Encoder-only Transformer
Encoder-only Transformer adalah salah satu varian arsitektur Transformer, yang hanya menggunakan bagian encoder dari struktur asli Transformer.

2. Decoder-only Transformer
Decoder-only Transformer adalah varian Transformer yang hanya menggunakan bagian decoder dari arsitektur asli, dan biasanya dipakai untuk generasi teks. Berbeda dengan encoder-only yang fokus understanding, decoder-only fokus generation.

## Modular Neural Network (MNN)

## Gated Recurrent Unit (GRU)

## Radial Basis Function Network (RBFN)

## Generative Adversarial Network (GAN)