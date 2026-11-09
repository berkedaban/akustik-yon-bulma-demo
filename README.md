# Akustik Yön Bulma Simülasyonu

Dört mikrofonlu bir dizinin ses kaynağının geliş yönünü nasıl tahmin edebileceğini etkileşimli olarak gösteren bitirme projesi demosu.

## Deneyde değiştirilebilen parametreler

- Kaynak açısı
- Mikrofon aralığı
- Sinyal/gürültü oranı
- Yankı seviyesi
- Her açıdaki tekrar sayısı

## Model kapsamı

Simülasyon sentetik sinyal, 2B düzlem dalga varsayımı, dört eşleşmiş mikrofon ve GCC-PHAT tabanlı yön kestirimi kullanır. Gerçek oda veya mikrofon ölçümü değildir; donanım başarımını temsil etmez.

Site, Python veya NumPy gerektirmeden modern bir tarayıcıda çalışır. Kaynak dosyası `site/index.html` konumundadır.
