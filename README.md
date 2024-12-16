# aygaz-bootcamp-project-zn
Bu proje, derin öğrenme tabanlı bir sinir ağı (CNN) modeli kullanarak farklı hayvan türlerini sınıflandırma ve görüntü manipülasyonu sonrası model performansını analiz etmeyi amaçlamaktadır.

Proje Hakkında
Proje, dört temel aşamadan oluşmaktadır:
1.Veri seti hazırlama: Veriler sınıflandırma için düzenlenmiş, normalize edilmiş ve eğitim/test kümelerine ayrılmıştır.
2.CNN Modeli Eğitimi: Hayvan türlerini sınıflandırmak için bir derin öğrenme modeli oluşturulmuş ve eğitilmiştir.
3.Görüntü Manipülasyonu: Test görüntüleri farklı ışık koşullarıyla manipüle edilerek model hassasiyeti değerlendirilmiştir.
4.Renk Sabitliği Uygulaması: Manipüle edilmiş görüntülere renk sabitliği algoritması uygulanarak model başarısındaki değişiklikler gözlemlenmiştir.

Kullanılan Veri Seti
Veri seti, Animals with Attributes 2 adlı Kaggle veri setidir.
Projede sadece şu 10 hayvan sınıfı kullanılmıştır:
collie, dolphin, elephant, fox, moose, rabbit, sheep, squirrel, giant panda, polar bear
Her sınıftan 650 resim seçilmiş, veriler aynı boyuta getirilmiş ve normalize edilmiştir.

Kullanılan Kütüphaneler
Projede Python dili ve şu kütüphaneler kullanılmıştır:
NumPy: Veri işlemleri
Pandas: Veri organizasyonu
OpenCV: Görüntü işleme
TensorFlow/Keras: CNN modeli tasarımı ve eğitimi
Matplotlib/Seaborn: Veri görselleştirme
scikit-learn: Veri bölme ve değerlendirme

Adımların Detayları
Veri Setinin Hazırlanması
10 sınıf için veriler seçilmiş, resimler yeniden boyutlandırılmış ve normalize edilmiştir.
Eğitim ve test kümeleri (%70 eğitim, %30 test) rastgele olarak oluşturulmuştur.
CNN Modeli Tasarımı

CNN modeli, Convolutional, Pooling ve Dense katmanları içerecek şekilde oluşturulmuştur.
Kayıp fonksiyonu olarak categorical_crossentropy, optimizasyon için Adam kullanılmıştır.

Manipüle Edilmiş Veriler Üzerinde Model Performansı
Test görüntülerine ışık manipülasyonu uygulanarak modelin performansı değerlendirilmiştir.

Renk Sabitliği Uygulanması
Gray World algoritması ile manipüle edilmiş görüntüler düzeltilmiş ve model yeniden test edilmiştir.

Sonuç ve Tartışma
Proje sonunda, üç farklı test seti için elde edilen başarı oranları karşılaştırılmıştır. Raporlama kısmında, CNN modellerinin hassasiyetine ve çözüm önerilerine yer verilmiştir.

.
