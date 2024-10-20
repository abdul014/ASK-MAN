<div align="center">

![image](https://github.com/user-attachments/assets/e3f87566-6217-4d7f-a2e6-38d66f59ee84)

# ASK-MAN

## Penerapan Deep Learning untuk Verifikasi Tanda Tangan Dokumen Menggunakan Convolutional Neural Network dan Siamese Neural Network dengan Jarak Mahalanobis

<p align="center">


[Tentang](#newspaper-Tentang)
•
[Deskripsi Project](#open_book-Project)
•
[Demo dan Alur Project](#books-Demo)
•
[Pengembang](#panda_face-Pengembang)
•
</div>

## :newspaper: Tentang

**Sekilas Tentang Pemalsuan Dokumen**

<p align="justify">
Pemalsuan dokumen tanda tangan semakin meningkat seiring dengan perkembangan era digital yang menghadirkan tantangan baru bagi keamanan dokumen dan autentikasi. Penelitian ini bertujuan mengembangkan verifikasi dan pengenalan tanda tangan berbasis Convolutional Neural Network (CNN) dan Siamese Neural Network (SNN) dengan layer distance mahanalobis untuk mendeteksi dan memverifikasi keaslian dokumen tanda tangan. Data dikumpulkan melalui webcam yang mencerminkan data dokumen tanda tangan pada perbankan. Setiap citra diberi label, augmentasi dan preprocessing dengan 2 size citra.
</p>



## :open_book: Project 

<div align="center">

![image](https://github.com/user-attachments/assets/29d16c29-7d61-41e9-b65c-d5e2be98e7ad)

<p align="center">

<p align="justify">
Model konvolusi menggunakan arsitektur lapisan embedding dan aktivasi ReLU, optimasi dilakukan dengan Adam optimizer untuk meminimalkan loss binary crossentropy. Pelatihan diterapkan menggunakan mini-batch perhitungan gradien dan pembaruan bobot melalui backpropagation. Pada tahapan akhir dilakukan verifikasi SNN dengan distance layer. Pengujian model dilakukan dalam skenario realtime OpenCV memungkinkan proses verifikasi berlangsung secara cepat, efisien, dan akurat. 
</p>

## :books: Demo
