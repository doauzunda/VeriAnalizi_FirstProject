# VeriAnalizi_FirstProject
# Customer Experience Data Analysis

## Proje Açıklaması

Bu proje, **Kız Başına Veri Analizi Bootcamp 1. Bitirme Projesi** kapsamında hazırlanmıştır. Amaç, gerçek bir müşteri deneyimi veri seti üzerinde veri analizi sürecinin temel adımlarını uygulayarak katılımcıların veri analizi becerilerini geliştirmektir. 

Proje süresince, istatistiksel özet çıkarma, eksik değer analizi, aykırı değer tespiti ve uygun görselleştirmelerle veriyi yorumlama adımları gerçekleştirilmiştir.

---

## Kullanılan Veri Seti

- **Customer Experience Dataset**
- İçerik: Müşteri ID’si, yaş, cinsiyet, konum, görüntülenen ürün sayısı, satın alınan ürün sayısı ve memnuniyet skoru gibi bilgiler yer almaktadır.
- Dosya: `customer_experience_data.csv`

---

## Yapılan Çalışmalar

- Veri seti yüklenip temel ön inceleme yapılmıştır.
- Değişkenler için merkezi eğilim ve dağılım istatistikleri hesaplanmıştır.
- Eksik değerler analiz edilmiş, doldurma ve silme yöntemleri uygulanmıştır.
- Sayısal değişkenlerde aykırı değerler boxplot ile incelenmiştir.
- Kategorik ve sayısal değişkenler için uygun görselleştirmeler üretilmiştir:
  - Memnuniyet Skoru Boxplot
  - Cinsiyete göre Ortalama Memnuniyet Skoru Barplot
  - Yaş Dağılımı Histogram
  - Konuma Göre Müşteri Dağılımı Countplot

---

## Kullanılan Kütüphaneler

Proje Python programlama diliyle hazırlanmıştır. Kullanılan başlıca kütüphaneler:
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`

---

## Nasıl Çalıştırılır

Aşağıdaki adımları terminalde sırasıyla çalıştırarak projeyi kendi bilgisayarınızda kullanabilirsiniz:

```bash
# 1) Reponun bir kopyasını bilgisayarınıza indirin
git clone <repo_link>

# 2) Proje klasörüne girin
cd <repo_adı>

# 3) Gerekli Python kütüphanelerini yükleyin
pip install pandas numpy seaborn matplotlib

# 4) main.ipynb veya .py dosyasını çalıştırarak analiz adımlarını inceleyin
