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
[ASK-Man](#panda_face-ASK-Man)
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
Model konvolusi menggunakan arsitektur lapisan embedding dan aktivasi ReLU, optimasi dilakukan dengan Adam optimizer untuk meminimalkan loss binary crossentropy. Pelatihan diterapkan menggunakan mini-batch perhitungan gradien dan pembaruan bobot melalui backpropagation. Pada tahapan akhir dilakukan verifikasi SNN dengan distance layer. Pengujian model dilakukan dalam skenario realtime OpenCV memungkinkan proses verifikasi berlangsung secara cepat, efisien, dan akurat. Untuk langkah dan Proses yang lebih jelas, akan di tunjukkan dalam diagram flowchart dibawah ini
</p>

<p align="center">

# :world_map: Diagram Alir Analisis

![WhatsApp Image 2024-10-18 at 16 00 56_4ac91ebd](https://raw.githubusercontent.com/abdul014/ASK-MAN/refs/heads/main/Pictures/alur%20proses.drawio.png)
<p align="justify">
Diagram alir dimulai dari mengumpulkan data yang kemudian dikategorikan menjadi anchor, positif, dan negatif, selanjutnya dilakukan penyimpanan data hasil pengkategorian. Pada langkah selanjutnya, augmentasi dan prapemrosesan data, membagi data menjadi data pelatihan dan data pengujian, Setelahnya adalah membangun model pelatihan, mengevaluasi model, menghitung metrik, melakukan uji waktu nyata, dan akhirnya menyimpulkan hasil keseluruhan.
</p>

</p>




## :books: Demo

<div align="center">

![image](https://github.com/abdul014/ASK-MAN/blob/main/Pictures/demo.gif)

<p align="center">

<p align="justify">
Berikut merupakan hasil pengujian menggunakan tanda tangan yang tidak tersimpan di dalam database atau dengan kata lain tanda tangan lain. Terlihat jika sistem menyatakannya sebagai False atau kesalahan.
</p>

## :panda_face: ASK-Man 

+ [Abd Rahman](https://github.com/abdul014/)
+ [Kevin_Alifviansyah](https://github.com/kevinsoewari/)
+ [Sean Marshelle](https://github.com/seanmarshelleproj)
+ [Meisyatul Ilma](https://github.com/meisyatulilma)

