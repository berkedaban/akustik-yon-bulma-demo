# Akustik Yön Bulma Simülasyonu

**Canlı demo:** https://berkedaban.github.io/akustik-yon-bulma-demo/

Dört mikrofonlu bir dizinin ses kaynağının geliş yönünü nasıl tahmin edebileceğini etkileşimli olarak gösteren bitirme projesi demosu.

## Deney ayarları

- Gerçek kaynak açısı
- Mikrofon aralığı
- Sinyal/gürültü oranı
- Yankı seviyesi
- Açı başına tekrar sayısı

Açı taraması kaynak yönü ile tahmini karşılaştırır ve ortalama açı hatasıyla ±5° içindeki ölçüm oranını gösterir. Tarama ilerlemesi canlı gösterilir.

## Orman sahası görseli

Dört mikrofon, ses kaynağı, yansıma ve yön kestirimi şematik bir ormanlık alan haritası üzerinde canlandırılır. Haritadaki ağaç örtüsü ve topoğrafya **temsili çizimdir**; gerçek arazi verisi değildir. Gerçek saha çalışmasında GPS koordinatları, harita/DEM verisi ve ölçülmüş ağaç/sensör konumlarıyla değiştirilmelidir.

## Model kapsamı

Simülasyon sentetik sinyal, 2B düzlem dalga varsayımı, eşleşmiş dört mikrofon ve GCC-PHAT tabanlı kestirim kullanır. Gerçek oda veya mikrofon ölçümü değildir; donanım başarımını temsil etmez. Gerçek prototipte kalibrasyon ve ölçümle doğrulanmalıdır.

Python, NumPy veya harici görsel kütüphaneler gerektirmez; güncel bir tarayıcıda çalışır. Ana dosya `site/index.html` konumundadır.
