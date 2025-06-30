# Brain Tumor Segmentation and Classification with U-Net and MobileNet

Proyek ini bertujuan untuk mendeteksi dan mengklasifikasikan tumor otak dari citra MRI menggunakan pendekatan deep learning. Dengan menggabungkan model segmentasi U-Net dan model klasifikasi MobileNet, proyek ini dikembangkan untuk mendukung proses diagnosis medis secara otomatis, akurat, dan efisien. Proyek ini dibuat sebagai bentuk kontribusi terhadap pemanfaatan teknologi kecerdasan buatan di bidang kesehatan, khususnya dalam membantu tenaga medis mengenali jenis tumor otak lebih cepat dan tepat.

Dataset ini terdiri atas tiga folder utama: train, valid, dan test, yang masing-masing berisi dua subfolder, yaitu images dan labels. Folder images berisi citra MRI otak, sedangkan folder labels berisi informasi kelas dan koordinat poligon dalam format YOLO yang merepresentasikan area tumor. Dataset ini mengandung tiga kelas tumor otak, yaitu:

1. Glioma
2. Pituitary
3. Meningioma

Pendekatan dan langkah-langkah utama:
1. Praproses citra MRI dan anotasi bounding box/mask.
2. Pelatihan model U-Net untuk segmentasi area tumor.
3. Ekstraksi area tumor hasil segmentasi.
4. Pelatihan model klasifikasi berdasarkan area tumor.
5. Evaluasi performa model segmentasi dan klasifikasi.

