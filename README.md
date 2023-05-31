
# Gender Detection webcam

Gerçek zamanlı olarak webcam üzerinden cinsiyet tespiti yapmayı amaçlayan Python projesidir.

![image3](https://github.com/meryemsena/Gender-detection/assets/17953518/31f7d282-8714-4bca-9a71-1d8bb9564eb1)


## Kütüphaneler

numpy

opencv-python

tensorflow

keras


## Kullanılan Veri

Bu çalışmada görseller ile oluşturulacak modeller için “Image Recognition - Gender Detection” veri seti kullanılmıştır. Veri seti; kadın ve erkek kategorileri için yaklaşık 1500’er fotoğraf içermektedir. 

![image1](https://github.com/meryemsena/Gender-detection/assets/17953518/ac5783df-b53c-4961-8f1a-270b75e2857a) ![image2](https://github.com/meryemsena/Gender-detection/assets/17953518/2339731a-828c-457e-a83d-573f9bd955e1)

Resim formatında (png) kaydedilen bu fotoğraflar Convolution Neural Network (CNN) ile sınıflandırılmıştır.  
Modeli yüklemek, eğitmek, test etmek ve değerlendirmek için bazı yardımcı işlevler de sağlayan modelin mimarisini tasarlamak için Keras kullanılmıştır. 
Verilerle ilgili bilgileri görüntülemek ve çizmek için, görüntülerle çalışmak için OpenCV kullanılmıştır.
