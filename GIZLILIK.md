---
layout: default
title: Gloria Gizlilik Politikası
---
# Gloria Gizlilik ve Veri Saklama Politikası

Son güncelleme: 10 Ağustos 2026

Gloria, komutları ve sunucu özelliklerini çalıştırmak için gerekli olan en az veriyi işler. 

## İşlenen veriler

- Sunucu, kanal, rol, kullanıcı ve mesaj kimlikleri; yalnızca etkinleştirilen özelliklerin çalışması için.
- Sunucu yöneticilerinin seçtiği yapılandırmalar ve moderasyon kayıtları.
- Rütbe sistemi yönetici tarafından açılmışsa sunucu içindeki mesaj/ses etkinliği toplamları. Rütbe takibi yeni sunucularda kapalıdır.
- Destek sistemi açıksa ticket sahibi, kategori, zaman, destek istatistiği ve ticket mesaj transkripti.
- Müzik tercihleri, geri bildirimleri ve kısa dinleme geçmişi.

Gloria mesaj içeriğini genel amaçlı olarak saklamaz. Destek transkriptleri yalnızca botun doğruladığı ticket kanallarında oluşturulur.

## Amaç ve saklama

Veriler, kullanıcının istediği bot işlevini sunmak, sunucu yöneticisinin etkinleştirdiği güvenlik/moderasyon yapılandırmasını uygulamak, kötüye kullanımı önlemek ve hizmet hatalarını incelemek için işlenir.

- Destek transkriptleri varsayılan olarak 30 gün saklanır; süre `SUPPORT_TRANSCRIPT_RETENTION_DAYS` ile 1-365 gün arasında ayarlanabilir.
- Discord yedek kanalındaki bot yedekleri varsayılan olarak 30 gün saklanır ve yeni yedek öncesinde süresi dolan bot mesajları temizlenir.
- Rütbenin günlük kanal ayrıntıları 90 gün tutulur; toplamlar kullanıcı silme talebine veya botun sunucudan ayrılmasına kadar saklanır.
- Bot bir sunucudan çıkarıldığında o sunucuya ait yerel yapılandırma, istatistik, ticket ve müzik kayıtları otomatik temizlenir.
- Discord üzerindeki mesajlar ve sunucu yöneticilerinin Discord içinde tuttuğu kayıtlar Gloria'nın yerel silme işleminin kapsamında değildir.

## Başvuru

Veri veya gizlilik soruları için `/bildir` komutunu ya da `/katıl` ile erişilen Gloria destek sunucusunu kullanabilirsiniz.
