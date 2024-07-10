## Naive Bayes Nedir?
Naive Bayes, olasılıksal makine öğrenimi modelleri ailesine ait bir sınıflandırma algoritmasıdır. Naive Bayes, temel olarak Bayes teoremine dayanır ve "naive" (saf) olarak adlandırılır 
çünkü her bir özellik diğerlerinden bağımsızmış gibi varsayılır.
### Bayes Teoremi 
<div align=center> 
<img src="https://i.arkeolojikhaber.com/pool_file/2018/26/37528_bayes-teoremi-formul.png">
</div> 

* **P(A\B)** : B olayının gerçekleşmesi durumunda A olayının olasılığı (posterior olasılık).
* **P(B\A)** : A olayının gerçekleşmesi durumunda B olayının olasılığı (likelihood).
* **P(A)** : A olayının gerçekleşme olasılığı (prior olasılık).
* **P(B)** : B olayının gerçekleşme olasılığı (marginal olasılık).

## ​Naive Bayes Türleri
**1. Gaussian Naive Bayes** : Sıcaklık veya boy gibi tüm özelliklerimiz sürekli değişkenler olduğunda kullanırız. <br>
**2. Multinomial Naive Bayes** : Örneğin aile üyelerinin sayısı veya bir kitaptaki sayfa sayısı gibi ayrık değerlere sahip olduğumuzda kullanırız.  <br>
**3. Bernoulli Naive Bayes**: Doğru veya yanlış, evet veya hayır gibi verilerimiz ikili olduğunda kullanırız.

## Naive Bayes'in Kullanım Alanları
* **Metin Sınıflandırma** : Spam tespiti, duygu analizi, haber kategorilendirme.
* **Doküman Filtreleme** : E-postaların spam olup olmadığını belirleme.
* **Tıbbi Teşhis** : Hastalıkların teşhisinde belirli semptomlara dayanarak olasılık hesaplama.
* **Öneri Sistemleri** : Kullanıcının geçmiş davranışlarına dayalı öneriler oluşturma.
