## Sınıflandırma (Classification) Nedir?
Sınıflandırma, makine öğreniminde verileri önceden tanımlanmış sınıflara veya kategorilere ayırma işlemidir. Bir sınıflandırma modelinin amacı, girdi verilerinin hangi sınıfa ait olduğunu tahmin etmektir. Bu işlem, genellikle etiketi veya hedef değişkeni kategorik olan veri setleri üzerinde yapılır.

## Sınıflandırma Algoritmaları Nelerdir?
* <b>Lojistik Regresyon</b> : İkili sınıflandırma problemleri için sıkça kullanılan temel bir algoritmadır.
* <b>Karar Ağaçları</b> : Verilerin özelliklerine dayalı olarak karar kuralları oluşturan algoritmalar.
* <b>Destek Vektör Makineleri (SVM)</b> : Verileri sınıflandırmak için en uygun hiperdüzlemi bulmaya çalışan algoritmalar.
* <b>K-En Yakın Komşu (K-NN)</b> : Bir veri noktasını, en yakın komşularının çoğunluğuna göre sınıflandıran algoritma.
* <b>Naive Bayes</b> : Bayes teoremi ve basit bağımsızlık varsayımlarına dayanan hızlı ve basit bir algoritma.
* <b>Yapay Sinir Ağları</b> : Daha karmaşık ve derin öğrenme teknikleri kullanan algoritmalar.
* <b>Rastgele Ormanlar (Random Forest)</b> : Birden fazla karar ağacının birleşimi ile daha doğru ve genelleştirilebilir sınıflandırma yapan algoritmalar.

## Sınıflandırma Modellerinin Performansını Değerlendirme

Makine öğreniminde sınıflandırma modellerinin performansını değerlendirmek, modelin ne kadar doğru tahmin yaptığını anlamak için kritik öneme sahiptir. Bu değerlendirme, çeşitli metrikler ve yöntemler kullanılarak yapılır.

* **Karmaşıklık Matrisi (Confusion Matrix)** :  Gerçek ve tahmin edilen sınıflar arasındaki ilişkileri gösteren bir tablodur.
  - **True Positive (TP):** Doğru pozitif tahminler
  - **True Negative (TN):** Doğru negatif tahminler
  - **False Positive (FP):** Yanlış pozitif tahminler
  - **False Negative (FN):** Yanlış negatif tahminler

* **Doğruluk (Accuracy)** : Doğru tahminlerin toplam tahminlere oranıdır. <br>
`Accuracy = (TP + TN) / (TP + TN + FP+ FN) `

* **Kesinlik (Precision)** : Pozitif olarak tahmin edilenlerin, gerçekten pozitif olanlarına oranıdır. <br>
`Precision = TP / (TP + FP)`

* **Duyarlılık (Recall)** : Gerçek pozitiflerin, doğru bir şekilde pozitif olarak tahmin edilme oranıdır. <br>
`Recall = TP / (TP + FN)`

* **F1 Skoru** : Kesinlik ve duyarlılığın harmonik ortalamasıdır. <br>
 `F1 Skoru = 2 * (Kesinlik * Duyarlılık) / (Kesinlik + Duyarlılık)`

* **ROC Eğrisi (Receiver Operating Characteristic Curve)** : Farklı eşik değerlerinin gerçek pozitif oran ile yanlış pozitif oran arasındaki dengeyi etkilediği ikili sınıflandırma sistemlerinde duyarlılık ve özgüllük arasındaki ilişkiyi gösteren bir grafiktir. <br>

* **AUC (Area Under the Curve)** : ROC eğrisinin altındaki alanı temsil eder ve modelin genel performansını değerlendirir.

## Sınıflandırmanın Kullanıldığı Alanlar
* <b>Tıp</b> : Hastalık teşhisi, tıbbi görüntü sınıflandırma.
* <b>Finans</b> : Dolandırıcılık tespiti, kredi risk değerlendirmesi.
* <b>Pazarlama</b> : Müşteri segmentasyonu, hedefli reklamcılık.
* <b>Doğal Dil İşleme</b> : Spam e-posta tespiti, duygu analizi.
* <b>Görüntü İşleme</b> : Yüz tanıma, nesne tespiti.
* <b>Sosyal Medya</b> : Kullanıcı profilleme, içerik filtreleme.
* <b>Otomotiv</b> : Otonom araçlarda yaya ve trafik işareti tanıma.
