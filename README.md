# 🚀 14 Günlük Uygulamalı NLP Kampı

Bu depo, 14 gün sürecek yoğunlaştırılmış Doğal Dil İşleme (NLP) yolculuğumdaki tüm teknik çalışmaları, projeleri ve veri setlerini içermektedir. Kamp boyunca her gün yeni bir teknik öğrenerek, gerçek dünya verileri üzerinde Türkçe NLP modelleri geliştiriyorum.

## 📅 Kamp Programı ve İlerleme Durumu

| Gün | Konu | Kullanılan Teknolojiler | Durum |
|:---:|:---|:---|:---:|
| **1** | **Metin Ön İşleme & Prototip** | NLTK, Zeyrek, Scikit-Learn | ✅ Tamamlandı |
| **2** | **Büyük Veri & Pandas Analizi** | Pandas, Matplotlib | ⏳ Sırada |
| **3** | **Vektörleştirme (TF-IDF)** | Scikit-Learn | ⏳ Beklemede |
| **4** | **Sınıflandırma Modelleri** | Logistic Regression | ⏳ Beklemede |

---

## 🛠️ Günlük Teknik Detaylar

### 🔹 1. Gün: Türkçe Metin Ön İşleme Hattı (Pipeline)
NLP projelerinin en kritik aşaması olan "Veri Temizleme" üzerine odaklanıldı. 
- **Tokenizasyon:** Metinler kelime birimlerine ayrıldı.
- **Morfolojik Analiz (Lemmatization):** Türkçe'nin eklemeli yapısı nedeniyle `Zeyrek` kütüphanesi kullanılarak kelimeler köklerine indirgenmiştir.
- **Stop-words Temizliği:** Analiz için değersiz olan bağlaç ve ekler (`ve`, `ama`, `ki` vb.) temizlendi.
- **Vektörleştirme:** `TF-IDF` (Term Frequency-Inverse Document Frequency) yöntemi ile metinler sayısal matrislere dönüştürüldü.
- **Tahmin:** İlk prototip model ile basit bir duygu analizi gerçekleştirildi.



---

## 💻 Nasıl İnceleyebilirim?
Tüm çalışmalar Google Colab üzerinde geliştirilmiştir. Repo içerisindeki `.ipynb` dosyalarına tıklayarak kodları ve analiz sonuçlarını doğrudan tarayıcı üzerinden inceleyebilirsiniz.

---
**Geliştiren:** [Aslı Korkmaz](https://github.com/aslikorkmaz48)
