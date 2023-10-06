# portfolio-FLO-crm-analytics
-------------

## Segmantaion With RFM 

**RFM Makale**:
https://medium.com/@kkakturk/rfm-ile-m%C3%BC%C5%9Fteri-segmentasyonu-69577e26210d

##### İş Problemleri 

Online ayakkabı mağazası olan FLO müşterilerini
segmentlere ayırıp bu segmentlere göre pazarlama
stratejileri belirlemek istiyor. Buna yönelik olarak
müşterilerin davranışları tanımlanacak ve bu
davranışlardaki öbeklenmelere göre gruplar oluşturulacak.


##### Veri Seti Hikayesi

Veri seti Flo’dan son alışverişlerini 2020 - 2021 yıllarında OmniChannel (hem online hem offline alışveriş yapan) 
olarak yapan müşterilerin geçmiş alışveriş davranışlarından elde edilen bilgilerden oluşmaktadır.


-------------

## BG-NBD ve Gamma-Gamma ile CLTV Tahmini 

**CLTV Makale**:
https://medium.com/@kkakturk/cltv-customer-lifetime-value-prediction-c996a09c059a

##### İş Problemleri 

FLO satış ve pazarlama faaliyetleri için roadmap 
belirlemek istemektedir. Şirketin orta uzun vadeli plan 
yapabilmesi için var olan müşterilerin gelecekte şirkete
sağlayacakları potansiyel değerin tahmin edilmesi
gerekmektedir.

##### Veri Seti Hikayesi

Veri seti Flo’dan son alışverişlerini 2020 - 2021 yıllarında OmniChannel (hem online hem offline alışveriş yapan) 
olarak yapan müşterilerin geçmiş alışveriş davranışlarından elde edilen bilgilerden oluşmaktadır.

-------------

### Değişkenler

master_id : Eşsiz müşteri numarası
order_channel : Alışveriş yapılan platforma ait hangi kanalın kullanıldığı (Android, ios, Desktop, Mobile)
last_order_channel : En son alışverişin yapıldığı kanal
first_order_date : Müşterinin yaptığı ilk alışveriş tarihi
last_order_date : Müşterinin yaptığı son alışveriş tarihi
last_order_date_online : Müşterinin online platformda yaptığı son alışveriş tarihi
last_order_date_offline : Müşterinin offline platformda yaptığı son alışveriş tarihi
order_num_total_ever_online : Müşterinin online platformda yaptığı toplam alışveriş sayısı
order_num_total_ever_offline : Müşterinin offline'da yaptığı toplam alışveriş sayısı
customer_value_total_ever_offline : Müşterinin offline alışverişlerinde ödediği toplam ücret
customer_value_total_ever_online : Müşterinin online alışverişlerinde ödediği toplam ücret
interested_in_categories_12 : Müşterinin son 12 ayda alışveriş yaptığı kategorilerin listesi

