# pandas-fundamentals-lab
Hands-on pandas fundamentals project including indexing, aggregation, cleaning and EDA case studies.
#  Pandas Fundamentals Lab

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.x-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-teal)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

##  Projenin Amacı

Bu çalışma, aynı zamanda veri analizi sürecini sistematik ve analitik bir çerçevede ele almayı hedefleyen uygulamalı bir laboratuvar çalışmasıdır.

Temel hedefler:

- Veri ile düşünme pratiği geliştirmek  
- Veri kalitesini sorgulama refleksi kazanmak  
- Analitik yorumlama disiplinini oturtmak  
- Portföy standardında, temiz ve açıklayıcı notebook yapısı oluşturmak  
---

# Notebook İçerikleri ve Analitik Çerçeve:

---

## 1️⃣ Pandas Methods & Indexing Case Lab

Bu bölümde pandas’ın temel yapı taşları ele alınmıştır:

- `.loc` ve `.iloc` ile veri seçimi
- Boolean filtreleme
- Koşullu veri çıkarımı
- Sütun ve satır bazlı operasyonlar
- `.describe()` ile betimsel istatistik analizi
###  Analitik Vurgu

Bu aşamada yalnızca teknik seçim yapılmamış;  
`.describe()` çıktısı üzerinden:

- Eksik veri tespiti  
- Değer aralığı analizi  
- Çeyrek dağılım yorumlama  
- Olası anomali kontrolü  

gibi veri kalitesi farkındalığı geliştirilmiştir.

---

## 2️⃣ Aggregation & Data Cleaning Mini Case

Bu notebook, veri analizi sürecinin en kritik kısmına odaklanır:  
**Veri temizliği ve toplulaştırma.**

Uygulanan başlıca kavramlar:

- Eksik veri analizi
- `groupby()` ve `agg()` kullanımı
- Değişken bazlı karşılaştırmalar
- Sabit (varyasyonsuz) kolon tespiti
- Negatif değerlerin anlamlandırılması

###  Veri Kalitesi Gözlemleri

Bu bölümde özellikle:

- Eksik değer sayılarının yorumlanması  
- Negatif finansal değerlerin olası anlamları  
- Sabit kolonların (örneğin 365 gün gibi) modelleme açısından anlamsızlığı  
- Yoğunlaşmış (clustered) dağılımların analizi  

ele alınmıştır.

Amaç yalnızca kod yazmak değil,  
**veriyle sorgulayıcı ilişki kurmaktır.**

---

## 3️⃣ Visualization & EDA Mini Lab

Bu bölüm keşifsel veri analizine odaklanır:

- Histogram ile dağılım inceleme
- Boxplot ile grup karşılaştırması
- Görsel üzerinden hipotez üretme
- Temel yorumlama pratiği

###  Analitik Yaklaşım

Görselleştirme yalnızca grafik üretme değildir.

Her grafik sonrası:

- Dağılım yapısı
- Olası çarpıklık
- Grup farklılıkları
- İstatistiksel anlamlılık ihtiyacı

gibi sorular sorulmuştur.

---

#  Metodolojik Yaklaşım

Bu proje şu prensiplere göre hazırlanmıştır:

- Notebook’lar baştan sona çalıştırılmıştır.
- Debug hücreleri temizlenmiştir.
- Markdown açıklamaları ile öğretici yapı korunmuştur.
- Veri kalitesi analizi bilinçli şekilde entegre edilmiştir.
- Kod + yorum + bağlam birlikte sunulmuştur.

Amaç:

> “Kod yazmak” değil,  
> “Analitik düşünceyi yapılandırmak”.

---

#  Kullanılan Araçlar

- Python 3.x  
- pandas 2.x  
- matplotlib  
- seaborn  
- Jupyter Notebook (Lab) 

---

#  Nihai Motivasyon

Bu çalışma, veri bilimi yolculuğunda sağlam bir temel oluşturma motivasyonu ile hazırlanmıştır.

Temel pandas becerilerini:

- bilinçli,
- sistematik,
- analitik,
- portföy standardında

bir yapıya dönüştürmek hedeflenmiştir.
