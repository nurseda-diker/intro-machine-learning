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
**1. Gaussian Naive Bayes** : Özelliklerin normal dağıldığını varsayar. Sürekli veri için uygundur. <br>
**2. Multinomial Naive Bayes** : Kelime sayma (word count) gibi diskret veri için kullanılır. Metin sınıflandırmada yaygındır. <br>
**3. Bernoulli Naive Bayes**: İkili (binary) özelliklere sahip veriler için uygundur. Belirli bir kelimenin bulunup bulunmadığını kontrol eden metin sınıflandırmalarında kullanılır.
