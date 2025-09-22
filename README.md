# News Site Project

Bu proje, modern web geliştirme tekniklerini ve özellikle CSS Grid sistemini öğrenmek amacıyla geliştirilmiş bir haber sitesi uygulamasıdır.

## 🎯 Proje Amacı

Bu proje, aşağıdaki modern web teknolojilerini ve prensiplerini uygulamalı olarak öğrenmek için tasarlanmıştır:

- CSS Grid sisteminin detaylı kullanımı
- Responsive tasarım prensipleri
- Flexbox ve Grid sistemlerinin birlikte kullanımı
- Modern CSS özellikleri ve best practice'ler

## 🛠 Kullanılan Teknolojiler

- HTML5
- CSS3
  - CSS Grid
  - Flexbox
  - CSS Variables
  - Media Queries
- Font Awesome (ikonlar için)
- Google Fonts

## 📋 Özellikler

- Responsive tasarım (mobil, tablet ve masaüstü uyumlu)
- Modern grid tabanlı sayfa düzeni
- Kategori bazlı içerik organizasyonu
- Dinamik header bölümü
- Özelleştirilebilir renk şeması (CSS değişkenleri ile)
- Sosyal medya entegrasyonu
- İletişim formu

## 📱 Responsive Tasarım Breakpoint'leri

- Mobil: < 500px
- Tablet: 768px
- Desktop: > 768px

## 🎨 Grid Sistemi Kullanım Örnekleri

Projede CSS Grid sistemi şu alanlarda kullanılmıştır:

1. Ana Sayfa Düzeni:
```css
.page-container {
    display: grid;
    grid-template-columns: 3fr 1fr;
    gap: 2rem;
}
```

2. Haber Kartları Grid'i:
```css
.articles-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem;
}
```

3. Footer Bölümü:
```css
.footer-container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 3rem;
}
```

## 📚 Öğrenilen Konular

1. CSS Grid Layout
   - Grid Container ve Grid Item kavramları
   - Grid template columns/rows
   - Grid gap ve spacing
   - Grid align ve justify özellikleri

2. Responsive Tasarım
   - Media queries kullanımı
   - Mobil öncelikli tasarım yaklaşımı
   - Breakpoint yönetimi

3. Modern CSS Özellikleri
   - CSS değişkenleri (Custom Properties)
   - Flexbox ile Grid entegrasyonu
   - Modern seçiciler ve pseudo-class'lar

## 🚀 Kurulum

1. Projeyi klonlayın
```bash
git clone https://github.com/kullaniciadi/news-site.git
```

2. Proje dizinine gidin
```bash
cd news-site
```

3. `index.html` dosyasını bir web tarayıcısında açın

## 💡 Geliştirme Notları

- CSS Grid sistemi, sayfa düzenini oluştururken maximum esneklik sağlamaktadır
- Responsive tasarım için Grid ve Flexbox kombinasyonu kullanılmıştır
- CSS değişkenleri ile tema renkleri merkezi olarak yönetilmektedir
- Semantik HTML yapısı kullanılmıştır

## 📝 Lisans

Bu proje MIT lisansı altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasını inceleyebilirsiniz.

## 👤 Yazar

- GitHub: [@emreyilmazxy](https://github.com/emreyilmazxy)

## ✨ Katkıda Bulunma

1. Projeyi fork edin
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'feat: Add amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request oluşturun