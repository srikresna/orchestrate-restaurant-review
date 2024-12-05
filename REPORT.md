Restaurant Review CLassification

| | Deskripsi |
| ----------- | ----------- |
| Dataset | [Restaurant Review](https://www.kaggle.com/datasets/d4rklucif3r/restaurant-reviews) |
| Masalah | Dalam industri restoran, ulasan pelanggan memainkan peran penting dalam mempengaruhi reputasi dan popularitas sebuah restoran. Namun, menganalisis ulasan ini secara manual dapat memakan waktu dan rentan terhadap bias. Tantangannya adalah mengotomatiskan proses mengklasifikasikan ulasan ini sebagai positif atau negatif, yang dapat membantu pemilik restoran memahami sentimen pelanggan dengan cepat dan obyektif serta meningkatkan layanan mereka. |
| Solusi machine learning | Melalui masalah yang ada, pendekatan _machine learning_ akan sangat membantu untuk mengklasifikasikan ulasan pelanggan yang berbasis teks. _Machine learning_, terutama _deep learning_ memiliki kemampuan yang baik dalam memproses data teks dan memberikan tingkat akurasi yang tinggi. Sehingga cocok digunakan untuk kasus ini. |
| Metode pengolahan | Data awal ulasan pelanggan akan dipisah menjadi data pelatihan dan data evaluasi dengan rasio 80:20, kemudian data akan melalui tahapan validasi untuk analisa dan menemukan anomali pada data. Tahap selanjutnya data akan diproses agar siap untuk masuk kedalam pelatihan. Setelah pelatihan selesai model akan di evaluasi dan di dikirim pada _endpoint_ dimana model siap dipakai. |
| Arsitektur model | Arsitektur yang digunakan cukup sederhana terdiri dari _layer Embedding_ dan satu _layer Dense_ sebagai _hidden layer_, kemudian fungsi aktivasi pada _output layer_ menggunakan _Sigmoid_ karena dalam kasus ini adalah _binary classification_.|
| Metrik evaluasi | Metrik evaluasi yang digunakan yaitu metrik klasifikasi seperti ExampleCount, AUC, FalsePositives, TruePositives, FalseNegatives, TrueNegatives, dan BinaryAccuracy. |
| Performa model | Evaluasi model diperoleh yaitu AUC sebesar 76%, kemudian example_count 201, dengan BinaryAccuracy 73%, dan loss sebesar 1.576. Untuk False Negatives 33, False Positive 21, True Negative 74 dan True Positive 73. Performa model dapat ditingkatkan lebih baik lagi, bisa dari segi data ataupun pemrosesan data yang lebih baik lagi. |
