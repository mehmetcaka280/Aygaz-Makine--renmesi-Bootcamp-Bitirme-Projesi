Aygaz Makine Öğrenmesi Bootcamp: Banka Müşteri Churn Analizi Projesi

Projenin Kaggle Linki:
https://www.kaggle.com/code/mehmetaka/aygaz-bootcamp-ml-project


Veri Seti:
Projede kullanılan veri seti, 'botswana_bank_customer_churn.csv' dosyasından yüklenmiştir. Veri seti, müşterilerin demografik bilgilerini, finansal durumlarını ve banka ile ilişkilerini içermektedir.

Proje Özeti:
Bu proje, Aygaz Makine Öğrenmesi Bootcamp kapsamında gerçekleştirilen bir banka müşteri churn analizi çalışmasıdır. Projenin amacı, müşteri verilerini kullanarak churn (müşteri kaybı) tahminlemesi yapmak ve müşteri segmentasyonu oluşturmaktır.



Kullanılan Teknolojiler ve Kütüphaneler:

Python
pandas
numpy
matplotlib
seaborn
scikit-learn

Proje Adımları
1. Veri Yükleme ve Keşifsel Veri Analizi (EDA):

Veri seti yüklendi ve genel bilgiler incelendi.
Temel istatistikler hesaplandı.
Korelasyon matrisi oluşturuldu.
Churn dağılımı ve gelir dağılımı görselleştirildi.
Gelir ve kredi skoru ilişkisi incelendi.

2. Veri Ön İşleme:

Gereksiz sütunlar kaldırıldı.
Kategorik değişkenler sayısallaştırıldı.
Tarih sütunları işlendi.
Eksik değerler dolduruldu.
Sayısal özellikler ölçeklendirildi.

3. Gözetimli Öğrenme: Lojistik Regresyon:

Veri seti eğitim ve test setlerine bölündü.
Normal Lojistik Regresyon modeli eğitildi ve değerlendirildi.
Hiperparametre optimizasyonu ile Lojistik Regresyon modeli iyileştirildi.

4. Gözetimsiz Öğrenme: K-Means Kümeleme:

K-Means algoritması uygulandı.
Silhouette skoru ile kümeleme performansı değerlendirildi.
Hiperparametre optimizasyonu ile K-Means modeli iyileştirildi.
Kümeleme sonuçları görselleştirildi.

Sonuçlar
Lojistik Regresyon Sonuçları:

Normal Lojistik Regresyon Doğruluğu: [Doğruluk değeri]
Optimize Edilmiş Lojistik Regresyon Doğruluğu: [Optimize edilmiş doğruluk değeri]

K-Means Kümeleme Sonuçları:

Normal K-Means Silhouette Skoru: 0.381
Optimize Edilmiş K-Means Silhouette Skoru: 0.37385

Çıkarımlar ve Öneriler:

Lojistik Regresyon modeli, müşteri churn'ünü tahmin etmede [başarı düzeyi] bir performans göstermiştir.
K-Means kümeleme, müşterileri [küme sayısı] gruba ayırmıştır, ancak gruplar arasında net bir ayrım gözlemlenmemiştir.
Gelir ve kredi skoru arasındaki ilişki, müşteri segmentasyonunda önemli faktörler olarak ortaya çıkmıştır.
