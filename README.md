# Türkiye Konut Piyasası Analizi

Bu proje [@laothrs](https://github.com/laothrs) tarafından geliştirilmiştir.

## Proje Hakkında

Bu analiz, Türkiye'deki konut piyasasının mevcut durumunun kapsamlı bir incelemesini sunmaktadır. Çalışma, 2024'ün başı itibariyle satılık 40.482 konut ilanını içeren bir veri kümesine dayanmaktadır.

## Analiz İçeriği

### 1. Veri Kaynağı
- Emlak listelerinin önde gelen bir Türk web sitesinden derlenmiştir
- 40.482 konut ilanı analiz edilmiştir
- Veriler 2024 yılı başına aittir

### 2. İncelenen Faktörler
- Fiyat
- Metrekare
- Metrekare başına birim fiyat
- İl bazlı dağılımlar
- Oda sayısı
- TOKİ ve TOKİ dışı konut karşılaştırması
- Acil ve lüks konut oranları

### 3. Türkiye Geneli Harita Analizleri

#### Türkiye Ortalama Konut Büyüklüğü Haritası
![Türkiye Metrekare Haritası](Analiz%20Fotoğrafları/turkiye_metrekare_haritasi.png)
*İllere göre ortalama konut büyüklüğü (m²) dağılımı*

#### Türkiye TOKİ Konutları Oranı Haritası
![Türkiye TOKİ Dağılım Haritası](Analiz%20Fotoğrafları/turkiye_toki_haritasi.png)
*İllere göre TOKİ konutlarının oranı (%)*

#### Türkiye Ortalama Konut Fiyatı Haritası
![Türkiye Fiyat Haritası](Analiz%20Fotoğrafları/turkiye_fiyat_haritasi.png)
*İllere göre ortalama konut fiyatı (TL) dağılımı*

### 4. Karşılaştırmalı Analizler

#### TOKİ vs Diğer Konutlar - Ortalama Metrekare
![TOKİ vs Diğer Konutlar - Ortalama m²](Analiz%20Fotoğrafları/tokivsdigermetrekare.png)

#### TOKİ vs Diğer Konutlar - Ortalama Fiyat
![TOKİ vs Diğer Konutlar - Ortalama Fiyat](Analiz%20Fotoğrafları/Tokivsdigerkonutlarfiyat.png)

#### Değişkenler Arası Korelasyon
![Değişkenler Arası Korelasyon](Analiz%20Fotoğrafları/KorelasyonAnalizi.png)

#### Metrekare - Birim Fiyat İlişkisi
![Metrekare - Birim Fiyat İlişkisi](Analiz%20Fotoğrafları/MetrekareBirimFiyat.png)

#### Oda Sayısına Göre Fiyat Dağılımı
![Oda Sayısına Göre Fiyat Dağılımı](Analiz%20Fotoğrafları/OdaSayisi.png)

### 5. Temel İstatistikler

#### Metrekare İstatistikleri
| İstatistik | Değer |
|------------|-------|
| Ortalama | 136.47 |
| Medyan | 135 |
| Standart Sapma | 58.29 |
| Minimum | 1.05 |
| Maksimum | 985 |

#### Fiyat İstatistikleri
| İstatistik | Değer |
|------------|-------|
| Ortalama | 3,292,594.15 ₺ |
| Medyan | 2,800,000.00 ₺ |
| Standart Sapma | 2,975,217.04 ₺ |
| Minimum | 110,000.00 ₺ |
| Maksimum | 250,000,000.00 ₺ |

### 6. Önemli Sonuçlar

1. TOKİ konutları, özel sektör konutlarına göre daha uygun fiyatlıdır
2. Büyük şehirlerde (özellikle İstanbul, Ankara ve Kocaeli) metrekare fiyatları daha yüksektir
3. Metrekare arttıkça birim fiyatlarda düşüş gözlemlenmektedir
4. 3+1 konutlar en geniş fiyat aralığına ve en yüksek medyan fiyata sahiptir
5. Doğu illerinde TOKİ konutlarının oranı daha yüksektir
6. Ortalama konut büyüklüğü doğu illerinde daha fazladır

## Detaylı Rapor

Projenin detaylı raporu için [Konut Veri Analizi Raporu](Konut%20Veri%20Analizi%20Raporu) dosyasını inceleyebilirsiniz.

## İletişim

Proje sahibi: [@laothrs](https://github.com/laothrs) 
