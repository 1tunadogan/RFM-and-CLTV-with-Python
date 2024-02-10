# RFM Analizi İle Müşteri Segmentasyonu ve CLTV Tahmini

FLO'yu Türkiye'nin en büyük ayakkabı firmalarından biri olarak biliyoruz. Bu projede FLO'nun müşterilerini segmentlere ayırması ve bu segmentlere uygun kampanyalar ile aksiyon alabilmesi için 2 analiz yapılacaktır.

### Veri Seti Hikayesi

Veri seti, FLO'dan son alışverişlerini 2020 - 2021 yıllarında OmniChannel (hem online hem offline alışveriş yapan) olarak yapan müşterilerin geçmiş alışveriş davranışlarından elde edilen bilgilerden oluşmaktadır. Veri setinde bulunan değişkenler şunlardır:

| Değişken                            | Açıklama                                                      |
|-------------------------------------|---------------------------------------------------------------|
| master_id                           | Eşsiz müşteri numarası                                        |
| order_channel                       | Alışveriş yapılan platforma ait hangi kanalın kullanıldığı   |
| last_order_channel                  | En son alışverişin yapıldığı kanal                           |
| first_order_date                    | Müşterinin yaptığı ilk alışveriş tarihi                      |
| last_order_date                     | Müşterinin yaptığı son alışveriş tarihi                      |
| last_order_date_online              | Müşterinin online platformda yaptığı son alışveriş tarihi     |
| last_order_date_offline             | Müşterinin offline platformda yaptığı son alışveriş tarihi    |
| order_num_total_ever_online         | Müşterinin online platformda yaptığı toplam alışveriş sayısı  |
| order_num_total_ever_offline        | Müşterinin offline'da yaptığı toplam alışveriş sayısı        |
| customer_value_total_ever_online    | Müşterinin offline alışverişlerinde ödediği toplam ücret    |
| customer_value_total_ever_offline   | Müşterinin online alışverişlerinde ödediği toplam ücret     |
| interested_in_categories_12         | Müşterinin son 12 ayda alışveriş yaptığı kategorilerin listesi|

## RFM Analizi ile Müşteri Segmentasyonu

RFM analizi, Recency (yenilik), Frequency (sıklık) ve Monetary (parasal değer) kriterlerini kullanarak müşterileri segmentlere ayırma yöntemidir. Bu analizde, müşteriler son alışveriş tarihlerine göre yenilik, toplam alışveriş sayılarına göre sıklık ve toplam harcama miktarlarına göre parasal değer baz alınarak segmentlere ayrılacaktır.

## BG-NBD ve Gamma-Gamma Modelleri ile CLTV Tahmini

Bu bölümde BG-NBD ve Gamma-Gamma modelleri kullanılarak müşteri yaşam boyu değeri (Customer Lifetime Value - CLTV) tahmin edilecektir. BG-NBD modeli, müşteri satın alma davranışlarını ve zaman içindeki tekrar etme olasılıklarını tahmin ederken, Gamma-Gamma modeli, müşteri değerlerini tahmin eder ve bu iki model bir araya gelerek müşterinin yaşam boyu değerini hesaplar.

Yukarıda belirtilen iki analiz yöntemi kullanılarak FLO'nun müşterilerini daha iyi anlaması ve segmentlere ayırması sağlanacaktır. Bu segmentlere göre uygun kampanyalar düzenlenerek müşteri sadakati artırılabilir ve gelir artışı hedeflenebilir.