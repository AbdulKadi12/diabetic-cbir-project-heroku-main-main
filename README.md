# PLANT IMAGE RETRIEVAL USING CNN

## Deskripsi Dataset
Dalam pembuatan project ini, dataset yang kami gunakan merupakan dataset yang berupa daun kacang dan daun kedelai yang didapatkan dari situs https://maxwell.ict.griffith.edu.au/cvipl/databases.html yang berjudul CVIP100 Leaf. Dataset ini berisi banyak jenis daun tanaman tetapi kami ambil sebanyak 132 gambar pada daun kacang dan 145 gambar pada daun kedelai dan semua gambar tersebut bertipe .jpg

## Jurnal Referensi
Jurnal referensi yang digunakan dalam pembuatan project ini berjudul [Fine-Grained Plant Leaf Image Retrieval Using Local Angle Coocurrence Histograms](http://www.doi.org/10.1109/ICIP42928.2021.9506351). Xin Chen, Jiawei You, Hui Tang, Bin Wang, Yongsheng Gao.

## Author
Kontributor dalam pengerjaan project ini adalah
1. Abdulkadir [abdulkadir@webmail.umm.ac.id](http://www.gmail.com) - 201810370311046
2. Auliya Tara SL [aultsl28@webmail.umm.ac.id](http://www.gmail.com) - 201810370311129

### Pre-Processing
Pre processing yang digunakan dalam project ini yaitu ekstrak file, split data, pemberian data augmentasi menggunakan image generator

### Modeling
Modeling yang digunakan dalam project ini adalah model VGG16, augmentasi, MaxPooling2D, AveragePooling2D, Hyperparameter, GlobalAveragePooling2D, Flatten,BatchNormalization, Dropout

![image](https://user-images.githubusercontent.com/92361807/149971430-e4049265-4224-4fe8-b445-edf6dca97ae2.png)

![image](https://user-images.githubusercontent.com/92361807/149971667-e2643287-a82c-4cdc-98eb-2425588918be.png)

## Overview Dataset
Jumlah dan persentase splitting dataset :
train (80%, jumlah data train)
validation (10%, jumlah data validation)
test (80%, jumlah data test)
