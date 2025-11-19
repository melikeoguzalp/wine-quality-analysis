# 🍷 Şarap Kalitesi Analizi (Wine Quality Analysis)

Bu proje, Python ve veri görselleştirme kütüphanelerini kullanarak kırmızı şarapların fizikokimyasal özelliklerini inceleyen ve bu özelliklerin şarap kalitesi üzerindeki etkilerini araştıran bir veri analizi çalışmasıdır.

## 🎯 Projenin Amacı
Şarapların asidite, şeker oranı, pH değeri ve alkol oranı gibi teknik özelliklerinin, şarap uzmanları tarafından verilen "kalite" puanlarıyla (0-10 arası) nasıl bir ilişkisi olduğunu görselleştirerek anlamak.

## 🛠 Kullanılan Teknolojiler ve Kütüphaneler
Bu projede aşağıdaki Python kütüphaneleri kullanılmıştır:

* **Python 3**
* **Pandas:** Veri manipülasyonu ve analizi (DataFrame işlemleri).
* **NumPy:** Sayısal hesaplamalar.
* **Matplotlib & Seaborn:** Veri görselleştirme (Heatmap, Countplot, Boxplot).

## 📊 Veri Seti Hakkında
Kullanılan veri seti, şarap örneklerinin kimyasal özelliklerini içerir.
* **Girdi Değişkenleri:** Sabit asidite, uçucu asidite, sitrik asit, kalan şeker, klorürler, serbest sülfür dioksit, toplam sülfür dioksit, yoğunluk, pH, sülfatlar, alkol.
* **Hedef Değişken:** Kalite (Quality) - 0 ile 10 arasında bir puan.

## 📈 Analizden Öne Çıkanlar
Proje içerisinde yapılan analizlerde şu adımlar izlenmiştir:

1. **Veri Ön İşleme:** Veri setinin genel yapısı incelendi, eksik veriler kontrol edildi.
2. **İstatistiksel Özet:** `describe()` fonksiyonu ile verilerin ortalama ve sapma değerleri incelendi.
3. **Korelasyon Analizi:** `Seaborn` kullanılarak çizilen Isı Haritası (Heatmap) ile değişkenler arasındaki ilişkiler incelendi.
    * *Gözlem:* Alkol oranı ile şarap kalitesi arasında pozitif bir korelasyon gözlemlendi.

## 🚀 Kurulum ve Çalıştırma

Bu projeyi kendi bilgisayarınızda çalıştırmak için:

1. Repoyu klonlayın:
   ```bash
   git clone [https://github.com/melikeoguzalp/wine-quality-analysis.git](https://github.com/melikeoguzalp/wine-quality-analysis.git)
