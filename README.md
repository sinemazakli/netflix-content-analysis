# Netflix İçerik Analizi

Bu proje, Netflix platformunda yer alan içeriklerin
veri analizi yöntemleriyle incelenmesini amaçlayan
bir **alıştırma (ısınma) projesidir**.

---

## Projenin Amacı
Bu çalışmada Netflix içerikleri;

- İçerik türü (Film / TV Show)
- Yayın yılına göre içerik artışı
- Ülkelere göre içerik dağılımı

başlıkları altında analiz edilmiştir.

Amaç, veri temizleme, keşifsel veri analizi (EDA) ve
görselleştirme konularında pratik kazanmak ve
iş dünyasına yönelik analiz bakış açısı geliştirmektir.

---

## Kullanılan Teknolojiler
- Python
- pandas
- matplotlib
- Jupyter Notebook

---

## Yapılan Analizler

### 📊 Yıllara Göre İçerik Dağılımı
Netflix içerik sayısında 2011 yılından sonra belirgin bir artış olduğu,
özellikle 2015 sonrası dönemde içerik üretiminin hızlandığı gözlemlenmiştir.

---

### 🎬 Film vs TV Show Analizi
Platformdaki içeriklerin yaklaşık %70’inin film,
%30’unun ise TV Show olduğu görülmüştür.
Bu durum, Netflix’in daha kısa süreli ve geniş kitlelere
hitap eden içeriklere ağırlık verdiğini göstermektedir.

---

### 🌍 Ülkelere Göre İçerik Dağılımı (Top 10)
İçerik üretiminde Amerika Birleşik Devletleri’nin açık ara lider olduğu,
ABD’yi Hindistan ve Birleşik Krallık’ın takip ettiği görülmüştür.
Bu dağılım, Netflix’in küresel pazarlara yönelik
yerel içerik stratejisini yansıtmaktadır.

---

## Teknik Notlar
- Birden fazla ülke içeren veriler `str.split()` ve `explode()` yöntemleriyle ayrıştırılmıştır.
- Veri manipülasyonu sırasında `SettingWithCopyWarning` uyarıları
  `.copy()` kullanılarak bilinçli şekilde yönetilmiştir.
- Kategorik veriler için uygun görselleştirme teknikleri tercih edilmiştir.

---

## Sonuç
Bu proje, veri analizi sürecine alışmak ve
daha kapsamlı, iş dünyasına yönelik projeler için
sağlam bir temel oluşturmak amacıyla hazırlanmıştır.

> Not: Bu çalışma bir **ısınma / pratik projesidir**.
> Devamında e-ticaret satış analizi gibi
> CV’ye yönelik ana projeler planlanmaktadır.

