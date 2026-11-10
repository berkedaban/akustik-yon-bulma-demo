# Akustik Yön Bulma ve Orman Yankı Haritalama

**Canlı demo:** https://berkedaban.github.io/akustik-yon-bulma-demo/

Bu sayfada iki ayrı sentetik senaryo vardır:

1. **Yön kestirimi:** dört mikrofonlu diziye ulaşan sesin geliş açısını GCC-PHAT yaklaşımıyla tahmin eder.
2. **Ağaç yankı haritalama:** bilinen konumdaki verici/alıcı dizisinin gönderdiği kısa darbenin ağaç gövdelerinden dönen yankılarını canlandırır. Yankı gecikmesinden menzil, dört mikrofon arasındaki geliş zamanı farkından yön kestirilip haritada ağaç noktaları oluşturulur.

## Haritalama simülasyonu ayarları

Ağaç yoğunluğu, sinyal/gürültü oranı ve ağaçtan yansıma gücü değiştirilebilir. Haritada temsili ağaç konumları ile yankılardan hesaplanan noktalar birlikte gösterilir; sonuçlarda bulunan ağaç sayısı, ortalama konum hatası ve algılama oranı yer alır.

## Bilimsel kapsam ve sınırlar

Orman senaryosu 100 × 60 m temsili bir alanda sentetik verilerle çalışır. Gerçek ağaç koordinatı veya gerçek mikrofon kaydı değildir. Mevcut konum tek bir küçük sensör dizisi için yerel yankı haritası gösterir; geniş alan haritası için diziyi GPS/ölçümle bilinen birden çok noktaya taşıyıp sonuçları birleştirmek gerekir. Gerçek donanımda mikrofonlar arası saat eşzamanlaması, kalibrasyon ve saha doğrulaması gerekir.

Site Python, NumPy veya harici görsel kütüphaneler gerektirmez. Kaynak HTML: `site/index.html`.
