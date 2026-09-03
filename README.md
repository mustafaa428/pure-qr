# pure-qr<div align="center">

# ⚡ PureQR

**1994'te icat edilmiş 2 boyutlu bir barkod için ayda 15 dolar ödemeyi bırakın.** *Stop paying $15/month for a 2D barcode invented in 1994.*

%100 İstemci taraflı, gizlilik odaklı, süresi asla dolmayan vektörel QR kod stüdyosu.  
*100% Client-side, privacy-first, vector QR code generator that never expires.*

[Canlı Demo / Live Demo](https://YOUR_USERNAME.github.io/pure-qr) • [Özellikler / Features](#-özellikler--features) • [Kurulum / Setup](#-kurulum--setup)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Vanilla JS](https://img.shields.io/badge/Vanilla-HTML%20%7C%20CSS%20%7C%20JS-yellow.svg)]()
[![No Backend](https://img.shields.io/badge/Backend-None%20(Client--side)-green.svg)]()

</div>

---

## 🛑 Ticari Sitelerin Tuzağı / The Subscription Scam

### 🇹🇷 Türkçe
Piyasadaki çoğu "ücretsiz" QR sitesi kullanıcıları abonelik tuzağına çeker:
1. Girdiğiniz bağlantıyı doğrudan QR içine yazmak yerine kendi sunucu linklerini (`site.com/qr/xyz`) koyarlar.
2. 14 günlük "deneme süresi" bittiğinde, aylık ücret ödemezseniz bu yönlendirmeyi kapatırlar.
3. Bastırdığınız menüler, el ilanları veya kartvizitler bir anda çöp olur.

**PureQR** bu aldatmacayı ortadan kaldırır. Veriyi doğrudan tarayıcınızın içinde QR kodun piksellerine işler. Aracı sunucu, veritabanı veya gizli süre kısıtlaması yoktur. **Oluşturulan kodlar sonsuza kadar çalışır.**

### 🇬🇧 English
Most commercial QR generators trick users into an expensive trap:
1. Instead of directly encoding your data, they encode a redirect URL (`site.com/qr/xyz`) hosted on their servers.
2. After a 14-day "free trial", they disable the link unless you subscribe.
3. Printed restaurant menus, business cards, and signs become instantly useless.

**PureQR** eliminates this scam completely. It encodes your actual data directly into the QR matrix inside your browser. No middleman, no redirects, no tracking, and **it will work forever**.

---

## ✨ Özellikler / Features

- **Süresi Asla Dolmaz / Never Expires:** Doğrudan kodlama sayesinde basılan kodlar ömür boyu çalışır. *(Direct encoding ensures lifetime validity.)*
- **%100 İstemci Taraflı & Güvenli / 100% Client-Side:** Hiçbir link veya dosya sunucuya gönderilmez. *(No data is ever transmitted to an external server.)*
- **Logo Yönetimi / Logo Integration:** Sürükle-bırak logo yükleme, kenar boşluğu koruması ve tek tıkla kaldırma. *(Drag & drop upload, safe-margin clearing, and instant logo removal.)*
- **Stil Özelleştirme / Custom Styles:** Yuvarlak, nokta veya klasik kare desenleri; özel renk paletleri. *(Rounded, classy, dot matrix styles, and custom hex colors.)*
- **Baskıya Hazır SVG / Vector SVG Export:** Matbaa ve tasarımcılar için pikselleşmeyen vektörel çıktı. *(Lossless vector export ready for high-resolution print design.)*
- **Sıfır Bağımlılık / Zero Build Steps:** Paket yöneticisi (npm), derleme süreci veya sunucu gerektirmez. *(Pure HTML, CSS, and Vanilla JS.)*

---

## 🚀 Canlı Önizleme / Live Demo

Kendi tarayıcınızda deneyin / *Try it in your browser:* 👉 **[https://YOUR_USERNAME.github.io/pure-qr](https://YOUR_USERNAME.github.io/pure-qr)**

*(GitHub Pages'i aktif ettikten sonra `YOUR_USERNAME` kısmını kendi kullanıcı adınızla değiştirin.)* *(Replace `YOUR_USERNAME` with your actual GitHub username after enabling Pages.)*

---

## 💻 Kurulum / Setup

### Yerel Ortam / Local Development
Projeyi çalıştırmak için Node.js veya sunucu kurulumu gerekmez:  
*No build tools, node modules, or local servers required:*

```bash
# Depoyu klonlayın / Clone the repository
git clone [https://github.com/YOUR_USERNAME/pure-qr.git](https://github.com/YOUR_USERNAME/pure-qr.git)

# Klasöre gidin / Navigate to directory
cd pure-qr

# index.html dosyasını tarayıcınızda açın / Open index.html in any browser
open index.html