# RFM ile Müşteri Segmentasyonu 

## İş Problemi 

- FLO müşterilerini segmentlere ayırıp bu segmentlere göre pazarlama stratejileri belirlemek istiyor.
- Buna yönelik olarak müşterilerin davranışları tanımlanacak ve bu davranış öbeklenmelerine göre gruplar oluşturulacaktır.

## Veri Seti Hikayesi
- Veri seti son alışverişlerini 2020 - 2021 yıllarında OmniChannel(hem online hem offline alışveriş yapan) olarak yapan müşterilerin geçmiş alışveriş davranışlarından elde edilen bilgilerden oluşmaktadır.

| Değişkenler                    | Açıklama                                                      |
| ------------------------ | ------------------------------------------------------------- |
| master_id                | Eşsiz müşteri numarası                                        |
| order_channel            | Alışveriş yapılan platforma ait kanal (Android, iOS, Desktop, Mobile) |
| last_order_channel       | En son alışverişin yapıldığı kanal                             |
| first_order_date         | Müşterinin yaptığı ilk alışveriş tarihi                        |
| last_order_date          | Müşterinin yaptığı son alışveriş tarihi                        |
| last_order_date_online   | Müşterinin online platformda yaptığı son alışveriş tarihi       |
| last_order_date_offline  | Müşterinin offline platformda yaptığı son alışveriş tarihi      |
| order_num_total_ever_online     | Müşterinin online platformda yaptığı toplam alışveriş sayısı    |
| order_num_total_ever_offline    | Müşterinin offline'da yaptığı toplam alışveriş sayısı           |
| customer_value_total_ever_offline    | Müşterinin offline alışverişlerinde ödediği toplam ücret       |
| customer_value_total_ever_online     | Müşterinin online alışverişlerinde ödediği toplam ücret        |
| interested_in_categories_12 | Müşterinin son 12 ayda alışveriş yaptığı kategorilerin listesi |
