# Hızlı Okuma — GitHub'a yükleme

1. Bu ZIP dosyasını bilgisayarında aç (ZIP'i doğrudan GitHub'a yükleme).
2. GitHub'da yeni bir Public repository oluştur. Adı örneğin hizli-okuma olsun.
3. Add file → Upload files seç. Açtığın ZIP'in İÇİNDEKİ tüm dosya ve klasörleri birlikte sürükle. index.html doğrudan deponun ana ekranında görünmeli; üstüne ek bir klasör koyma.
4. Commit changes düğmesine bas.
5. Settings → Pages → Source: Deploy from a branch seç.
6. Branch: main, klasör: /(root) seçip Save düğmesine bas.
7. Yayın tamamlandığında aynı Pages ekranındaki Visit site bağlantısını aç. Adres genellikle https://KULLANICI.github.io/hizli-okuma/ olur.

ÖNEMLİ: assets, pdf-fonts ve pdf-wasm klasörlerini de yükle. Terminal, Node.js, API anahtarı, ücretli sunucu veya GitHub Actions dosyası gerekmiyor. ZIP içindeki index.html dosyasını çift tıklayarak açmak yerine GitHub Pages adresini kullan.

Bu paket derlenmiş statik sitedir. PDF, EPUB, TXT ve metin okuma tarayıcıda çalışır. Kitaplık ve ayarlar bu tarayıcıda saklanır; başka cihazlara eşitlenmez. PDF'lerde seçilebilir metin gerekir; taranmış resimler için OCR yoktur. DRM korumalı EPUB desteklenmez. Özel CJK CMap gerektiren bazı PDF'ler desteklenmeyebilir. Yazı tipleri sistemdeki karşılıklarını kullanır; OpenDyslexic kurulu değilse alternatif yazı tipi kullanılır.

Kontrol: üretim derlemesi ve TypeScript denetimi geçti. Yerel tarayıcıda alt klasörden açılış, metin oynatma, ileri kelime, PDF, EPUB ve yenileme sonrası kitaplığın korunması doğrulandı. GitHub'a yayınlama henüz yapılmadı.

Resmî GitHub adımları: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
