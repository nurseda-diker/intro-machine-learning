## Yapay Sinir Ağları (YSA) Nedir?
Yapay sinir ağları, insan beyninin çalışma prensiplerinden ilham alınarak geliştirilmiş makine öğrenimi ve derin öğrenme algoritmalarıdır. 
YSA, sinir hücreleri ve bunlar arasındaki bağlantılardan oluşan bir ağ yapısı ile verileri işleyerek belirli görevleri öğrenir ve gerçekleştirir. 
YSA, özellikle karmaşık ve büyük veri setlerinde yüksek doğrulukla sınıflandırma, regresyon ve diğer tahmin problemlerini çözmek için kullanılır.

## YSA'nın Kullanım Alanları
* **Görüntü Tanıma** : Nesne tespiti, yüz tanıma ve görüntü sınıflandırma gibi görevlerde kullanılır.
* **Doğal Dil İşleme (NLP)** : Metin sınıflandırma, duygu analizi, dil modelleme ve makine çevirisi gibi alanlarda kullanılır.
* **Ses Tanıma** : Konuşma tanıma ve sesli komut sistemlerinde kullanılır.
* **Oyun ve Robotik** : Oyun yapay zekası ve robot kontrol sistemlerinde kullanılır.
* **Tahmin ve Finans** : Borsa tahminleri, kredi risk analizi ve müşteri davranış tahminlerinde kullanılır.
* **Tıp ve Sağlık** : Hastalık teşhisi, tıbbi görüntü analizi ve ilaç keşfinde kullanılır.

## YSA Nasıl Çalışır?
**1. Giriş Katmanı (Input Layer)** : Ham verinin modele beslendiği katmandır. Her bir nöron, bir özellik veya giriş değeri temsil eder.<br>
**2. Gizli Katmanlar (Hidden Layers)** : Giriş katmanı ile çıkış katmanı arasında yer alır ve nöronlar arasındaki ağırlıklı bağlantılar yoluyla veriyi işler. YSA'nın öğrenme kapasitesini artıran katmanlardır. <br>
**3. Çıkış Katmanı (Output Layer)** : Modelin tahmin veya sınıflandırma sonuçlarını verdiği katmandır. Çıkış nöronları, modelin son tahminlerini temsil eder.

## YSA'nın Çalışma Adımları
**1. İleri Yayılım (Forward Propagation)** : Giriş verisi, giriş katmanından başlayarak ağırlıklı bağlantılar yoluyla gizli katmanlar üzerinden çıkış katmanına kadar ilerler. Her bir nöron, aktivasyon fonksiyonu (örneğin ReLU, Sigmoid) aracılığıyla giriş verilerini işler ve bir çıktı üretir.<br>
**2. Hata Hesaplama (Error Calculation)** : Çıkış katmanında üretilen tahminler, gerçek değerlerle karşılaştırılarak hata hesaplanır. Bu hata, genellikle kayıp fonksiyonu (loss function) aracılığıyla ölçülür.<br>
**3. Geri Yayılım (Backpropagation)** : Hesaplanan hata, modelin ağırlıklarını güncellemek için geriye doğru yayılır. Bu süreçte, gradyan inişi (gradient descent) algoritması kullanılarak her bir ağırlığın ne kadar değiştirileceği hesaplanır.<br>
**4. Ağırlık Güncelleme (Weight Update)** : Geri yayılım sırasında hesaplanan gradyanlar kullanılarak ağırlıklar güncellenir. Bu işlem, modelin öğrenmesini sağlar ve her bir yineleme (epoch) sonunda modelin doğruluğunu artırır.

