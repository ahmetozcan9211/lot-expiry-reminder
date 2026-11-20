# Lot ve Son Kullanma Tarihi Hatırlatıcı

Üretim lotları için iş emri açılış ve son kullanma tarihlerini takip eden, zamanı gelen lotlar için sorumlulara otomatik e-posta gönderen web uygulaması.

> Bu depo bir proje vitrinidir. Kaynak kod paylaşılmamaktadır.

## Özellikler

- Lot bazında hatırlatma kaydı: açılış tarihi, son kullanma tarihi (SKT), açıklama
- Benzersiz lot kontrolü
- Her sabah 09:00'da çalışan zamanlanmış kontrol ve HTML e-posta bildirimi
- JWT ile oturum, girdi doğrulama
- Hatırlatma listeleme, düzenleme ve silme

## Teknolojiler

`Node.js` · `Express` · `PostgreSQL` · `node-cron` · `Nodemailer` · `JWT` · `React`
