# sigorta_analiz
# Sigorta Çağrı Merkezi Analiz Raporu
Bu proje, Power BI kullanılarak oluşturulmuş bir Sigorta Çağrı Merkezi Veri Analizi Raporudur. Rapor, çağrıların durumu, zaman dağılımı, müşteri temsilcisi performansı ve diğer önemli metrikleri görsel olarak analiz etmeyi amaçlar.

## Proje Amacı
Sigorta firmalarının çağrı merkezi süreçlerini optimize etmelerine yardımcı olmak için aşağıdaki sorulara yanıt verir:
- Günlük veya aylık çağrı yoğunluğu nasıldır?
- Çağrıların ne kadarı olumlu sonuçlanmıştır?
- En çok çağrı alan veya en iyi performansı gösteren temsilciler kimlerdir?
- Hangi konular daha sık çağrı alıyor? (Hasar bildirimi, poliçe bilgisi, vb.)

![image](https://github.com/user-attachments/assets/8264361c-6464-4155-a724-5e18801a73e9)

## Kullanılan Veriler
- Alan Adı	Açıklama
- CallDate	Çağrının gerçekleştiği tarih
- Duration	Çağrının süresi (dk)
- AgentName	Çağrıyı yanıtlayan temsilcinin adı
- Status	Olumlu / Olumsuz çağrı durumu
- CallType	Çağrının konusu (hasar, şikayet, vs.)
- Region	Bölge (Marmara, Ege, vs.)

## Öne Çıkan Görselleştirmeler
- Zaman Serisi Analizi: Aylara göre çağrı sayılarının dağılımı
- Gauge Grafik: Olumlu çağrıların oranı
- Donut Grafik: Olumlu – Olumsuz çağrı dağılımı
- Temsilci Performans Grafiği: Her temsilcinin olumlu/olumsuz çağrı sayıları
- Konu Bazlı Butonlar: Hasar bildirimi, poliçe bilgisi gibi çağrı konularına filtreleme

## Kullanılan Teknolojiler
 Power BI Desktop, 
 Excel ile veri hazırlama (opsiyonel), 
 GitHub ile paylaşım.
