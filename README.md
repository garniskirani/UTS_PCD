# UTS_PCD
Dari program soal UTS yang telah diperbaiki itu memberikan pemahaman dan contoh implementasi dalam pengolahan citra menggunakan Python, khususnya dengan menggunakan modul (penggunaan library) seperti NumPy, OpenCV, dan Matplotlib.
Selain itu program tersebut juga banyak memaparkan tentang histogram. Histogram citra (image histogram) merupakan informasi yang penting mengenai isi citra digital. Histogram citra adalah grafik yang menggambarkan penyebaran nilai-nilai intensitas pixel dari suatu citra atau bagian tertentu di dalam citra. Dari sebuah histogram dapat diketahui frekuensi kemunculan nisbi (relative) dari intensitas pada citra tersebut. Histogram juga dapat menunjukkan banyak hal tentang kecerahan (brightness) dan kontras (contrast) dari sebuah gambar. Karena itu, histogram adalah alat bantu yang berharga dalam pekerjaan pengolahan citra baik secara kualitatif maupun kuantitatif.
 Program tersebut menjelaskan tentang:

1.  Manipulasi Citra:
   - Pemanfaatan array NumPy dan modul OpenCV untuk merepresentasikan dan memanipulasi citra.
   - Pemisahan saluran warna (RGB) dari citra menggunakan OpenCV.
Manipulasi citra merupakan proses pengolahan dan transformasi suatu gambar digital dengan tujuan untuk menghasilkan efek tertentu atau meningkatkan kualitas citra. Dalam konteks pengolahan citra, manipulasi mencakup berbagai operasi seperti perubahan warna, kontrast, kecerahan, dan transformasi bentuk. Operasi tersebut dapat dilakukan dengan menggunakan berbagai teknik dan rumus matematis untuk mengubah intensitas piksel atau distribusi warna pada citra.
2. Analisis Histogram:
   - Pembuatan dan visualisasi histogram untuk memahami distribusi intensitas piksel dalam citra.
   - Analisis histogram pada citra berwarna dan citra greyscale.
Analisis histogram adalah suatu metode dalam pengolahan citra yang bertujuan untuk memahami distribusi intensitas piksel dalam suatu citra. Histogram merepresentasikan sebaran frekuensi kemunculan nilai intensitas piksel, diukur dalam bentuk interval atau "bin." Setiap bin pada histogram menunjukkan berapa banyak piksel dalam citra yang memiliki intensitas tertentu. Analisis histogram memberikan pemahaman visual tentang distribusi warna atau kecerahan pada seluruh citra, membantu mengidentifikasi pola dan karakteristik yang mungkin tidak terlihat secara langsung.
3. Transformasi Citra:
   - Implementasi operasi seperti inversi, peningkatan kecerahan, dan transformasi non-linear pada citra.
   - Visualisasi hasil transformasi menggunakan fungsi `cv_imshow` dan `plt.show()`.
Tujuan dari transformasi citra dapat beragam, seperti peningkatan kontras, pengurangan kecerahan, penerapan efek artistik, atau bahkan perubahan bentuk geometris. Transformasi citra dapat dilakukan dengan berbagai metode matematis, dan hasilnya dapat mempengaruhi tampilan visual atau ekstraksi informasi dari citra tersebut.
4. Analisis Saluran Warna (RGB):
   - Analisis distribusi intensitas piksel pada saluran warna biru, hijau, dan merah secara terpisah.
Analisis saluran warna (RGB) adalah suatu pendekatan dalam pengolahan citra yang melibatkan pemisahan dan pemeriksaan setiap komponen warna utama dalam citra berwarna, yaitu merah (Red), hijau (Green), dan biru (Blue). Citra berwarna direpresentasikan dalam model warna RGB, di mana setiap piksel memiliki intensitas nilai untuk ketiga saluran warna tersebut. Analisis saluran warna memungkinkan pemahaman mendalam tentang kontribusi masing-masing warna terhadap tampilan keseluruhan citra.
5. Analisis Citra Greyscale:
   - Pemisahan dan visualisasi saluran warna biru dari citra.
   - Pembuatan dan visualisasi histogram untuk citra greyscale.
Dalam analisis citra greyscale, histogram intensitas piksel digunakan untuk menyajikan frekuensi kemunculan nilai intensitas tertentu. Hal ini membantu dalam mengidentifikasi pola intensitas piksel, tingkat kontrast, dan sebaran kecerahan dalam citra. Analisis citra greyscale sering digunakan dalam konteks pengolahan citra medis, analisis tekstur, dan deteksi tepi, di mana informasi kecerahan menjadi fokus utama.
6. Integrasi Visualisasi:
   - Penggunaan berbagai modul dan fungsi visualisasi seperti `cv_imshow` dan `plt.show()` untuk menyajikan hasil eksplorasi (image) dengan jelas.
Integrasi visualisasi merujuk pada penggabungan atau penyatuan berbagai teknik visualisasi dalam konteks analisis atau pemahaman data. Dalam konteks pengolahan citra, integrasi visualisasi mengacu pada penggunaan metode visual untuk menggabungkan informasi dari berbagai aspek atau representasi citra. Hal ini dapat melibatkan penyatuan hasil analisis statistik, histogram, transformasi citra, atau analisis saluran warna dalam satu tampilan visual yang holistik.

