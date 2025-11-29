# STOCk EXCHANGE SYSTEM

## Trading Floor

Trading floor adalah area fisik di sebuah bursa di mana para trader dan broker melakukan transaksi jual-beli aset terutama saham. Sekarang banyak trading floor sudah digantikan oleh sistem elektronik, karena komputer bisa mengeksekusi order lebih cepat dan efisien. Beberapa bursa besar seperti NYSE masih mempertahankan floor untuk simbolik atau beberapa transaksi tertentu, tapi sebagian besar sudah digital.

## INET

INET adalah sistem elektronik yang digunakan untuk menghubungkan broker, investor, dan bursa saham Indonesia (IDX) dalam proses transaksi saham. Ini adalah platform perdagangan elektronik yang menggantikan cara lama, yaitu trading floor, di mana transaksi dilakukan secara fisik di lantai bursa.

## Electronic Trading System (ETS)

Electronic Trading System (ETS) adalah platform elektronik yang memungkinkan proses jual beli aset keuangan yang dilakukan secara otomatis dan digital, tanpa perlu interaksi tatap muka atau via telepon antara pembeli dan penjual.

## Execution Management System (EMS)

Execution Management System (EMS) adalah sistem perangkat lunak trading yang dirancang khusus untuk menjalankan order beli/jual secara cepat dan efisien di berbagai pasar dan bursa.

## Order Management System (OMS)

Order Management System (OMS) adalah sistem perangkat lunak yang digunakan untuk mengelola, memantau, dan mengeksekusi pesanan transaksi keuangan secara efisien.

## Order-driven Market

Order-driven market adalah sistem perdagangan di pasar saham di mana harga dan transaksi ditentukan berdasarkan order dari para peserta pasar. Tidak ada perantara yang menentukan harga; harga terbentuk dari interaksi langsung antara penawaran dan permintaan.

### How It Works

1. Investor memasukkan order beli (bid) dan order jual (ask) ke sistem.

2. Sistem memadankan order berdasarkan harga terbaik dan waktu masuk order atau price-time priority.

3. Jika ada kecocokan, transaksi terjadi.

## Discretionary Orders

Discretionary orders adalah jenis order saham di mana trader atau broker memiliki fleksibilitas untuk menentukan harga eksekusi dalam batas tertentu, bukan harus persis pada harga yang ditentukan di order.

Example:

Trader ingin membeli saham AAPL pada $150, tapi menempatkan discretionary range ±$0,50. Broker atau sistem bisa mengeksekusi order antara $149,50 sampai $150,50, tergantung likuiditas dan harga pasar.

## Pegging Orders

Pegging orders adalah jenis order saham yang mengikuti harga referensi tertentu secara otomatis. Dengan kata lain, harga eksekusi order menempel atau menyesuaikan diri dengan harga pasar tertentu, biasanya bid, ask, atau midpoint.

Example:

Trader ingin menjual saham AAPL dengan primary peg. Jika bid terbaik saat ini $149,90, order otomatis menyesuaikan menjadi $149,90. Jika bid berubah menjadi $150, order juga ikut naik menjadi $150.

### 1. Primary Peg

Mengikuti best bid untuk jual atau best ask untuk beli.

### 2. Market Peg

Mengikuti bid atau ask terbaik dari seluruh pasar, tidak terbatas di satu bursa.

### 3. Midpoint Peg

Menargetkan tengah antara bid dan ask.

## Random Reserve

Random reserve adalah jenis order saham di mana hanya sebagian dari total jumlah order yang terlihat di buku pasar, sementara sisanya disembunyikan secara acak.

Ini biasanya digunakan dalam protokol special handling seperti RASH di NASDAQ.

Example:

Trader menempatkan order misalnya 1.000 saham, tapi hanya 200 saham yang terlihat di buku pasar. Saat sebagian order dieksekusi, sistem akan menampilkan sebagian lagi dari sisa order secara acak. Tujuannya adalah mengurangi dampak pasar dan mencegah prediksi strategi oleh trader lain.

### How It Works

1. Trader kirim order 1.000 saham dengan random reserve = 20% terlihat.

2. Buku pasar menampilkan 200 saham saja.

3. Jika 200 saham dieksekusi, sistem menampilkan jumlah lain dari sisa order, misalnya 150 saham secara acak.

4. Proses berlanjut sampai semua order dieksekusi.

## Order Validation

Order validation adalah proses memeriksa apakah suatu perintah transaksi sah dan memenuhi semua persyaratan teknis, hukum, dan pasar sebelum order tersebut dikirim ke sistem perdagangan atau bursa.

## Order Matching

Order matching adalah proses mencocokkan order beli dan order jual di pasar keuangan berdasarkan harga dan waktu untuk melakukan transaksi.

## Execution Management System (EMS)

Execution Management System (EMS) adalah sistem perangkat lunak trading yang dirancang khusus untuk menjalankan order beli/jual secara cepat dan efisien di berbagai pasar dan bursa.

## Matching Engine

Matching engine adalah inti dari sistem perdagangan elektronik yang bertugas untuk mencocokkan order beli dan order jual secara otomatis di pasar keuangan.

## Routing Logic

Routing Logic adalah algoritma yang digunakan dalam sistem perdagangan elektronik untuk menentukan ke mana sebuah order beli/jual harus dikirim agar mendapat eksekusi terbaik berdasarkan harga, volume, kecepatan, atau prioritas lainnya.

## Running Trade

Running Trade adalah sebuah informasi transaksi yang ditampilkan secara realtime pada aplikasi broker. Informasi yang ditampilkan meliputi volume, waktu, harga dan kode broker. Informasi yang ditampilkan pada running trade adalah transaksi yang sudah tereksekusi.

## Circuit Breaker

Circuit Breaker adalah mekanisme otomatis untuk menghentikan sementara perdagangan ketika terjadi penurunan harga yang sangat drastis dalam waktu singkat.

## Partial Fill

Partial fill adalah sebagian dari order yang kita kirimkan berhasil dieksekusi, sementara sisanya belum terpenuhi karena tidak ada cukup lawan transaksi pada harga yang sama.

## OUCH

OUCH adalah protocol sistem komunikasi elektronik yang digunakan untuk melakukan order routing dan eksekusi perdagangan saham di bursa, terutama untuk NASDAQ.

OUCH memungkinkan broker atau trader untuk mengirim order beli/jual secara cepat ke bursa, dan menerima konfirmasi secara real-time. OUCH termasuk protokol TCP/IP low-latency, sehingga sangat populer di kalangan high-frequency trading (HFT).

### How It Works

1. Broker membeli 1.000 saham AAPL.
2. Mereka mengirim order via OUCH.
3. bursa menerima, mengeksekusi, dan mengirim konfirmasi kembali.

## RASH

RASH adalah lrotokol komunikasi elektronik untuk order saham di NASDAQ, mirip dengan OUCH, tapi dengan fitur tambahan untuk routing dan special handling.

### How It Works

1. Trader mengirim order via RASH ke NASDAQ.

2. NASDAQ memeriksa apakah bisa dieksekusi. Jika bisa maka dieksekusi, dan dikirim konfirmasi. Jika tidak maka bisa diarahkan ke bursa lain otomatis atau routing.

3. Trader menerima update status order secara real-time.

## Stocks Brokerage Platforms

### 1. FlexTrade

FlexTrade adalah perusahaan teknologi keuangan yang mengembangkan solusi trading elektronik seperti Execution Management System (EMS) dan Order Management System (OMS) untuk klien institusional besar.

### 2. Portware

Portware adalah Execution Management System (EMS) canggih yang dirancang khusus untuk klien institusional seperti manajer aset, hedge fund, quantitative trading desks, dan tim trading di aset global.

### 3. Tora

Tora adalah platform cloud-based canggih yang menyediakan solusi menyeluruh untuk order & execution management (OEMS), portfolio management (PMS), transaction cost analysis (TCA), dan risk & compliance dalam satu sistem terpadu. Awalnya berdiri independen pada tahun 2004, dan kini telah diakuisisi oleh London Stock Exchange Group (LSEG) pada Februari 2022 senilai $325 juta.

## In-house Management Systems

### 1. Asset, Liability, Debt & Derivative Investment Network (Aladdin)

Asset, Liability, Debt & Derivative Investment Network adalah sistem manajemen risiko dan investasi tingkat institusi yang dikembangkan oleh BlackRock, salah satu perusahaan manajemen aset terbesar di dunia.