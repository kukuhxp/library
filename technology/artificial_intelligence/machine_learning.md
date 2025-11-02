# MACHINE LEARNING (ML)

Machine Learning (ML) adalah cabang dari kecerdasan buatan yang memungkinkan komputer belajar dari data dan membuat keputusan tanpa diprogram secara eksplisit. Ada beberapa jenis dari machine learning, yaitu:

- Supervised Learning
- Unsupervised Learning
- Reinforcement Learning

## Deep Learning

Deep learning adalah cabang dari machine learning yang menggunakan jaringan saraf tiruan berlapis-lapis. Deep learning digunakan untuk memproses data dan membuat keputusan atau prediksi.

## Probabilistic Language Model

adalah model yang memprediksi kemungkinan atau probabilitas suatu urutan kata muncul dalam sebuah bahasa. Model ini mencoba menebak kata berikutnya berdasarkan seberapa besar peluang kata itu muncul setelah kata-kata sebelumnya.

Model seperti GPT masih berbasis probabilitas, tapi menggunakan Neural Probabilistic Language Model, di mana probabilitas ditentukan oleh jaringan saraf atau neural network.

Model belajar representasi kata dalam bentuk embedding. Prediksi kata berikutnya dilakukan berdasarkan distribusi probabilitas atas seluruh kosakata.

Kalimat yang dihasilkan model AI sebenarnya adalah hasil dari prediksi probabilistik berantai.

Contoh:

“Saya makan nasi.”

Model probabilistik akan memperkirakan P(“Saya”) atau P(“makan” | “Saya”) atau P(“nasi” | “Saya makan”)

Nilai:

Saya = 0.05
makan = 0.02
nasi = 0.03
Jadi total probabilitas kalimat = 0.05 × 0.02 × 0.03 = 0.00003

Jenis:

1. Unigram Model
Menganggap tiap kata independen. Contoh model sangat sederhana tapi kurang akurat.

2. Bigram Model
Menganggap kata tergantung pada 1 kata sebelumnya.

3. Trigram Model
Menganggap kata tergantung pada 2 kata sebelumnya.

4. N-gram Model
Generalisasi dari bigram/trigram. Semakin besar n, semakin banyak konteks yang dipertimbangkan.

## Nearest Neighbor Search (NNS)

Nearest Neighbor Search (NNS) adalah proses dalam ilmu komputer dan machine learning untuk mencari data atau titik yang paling mirip, dekat, atau relevan dengan data tertentu, berdasarkan jarak matematis.

## Affective Computing

Affective computing adalah bidang dalam kecerdasan buatan (AI) dan ilmu komputer yang berfokus pada mendeteksi, memahami, meniru, dan merespons emosi manusia melalui teknologi.

## Large Language Models (LLM)

Large Language Models (LLM) adalah jenis model kecerdasan buatan (AI) yang dilatih untuk memahami dan menghasilkan teks dalam bahasa manusia dengan tingkat pemahaman yang sangat tinggi.

## Attention

Attention adalah mekanisme yang membuat model fokus pada bagian penting dari data saat memproses informasi.

Contoh:

dalam kalimat “Dia makan karena lapar”, model tahu kata “lapar” berkaitan dengan “dia”, bukan “makan”. Jadi, attention membantu AI memahami konteks dan hubungan antar kata agar hasilnya lebih akurat.

## Tokenization

Tokenization adalah proses memecah teks menjadi potongan-potongan kecil yang disebut token agar bisa dipahami oleh AI. Token bisa berupa kata, sub-kata, atau bahkan huruf, tergantung modelnya. Tujuannya adalah supaya komputer bisa memproses bahasa manusia dalam bentuk angka (vektor).

Contoh:

Kalimat “Saya suka apel merah.”, diubah menjadi token ["Saya", "suka", "apel", "merah", "."]

## Token ID

Token ID adalah nomor unik yang diberikan pada setiap token setelah proses tokenization.

Contoh:

Kalimat “Saya suka apel”, dipecah menjadi token ["Saya", "suka", "apel"], lalu diubah menjadi token ID [1052, 207, 892]

## Embedding Layer

## Embedding Matrix

## Word Embedding

## Byte Pair Encoding (BPE)

Byte Pair Encoding (BPE) adalah algoritma kompresi yang diadaptasi untuk tokenisasi teks dalam model bahasa besar seperti GPT Tujuannya adalah memecah kata menjadi potongan (sub-kata) yang efisien dan tetap bermakna, meskipun model belum pernah melihat kata itu sebelumnya.

## Tiktoken

Tiktoken adalah tokenizer resmi buatan OpenAI, digunakan untuk mengubah teks menjadi token (angka) agar bisa diproses oleh model GPT seperti GPT-3.5 atau GPT-4.

## Vector Database

Vector database adalah jenis basis data khusus yang dirancang untuk menyimpan dan mencari data dalam bentuk vektor.

## Computer Vision (CV)

Computer Vision (CV) adalah cabang dari kecerdasan buatan (AI) yang berfokus pada membuat komputer bisa melihat, memahami, dan mengambil keputusan.

## Natural Language Processing (NLP)

Natural Language Processing (NLP) adalah cabang dari kecerdasan buatan (AI) yang berfokus pada interaksi antara komputer dan bahasa manusia. NLP bertujuan agar komputer bisa memahami, menafsirkan, menghasilkan, dan merespons bahasa manusia secara alami.

## Backpropagation

Backpropagation adalah algoritma inti dalam pelatihan neural network. Backpropagation digunakan untuk menghitung dan memperbaiki kesalahan dengan mengubah bobot pada setiap neuron agar model menjadi lebih akurat.

## Stochastic

Stochastic dalam konteks AI adalah algoritma yang mengandung elemen acak untuk membuat keputusan, mempelajari pola, atau mengeksplorasi solusi.

## Deterministic

Deterministic dalam konteks AI adalah algoritma yang selalu memberikan hasil yang sama jika diberikan input yang sama, tanpa unsur acak.

## Temperature

Temperature dalam konteks AI adalah parameter yang mengatur tingkat kreativitas atau keacakan dalam output model.

## Generalized Knowledge Rollover (GKR)

GKR (Generalized Knowledge Rollover) berarti kemampuan sistem untuk membawa pengetahuan umum yang telah dipelajari sebelumnya ke situasi baru, tanpa harus mempelajari semuanya dari awal.
Konsep ini dekat dengan transfer learning, generalization, atau knowledge reuse dalam bidang AI dan cognitive science.

## Inference

inference berarti menggunakan model yang sudah dilatih untuk membuat prediksi atau keputusan baru berdasarkan data input baru. Jadi, training adalah proses belajar model, sedangkan inference adalah proses menggunakan hasil belajar itu.

Contoh:

Model AI sudah dilatih untuk mengenali gambar kucing dan anjing. Saat kamu masukkan gambar baru, proses menentukan apakah itu kucing atau anjing disebut inference.

## Parameter Model

Parameter model adalah nilai-nilai internal di dalam sebuah model yang menentukan bagaimana model tersebut berperilaku dan membuat prediksi. Dengan kata lain, parameter adalah isi otak model yang dipelajari selama proses training. Saat model belajar dari data, ia berusaha menemukan parameter terbaik agar hasil prediksinya paling akurat.

Mereka diubah-ubah selama training sampai hasil prediksi mendekati data sebenarnya. Dalam Model AI seperti ChatGPT, CNN, dll. Model seperti ChatGPT atau GPT-5 memiliki miliaran parameter.
Parameter-parameter ini menyimpan pengetahuan dan pola bahasa yang dipelajari dari data teks selama training.

Semakin banyak parameter, semakin besar kapasitas model bisa memahami konteks dan pola yang lebih kompleks.

Contoh:

1. GPT-2 memiliki 1,5 miliar parameter.
2. GPT-3 memiliki 175 miliar parameter.
3. GPT-4 memiliki >1 triliun parameter.
4. GPT-5 lebih besar lagi.

Jenis:

1. Weights
Mengatur seberapa kuat pengaruh tiap fitur input terhadap output.
2. Biases
Nilai tambahan agar model bisa menggeser hasil tanpa mengubah input.
3. Embedding weights
Digunakan untuk merepresentasikan kata atau simbol ke dalam bentuk vektor angka.

## Context Window

Context window atau jendela konteks adalah jumlah token yang bisa diingat dan diproses oleh model dalam satu waktu percakapan. Context window mencakup pesan dari pengguna, jawaban model sebelumnya, sistem prompt, informasi tambahan.

Contoh:

Misal sebuah model punya context window 8.000 token, berarti model hanya bisa melihat dan memahami 8.000 token terakhir dari percakapan atau teks yang kamu kirim. Jika percakapan melewati batas itu, bagian paling awal akan tergeser keluar dari jendela konteks.

GPT-3.5 dapat mengingat 4.000–16.000 token.
GPT-4 dapat mengingat 8.000–32.000 token.
GPT-5 dapat mengingat 128.000 token.

## Chain Rule of Probability

## Byte Pair Encoding (BPE)

## Top-k

## Top-p

## Subword Tokenization

## Positional encoding

## Stacked Transformer blocks

## Softmax

## Tokenizer