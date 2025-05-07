# rust-nn-qt-group7
1. instal ubuntu, rust, QT
2. melakukan pemrograman Rust sine dan cosine menggunakan pendekatan taylor series
3. melakukan pemrograman Rust sine dan cosine menggunakan lookup table
4. melakukan pemrograman Rust Machine Learning dengan metode Support Vector Machine
5. (SVM) dan kNN dengan menginput kan dataset
6. Melakukan pemrograman Rust Neural Network
7. Membuat arsitektur Neural Network 
8. Membuat module class, function, structure, program Rust Project
9. Program ini dapat di jalankan di Ubuntu Linux
10. Membuat akun GitHub
11. Pengaplikasian Neural Network dengan backend menggunakan Rust dan Frontend menggunakan QT untuk aplikasi desktop 
12. Memasukkan seluruh data pemrograman ke akun GitHub
13. Membuat Laporan
14. Membuat PPT

Analisa :

Berdasarkan hasil proyek, bahasa pemrograman Rust terbukti cukup efisien dalam pemrosesan data dan memberikan kecepatan yang signifikan selama eksperimen. Namun, penggunaannya memerlukan ketelitian, terutama saat mengintegrasikan library eksternal, karena sintaks Rust dapat berbeda tergantung pada fitur yang digunakan. Pada tahap klasifikasi, metode SVM-KNN diuji namun menghasilkan akurasi yang relatif rendah, meskipun telah dilakukan upaya seperti normalisasi data dan penyesuaian parameter gamma. Parameter gamma yang tidak tepat dapat menyebabkan overfitting atau underfitting, dan dalam kasus ini, penyesuaiannya tidak memberikan dampak yang signifikan terhadap akurasi. Sebaliknya, metode Neural Network yang diimplementasikan menggunakan framework Qt memberikan hasil yang lebih baik. Dua dataset digunakan dalam pengujian, yaitu 5000 dan 8000 data. Menariknya, dataset 5000 data justru memberikan akurasi lebih tinggi. Hal ini diduga karena dataset 8000 data merupakan hasil augmentasi menggunakan Python, sehingga sebagian data menjadi kurang realistis dan menurunkan performa model.
