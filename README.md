# Kaplan Orme Website

Bu repo, Kaplan Orme icin hazirlanan ve GitHub Pages uzerinden yayinlanan statik kurumsal tekstil web sitesidir.

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

Bu proje su adreste tutulur:

- Repo: https://github.com/canererden/kaplanorme

GitHub Pages ayarlari:

- Branch: main
- Folder: /(root)
- Custom domain: kaplanorme.com

## IHS DNS Kayitlari

Alan adini IHS panelinden GitHub Pages'e yonlendirmek icin genel olarak su kayitlar kullanilir:

- A kaydi: 185.199.108.153
- A kaydi: 185.199.109.153
- A kaydi: 185.199.110.153
- A kaydi: 185.199.111.153
- www icin CNAME: canererden.github.io

## Yayin Kontrolu

- GitHub Pages kaynak adresi: https://canererden.github.io/kaplanorme/
- Ozel alan adi: http://kaplanorme.com/
- `CNAME` dosyasi repo icinde tutulur.
- `.nojekyll` dosyasi root dizinde tutulur.

## Not

DNS yayilimi tamamlanmadan ozel alan adinda gecici erisim veya SSL gecikmesi gorulebilir. GitHub sertifikasi olustuktan sonra HTTPS zorlamasi acilabilir.
