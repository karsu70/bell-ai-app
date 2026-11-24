BELL AI PWA - ÖN SÜRÜM

İçerik:
- index.html: mevcut OneState kural asistanı prototipi
- manifest.webmanifest: ana ekrana eklenebilir uygulama tanımı
- sw.js: temel çevrimdışı önbellek
- icon-192.png / icon-512.png: uygulama simgeleri

YAYINLAMA:
Bu dosyaları HTTPS destekleyen bir statik web barındırma hizmetine yükleyin. Ana sayfa index.html olmalıdır.

ANDROID:
Siteyi Chrome'da açın > menü > Uygulamayı yükle / Ana ekrana ekle.

IPHONE:
Siteyi Safari'de açın > Paylaş > Ana Ekrana Ekle.

ÖNEMLİ SINIRLAR:
Bu PWA, iOS ve Android'de uygulama gibi açılabilir. İçindeki B simgesi yalnızca BELL AI sayfası açıkken hızlı panel açar. Başka uygulamaların/oyunun üzerine gerçek sistem seviyesi kayan pencere açmaz.
Android'de diğer uygulamaların üzerinde gerçek kayan pencere için ayrıca yerel Android uygulaması ve kullanıcının özel izin vermesi gerekir. iOS, üçüncü taraf uygulamalara oyunların üzerinde genel amaçlı kayan pencere izni vermez.

GÜVENLİK:
Bu sürümde gerçek Admin/Helper kimlik doğrulaması, sunucu, ortak veri tabanı veya gerçek AI API bağlantısı yoktur. Arayüzdeki erişim ibaresi güvenlik kontrolü değildir. Gerçek kullanım öncesi sunucu taraflı kimlik doğrulama ve yetkilendirme kurulmalıdır.
