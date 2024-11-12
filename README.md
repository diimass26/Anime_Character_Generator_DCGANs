<p align="center">
  <a href="" rel="noopener">
 <img src="https://akuma.ai/_next/image?url=%2Fanime-art-models-2.png&w=3840&q=75" alt="Project Thumbnail"></a>
</p>
<h3 align="center">Anime Character Generation with DCGANs</h3>

<div align="center">

<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue">
<img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white">
<img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white">
<img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white">
<img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white">
<img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white">
</div>

---

<p align="center"> Selamat datang di repositori ini! Proyek ini menunjukkan cara membuat anime character generate menggunakan Deep Convolutional Generative Adversarial Network (DCGAN). DCGAN adalah kelas Generative Adversarial Network (GAN) yang memanfaatkan Convolutional Neural Network (CNN) untuk membuat gambar realistis. Dalam kasus ini saya menggunakan dataset anime face character dari kaggle.</p>
    <br> 
</p>

## Table of Content
- [Project Overview](#project-overview)
- [Dataset Overview](#dataset-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Technology Used](#technology-used)
- [Analyze About Technology Used](#analyze-about-technology-used)
- [Conclusion](#conclusion)

## Project Overview
DCGAN adalah kelas Generative Adversarial Network (GAN) yang memanfaatkan Convolutional Neural Network (CNN) untuk membuat gambar realistis. Dalam kasus ini saya menggunakan dataset anime face character dari kaggle. Dataset asli memiliki 63.632 anime face images, tetapi dalam projek ini, saya hanya mengambil sampel 20.000 gambar secara acak dan merubah nama datasetnya menjadi `cartoon_20000`. Hal ini dilakukan untuk mempercepat proses pelatihan model nantinya.

## Dataset Overview
Dataset yang digunakan dalam proyek ini adalah dataset anime face character dari kaggle. Dataset ini terdiri dari 63.632 gambar anime face character yang diambil dari berbagai sumber. Dataset ini telah diubah, saya hanya mengambil sampel 20.000 gambar secara acak dan merubah nama datasetnya menjadi `cartoon_20000`. Anda bisa mengakses dataset pada link berikut : https://www.kaggle.com/datasets/splcher/animefacedataset

Berikut merupakan beberapa sample image dari dataset yang digunakan dalam projek ini:
<img src="https://raw.githubusercontent.com/Mckinsey666/Anime-Face-Dataset/master/test.jpg"></a>


## Installation
1. Clone repositori github ini ke local computer anda .
2. Buka terminal dan jalankan perintah berikut untuk menginstall semua dependencies yang diperlukan:
```
pip install tensorflow keras numpy pandas scikit-learn seaborn matplotlib
```

## Usage
1. Buka file `anime_character_generator.ipynb` dan jalankan seluruh kode untuk melihat hasil pelatihan model.

## Technology Used
- Python
- Jupyter Notebook
- TensorFlow
- Keras
- scikit-learn
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Kaggle

## Analyze About Technology Used
- Python : Python adalah bahasa pemrograman yang digunakan untuk mengimplementasikan model DCGAN. Python memiliki banyak pustaka dan modul yang dapat digunakan untuk memudahkan pengembangan model.
- Jupyter Notebook : Jupyter Notebook adalah platform yang digunakan untuk menulis dan menjalankan kode Python. Jupyter Notebook memungkinkan pengguna untuk menulis kode, menjelaskan algoritma, dan menampilkan visualisasi data dalam satu dokumen.
- TensorFlow : Library open-source machine learning canggih yang digunakan untuk membangun dan melatih model DCGAN, menyediakan backend untuk dukungan Keras dan GPU.
- Keras : Library open-source neural network yang membantu pemngembangan dan pelatihan model deep learning, termasuk untuk arsitektur DCGAN.
- Scikit-Learn : Library open-source machine learning yang digunakan untuk memproses data dan mengevaluasi model.
- Numpy : Library open-source untuk komputasi numperik matematika.
- Pandas : Library open-source untuk analisis data dan manipulasi data.
- Matplotlib : Library open-source untuk membuat visualisasi data.
- Seaborn : Library open-source untuk membuat visualisasi data yang lebih interaktif dan lebih menarik.
- Kaggle : Platform yang digunakan untuk mengakses dataset anime face character.

## Conclusion
Projek ini berhasil menunjukkan cara membuat anime face generator menggunakan Deep Convolutional Generative Adversarial Network (DCGAN). Dengan memanfaatkan tools machine learning yang canggih seperti TensorFlow dan Keras, beserta library manipulasi data dan visualisasi penting seperti Numpy, Pandas, Matplotlib, dan Seaborn, proyek ini membuat wajah anime yang unik dan realistis. Dengan menggunakan kumpulan data wajah anime Kaggle, model ini menunjukkan kemampuan DCGAN untuk mempelajari pola visual yang kompleks, menjadikannya sebuah gebrakan baru untuk aplikasi kreatif, seperti desain karakter game. Projek ini menunjukkan efektivitas DCGAN dalam tugas generate gambar, membuktikan kehebatan DCGAN dalam menghasilkan wajah anime.