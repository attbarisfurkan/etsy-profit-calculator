ETSY FİYAT & KÂR HESAPLAYICI - PWA KURULUM

Bu paket bir PWA mini uygulamasıdır. İnternetsiz çalışır, telefonda ana ekrana uygulama gibi eklenebilir.

DOSYALAR
- index.html: Uygulamanın kendisi
- manifest.webmanifest: PWA uygulama bilgileri
- service-worker.js: Offline çalışma dosyası
- icons/: Uygulama ikonları

ÖNEMLİ
PWA olarak tam kurulabilmesi için uygulamanın HTTPS üzerinden açılması gerekir.
Yani dosyayı direkt telefonda açarsan hesaplayıcı çalışır; ancak Chrome her zaman "uygulama olarak kur" seçeneğini göstermeyebilir.

EN KOLAY KURULUM YÖNTEMİ
1. Bu klasörü GitHub Pages, Netlify, Vercel veya kendi sitene yükle.
2. Telefonda Chrome ile index.html adresini aç.
3. Chrome menüsü > Ana ekrana ekle / Uygulamayı yükle seçeneğine bas.
4. Sonra normal uygulama gibi açılır ve offline çalışır.

DOSYAYI TELEFONDA SADECE HTML GİBİ KULLANMAK
- index.html dosyasına dokunup Chrome ile açabilirsin.
- Hesaplama özellikleri çalışır.
- Ama PWA kurulum/offline cache özelliği bazı cihazlarda tam devreye girmeyebilir.

ÖZELLİKLER
- Satış fiyatı, ürün maliyeti, kargo, paketleme, diğer gider, Etsy Ads harcaması
- Normal Etsy kesintisi: varsayılan %18
- KDV/VAT dahil senaryo: %21
- Offsite Ads: %15 veya %12
- Manuel kesinti oranı
- Dolar/TL kuru ve TL ek gider
- Net kâr, kâr marjı, ROI, başabaş fiyat
- Hedef kâra göre gerekli satış fiyatı
- .99, tam dolar, 5 dolara ve 9'a biten fiyat önerileri
- %5 - %50 indirim tablosu
- Koyu/açık tema
- Ayarları telefonda saklama
- Hesap özeti kopyalama ve TXT olarak indirme


SÜRÜM 2 NOTLARI
- İnternet varken USD/TRY kuru otomatik güncellenir.
- İnternet yoksa son kaydedilen kur kullanılır.
- ExchangeRate-API açık endpoint'i ilk kaynak, Frankfurter yedek kaynak olarak kullanılır.
- Satış, maliyet, kesinti ve kâr satırlarının yanında TL karşılığı gösterilir.
- Güncelleme sonrası service-worker cache sürümü v2 yapılmıştır.
