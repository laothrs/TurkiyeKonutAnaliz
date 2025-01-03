# Türkiye Konut Piyasası Analizi

Bu proje [@laothrs](https://github.com/laothrs) tarafından geliştirilmiştir.

## Kurulum

1. Python 3.8 veya üzeri sürümün yüklü olduğundan emin olun
2. Sanal ortam oluşturun ve aktifleştirin:
```bash
python3 -m venv venv
source venv/bin/activate  # Linux/Mac için
# veya
venv\Scripts\activate  # Windows için
```
3. Gerekli paketleri yükleyin:
```bash
pip install -r requirements.txt
```
4. Jupyter Notebook'u başlatın:
```bash
jupyter notebook
```
5. Tarayıcıda açılan Jupyter arayüzünden `KonutAnalizi.ipynb` dosyasını açın

## Proje Hakkında

Bu analiz, Türkiye'deki konut piyasasının mevcut durumunun kapsamlı bir incelemesini sunmaktadır. Çalışma, 2024-2025 yılları arasında toplanan 40.482 konut ilanını içeren bir veri kümesine dayanmaktadır.

## Analiz İçeriği

### 1. Veri Kaynağı
- Emlak listelerinin önde gelen bir Türk web sitesinden derlenmiştir
- 40.482 konut ilanı analiz edilmiştir
- Veriler 2024 yılından 2025 süresince geçen süreye aittir

### 2. İncelenen Faktörler
- Fiyat
- Metrekare
- Metrekare başına birim fiyat
- İl bazlı dağılımlar
- Oda sayısı
- TOKİ ve TOKİ dışı konut karşılaştırması
- Acil ve lüks konut oranları

### 3. Önemli Bulgular

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

### 4. Temel İstatistikler

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

### 5. Önemli Sonuçlar

1. TOKİ konutları, özel sektör konutlarına göre daha uygun fiyatlıdır
2. Büyük şehirlerde (özellikle İstanbul, Ankara ve Kocaeli) metrekare fiyatları daha yüksektir
3. Metrekare arttıkça birim fiyatlarda düşüş gözlemlenmektedir
4. 3+1 konutlar en geniş fiyat aralığına ve en yüksek medyan fiyata sahiptir

## Detaylı Rapor

Projenin detaylı raporu için [Konut Veri Analizi Raporu](Konut%20Veri%20Analizi%20Raporu) dosyasını inceleyebilirsiniz.

## İletişim

Proje sahibi: [@laothrs](https://github.com/laothrs) 
