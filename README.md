# Atölye Veri Bilimine Giriş

Bu repository, veri bilimi atölyesi kapsamında yapılan ödevleri içermektedir. Her ödev, farklı veri analizi ve görselleştirme tekniklerini uygulamayı amaçlamaktadır.

## 📁 Proje Yapısı

```
AtolyeVeriBilimineGiris/
├── Ödev 1/
│   ├── country.csv
│   └── Veri_filtreleme_sıralama_projesi.ipynb
├── Ödev 2/
│   ├── 50_Startups.csv
│   └── Veri_Görselleştirme_odevi.ipynb
└── README.md
```

## 📚 Ödevler

### Ödev 1: Veri Filtreleme ve Sıralama Projesi

**Dosya:** `Ödev 1/Veri_filtreleme_sıralama_projesi.ipynb`

**Veri Seti:** `country.csv` - Ülkeler hakkında demografik, ekonomik ve coğrafi veriler içeren bir veri seti.

**Kapsam:**
Bu ödev, pandas kütüphanesi kullanılarak veri filtreleme ve sıralama işlemlerini içermektedir.

**Görevler:**
1. Nüfusa göre azalan sırada sıralama
2. GDP per capita'ya göre artan sırada sıralama
3. Nüfusu 10 milyonun üzerinde olan ülkeleri filtreleme
4. Okur-yazarlık oranına göre en yüksek 5 ülkeyi seçme
5. Kişi başı GSYİH'ı 10.000'in üzerinde olan ülkeleri filtreleme
6. En yüksek nüfus yoğunluğuna sahip ilk 10 ülkeyi seçme

**Veri Seti Özellikleri:**
- Country: Ülke adı
- Region: Bölge
- Population: Nüfus
- Area (sq. mi.): Yüzölçümü
- Pop. Density: Nüfus yoğunluğu
- GDP ($ per capita): Kişi başına düşen GSYİH
- Literacy (%): Okur-yazarlık oranı
- Ve daha fazlası...

### Ödev 2: Veri Görselleştirme Ödevi

**Dosya:** `Ödev 2/Veri_Görselleştirme_odevi.ipynb`

**Veri Seti:** `50_Startups.csv` - 50 farklı startup şirketinin harcama ve kârlılık verilerini içeren veri seti.

**Kapsam:**
Bu ödev, matplotlib kütüphanesi kullanılarak çeşitli veri görselleştirme tekniklerini uygulamayı içermektedir.

**Görevler:**
1. R&D Harcaması ve Kâr Arasındaki İlişki (Scatter Plot)
2. Yönetim Harcamaları ve Kâr Arasındaki İlişki (Scatter Plot)
3. Eyaletlere Göre Ortalama Kâr (Bar Chart)
4. Harcama Türlerinin Karşılaştırması (Boxplot)

**Veri Seti Özellikleri:**
- R&D Spend: Ar-Ge harcaması
- Administration: Yönetim harcaması
- Marketing Spend: Pazarlama harcaması
- State: Eyalet
- Profit: Kâr

## 🛠️ Kullanılan Teknolojiler

- **Python**: Programlama dili
- **Pandas**: Veri manipülasyonu ve analizi
- **NumPy**: Sayısal hesaplamalar
- **Matplotlib**: Veri görselleştirme
- **Jupyter Notebook**: Etkileşimli geliştirme ortamı

## 📦 Gereksinimler

Projeyi çalıştırmak için aşağıdaki Python kütüphanelerine ihtiyacınız vardır:

```bash
pip install pandas numpy matplotlib jupyter
```

## 🚀 Kullanım

1. Repository'yi klonlayın:
```bash
git clone <repository-url>
cd AtolyeVeriBilimineGiris
```

2. Jupyter Notebook'u başlatın:
```bash
jupyter notebook
```

3. İlgili ödev klasöründeki notebook dosyasını açın ve hücreleri sırayla çalıştırın.

## 📝 Notlar

- Her ödev, kendi veri seti ile birlikte gelmektedir.
- Notebook'lar, adım adım açıklamalar ve görev tanımları içermektedir.
- Veri setleri CSV formatındadır ve pandas ile kolayca okunabilir.

## 📄 Lisans

Bu proje eğitim amaçlıdır.
