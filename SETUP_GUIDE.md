#  Pandas Fundamentals Lab – Kurulum ve Çalıştırma Rehberi

Bu rehber, projeyi sıfırdan kurmak, çalıştırmak ve birebir pratik yapmak isteyenler için hazırlanmıştır.

---

## 1️⃣ Sistem Gereksinimleri

## Python

- Python 3.10 veya üzeri önerilir
- Minimum: Python 3.x
  
---

Versiyon kontrolü:

bash
python --version

---

## 2️⃣ Ortam Kurulumu (Önerilen: Sanal Ortam)

Projeyi temiz bir ortamda çalıştırmak için:

Sanal ortam oluşturma

python -m venv venv

Ortamı aktive etme
Windows:venv\Scripts\activate

---

## 3️⃣ Gerekli Kütüphaneler

pip install pandas matplotlib seaborn notebook

pip list

---

## 4️⃣ Jupyter Notebook Başlatma

jupyter notebook - jupyter LAB

---

## 5️⃣ Notebook Çalıştırma Hiyerarşisi

Notebook’lar aşağıdaki sırayla çalıştırılmalıdır:

01_pandas_methods_and_indexing_case_lab.ipynb

02_pandas_aggregation_and_cleaning_mini_case.ipynb

03_pandas_visualization_and_eda_mini_lab.ipynb

Her notebook için önerilen çalışma yöntemi:

Kernel → Restart

Run → Run All

Bu, kodun baştan sona hatasız çalıştığını doğrulamanızı sağlar.

---

## 6️⃣ Analitik Yaklaşım Rehberi

Bu projeden maksimum fayda sağlamak için:

✔ Kodları sadece çalıştırmayın
✔ Markdown açıklamalarını dikkatle okuyun
✔ .describe() çıktısını yorumlamaya çalışın
✔ Eksik veri nedenlerini sorgulayın
✔ Negatif değerlerin anlamını düşünün
✔ Sabit kolonların modelleme üzerindeki etkisini değerlendirin

---

## 7️⃣ İleri Seviye Pratik Önerileri

Projeyi tamamladıktan sonra:

Aynı analizleri farklı bir dataset üzerinde tekrar edin

Ek görselleştirmeler ekleyin

Farklı groupby() kombinasyonları deneyin

Eksik veri stratejisini değiştirerek sonuçları kıyaslayın

Küçük bir rapor (PDF / Markdown) oluşturun

Bu repo bir “son nokta” değil,
veri analizi yolculuğunda bir temel yapı taşıdır.

---

## 8️⃣ Sorun Giderme
Kernel hatası alırsanız:

Ortamın aktif olduğundan emin olun

pip list ile paketlerin kurulu olduğunu kontrol edin

Grafik görünmüyorsa:

Notebook içinde şu satırın olduğundan emin olun:

 // **import matplotlib.pyplot as plt**
 
 // **%matplotlib inline**

---
