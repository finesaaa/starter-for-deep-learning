# 🦾 Neural Network Application Projects

💭 **Discussion: Model Improvement**
Kita bisa mengimprove model sesuai hyper-parameter pada model:
* Jumlah neuron (di hidden layer)
* Jumlah layer (di hidden layer)
* Jenis optimizer
* Learning rate
* Epoch 
* Jenis activation function (hidden layer) - Relu, tanh

💭 **Discussion: Determine The Number of Hidden Layer and Hidden Neuron**

Ada beberapa rule-of-thumb untuk menentukan jumlah neuron yang digunakan pada hidden layer, seperti berikut:

* Jumlah neuron pada hidden layer (n) seharusnya kurang dari 2 kali dari ukuran input layer (i)
  > n < 2i
* Jumlah neuron pada hidden layer (n) berada diantara ukuran input dan ukuran output (o)
  > o < n < i
* Jumlah neuron pada hidden layer setidaknya ⅔ dari ukuran input, ditambah dengan ukuran output
  > n <= 2/3 i + o

Tambahan lainnya,
* 📁 Beberapa kasus dengan data sederhana bisa terselesaikan dengan cukup baik dengan satu hidden layer dengan jumlah neuron rata-rata data input dan output layer. 
* 🗃️ Jika data training cukup banyak, maka kita dapat menggunakan multiple hidden layer, tapi terkadang 2 hidden layer bekerja cukup baik untuk data yang kecil

Dan saat ini, riset pada arsitektur deep learning sangat berkembang dan banyak, dan dapat diketahui bahwa banyaknya hidden layer akan dapat bermanfaat untuk mengenali objek yang sulit, karakter tulisan tangan, dan masalah pengenalan wajah.
Karena pada ujungnya jumlah neuron dan jumlah layer yang diperlukan untuk hidden layer sebenarnya tergantung pada kasus, jumlah outliers, kompleksitas data yang akan dipelajari.

✨ Disini, saya berikan beberapa referensi untuk arsitektur deep learning yang cukup robust dan sering dipakai praktisnya untuk tiap-tiap jenis datanya.

📩 TEXT
- [Tensorflow - Basic Text Classfication with Keras](https://tensorflow.rstudio.com/tutorials/keras/text_classification)
- [Sentiment Analysis with LSTM](https://algotech.netlify.app/blog/text-lstm/)

📸 IMAGE
- [Dataset Site from Tensorflow Google](https://knowyourdata-tfds.withgoogle.com/)
- [Tensorflow - Basic Flower Image Classification with Keras](https://tensorflow.rstudio.com/tutorials/keras/classification)
- [Tensorflow - Image Classification from Scratch using (Convolutional Neural Network)](https://tensorflow.rstudio.com/examples/image_classification_from_scratch)
- [Image Classification with Convolutional Neural Network](https://algotech.netlify.app/blog/image-classification-cnn/)

📊 TABULAR
- [Basic Regression with Keras](https://tensorflow.rstudio.com/tutorials/keras/regression)
- [Time Series Prediction with LSTM](https://algotech.netlify.app/tags/rnn/)

🔊 AUDIO (Python)
- [Simple Audio Recognition](https://www.tensorflow.org/tutorials/audio/simple_audio)
- [Music Generation](https://www.tensorflow.org/tutorials/audio/music_generation)