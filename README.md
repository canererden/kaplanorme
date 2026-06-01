# Kaplan Orme Website

Bu proje, Kaplan Orme icin hazirlanan GitHub Pages uyumlu statik tekstil web sitesidir.

## Dosya Yapisi

- index.html: Ana sayfa ve tum bolumler
- styles.css: Tasarim sistemi ve responsive stiller
- script.js: Giris animasyonlari ve alt bilgi yili
- CNAME: Ozel alan adi tanimi
- .nojekyll: GitHub Pages'in dosyalari oldugu gibi yayinlamasi icin

## Yerel Onizleme

Proje klasorunde basit bir yerel sunucu calistirmak icin:

```bash
python3 -m http.server 8080
```

Ardindan tarayicida http://localhost:8080 adresini acin.

## GitHub Pages Baglama

1. Bu klasoru bir GitHub reposuna gonderin.
2. GitHub repository ayarlarinda Pages bolumunu acin.
3. Deploy from a branch secin.
4. Branch olarak main, klasor olarak root secin.
5. DNS tarafinda kaplanorme.com icin GitHub Pages kayitlarini tanimlayin.
6. CNAME dosyasi sayesinde ozel alan adi korunur.

## IHS DNS Kayitlari

Alan adini IHS panelinden GitHub Pages'e yonlendirmek icin genel olarak su kayitlar kullanilir:

- A kaydi: 185.199.108.153
- A kaydi: 185.199.109.153
- A kaydi: 185.199.110.153
- A kaydi: 185.199.111.153
- www icin CNAME: kullaniciadi.github.io

Not: `kullaniciadi.github.io` kismini kendi GitHub kullanici ya da organizasyon adresinizle degistirin.

## Not

Bu ilk kurulumda iletisim bilgileri taslak olarak birakildi. Yayina almadan once gercek telefon, e-posta ve adres bilgilerini guncelleyin.
