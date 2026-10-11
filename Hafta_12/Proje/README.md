# Hizmet Sağlayıcı Eşleştirme Aracı

YetGen Core Python Programı bitirme projesi.

Bir firmanın ihtiyaç duyduğu hizmeti, çalıştığı bölgeyi ve sektörünü seçmesiyle, bu kriterlere uyan dijital hizmet firmalarını listeleyen bir Python uygulaması.

## Ne yapıyor?

1. `data.xlsx` dosyasında her biri ayrı sayfada duran 17 firmanın bilgilerini tek bir tabloda birleştirir.
2. Hizmet alanı, bölge ve sektör sütunlarındaki virgülle ayrılmış değerleri ayırır, tekrarları temizler ve kullanıcıya numaralı menü olarak sunar.
3. Kullanıcı birden fazla hizmet ve bölge, bir de sektör seçer.
4. Seçimlerin hepsine uyan firmaları referansları, iletişim bilgileri ve sektörleriyle birlikte listeler.
5. Bulunan firmaları referans, hizmet alanı, sektör ve bölge sayılarına göre karşılaştıran bir grafik çizer.

## Kullanılanlar

Python, Pandas, Matplotlib, Jupyter Notebook

## Nasıl çalıştırılır?

```bash
pip install pandas openpyxl matplotlib
```

`HizmetSaglayiciEslestirme.ipynb` dosyasını Jupyter'de açıp hücreleri sırayla çalıştırın. `data.xlsx` dosyası notebook ile aynı klasörde olmalıdır.

## Örnek

Notebook'taki örnek çalıştırmada *SEO Danışmanlığı* ve *Sosyal Medya Yönetimi* hizmetleri, *Avrupa* bölgesi ve *E-ticaret* sektörü seçilmiştir. Uygulama bu kriterlere uyan 4 firma bulmuştur.

---

**English summary:** A Python tool that merges company profiles stored in separate Excel sheets into one dataset, lets the user choose the services, regions and sector they need, and lists the matching service providers with their references and contact details. Built with Pandas and Matplotlib as the final project of the YetGen Core Python Program.
