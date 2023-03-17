## Optik koherens tomografi

21.yüzyılda optik koherens tomografi (OCT) teknolojisinin gelişimi, maküler hastalıkların teşhisi ve tedavilerinin değerlendirilmesinde büyük bir ilerleme sağlamıştır. Dünya genelinde yaklaşık 30 milyon OCT taranması yılda gerçekleştirilmekte ve bu, en sık uygulanan tıbbi görüntüleme prosedürlerinden biri haline gelmiştir. OCT görüntüleme, yaşa bağlı makula dejenerasyonu (AMD) ve diyabetik maküla ödemi gibi önlenebilir körlüklerin tanı ve tedavisinde rehberlik eden bir standart haline gelmiştir.

Bu hastalığın teşhisinde kullanılan 4 farklı sınıf (CNV-DME-DRUSEN-NORMAL) EfficientNetB3 modeli ile eğitim gerçekleştirdim. Aşağıda elde ettiğim sonuçları, Confusion Matrix ve ROC grafik değerlerini paylaşıyorum.

![output](https://user-images.githubusercontent.com/97342455/226048498-a241853c-b511-43f0-8b5d-11cf76133c5c.png)
![output1](https://user-images.githubusercontent.com/97342455/226048646-25675e76-c954-4689-b879-f6eea8b6c259.png)


## Retinopati

Diyabetik retinopati, şeker hastalarında görülen bir göz rahatsızlığıdır. Şeker hastalığı vücuttaki damar ve sinirleri etkileyen bir hastalıktır. Hastalığın seyri sırasında gözdeki damar ve sinirlerin en yoğun olduğu retina katmanında ortaya çıkan değişikliklere diyabetik retinopati denir.

Bu hastalığın teşhisinde,görüntüdeki damarların daha net gözükmesi ve hastalığın daha iyi teşhis edilebilmesi adına, "L-A-B" görüntü kanallarından L kanalında CLAHE- Kontrast Limitli Adaptif Histogram Eşitleme- uygulaması yaptım.

#### Clahe-Öncesi
![clahe-öncesi](https://user-images.githubusercontent.com/97342455/226059599-63418adc-696d-4a8e-bfee-c1f4aa68c109.png)

#### Clahe-Sonrası

![5output](https://user-images.githubusercontent.com/97342455/226059731-5461576d-e5be-4d34-99a1-eda796356248.png)


ardından kullanılan 5 farklı sınıfın sınıflandırılması için EfficientNetB1 modeli ile eğitim gerçekleştirdim.
